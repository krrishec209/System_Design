SpringBoot interview question and answer 
------------------------------------------------------
How do you handle inter-service communication in a microservice architecture in Springboot? 

There are 3 ways we can approach 

1️⃣ If it is simple microservice means we can use REST API's for communication. If one microservice send HTTP request other microservice receive response. It is synchronous communication.

2️⃣ In more complex applications, instead of manually creating HTTP requests, we can use Spring Cloud OpenFeign. It provides a declarative way to define REST clients, making the code cleaner and easier to manage. 

3️⃣ For asynchronous communication between 2 microservices we can use Apache Kafka. Here one microservice acts as a producer, sending messages to a Kafka topic. Another microservice acts as a consumer, processing the messages at its own pace.
