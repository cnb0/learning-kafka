## [Confluent Schema Management](https://docs.confluent.io/current/schema-registry/index.html)


        - Confluent Schema Registry provides a serving layer for your metadata. 
        - It provides a RESTful interface for storing and retrieving your Avro®, JSON Schema, and Protobuf schemas. 
        - It stores a versioned history of all schemas based on a specified subject name strategy, provides multiple
          compatibility settings and allows   evolution of schemas according to the configured compatibility settings and
          expanded support for these schema types. It provides serializers that plug into Apache Kafka® clients that
          handle schema storage and retrieval for Kafka messages that are sent in any of the supported formats.

        - Schema Registry lives outside of and separately from your Kafka brokers. 
        - Your producers and consumers still talk to Kafka to publish and read data (messages) to topics. 
        - Concurrently, they can also talk to Schema Registry to send and retrieve schemas that describe the 
          data models for the messages.


            - Install and config
            - schema registry tutorials
            - schema validation
            - monitoring
            - Schema formats,serializers & deserializers
            - single and multi data centre setup
            - Schema evolution and compatibility
            - Schemas in control center
            - Schemas on confluent cloud
            - migrate schemas
            - deleting schemas
            - Security
            - Developer guide
            - Using Kafka Connect with Schema Registry
