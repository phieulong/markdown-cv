---
layout: cv
title: Nguyen Quang Nhat's CV
---

# Nguyen Quang Nhat

Software Engineer, FPT University

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
Award in Discussion contest in American embassy

## Skills

### Web Developer

`Languages`

- Java, Golang, Rust

`Framework/Lib`

- Spring Boot, Nginx, Tokio-

`Database`

- MySql, PostgresQl

`Message Queues`

- Kafka, Redis

`DevOps`

- Github, CI/CD, Docker, AWS

`Test`

- Automation test, BDD, TDD
- Performance Test

`OS`

- Linux, Vim

`Monitor`

- Splunk, Sentry, Garfana, Promethus

## Artificial intelligence

`Languages`

- python

`Framework/lib`

- Pytorch, Onnx

## Work Experience

### FPT

`2016-2017`

- Develop a web to study online for FPT University

### VinID

`2019-2020`

- Apply micro service architecture with Spring Boot to build Scan and Go
- User 3'rd parties: Kafka,elasticsearch, Algolia, Splunk.
- Use platform to build app: Gitlab, Docker, K8s

### OneID

`2020-2021`

- Build new payment gateway using design pattern: Orchestrator, Chain, Strategy, Factory,..

### One Mount Consumer

`2021-2023`

- Build social services to serve ecommerce: comment, reactions, ...
- Applied server send event to push comment near real time

### Vuadu

`2023-present`

- Ai pricing research
- Build ai cost web
- Study fast.ai course

## Projects

### Order Service

- I have created a new API to retrieve a list of orders. The API allows searching based on various criteria and utilizes cursor pagination to enhance search efficiency1.

### Product Service

To efficiently facilitate the rapid search of various variants of a product item, I conducted research and leveraged the Algolia service. Here is what I implemented:

- Snapshot Push to Algolia:
  - I created a background worker that runs daily.
  - This worker retrieves snapshot information for each variant and pushes it to Algolia.
  - By doing so, Algolia is kept up-to-date with the latest variant data.
- API for Mobile Retrieval:
  - Additionally, I developed an API specifically for mobile devices.
  - After receiving search results from Algolia, this API allows mobile clients to retrieve detailed information for each variant.
  - Algolia has proven to be an effective solution for enhancing search performance and providing real-time data access.

### Payment Gateway

Due to the company"s anticipated need to support multiple payment methods in the future, adjustments are necessary for the order service to facilitate easier configuration. In this project, my co-workers and I implemented an abstraction layer for order payment by building an additional service orchestration. This orchestration coordinates payment flows, allowing the order service to call it instead of directly invoking the payment service as previously done.

### Chat Service

I am the primary backend developer for this project. I have created two services: Comment and Notification. The Comment service is responsible for recording comment and chat content, and subsequently sending messages upon successful creation. The Notification service listens for events and pushes notifications to clients via Server-Sent Events (SSE). Additionally, the Notification service provides an API for clients to subscribe and receive notifications during conversations or videos.

<!-- ### Footer

Last updated: May 2013 -->
