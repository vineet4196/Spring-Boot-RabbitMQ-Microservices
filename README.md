# Spring Boot RabbitMQ Microservices Project

## Overview
This project shows how to build an **event-driven microservices architecture** using **RabbitMQ** as a message broker. Multiple services communicate asynchronously by publishing and consuming messages.

## Features
- **Order Service**: Publishes messages when an order is created.
- **Stock Service**: Consumes messages to manage inventory.
- **Email Service**: Consumes messages to send notifications.
- **Multiple Queues**: Different queues for different types of events.
- **Decoupled Communication**: Services are independent and interact only via RabbitMQ.

## Tech Stack
- Java, Spring Boot
- RabbitMQ
- Spring AMQP

## Learning Goals
- Integrate RabbitMQ with Spring Boot
- Configure exchanges, queues, and bindings
- Build microservices that use asynchronous messaging
- Understand routing patterns in RabbitMQ
