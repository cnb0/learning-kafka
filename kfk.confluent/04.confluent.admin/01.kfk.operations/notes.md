


[Self-Balancing Clusters](https://docs.confluent.io/platform/current/kafka/sbc/index.html)
[Adding and removing brokers](https://docs.confluent.io/platform/current/kafka/sbc/sbc-tutorial.html)
[Configuration Options and Commands for Self-Balancing Clusters](https://docs.confluent.io/platform/current/kafka/sbc/configuration_options.html)
       ```
    - Self-Balancing Configurations on the Brokers
    - Required Configurations for Control Center
    - Update broker configurations on the fly
        - Enable Self-Balancing
        - Set trigger condition for rebalance
        - Set or remove a custom throttle
    - kafka-remove-brokers-  Broker Removal Phases
    ```

[Changing Broker Configurations Dynamically](https://docs.confluent.io/platform/current/kafka/dynamic-config.html#)
        - Changing Topic Configurations Dynamically

[Post Kafka Deployment](https://docs.confluent.io/platform/current/kafka/post-deployment.html)
```
        - Logging
        - Controller
        - State Change Log
        - Request logging
        - Admin operations
            - Adding/modifying/deleting topics
            - graceful shutdown
        - rolling restart 
        - Scaling the Cluster
        - Increasing replication factor
        - Limiting Bandwidth Usage during Data Migration
        - Balancing Replicas Across Racks
        - Enforcing Client Quotas
        - Performance Tips
            - Picking the number of partitions for a topic
            - Tuning virtual memory
            - Lagging replicas
            - Handling large message sizes
    [Performance and Resource Usage Test Results](https://docs.confluent.io/platform/current/kafka/sbc/performance.html)
        - Add brokers to expand a small cluster with a high partition count
        - Test scalability of a large cluster with many partitions
        - Repeatedly bounce the controller
    [Auto Data Balancing](https://docs.confluent.io/platform/current/kafka/rebalancer/index.html)
    [Upgrade Confluent Platform](https://docs.confluent.io/platform/current/installation/upgrade.html#)
    [Prepare ansible install](https://docs.confluent.io/ansible/current/ansible-prepare.html)
   ``` 

