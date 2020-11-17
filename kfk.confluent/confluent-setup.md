## Confluent platform setup 

``

- Get started with Confluent Platform
        Confluent Platform is a streaming platform that enables you to organize and manage data from 
        many different sources with one reliable, high performance system. 
        
        - What is Confluent Platform?
        - Apache Kafka Quick Start
            - Start Kafka in any cloud (AWS, Azure, GCP)
            - Install Apache Kafka using Confluent Platform on your machine
                - [Docker](https://docs.confluent.io/current/quickstart/ce-docker-quickstart.html#ce-docker-quickstart)
                - [Local](https://docs.confluent.io/current/quickstart/ce-quickstart.html#ce-quickstart)

        - [Kafka Basics on Confluent Platform](https://docs.confluent.io/current/kafka/kafka-basics.html#ak-basics)
        
        - [Introduction to Kafka](https://docs.confluent.io/current/kafka/introduction.html#intro-to-ak)
        
        - [Kafka Design](https://docs.confluent.io/current/kafka/design.html#ak-design)

        - [Confluent Demos](https://docs.confluent.io/current/tutorials/index.html#tutorials)

                - Confluent Platform Demo -[cp-demo](https://docs.confluent.io/current/tutorials/cp-demo/docs/index.html#cp-demo)
                - [github examples](https://github.com/confluentinc/examples)
                - [streams github](https://github.com/confluentinc/kafka-streams-examples)
                - [Build Your Own Demos](https://docs.confluent.io/current/tutorials/build-your-own-demos.html#build-your-own-demos)
                - [Security Tutorial]()
                - [Write a User Defined Function (UDF) for ksqlDB]
                - [Monitoring Kafka in Confluent Control Center]


- Get started with Confluent Cloud
        - Confluent Cloud is a resilient, scalable streaming data service based on Apache Kafka®, delivered as a fully managed service. 
          Confluent Cloud has a web interface and local command line interface. 
        - You can manage cluster resources, settings, and billing with the web interface. 
          You can use Confluent Cloud CLI to create and manage Kafka topics. 
        - Sign up for Confluent Cloud to get started.

               - What is Confluent Cloud?
               - Quick Start for Apache Kafka using Confluent Cloud
               - Supported Features for Confluent Cloud
               - FAQ for Confluent Cloud
               - Confluent Cloud documentation

               - [Confluent Cloud Demos Overview](https://docs.confluent.io/current/tutorials/examples/ccloud/docs/ccloud-demos-overview.html#ccloud-demos-overview)











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
