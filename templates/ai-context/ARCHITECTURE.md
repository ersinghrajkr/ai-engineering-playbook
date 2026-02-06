# 🏗 Architecture — GharTak

## Style
NestJS Modular Monolith

## Communication
- REST APIs only
- GraphQL optional for admin dashboards only
- No event-driven architecture
- No queues
- No Kafka/RabbitMQ
- No microservices

## Module Pattern
Each feature is isolated:

feature/
  feature.module.ts
  feature.controller.ts
  feature.service.ts
  feature.repository.ts
  dto/
  entities/

## Flow
Controller → Service → Repository → Database

## Infrastructure
- Single VPS
- Docker
- Nginx
- Single database

## Philosophy
Keep architecture simple.
Scale only when required.
Avoid premature optimization.
