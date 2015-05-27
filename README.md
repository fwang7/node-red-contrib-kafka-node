# Kafka Node
Kafka node can produce/consume the mesasges to/from kafka cluster along with topic(s) on [NodeRED].


# Install

Install from [npm](http://npmjs.org)
```
npm install -g node-red-contrib-kafka-node
```

# Prerequisites
 * Node-RED platform. (see [Node-RED](http://nodered.org/docs/getting-started/installation.html))
 * Kafka cluster (see [Kafka](http://kafka.apache.org/documentation.html#gettingStarted)). 
 * Some topics (see [how to create a topic](http://kafka.apache.org/documentation.html#quickstart))

# Usage
##### Producer Node
- Parameters:
 - Zookeeper Quarum
 - Topics

##### Consumer Node
- Parameters:
 - Zookeeper Quarum
 - Topics
 - GroupId


# Version
0.1.1

# Tech
 * [Kafka] - Apache Kafka is publish-subscribe messaging rethought as a distributed commit log.
 * [Zookeeper] - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.
 * [Kafka-Node] - Kafka-node is a Node.js client with Zookeeper integration for Apache Kafka 0.8.1 and later. 

[Kafka]:http://kafka.apache.org/
[Zookeeper]:https://zookeeper.apache.org/
[NodeRED]:http://nodered.org
[Kafka-Node]:https://www.npmjs.com/package/kafka-node


# Authors

* Feng Wang - [fwang1@us.ibm.com](mailto:fwang1@us.ibm.com)