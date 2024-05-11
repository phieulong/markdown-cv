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

`online cv`
[https://phieulong.github.io/markdown-cv/](https://phieulong.github.io/markdown-cv/)

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
Java, Golang, Rust, Elixir

`Framework/Lib`
Spring, Spring Boot, Spring web, Spring Secure, Spring Jpa, Nginx, Tokio

`Database`
MySql, PostgresQl

`Message Queues`
Kafka

`Caching`
Redis

`Version control`
Gitlab, Github

`DevOps`
CI/CD, Docker, AWS

`Test`
Automation test, BDD, TDD
- Performance Test

`OS`
Linux, Vim

`Monitor`
Splunk, Sentry, Garfana, Promethus

### Artificial intelligence

`Languages`
Python

`Framework/lib`
Pytorch, SpeechBrain, Onnx

## Work Experience

### FPT

`2016-2017`
Develop an internal web for an Japan bank.

### VinID

`2019-2020`
Build VinID services.
- Apply micro service architecture with Spring Boot.
- User 3'rd parties: Kafka,elasticsearch, Algolia, Splunk.
- Use platform to build app: Gitlab, Docker, K8s.

### OneID

`2020-2021`
- Build new payment gateway using design pattern:
  - Orchestrator
  - Strategy

### One Mount Consumer

`2021-2022`
Build social services to serve e-commerce: comment, reactions.
- Applied server send event to push comment near real time.
- Maintain loyalty customer services.

### Vuadu

`2023-present`

Ai pricing research.
- Build ai cost web.
- Convert pytorch model to onnx model.
- Study fast.ai course.

## Projects

### Order

`Description`
Create a new API to retrieve a list of orders. The API allows searching based on various criteria and utilizes cursor pagination to enhance search efficiency.

`Team size`
5

`My position`
Fresher

`My responsibilities`
Run project.
- Analyze requirements.
- Create a new api.
- Create test cases.
- Integrate with FE.

`Technologies used`
Language: Java 1.8,
- Framework: Spring, Springboot, Spring web, Spring jpa
- API: Restful
- Architecture: Microservices, Hexagonal.
- DB: MySql
- Version control: Gitlab.

### Product

`Description`
Create new api to efficiently facilitate the rapid search of various variants of a product item.

`Team size`
3

`My position`
Fresher

`My responsibilities`
Analyze requirements.
- Research about Algolia search engine.
- Create a background cronjob that runs daily midnight to push snapshot product information to Algolia.
- Create new an API specifically for mobile devices allows to retrieve detailed information for each variant.
- Write test case.
- Integrate with FE.
- Deploy to production.

`Technologies used`
Language: Java 1.8,
- Framework: Spring, Springboot, Spring web, Spring JPA
- Search Engine: Algolia
- Architecture: Microservices, Hexagonal.
- DB: MySql
- Version control: Gitlab.

### Payment

`Description`
New development of an _orchestrator_ microservice (in e-commerce system) includes operations related _Payment_ entity.

`Team size`
6

`My position`
Software Engineer.

`My responsibilities`
Analyze requirements.
- Build source base for project.
- Build CI/CD based on previous project.
- Write test cases.
- Write code implement test cases.
- Review code.

`Technologies used`
Software development practice: TDD
- Language: Java 11,
- Framework: Spring core, Springboot, Spring Web, Spring secure, Spring JPA, Kafka.
- Architecture: Microservices, Hexagonal.
- Design pattern: orchestration, strategy.
- Devops: Docker, Gitlab CI.
- DB: MySql
- Version control: Gitlab.

### Chat

`Description`
New development of a microservice (in e-commerce system) includes operations related _Comment_ entity.

`Team size`
_Only me_

`My position`
Software Engineer.

`My responsibilities`
Analyze requirement as storyboard.
- Design database and system.
- Integrate with Devops to get resource permission.
- Build source base for project.
- Build CI/CD based on previous project.
- Write test cases.
- Write code implement test cases.
- Integrate with FE members of other team.
- Integrate with Devops deploy service to stages (test, production).

`Technologies used`
Software development practice: TDD
- Language: Java 11.
- Framework: Spring core, Springboot, Spring web, Spring secure, Spring JPA  Kafka.
- Lib: Server send event to push new message from server.
- Architecture: Microservices, Hexagonal.
- Design pattern: strategy.
- Devops: Docker, Gitlab CI/CD.
- DB: MySql
- Version control: Gitlab.

### Loyalty Customer

`Description`
Team leader in maintaining a loyalty system.

`Team size`
4

`My position`
Software Engineer.

`My responsibilities`
Receive completely loyalty system.
- Monitor.
- Run campaign from marketing.
- Fix bugs.
- Develop new features.

`Technologies used`
Software development practice: TDD
- Language: Golang.
- Framework: Springboot, Spring eco, Apache Flink.
- Architecture: Microservices, Hexagonal
- Devops: Docker.
- DB: MySql
- Version control: Gitlab.

### Rezza

`Description`
Build an new application that allows user to create an 'Uber for X' type of app simply by dragging and dropping the business process

`Team size`
5

`My position`
Software Engineer.

`My responsibilities`
Analyze requirements.
- Build an MVP server with basic features such as CRUD for organizations, authentication.
- Deploy to test stage.

`Technologies used`
Software development practice: TDD
- Test practice: Automation.
- Language: Rust.
- Framework: Tokio, Oso, Cucumber.
- Architecture: Microservices, Hexagonal
- Devops: Docker, Github CI/CD.
- DB: Postgres.
- Version control: Github.

### Parser

`Description`
Write a parser with PEG lib.

`Team size`
_Only me_

`My position`
Software Engineer.

`My responsibilities`
Research parser algorithm and Pest lib.
- Write parser.

`Technologies used`
Software development practice: TDD
- Language: Rust.
- Lib: Pest.
- Version control: Github.

### AWS service migration

`Description`
Migrate completely all cloud services from EC2 to Lightsail.

`Team size`
_Only me_

`My position`
Software Engineer.

`My responsibilities`
Migrate completely all cloud services from Aws EC2 to Aws Lightsail.

`Technologies used`
Language: Elixir.
- Devops: Docker swarm, AWS Lightsail, Github Action.
- Platform: Prometheus, Grafana.
- Os: Linux.
- Version control: Github.

### AiPricing

`Description`
Build a new website allow user compare cost of ai.

`Team size`
2

`My position`
Software Engineer.

`My responsibilities`
Analyze requirements.
- Research cost ai.
- Research how a specific gpu compute and generate tokens in inference stage.
- Research how to quantize params of ai model.
- Build website to craw data from other website and calculate price.
- Deploy.

`Technologies used`
Language: Elixir.
- Devops: Fly.io.
- Version control: Github.

### Convert model
`Description`
Convert a pytorch model to run in client instead of server.

`Team size`
_Only me_

`My position`
Software Engineer.

`My responsibilities`
Study fast.ai course.
- Research onnx framework.
- Convert pytorch model to onnx which one can run in client instead of server.

`Technologies used`
Language: Python.
- Framework: Pytorch, Speechbrain, onnx.
- Version control: Github.

<!-- ### Footer

Last updated: May 2013 -->
