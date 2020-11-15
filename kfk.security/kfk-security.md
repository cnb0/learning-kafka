
## [kafka security](https://docs.confluent.io/current/security/index.html)

- Confluent Platform is the central nervous system for a business, uniting your organization around an Apache Kafka®-based single source of truth. 
- It is frequently used to store mission-critical data, and therefore enabling security features are crucial.

- By default, there is no encryption, authentication, or ACLs configured.
- Any client can communicate to Kafka brokers via the PLAINTEXT port. It is critical that access via this port is restricted to trusted clients only. Network segmentation and/or authorization ACLs can be used to restrict access to trusted IPs in such cases. If neither is used, the cluster is wide open and can be accessed by anyone.

While non-secured clusters are supported, as are a mix of authenticated, unauthenticated, encrypted and non-encrypted clients, it is recommended to secure the components in your Confluent deployment.

To learn more, refer to Best Practices to Secure Your Apache Kafka Deployment.

To see a working deployment of encryption, authentication, and authorization configured end-to-end across all Confluent Platform components, check out the Confluent Platform demo.


```
                Security Tutorial
                Encryption with SSL
                Secrets
                Encryption and Authentication with SSL
                Authentication with SASL
                HTTP Basic Auth
                Authorization using Role-Based Access Control
                Authorization using centralized ACLs
                Configure RBAC using the REST API
                Authorization using ACLs
                Audit Logs
                Cluster registry
                Streams Security
                Kafka Connect Security
                ksqlDB RBAC
                Confluent Control Center Security
                REST Proxy Security
                Schema Registry Security
                Confluent Security Plugins
                Docker Security
                Prefixes for Configuring Security
                Security Compliance
                ZooKeeper Security
                Adding security to a running cluster
    ```