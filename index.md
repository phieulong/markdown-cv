---
layout: cv
title: Nguyen Quang Nhat's CV
---

# Nguyen Quang Nhat

Software Engineer, FPT University

## Contact

`email`
phieulong97@gmail.com
`phone number`
0837060716

## Research interests

Web developer, artificial intelligence

## Education

`2015-2019`
FPT University
GPA: 2.6

## Awards

`2013`

3rd prize of Nghe An provincial in information technology excellent student contest.

`2016`

Award in Discussion contest in American embassy.

## Skills

### Web Developer

`Languages`

- Java, Golang, Rust, Elixir

`Framework/Lib`

- Spring Boot, Nginx, Tokio

`Database`

- MySql, PostgresQl

`Message Queues`

- Kafka

`Caching`

- Redis

`Version control`

- Gitlab, Github

`DevOps`

- CI/CD, Docker, AWS

`Test`

- Automation test, BDD, TDD
- Performance Test

`OS`

- Linux, Vim

`Monitor`

- Splunk, Sentry, Garfana, Promethus

### Artificial intelligence

`Languages`

- Python

`Framework/lib`

- Pytorch, SpeechBrain, Onnx

## Work Experience

### FPT

`2016-2017`

- Develop an internal web for an Japan bank.

### VinID

`2019-2020`

- Build VinID services.
- Apply micro service architecture with Spring Boot.
- User 3'rd parties: Kafka,elasticsearch, Algolia, Splunk.
- Use platform to build app: Gitlab, Docker, K8s.

### OneID

`2020-2021`

- Build new payment gateway using design pattern:
  - Orchestrator
  - Strategy
  - Factory

### One Mount Consumer

`2021-2022`

- Build social services to serve e-commerce: comment, reactions.
- Applied server send event to push comment near real time.
- Maintain loyalty customer services.

### Vuadu

`2023-present`

- Ai pricing research.
- Build ai cost web.
- Convert pytorch model to onnx model.
- Study fast.ai course.

## Projects

### Order

- I created a new API to retrieve a list of orders. The API allows searching based on various criteria and utilizes cursor pagination to enhance search efficiency.

### Product

To efficiently facilitate the rapid search of various variants of a product item, I conducted research and leveraged the Algolia service. Here is what I implemented:

- I created a background worker that runs daily to snapshot push to Algolia:
- Additionally, I developed an API specifically for mobile devices.
  - After receiving search results from Algolia, this API allows mobile clients to retrieve detailed information for each variant.
  - Algolia has proven to be an effective solution for enhancing search performance and providing real-time data access.

### Payment

In this project, my co-workers and I implemented an abstraction layer for order payment by building an additional orchestration service. This service coordinates payment flows, allowing the order service to call it instead of directly invoking the payment service as previously done.

### Chat

I was the primary backend developer for this project. I have created two services: Comment and Notification. The Comment service is responsible for recording comment and chat content, and subsequently sending messages upon successful creation. The Notification service listens for events and pushes notifications to clients via Server-Sent Events (SSE). Additionally, the Notification service provides an API for clients to subscribe and receive notifications during conversations or videos.

### Loyalty Customer

I was the leader of a backend developer team and have been entrusted with the customer care system. My main responsibilities include monitoring and, along with my fellow fresher colleagues, running marketing campaigns and fixing bugs. The core technology in this system is Kafka Flow, which handles event reception, filtering, and computation based on available information and predefined event structures. Microservices are built around this technology to create campaigns, define event structures, and allow consumers to listen for events from Kafka Flow to distribute rewards or points to users.

### Rezza

Rezza is an application that allows you to create an 'Uber for X' type of app simply by dragging and dropping the business process. Myself and another backend developer have built an MVP server with basic features such as CRUD for organizations, authentication, and copying process-related features like creation, updating, and execution. We used the Rust programming language for development.

### Parser

I created a parser supported by Pest. This parser parses PEG into an rust object.

### AWS service migration

I have completely migrated all cloud services from EC2 to Lightsail.

### AiPricing

I and my co-worker collected data from websites that offer AI services or rent GPUs for deploying AI models. Additionally, I researched how to calculate the number of tokens processed and generated within a specific time frame by a GPU and a pre-trained model. Based on this, we built a price comparison website for running or training models from various providers. We used the Elixir programming language for development and Fly.io to deploy.

### Convert model

I have converted pytorch model to onnx which one can run in client instead of server.

<!-- ### Footer

Last updated: May 2013 -->
