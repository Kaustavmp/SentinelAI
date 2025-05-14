# SentinelAI 🛡️
> Autonomous Cyber Threat Hunting Agents using Multi-Agent AI and RAG

SentinelAI is a real-time cybersecurity system that uses a swarm of intelligent agents to detect, triage, and respond to threats autonomously. It combines anomaly detection, reinforcement learning, and retrieval-augmented generation (RAG) to proactively secure systems against modern threats.

---

## 🧠 Core Features

- Anomaly Detection Models  
  Trained unsupervised models (Autoencoders, Isolation Forest) on system logs and network traffic to detect outliers.

- LLM-Powered Log Parsing  
  Used GPT-based agents to extract threat-relevant patterns and recommend actions.

- RAG Pipelines for Threat Intel  
  Integrated LangChain + ElasticSearch to fetch live CVEs and MITRE ATT&CK context during triage.

- Multi-Agent Reinforcement Learning  
  Simulated red/blue team strategies for agent learning and testing.

- Real-Time Monitoring and Visualization  
  Kafka + Ray for concurrent log ingestion; Streamlit dashboard for incident visualization.

---

## 🚀 Architecture Overview

- Agent Orchestration: (https://ray.io)
- Threat Detection: PyTorch models + OpenAI API (log classification & summarization)
- Threat Intel Retrieval: LangChain + ElasticSearch
- Stream Processing: Apache Kafka
- Visualization: Streamlit dashboard with dynamic threat severity scoring

---

## 🔍 Prompt Template (LLM Agent)

---

## 💡 Use Cases

- Security Operations Center (SOC) automation  
- Red team / Blue team simulations  
- Enterprise-level log analysis & zero-day detection  
- Threat detection with explainability

---

## 📈 Why It Matters in 2025

SentinelAI reflects the next frontier in AI-native cybersecurity—autonomous, real-time, and self-improving through multi-agent learning. It highlights practical applications of LLMs and agent-based orchestration in high-stakes environments.

---

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

    
## 📂 Coming Soon

- 📊 Jupyter Notebooks for training logs  
- 🧪 Simulated attack datasets  
- 🛠️ Plug-and-play backend with Elastic SIEM

---

## 🔒 Built with ❤️ by Kaustav
