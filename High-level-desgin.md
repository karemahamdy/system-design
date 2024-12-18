
# High-Level Design
High-level design or HLD refers to the overall system, a design that consists description of the system architecture and design and is a generic system design that includes:
- System architecture
- Database design
- Brief description of systems, services, platforms, and relationships among modules.

`Scope of High-Level Design Document:` The High-Level Design documentation presents the structure of the system as the application/database architecture, application flow, and technology architecture.

# Components of High-Level Design
1- Attributes and features of software entities.  
2- Relationships between different software entities (components, modules, classes, etc)

# What are the components of System Design?

 ## 1- Load Balancer:

    Distributes incoming requests across multiple servers to avoid overloading and ensure efficient resource utilization. Types include Layer 4 (network-based), Layer 7 (application-based), global, and application-specific load balancers.

 ## 2- Key-Value Stores:
    NoSQL databases storing data as key-value pairs, providing fast access. They are used in applications like caching and session management. Types include in-memory and persistent stores, ideal for scalability and performance in distributed systems.

 ## 3- Blob Storage & Databases: 
    Blob storage is used for unstructured data (e.g., media files), while databases store structured data for querying. Both are essential for managing different data types in distributed systems.

 ## 4- Rate Limiters: 
     Controls the rate of requests or actions to protect systems from overload. Types include request, action, and user rate limiters, with mechanisms like token buckets to regulate excess requests.

 ## 5- Monitoring System:
    Tracks performance metrics (e.g., network, systems, applications) to ensure system health and reliability. It provides real-time visibility for troubleshooting and performance insights.

 ## 6- Distributed System Messaging Queues:
    Enables asynchronous communication between nodes, decoupling senders and receivers. Types include point-to-point, publish-subscribe, and hybrid queues, improving scalability and resilience. Common tools are Apache Kafka, RabbitMQ, and AWS SQS.

# Purpose of High-Level Design
The purpose of this High-Level Design (HLD) is to add the necessary detailed description to represent a suitable model. This is designed to help with operational requirements and can be used as a reference manual for how the modules interact. 

#  How To Design Scalable High-level Design (HLD) Systems
`This passage provides an overview of various concepts in system design, focusing on scalability, efficiency, and robustness:`

- `Capacity Estimation:` 
  
  Predicting the necessary resources like processing power, memory, and bandwidth to ensure the system can handle its workload without bottlenecks.

- `HTTP and HTTPS Methods:`
  
   Describes common methods like GET, PUT, and POST used for communication between clients and servers.

- `WebSockets:` 
 
  Enables real-time, two-way communication between a client and a server without waiting for responses, used in applications like gaming and chat.

- `Polling:`

  A technique where a client continuously requests updates from the server at regular intervals.

- `Server-Sent Events (SSE):`

  One-way communication where the server sends updates to the client, commonly used for real-time data streaming.

- `Filtering: In APIs`
  
   filtering allows retrieval of specific data by applying conditions like sorting and pagination to manage large datasets.

- `Rate Limiting:` 
 
  Controls the number of requests a system can process in a specific time to avoid overloading.

- `Resiliency:`

  Ensuring a system can recover from faults through methods like replication, redundancy, and availability.

- `Paging:` 
   
   Handling large datasets by breaking them into manageable chunks and filtering specific data based on requirements.

- `Logging:` 
  
   Keeping records of events for tracking, debugging, and monitoring system health, crucial in distributed systems.

  
# The three major principles for creating a good system design are:

`Scalability:` The system should be able to handle increasing amounts of work, data, or users efficiently without a significant drop in performance. This involves proper capacity estimation, resource allocation, and architectural decisions that support horizontal or vertical scaling.

`Reliability:` The system must be dependable, with the ability to recover from faults or failures. Resiliency is key, achieved through mechanisms like redundancy, replication, and fault-tolerant design to ensure minimal downtime and data loss.

`Maintainability:` The system should be easy to update, debug, and enhance over time. This includes modular design, clean code practices, and logging mechanisms that help monitor, troubleshoot, and extend the system without disrupting its operations.
