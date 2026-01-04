# Desafio BTG Pactual Backend — Spring Boot, RabbitMQ e MongoDB

Este repositório contém a resolução do desafio backend do BTG Pactual em Java, com foco em tecnologias do ecossistema Spring e mensageria. O objetivo principal foi replicar a solução e aprimorar minhas habilidades com:

- Spring Boot
- RabbitMQ
- MongoDB
- Docker e Docker Compose
- APIs REST

Esse projeto foi ideal para praticar e me aprofundar conceitos de microserviços, filas de mensagens e bancos NoSQL em um contexto real de desafio técnico.

## Estrutura do Projeto

Após clonar este repositório, você encontrará:

| Arquivos                  |
|---------------------------|
| `src/`                    |
| `docker-compose.yml`      |
| `Dockerfile`              |
| `pom.xml `                |
| `problem.md (enunciado)`  |
| `README.md`               |

## Sobre o Desafio

1. Criar uma API REST com Spring Boot.
2. Consumir mensagens da fila RabbitMQ.
3. Persistir dados no MongoDB.
4. Configurar os serviços via Docker/Docker Compose.

## Vídeo de Apoio — Build & Run

Utilizei um vídeo tutorial completo do canal **Build & Run** que resolve esse mesmo desafio.

🔗 **Assista aqui:**  
👉 (https://www.youtube.com/watch?v=e_WgAB0Th_I&t=427s)
Esse vídeo demonstra passo a passo do zero ao funcionamento, o que foi um suporte valioso enquanto eu replicava o desafio em meu ambiente local.

## Como Rodar o Projeto

### 1. Clone este repositório
```bash
git clone https://github.com/Ikajira/desafio-btg-pactual-backend.git
cd desafio-btg-pactual-backend
```

### 2 - Inicie o Docker Compose:
  ```bash
  docker compose up -d
  ```

### 3 -  Execute a aplicação:
```bash
mvn spring-boot:run
```
### 4 - Acesse os endpoints da API:
Use ferramentas como Postman ou Insomnia para testar a API.
