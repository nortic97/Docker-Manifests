# Docker Compose Manifests Repository

This repository contains several Docker Compose manifests designed to deploy different services.

## Contents

- **[Bitnami-Kafka](https://hub.docker.com/r/bitnami/kafka)**
  - **Description:** This Docker Compose manifest deploys a Kafka cluster using Bitnami images, ensuring an easy and efficient setup. Along with Kafka, AKHQ (formerly known as KafkaHQ) is deployed, a management tool for Kafka that allows you to visualize, manage, and operate Kafka clusters through a web interface.

- **[Redis](#https://hub.docker.com/_/redis)**
  - **Description:** This manifest sets up a Redis instance along with RedisInsight, a graphical management tool for Redis.

## Included Services

### **[Bitnami-Kafka](https://hub.docker.com/r/bitnami/kafka)**

Bitnami Kafka is an optimized and easy-to-use distribution of Apache Kafka. This service includes the following components:

- **Kafka**: A broker that handles distributed messaging.

### **[Akhq.io](https://akhq.io/docs/)**

AKHQ is a web-based management platform for Apache Kafka. It provides the following features:

- Visualization of Kafka clusters and topics.
- Creation, update, and deletion of topics.
- Monitoring of consumers and producers.
- Viewing and querying messages.

#### **[Redis](https://redis.io/es/)**

Redis is an open-source, in-memory key-value store that supports various data structures and provides high performance and versatility.

**Features:**
- In-memory data storage with low latency.
- Support for complex data types like strings, hashes, lists, sets, and sorted sets.
- Persistence through RDB snapshots and AOF logs.
- Pub/Sub messaging and Lua scripting.
- Horizontal scaling with Redis Cluster and Redis Sentinel for high availability.

#### **[RedisInsight](https://redis.io/insight/)**

RedisInsight is a web-based management platform for Redis that simplifies the visualization and management of Redis databases.

**Features:**
- Explore and interact with Redis data structures through an intuitive interface.
- Monitor performance metrics, including latency and memory usage.
- Visualize key distributions and optimize database usage.
- Debug and execute Redis commands directly from the interface.
- Manage multiple Redis databases from a single dashboard.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/nortic97/Docker-Manifests.git
   cd Docker-Manifests
