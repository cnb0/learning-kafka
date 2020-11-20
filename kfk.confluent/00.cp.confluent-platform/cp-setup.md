## Confluent platform 

```
Manual : 

    - Quick Start for Apache Kafka using Confluent Platform (Local)  - GUI 
        -  Setup Confluent Platform and its main components in a dev environment. 
        -  Uses Confluent Control Center included in Confluent Platform for topic management and event stream processing using ksqlDB.
            - We create Apache Kafka® topics, 
            - use Kafka Connect to generate mock data to those topics 
            - create ksqlDB streaming queries on those topics. 
            - UseControl Center to monitor and analyze the streaming queries.
            - https://docs.confluent.io/current/quickstart/ce-quickstart.html#ce-quickstart
            - https://github.com/confluentinc/examples/blob/6.0.0-post/cp-quickstart/README.md

                - Step 1: Download and Start Confluent Platform
                - Step 2: Create Kafka Topics
                - Step 3: Install a Kafka Connector and Generate Sample Data
                - Step 4: Create and Write to a Stream and Table using ksqlDB
                - Step 5: Monitor Consumer Lag
                - Step 6: Stop Confluent Platform


    - Quick Start for Apache Kafka using Confluent Platform Community Components (Local) - CLI

        - Setup and  running with Confluent Platform and Confluent Community components in a development environment.
        - we create Apache Kafka® topics, use Kafka Connect to generate mock data to those topics, and create ksqlDB streaming queries on those topics.
        - This quick start leverages the 
                - Confluent Platform CLI, 
                - the Apache Kafka® CLI, 
                - ksqlDB CLI. 
                
                
        - For a rich UI-based experience, try out the Confluent Platform quick start with commercial components.

            - Step 1: Download and Start Confluent Platform
            - Step 2: Create Kafka Topics
            - Step 3: Install a Kafka Connector and Generate Sample Data
            - Step 4: Create and Write to a Stream and Table using ksqlDB
                - Examine Streams, Tables, and Queries
            - Step 5: Monitor Streaming Data

 
Docker :
        - https://github.com/cnb0/learning-kafka/tree/main/WS/00.kfk.confluent.docker.setup
                Single Zookeeper / Single Kafka
                Single Zookeeper / Multiple Kafka
                Multiple Zookeeper / Single Kafka
                Multiple Zookeeper / Multiple Kafka

       -  Quick Start for Apache Kafka using Confluent Platform (Docker)
                 Step 1: Download and Start Confluent Platform Using Docker
                 Step 2: Create Kafka Topics
                 Step 3: Install a Kafka Connector and Generate Sample Data
                 Step 4: Create and Write to a Stream and Table using ksqlDB
                 Step 5: Monitor Consumer Lag
                 Step 6: Stop Docker

Automated :
    - Ansible
    - kubernetes 
Cloud :
Kubernetes :
