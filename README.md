# 🏨 Turismo 4.0 API

[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-6DB33F?style=for-the-badge&logo=spring)](https://spring.io/)
[![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker)](https://www.docker.com/)

API backend desenvolvida em **Java / Spring Boot** para o ecossistema Turismo 4.0, orquestrando pontos turísticos, rotas e serviços aos viajantes.

---

## 📌 Sobre o Projeto

A **Turismo 4.0 API** centraliza o catálogo de atrativos turísticos, hotéis, restaurantes e eventos culturais. Ela se integra ao motor de IA (`turismo-route-ai`) para fornecer aos turistas itinerários inteligentes e personalizados de acordo com suas preferências e tempo disponível.

## 🚀 Funcionalidades

- 📍 **Cadastro de Pontos Turísticos:** Gestão de atrativos com geolocalização e fotos.
- 🧭 **Consulta de Rotas Otimizadas:** Comunicação com o motor genético de rotas.
- 🐳 **Ambiente Dockerizado:** `docker-compose.yml` para implantação simplificada com banco de dados.
- 🔒 **Arquitetura em Camadas:** Padrão Controller-Service-Repository com DTOs.

## 🛠️ Tecnologias Utilizadas

- **Java 17 (LTS)**
- **Spring Boot 3**
- **Maven**
- **Docker & Docker Compose**

## ⚙️ Como Executar Localmente

```bash
git clone https://github.com/IuryAlmeidaDev/turismo-api.git
cd turismo-api

# Via Maven
./mvnw clean spring-boot:run

# Via Docker Compose
docker-compose up --build
```

---

## 👤 Autor

Desenvolvido por **[Iury Almeida](https://github.com/IuryAlmeidaDev)**.
