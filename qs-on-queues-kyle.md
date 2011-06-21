Spearker: Eric Day
==================

Gist: Queueing systems

Queues are everywhere. Yep.

Queue types
==================
* FIFO
* LIFO
* Priority
* Circular
* Custom
Why?
==================
* Scale out
* Concurrency
* Async
* Resource Specialization
How?
==================
* Local (shared memory)
* Clustered (LAN)
* Distributed (WAN, cloud)
Network chattiness
==================
* How chatty is the queue? This matters. Less round trip times.

Broker vs brokerless
==================
* Brokers
* * Brokers are a point of failure
* * provides retry abilities
* Brokerless
* * Brokerless is only one hop
Security
==================
* Queues don't really come with security
* Assumes you are in a trusted network
* Homebrew security?
* privies
* Piping through SSH. haha, awesome.
Poll vs Push
==================
* Polling sucks. GROSSSSSS
* Push is better, tells client that it's ready
* Chattiness matters here again
Batch Processing
==================
* Sending emails at once, why would you do that one at a time
Availability
==================
* Language
* Data formats
* ect
Protocols
==================
* AMQP
* PuSH
* Atom/RSS
* JMS - not really a protocol. Java stuff. Eeeww.
* XMPP
* REST
* * Amazon SQS
* Custom
* * Memcached
* * Redis?
* Stomp
* * Rabbit
ZeroMQ
==================
* Fast/lightweight
* Brokerless
* Multiple languages
* Supports simple, multicast and pub/sub
