# 🌐 TCW Project

Welcome to the **TCW Organization** — a modular system for web crawling, graph analysis, and knowledge storage.

## 🚀 Repositories
- [tcw-core](https://github.com/your-org/tcw-core) → C++ engine for crawling & graph algorithms
- [tcw-db](https://github.com/your-org/tcw-db) → Database layer (Neo4j + persistence API)
- [tcw-gateway](https://github.com/your-org/tcw-gateway) → Flask API gateway connecting frontend ↔ core ↔ db
- [tcw-frontend](https://github.com/your-org/tcw-frontend) → Web UI
- Additional microservices coming soon…

## 🏗️ Architecture
```mermaid
graph TD
    Frontend --> Gateway
    Gateway --> Core
    Gateway --> DB
    Core --> DB
