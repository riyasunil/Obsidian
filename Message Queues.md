Types of message queues:
- Point-2-Point
	```Producer sends msg -> Stored in Q -> Consumer gets msg```
	Once a msg is used by a consumer it no longer exists and cannot be used by another consumer
	P2P is implemented in diff patterns like : 
	- Req-Res
	- Work Q
	- Guaranteed Delivery (consumer retires until success)
- Pub Sub 
		```Producer publishes a msg to a q -> Broadcasted to all Consumers that are subbed to that q```
	Consumers can be subbed to many q's at a time
	used for social media systems, real time systems, to implement event driven architecture

Message Routing:
- Topic based
- Direct routing
- Content based

# RabbitMQ
[install](https://www.rabbitmq.com/docs/download)
	