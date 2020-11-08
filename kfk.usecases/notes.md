
## kafka usecases 


Understanding Kafka Storage Architecture

          Kafka Topics and Partitions
          Kafka Topic Replication
          Partition Leaders and Followers
          Kafka Log Segments
          Kafka Message Offsets
          Kafka Message Index

 Understanding Kafka Cluster
            Zookeeper in Kafka
            Kafka Cluster Controller
            Partition Allocation and Fault Tolerance
            Partition Leader Vs Partition Follower
            The ISR List - In Sync Replica
            Committed Vs Un-Committed Records
            Minimum ISR List

kafka producer internals 
     Introducing Kafka Producers
     Creating your first Kafka Producer
     Producer Record
     Producer Serializer
     Producer Partitioner
     Message Timestamp
     Producer Message Buffer
     Producer IO Thread and Retires

Advanced Kafka producer
    Horizontal Vs. Vertical Scalability
    Producer Multi-Threading Scenario
    Creating Multi-Threaded Kafka Producer
    At Least Once Vs. At Most Once
    Exactly Once - Producer Idempotence
    Transactions in Kafka Producer
        
Kafka Consumers
    Creating Kafka Consume - Transform - Produce Pipeline
    Consumer Group and Scalability
    Consumer Positions - Current Offset Vs. Committed Offset


Types and Serialization
     Working with Types and Serialization
     Using JSON Schema - POS Simulator using JSON Serialized Invoices
     Using AVRO Schema - POS Simulator using AVRO Serialized Invoices




Kafka Twitter Producer & Advanced Configurations

    Producer and Advanced Configurations Overview
    Twitter Setup
    Producer Part 1 - Writing Twitter Client
    Producer Part 2 - Writing the Kafka Producer
    Producer Configurations Introduction
    acks & min.insync.replicas
    retries, delivery.timeout.ms & max.in.flight.requests.per.connection
    Idempotent Producer
    Producer Part 3 - Safe Producer
    Producer Compression
    Producer Batching
    Producer Part 4 - High Throughput Producer
    Producer Default Partitions and Key Hashing
    max.block.ms and buffer.memory





Topic with Multiple Partitions
Kafka Cluster with Multiple Brokers
Multiple Brokers and Topic with Replication
Kafka Consumer Groups
Performance Testing
Java/Python/nodejs


