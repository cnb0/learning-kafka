
### Kafka - Avro 
          - Confluent Schema Registry 
          - Kafka REST Proxy 
          - Build Avro Producers/Consumers, Evolve Schemas


```
## Objectives :

Write simple and complex Avro Schemas
Create, Write and Read Avro objects in Java
Write a Java Producer and Consumer leveraging Avro data and the Schema Registry
Learn about Schema Evolution
Perform Schema evolution using the command line and in Java
Utilize the REST Proxy using a REST Client

## Module outline

    - Introduction: 
                - Let's learn why we need Schema, and what the target Kafka architecture will look like. 

    - Avro Schemas: 
                - Master how to write simple and complex Avro Schemas for your Kafka messages, 
                as well as Schema Evolution rules and guidelines. 

    - Avro in Java: 
                - Learn how to create Avro records using GenericRecord, SpecificRecord, and ReflectedRecord. 
                - Also perform your first schema evolution in Java. 

    - Setup and Launch Kafka: 
            - Install Docker and use Docker Compose to start your Apache Kafka Cluster 
              that will contain the Confluent Schema Registry and the Kafka REST Proxy.

    - Confluent Schema Registry and Kafka: 
            - Learn what is the Confluent Schema Registry, how it works. 
            - Learn to use the Kafka Avro Console Producer & Consumer 
            - write your first Apache Kafka Avro Java Producer and Avro Java Consumer.
              Perform a fully compatible schema evolution

   - Confluent REST Proxy: 
           - Learn how to use the REST Proxy with a REST Client (Insomnia) in order to interface with Apache Kafka using REST. 
           - Understand how to read Kafka topic metadata, produce and consume binary, JSON and Avro data


## Apache Avro 

        - It is one of the most powerful and most popular fast data serialisation mechanism with Apache Kafka
        - Schema is a first class citizen of the data
        - Data serialisation format that is lightweight
        - Documentation is embedded in the schema
        - Easy to read and write using many languages
        - Fast & Big data de-facto data serialisation format

##  Confluent Schema Registry for Apache Kafka

        - It is the de-facto standard way of storing Avro Schemas for your Apache Kafka Topics.
        - Stores a versioned history of all your schemas in Apache Kafka
        - Supports and enforces conditions for schema evolution (backward, forward, full compatibility)
        - Kafka Avro Serialiser and Deserialiser automatically integrate with Apache Kafka and Confluent Schema Registry
        - Make your messages much smaller and lighter! Perfect for increasing Apache Kafka throughput and performance

## Confluent REST Proxy 

        - It is  the perfect way to communicate for sending Avro data using non Java languages to Apache Kafka. 
        - Write and Read binary, JSON and Avro data to Apache Kafka using an HTTP REST API
        - Interact with Apache Kafka using any programming language (not just Java)
        - Consult topic list and topic metadata in Apache Kafka
        - Avro Schema and Avro in Java is fully understood before moving to the Confluent Schema Registry for Apache Kafka. 


## Resources :

        - [avro](https://www.tutorialspoint.com/avro/avro_schemas.htm)
