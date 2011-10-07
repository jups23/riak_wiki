# Operations

This section contains information pertinent to operating Riak.

## Basics

* [[System Requirements]]
* [[Storage Backends]]
  * [[Bitcask]]
  * [[Innostore]]
  * [[LevelDB]]
  * [[Memory]]
  * [[Multi]]

## Configuration and Management:

* [[Configuration Files]]
* [[Adding and Removing Nodes]]
* [[Recovering a Failed Node]]
* [[Command-Line Tools]]
* [[Rolling Upgrades]]
* [[Installing with Chef]]
* Troubleshooting   
  * [[Open Files Limit]]
  * [[Riak Search|Riak Search - Operations and Troubleshooting]]
  
## Best Practices
  
* Capacity Planning
  * [[Cluster|Cluster Capacity Planning]]
  * [[Bitcask|Bitcask Capacity Planning]]
* [[Network Security and Firewall Configurations]]

## Additional Information

* [[Benchmarking]]
* [[Release Notes]]

## Philosophy

Riak is designed to make operations as easy as possible. Adding a node to
cluster is as simple as typing two commands into a shell. Further, with a good
understanding of Riak, appropriate capacity planning, and suitable redundancy,
operations can be a 9-5 job. Ops teams should be able to rest easy with the
knowledge that they are running a fault tolerant system with predictable failure
states that should never compromise their data. When the 2AM phone call comes in
that the server hosting a Riak node has gone down, panic need not ensue.
Instead, you can fix or replace the failed server in the morning, confident that
your data will all be there when you get into the office.