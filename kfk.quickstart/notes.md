## Kafka Learning path 
```

Theory Overview
        Topics, Partitions and Offsets
        Brokers and Topics
        Topic Replication
        Producers and Message Keys
        Consumers & Consumer Groups
        Consumer Offsets & Delivery Semantics
        Kafka Broker Discovery
        Zookeeper
        Kafka Guarantees

Starting kafka
    Starting Kafka with the Confluent CLI/Cloud/Confluent Platform
    Starting a multi broker Kafka Cluster using Binaries
    Start Kafka Development environment using Docker
    Starting a multi broker Kafka Cluster using Docker
    Kafka Advertised Host Setting
    
Kafka CLI 
        Kafka Topics CLI
        Kafka Console Producer CLI
        Kafka Console Consumer CLI
        Kafka Consumers in Group
        Kafka Consumer Groups CLI
        Resetting Offsets
        CLI Options that are good to know
        What about UIs? Conduktor
        KafkaCat as a replacement for Kafka CLI

Advanced Topic config
        Changing a Topic Configuration
        Segment and Indexes
        Log Cleanup Policies
        Log Cleanup Delete
        Log Compaction Theory
        Log Compaction Practice
        min.insync.replicas reminder
        Unclean Leader Election

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


Kafka ElasticSearch Consumer & Advanced Configurations
        Consumer and Advanced Configuration Overview
        Setting up ElasticSearch in the Cloud
        ElasticSearch 101
        Consumer Part 1 - Setup Project
        Consumer Part 2 - Write the Consumer & Send to ElasticSearch
        Delivery Semantics for Consumers
        Consumer Part 3 - Idempotence
        Consumer Poll Behaviour
        Consumer Offset Commit Strategies
        Consumer Part 4 - Manual Commit of Offsets
        Consumer Part 5 - Performance Improvement using Batching
        Consumer Offsets Reset Behaviour
        Consumer Part 6 - Replaying Data
        Consumer Internal Threads
