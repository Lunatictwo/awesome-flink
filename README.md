# awesome-flink
🐟🐟🐟

## Concepts

### Table API & SQL
  * [Eager View Maintenance](http://shodhganga.inflibnet.ac.in/bitstream/10603/98388/13/13_chapter3.pdf)
  A view can be refreshed within the transaction that updates the base tables, or the refresh can be delayed. The former case is referred to as immediate(eager) view maintenance, while the latter is called deferred(lazy) view maintenance. 
  * [Distributed Snapshots: Determining Global States of Distributed Systems](http://lamport.azurewebsites.net/pubs/chandy.pdf)
  A snapshot algorithm is used to create a consistent snapshot of the global state of a distributed system. Due to the lack of globally shared memory and a global clock, this isn't trivially possible. Also known as Chandy Lamport Algorithm.(for flink checkpoint)
  * ...
