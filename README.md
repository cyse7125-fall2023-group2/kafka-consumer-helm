# Kafka and Web Application Helm Chart

This Helm chart deploys Apache Kafka along with a web application that interacts with Kafka. The chart is designed to provide a convenient way to set up and manage Kafka and the associated web application in a Kubernetes environment.

## Prerequisites

- Helm should be installed in your Kubernetes cluster.
- [Optionally] Kafka and Zookeeper should be available in your container registry.



# Kafka and Web Application Helm Chart

This Helm chart deploys Apache Kafka along with a web application that interacts with Kafka. The chart is designed to provide a convenient way to set up and manage Kafka and the associated web application in a Kubernetes environment.

## Project Overview

The project consists of two main components:

1. **Kafka Deployment:**
    - Apache Kafka is a distributed streaming platform that allows you to build real-time data pipelines and streaming applications. This Helm chart facilitates the deployment of Kafka brokers in a scalable and fault-tolerant manner.
    - Kafka is exposed with a service for communication with external components.

2. **Web Application Deployment:**
    - The web application is an example application that demonstrates interacting with Kafka. It can produce and consume messages from Kafka topics.
    - The web application is packaged as a container image.

