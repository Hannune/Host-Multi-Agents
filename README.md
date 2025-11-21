# Host-Multi-Agents

This repository is dedicated to hosting a variety of AI agents locally. Most agents are either built from scratch or modified using wrappers to improve performance or address usability issues. The repository also includes LangGraph versions of n8n templates and agents that can run on Windows. All agents are containerized and managed using Docker for easy deployment and scalability.

---

## 🚀 Features

- Self-built and modified agents for improved performance and usability
- LangGraph versions of n8n templates
- Windows-compatible agents
- All agents are Dockerized for seamless deployment

---

## 📦 Getting Started

### Prerequisites

- Docker installed on your system
- Docker Compose (optional, for multi-container setups)

### Installation

1. Clone this repository:
```
git clone https://github.com/Hannune/Host-Multi-Agents.git
cd Host-Multi-Agents
```

2. Build and run an agent:
```
docker-compose up -d
```
(or use `docker build` and `docker run` for individual agents)

---

## 🛠️ Usage

- Each agent has its own directory with a Dockerfile and instructions.
- Check the README in each agent's folder for specific usage details.
- For LangGraph agents, refer to the included workflow diagrams and template files.

---

## 🌐 Supported Platforms

- Linux (Ubuntu, Debian, etc.)
- Windows (via Docker Desktop)

---

## 📝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have an agent to add or want to improve existing ones.

---

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or suggestions, feel free to open an issue or reach out via email.


