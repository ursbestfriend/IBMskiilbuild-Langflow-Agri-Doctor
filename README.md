# Agri-Doctor: AI Agent for Smart Farming Advice

An intelligent, multi-agent agricultural decision-support system built using **LangFlow**, **IBM watsonx.ai**, and the **IBM Granite-8B** foundational model. This project transforms fragmented agricultural data into precise, localized, and context-aware action plans to empower farmers against the challenges of climate change, pest infestations, and low crop yields.

[![Platform](https://img.shields.io/badge/Orchestration-LangFlow%201.9.6-blueviolet)](https://docs.langflow.org/)
[![Model](https://img.shields.io/badge/LLM-IBM%20Granite--8B--Code--Instruct-blue)](https://www.ibm.com/granite)
[![Cloud](https://img.shields.io/badge/Cloud-IBM%20watsonx.ai-0f62fe)](https://www.ibm.com/watsonx)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 Project Overview & Problem Statement

Modern agriculture is increasingly vulnerable to unpredictable weather patterns, rapid pest infestations, and low overall crop yields. Traditional advisory setups are frequently segmented, slow, and fail to provide personalized advice calibrated to a farmer's precise soil composition or localized climate conditions. 

**Agri-Doctor** addresses these limitations by substituting conventional single-prompt chatbots with an autonomous, collaborative **Multi-Agent Architecture**. The solution uses specialized agent routing and large language model reasoning to process real-time environmental metadata and produce structured, understandable field actions.

---

## 🛠 Technology Stack

* **Orchestration Layer:** `LangFlow Engine` (Visual graph routing executed locally at `localhost:7860`).
* **Cloud Infrastructure:** `IBM watsonx.ai Platform` (Hosted via the Asia-Pacific regional instance `https://au-syd.ml.cloud.ibm.com`).
* **Core LLM Engine:** `ibm/granite-8b-code-instruct`.
  * *Configuration:* Temperature: `0.1`, Top P: `0.9` (Tuned for precise, hallucination-free technical advice).
* **User Interface:** `Streamlit / React Dashboard` concept integrated via LangFlow API nodes.

---

## 📐 System Architecture & Workflow

The platform functions as a sequential multi-agent orchestration pipeline that filters technical data into immediate, operational field actions:

1. **Data Ingestion (`ChatInput`):** Captures crop issues, soil observations, or land criteria from the farmer.
2. **Officer 1 (`Plant Pathology Expert`):** Evaluates biological indicators to isolate plant diseases or nutrient deficiencies, outputting scientific organic or chemical countermeasures.
3. **Officer 2 (`Agricultural Extension Officer`):** Automatically intercepts Officer 1's scientific findings and converts them into simple, non-technical, localized steps.
4. **Delivery (`ChatOutput`):** Renders the final 24–48 hour field action plan within the user dashboard interface.

---

## 🚀 Future Roadmap

1. **IoT Sensor Integration:** Stream live soil moisture metrics, ambient pH, and microclimate telemetry directly into the active LangFlow graph via webhooks.
2. **Voice & Multilingual Support:** Implement natural language voice pipelines to process and reply in regional vernacular dialects for rural accessibility.
3. **Multimodal Computer Vision:** Embed live vision processing components to map leaf photo uploads directly onto a custom image classification database.
4. **Dynamic Live RAG Systems:** Connect the retriever nodes directly to real-time government mandi portals and university research vectors.

---

## 💻 Installation & Local Setup

### Prerequisites
* Windows 10/11 or Linux environment
* Python 3.10+ installed
* Valid IBM watsonx.ai Account Credentials (`API Key` and `Project ID`)

### 1. Clone the Repository
```bash
git clone [https://github.com/ursbestfriend/IBMskiilbuild-Langflow-Agri-Doctor.git](https://github.com/ursbestfriend/IBMskiilbuild-Langflow-Agri-Doctor.git)
cd IBMskiilbuild-Langflow-Agri-Doctor
