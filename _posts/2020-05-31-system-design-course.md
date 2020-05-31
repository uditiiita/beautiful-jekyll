Lecture 1:
- What exactly is a System Design Interview?
- Expectations from Interviewee
	- Breadth Vs Depth
	- Should you know everything about everything?
- System Design Process ( Motivating Example: Design UBER.)
	- Common Mistakes
	- Chaotic Approach
	- Systematic Approach

Lecture 2:
- Trade-offs in a large scale system
	- Evolution of systems
	- Performance Vs Scalability
	- Latency Vs Throughput
	- Availability Vs Consistency(CAP Theorem)

Lecture 3:
- Patterns of Enterprise Application Architecture
	- MicroService Vs Monolith
	- Service Discovery
	- API Gateway
	- Client - server communications: 
		- Different types and which one to use when.
		- Long polling
		- Sockets
		- Http 
		- Server sent events
	- Start designing first system.

Lecture 4:
- Replication and Redundancy
	- Achieving Availability
	- Strongly versus eventual consistent systems
	- Quorums
	- Load balancers
	- Identify and fix availability problems with service we built in previous lecture.

Lecture 5:
- Sharding or Data Partitioning
	- Achieving scalability.
	- Consistent Hashing
	- Routing
	- Identify and fix scalability problems with service we built in previous lecture.


Lecture 6:
- Components of a large scale system
	- Databases/Storage Layer
		- SQL vs NoSQL (Lab Session:  RDS and DynamoDb)
		- How NoSQL databases work?
		- Why NoSQL databases scale well?
		- Build a scalable database like dynamodb
		- Practical Examples of SQL/NoSQL database usages.


Lecture 7:
- Components of a large scale system
	- Caching
		- All about caching - Policies, usages etc.
		- Practical examples to demonstrate use and helpfulness of cache
	- CDNs


Lecture 8:
- Components of a large scale system
	- Queues and asynchronous systems
		- Event driven systems
		- SQS and Kafka
		- Events Ordering
		- Example system design using queues - Search Indexing, etc.


Lecture 9:
- Large data / Large QPS Systems
	- Batch processing
	- Stream processing
	- Lab Session for batch processing using Dynamo, Queues and Lambdas


Lecture 10:
- Tips to excel in SDI. 
- System design examples like netflix, etc



Extras if time remains in the lecture:

Case studies:
Lecture: System design example: Building a scalable distributed cache
Lecture: Sorting 1 TB data.

Common: DNS,
- Instrumentation
	- Identifying bottlenecks
	- Lab Session: Splunk, New Relic / DataDog



