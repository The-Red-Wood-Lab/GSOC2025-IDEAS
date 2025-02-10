
---

# GSOC 2025 IDEAS

## Projects

- [Misinformation Shield: AI Toolkit for Social Media Fact-Checking](#misinformation-shield-ai-toolkit-for-social-media-fact-checking)
- [Speaker Diarization with NLP](#speaker-diarization-with-nlp)
- [AI Virtual Assistant for Organization Website](#ai-virtual-assistant-for-organization-website)
- [Reinforcement Learning-Based Visual Transformer for Adaptive Patch Sampling](#reinforcement-learning-based-visual-transformer-for-adaptive-patch-sampling)
- [Reinforcement Learning-Based Color Bot for Adaptive Fabric Design](#reinforcement-learning-based-color-bot-for-adaptive-fabric-design)
- [DAGFlow: A Lightweight DAG-Based Workflow Orchestration System](#dagflow-a-lightweight-dag-based-workflow-orchestration-system)
- [AniMax: A Conversational Multi-Modal Animal Information Assistant](#animax-a-conversational-multi-modal-animal-information-assistant)
- [ChaosOps: Automated Chaos Engineering Platform](#chaosops-automated-chaos-engineering-platform)

---

# Misinformation Shield: AI Toolkit for Social Media Fact-Checking

## Overview

Social media is a double-edged sword—while it connects us, it also floods our feeds with hate, sarcasm, and negativity. Misinformation Shield is our answer to this challenge. By blending NLP, reinforcement learning, and attention mechanisms (including bi-directional LSTM), this toolkit digs deep into social media content to distinguish genuine hate from sarcasm and plain negativity. The goal is to empower users with a clearer understanding of online discourse.

## Key Features

- **Data Acquisition**: Web scraping to collect relevant social media data.
- **Data Preprocessing**: Robust cleaning and normalization of textual data.
- **Advanced Classification**: Transformer-based models to accurately differentiate between factual and misleading content.
- **Explainability**: Utilization of explainability techniques (e.g., SHAP values) to provide insights into model decisions.

## Expected Outcomes

- A modular, Python-based toolkit for misinformation detection.
- Pretrained models ready for deployment.
- A comprehensive API and documentation for community engagement and further development.

## Technology Stack

- **Programming Language**: Python
- **Libraries/Frameworks**: Transformers, spaCy, scikit-learn
- **Additional Tools**: Web scraping frameworks (Selenium or Beautiful Soup) and API development libraries
- **Web Development Tools**: React.js/Next.js, HTML, CSS, JavaScript

## Project Details

- **Difficulty**: Medium to Hard
- **Estimated Timeline**: 175 to 350 hours (depending on feature scope and complexity)

## Mentor 
- **ORGADMIN** - [Abhiman Panwar](https://github.com/Kroszborg)
- **BACKEND** - [Abhinav Singh](https://github.com/Abhinavexists)

---

# Speaker Diarization with NLP

## Overview

Imagine a tool that listens to a group conversation and effortlessly tells you who said what—almost like having a personal moderator. Our speaker diarization project aims to do just that. By integrating advanced NLP and voice recognition, it transforms raw audio into well-organized transcripts, ensuring every speaker is accurately identified. This makes meetings, legal proceedings, and conference calls much easier to review.

## Applications

- Automated transcription services
- Legal documentation and proceedings
- Analysis of conference calls
- Assistive technologies in healthcare

## Technology Stack

- **Tools & Libraries**: PyAnnotate, NVIDIA NeMo
- **Techniques**: Advanced NLP for contextual analysis

## Project Details

- **Difficulty**: Medium to Hard
- **Estimated Timeline**: Approximately 175 hours

## Mentor
- **BACKEND** - [SujalRajput](https://github.com/SujalRajpt)
- **FRONTEND** - [RohitSharma](https://github.com/rohitsharma2610)

---

# AI Virtual Assistant for Organization Website

## Overview

Picture a friendly guide waiting on your organization’s website—ready to answer questions, provide information, and help visitors navigate effortlessly. Our AI Virtual Assistant is designed to offer personalized and timely details about the organization, enhancing user experience with natural, conversational interactions.

## Technology Stack

- **Frontend**: React.js, Next.js
- **Backend**: Python, Langchain, Gemini

## Project Details

- **Difficulty**: Easy
- **Estimated Timeline**: Around 90 hours

## Mentor
- **BACKEND** - [Eeshan Bablani](https://github.com/eeshan15)
- **FRONTEND** - [Abhiman Panwar](https://github.com/Kroszborg)

---

# Reinforcement Learning-Based Visual Transformer for Adaptive Patch Sampling

## Overview

What if a computer could learn to look at an image like a human—focusing only on the parts that truly matter? Our project does exactly that by merging a visual transformer with adaptive patch sampling. Instead of processing every pixel equally, the model zeroes in on key areas. An RL agent refines these choices over time, making the system increasingly efficient at recognizing and understanding complex scenes.

## Technology Stack

- **PyTorch**: Our go-to framework for deep learning model development.
- **Reinforcement Learning Libraries**: Tools such as [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3) or [RLlib](https://docs.ray.io/en/latest/rllib.html)
- **Image Processing**: OpenCV, PIL for image handling and augmentation.
- **Visualization & Monitoring**: TensorBoard, Matplotlib
- **Experiment Tracking**: Weights & Biases (W&B) or MLflow
- **Data Manipulation**: NumPy, Pandas

## Project Details

- **Difficulty**: Hard
- **Estimated Timeline**: Approximately 375 hours

## Mentor
- **BACKEND** - [Eeshan Bablani](https://github.com/eeshan15) & [Abhinav Singh](https://github.com/Abhinavexists)
- **FRONTEND** - [Abhiman Panwar](https://github.com/Kroszborg) & [RohitSharma](https://github.com/rohitsharma2610)

---

# Reinforcement Learning-Based Color Bot for Adaptive Fabric Design

## Overview

Imagine a digital assistant for fabric designers that truly understands the art of color. Instead of offering generic palettes, our Color Bot dives into the details of fabric patterns and evolving trends. It combines the precision of Spiking Neural Networks with the adaptability of reinforcement learning and the sequential insights of LSTM models. The result? Personalized, dynamic color recommendations that keep up with the latest fashion trends and design nuances.

## Technology Stack

- **PyTorch**: For building SNNs, LSTMs, and RL agents.
- **Reinforcement Learning Libraries**: [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3) or [RLlib](https://docs.ray.io/en/latest/rllib.html)
- **Neuromorphic Computing Frameworks**: Nengo, BindsNET, or SpykeTorch
- **Image Processing**: OpenCV, PIL
- **Visualization & Monitoring**: TensorBoard, Matplotlib
- **Experiment Tracking**: Weights & Biases (W&B) or MLflow
- **Data Manipulation**: NumPy, Pandas

## Project Details

- **Difficulty**: Hard
- **Estimated Timeline**: Approximately 375 hours

## Mentor
- **BACKEND** - [Eeshan Bablani](https://github.com/eeshan15) & [Abhinav Singh](https://github.com/Abhinavexists)

---

# DAGFlow: A Lightweight DAG-Based Workflow Orchestration System

## Overview

Think of DAGFlow as your personal conductor for orchestrating complex workflows. It uses a directed acyclic graph (DAG) approach to manage tasks in data pipelines, ML processes, and CI/CD operations. Unlike bulky orchestration tools, DAGFlow is built to be lightweight and scalable—helping you define, execute, and monitor tasks effortlessly while keeping the process smooth and intuitive.

## Technology Stack

- **Python**: The primary language for the orchestration engine.
- **Flask/FastAPI**: For building APIs to manage workflows.
- **Celery/RQ**: For task scheduling and background execution.
- **Graph Algorithms**: To implement efficient DAG scheduling.
- **PostgreSQL/MongoDB**: For storing DAG metadata and logs.
- **Docker & Kubernetes**: To support distributed task execution.
- **React.js or Vue.js**: (Optional) For a user-friendly web dashboard.
- **Visualization & Monitoring Tools**: TensorBoard or Matplotlib

## Project Details

- **Difficulty**: Medium to Hard
- **Estimated Timeline**: Approximately 175 hours for the basic engine and API, extending to 350 hours for advanced features and UI integration.

## Deliverables

- **DAG Execution Engine**
- **Pipeline Definition API**
- **Failure Handling and Logging**
- **Basic Web UI**
- **Documentation and Tutorials**

## Mentor
- **BACKEND** - [SujalRajput](https://github.com/SujalRajpt)

---

# AniMax: A Conversational Multi-Modal Animal Information Assistant

## Overview

Our current animal info chatbot is pretty one-dimensional—it just fetches data from images without really talking back or remembering previous chats. AniMax is set to change that by turning it into a full-fledged conversational assistant. By combining advanced NLP with the existing image model and adding chat history, AniMax offers rich, interactive, and context-aware animal information. It's like having a knowledgeable friend who can show you visuals and explain details in a friendly conversation.

## Technology Stack

- **Python**: For backend services and AI integration.
- **Flask/FastAPI**: For building RESTful APIs.
- **Transformer-based NLP Models**: GPT, BERT, etc., for natural language understanding.
- **Image Processing Libraries**: OpenCV, PIL; along with PyTorch or TensorFlow.
- **Database**: PostgreSQL or MongoDB for storing chat histories and session data.
- **Frontend Framework**: React.js or Vue.js for a responsive web interface.
- **Chatbot Management Tools** (Optional): Rasa or Dialogflow

## Project Details

- **Difficulty**: Medium to Hard
- **Estimated Timeline**: Approximately 250 hours for core functionalities, with extended scope up to 375 hours for advanced features.

## Deliverables

- **Conversational Engine**
- **Chat History Management**
- **Multi-Modal Integration**
- **API and Web Interface**
- **Documentation and Tutorials**

## Mentor
- **BACKEND** - [Eeshan Bablani](https://github.com/eeshan15) & [Abhinav Singh](https://github.com/Abhinavexists)
- **FRONTEND** - [Abhiman Panwar](https://github.com/Kroszborg) & [RohitSharma](https://github.com/rohitsharma2610)

---

# ChaosOps: Automated Chaos Engineering Platform

## Overview

Imagine having a tool that purposely shakes up your system to reveal its hidden weaknesses—before they become real problems. ChaosOps does exactly that by automatically injecting controlled failures into production-like environments. Using a blend of chaos engineering techniques and reinforcement learning, it smartly schedules these experiments based on live system feedback. The outcome is a platform that not only identifies vulnerabilities but also learns to optimize its testing strategy over time, keeping your systems robust and resilient with minimal manual effort.

## Technology Stack

- **Python**: For scripting chaos experiments and automation logic.
- **Flask/FastAPI**: To build APIs for triggering experiments and monitoring responses.
- **Kubernetes & Docker**: For safely running chaos experiments in isolated containers.
- **Chaos Engineering Tools**: Integration with tools like Chaos Monkey or LitmusChaos.
- **Reinforcement Learning Libraries**: Stable Baselines3 or RLlib to optimize scheduling.
- **Database**: PostgreSQL or MongoDB for logging experiment data.
- **Monitoring & Visualization**: Prometheus and Grafana for real-time dashboards.

## Project Details

- **Difficulty**: Hard
- **Estimated Timeline**: Approximately 350 hours for core functionalities, with potential extensions up to 400 hours for advanced scheduling algorithms and multi-cluster support.

## Deliverables

- **Chaos Experiment Engine**
- **RL-Driven Scheduling Module**
- **Monitoring Dashboard**
- **API Services**
- **Documentation and Tutorials**

## Mentor
- **BACKEND** - [SujalRajput](https://github.com/SujalRajpt)

---

## License

All the above project ideas are licensed under the [Apache 2.0](LICENSE).

---
