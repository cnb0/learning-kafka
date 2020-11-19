# learning-kafka
```

1. Kafka Cluster Setup
        - Standalone
            - A single node – single  broker cluster
            - A single node – multiple broker clusters
        - Confluent
        - Hardware and OS Config
            - OS,Disks and Filesystems
            - Application vs OS Flush Management
            - Linux Flush Behavior
            - Ext4 filesystem

2. Kafka Cluster Architecture/Components
        - Zookeeper in Kafka
        - Kafka Cluster Controller
        - Partition Allocation and Fault Tolerance
        - Partition Leader Vs Partition Follower
        - The ISR List - In Sync Replica
        - Committed Vs Un-Committed Records
        - Minimum ISR List
        - Kafka Storage Architecture
               - Topics, Replication and Partitions
               - Partition Leaders and Followers
               - Log Segments
               - Message Offsets,Index
 
 3. Kafka cluster Admin/Config/Tuning
       - KAFKA CLI/UI
            - Console Producer/Consumer CLI
            - Topics CLI
            - Consumers in Group
            - Kafka Consumer Groups CLI
            - Resetting Offsets
            - What about UIs? Conduktor
            - KafkaCat as a replacement for Kafka CLI
            - Confluent Control Center (UI)
        - Broker Config
        - Topic Config
        - Producer Config
        - Consumer Config
        - Kafka Connect Configs
        - kafka Client/Server Configs
        - Graceful shutdown
        - Balancing leadership
        - Checking consumer position
        - Mirroring data between clusters
        - Expanding your cluster
        - Decommissioning brokers
        - Config replication factor
        - Kafka Cluster Upgrade
       
               
4. Kafka KSQL/ksqlDB, Avro, Confluent Schema Registry and Kafka REST Proxy
      -  Build Avro Producers/Consumers, Evolve Schemas
          - Avro Schemas
          - Avro in Java/Python/C++
          - Setup and Launch Kafka
      -  Confluent Schema Registry and Kafka
      - Confluent REST Proxy
      - KSQL/KSQLDB in Dev/Production
     -  Kafka Streams Using the UI 
   
5. Kafka Connect
        - How to Source Twitter Data, Store in Apache Kafka Topics &
          Sink in ElasticSearch and PostgreSQL
        - Setup and Launch Kafka Connect Cluster
        - Kafka Connect Source and Sink
        - Troubleshooting Kafka Connect
        - Kafka Connect in production

6. Kafka Security, Monitoring & Operations
       - Monitoring server statistics
       - Monitoring producer statistics
       - Monitoring consumer statistics
       - Implementing authentication using SSL
       
Kafka Workshop - Projects/UseCases :
       - Kafka Twitter Producer & Advanced Configurations
       - Topic with Multiple Partitions
       - Kafka Cluster with Multiple Brokers
       - Multiple Brokers and Topic with Replication
       - A multi-node – multiple broker clusters  
       - Spark overview
       - Kafka Consumer Groups
       - Performance Testing
       - Java/Python/nodejs
