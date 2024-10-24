# Docker Compose Manifests Repository

This repository contains several Docker Compose manifests designed to deploy different services.

## Contents

- **[Bitnami-Kafka](https://hub.docker.com/r/bitnami/kafka)**
  - **Description:** This Docker Compose manifest deploys a Kafka cluster using Bitnami images, ensuring an easy and efficient setup. Along with Kafka, AKHQ (formerly known as KafkaHQ) is deployed, a management tool for Kafka that allows you to visualize, manage, and operate Kafka clusters through a web interface.

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

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/nortic97/Docker-Manifests.git
   cd Docker-Manifests
