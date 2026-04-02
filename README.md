<<<<<<< HEAD
# Spring-AI

A simple Spring Boot project integrating AI capabilities using modern tools and APIs.

## 🚀 Features

* Spring Boot based backend
* AI integration (chat / text generation)
* REST APIs for interaction
* Easy to extend and customize

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring AI (or OpenAI API)
* Maven

## 📂 Project Structure

```
Spring-AI/
│── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│── pom.xml
│── README.md
```

## ⚙️ Setup & Run

1. Clone the repository

```
git clone https://github.com/Seenu-keshav/Spring-AI.git
```

2. Navigate to project

```
cd Spring-AI
```

3. Build the project

```
mvn clean install
```

4. Run the application

```
mvn spring-boot:run
```

## 🔑 Configuration

Add your API key in `application.properties`:

```
openai.api.key=YOUR_API_KEY
```

## 📡 API Example

```
GET /api/chat?message=Hello
```

## 🤝 Contributing

Feel free to fork this repo and submit pull requests.

## 📄 License

This project is open-source and available under the MIT License.

---

✨ Created by Seenu Keshav
=======
# From Java Dev to AI Engineer: Spring AI Fast Track

## 🌱 Spring AI Course – Resources & Reference Links

Welcome to the official GitHub repository for the **Spring AI Course**. This course helps you build intelligent applications using the Spring AI framework and integrate powerful LLMs like OpenAI into your Spring Boot apps.

Below are some carefully curated reference links and tools used throughout the course. Bookmark this information for quick access during development and exploration.

---

## 📘 Official Documentation

- **[Spring AI Official Documentation](https://docs.spring.io/spring-ai/reference/index.html)**  
  The core reference for understanding Spring AI modules, configuration, and supported AI providers.

- **[OpenAI Platform Docs](https://platform.openai.com/docs/overview)**  
  Learn how to use OpenAI's APIs including ChatGPT, GPT-4, embeddings, and more.

---

## 🤖 AI Providers & Runtimes

- **[Ollama](https://ollama.com)**  
  Run open-source large language models (LLMs) locally on your machine with simple commands.

- **[AWS Bedrock](https://aws.amazon.com/bedrock/)**  
  Access foundation models from various providers via a fully managed AWS service.

- **[Docker Desktop](https://www.docker.com/products/docker-desktop/)**  
  Essential for running local AI model runtimes and Docker Compose setups used in the course.

- **[Docker Model Runner](https://docs.docker.com/ai/model-runner/)**  
  Use Docker’s official tool for running and managing AI models locally.

---

## 📚 Foundational Papers & Tools

- **[Attention Is All You Need (Transformer Paper)](https://arxiv.org/abs/1706.03762)**  
  The seminal research paper that introduced the Transformer architecture behind modern LLMs.

- **[OpenAI Tokenizer Tool](https://platform.openai.com/tokenizer)**  
  Visualize how OpenAI tokenizes input prompts and estimate token usage.

---

## 📦 Vector Store & MCP

- **[Qdrant Vector Database](https://qdrant.tech)**  
  An open-source vector store used in Retrieval-Augmented Generation (RAG) demos with Spring AI.

- **[Model Context Protocol (MCP)](https://modelcontextprotocol.io/)**  
  A protocol for connecting AI clients and servers in a decoupled and extensible way.

---

## 📊 Observability & Monitoring Tools

- **[Prometheus](https://prometheus.io/)**  
  Monitoring and alerting toolkit for collecting Spring Boot and AI app metrics.

- **[Micrometer](https://micrometer.io/)**  
  Java metrics collection library used with Spring Boot to expose observability data.

- **[OpenTelemetry](https://opentelemetry.io/)**  
  Industry-standard framework for distributed tracing and telemetry data.

- **[Grafana](https://grafana.com/)**  
  Visualization tool for creating dashboards from Prometheus and other data sources.

- **[Jaeger Tracing](https://www.jaegertracing.io/)**  
  Distributed tracing platform used to trace and monitor AI request flows.

---

## 📎 Stay Connected

---

📬 For questions or issues, raise a GitHub issue or connect with the course instructor

Happy Learning! 🚀  
>>>>>>> ec5038f (Initial commit)
