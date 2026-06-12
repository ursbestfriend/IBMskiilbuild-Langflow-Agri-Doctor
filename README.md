# Agri-Doctor: AI Agent for Smart Farming Advice

[cite_start]An intelligent, multi-agent agricultural decision-support system built using **LangFlow**, **IBM watsonx.ai**, and the **IBM Granite-8B** foundational model[cite: 21, 26, 30]. [cite_start]This project transforms fragmented agricultural data into precise, localized, and context-aware action plans to empower farmers against the challenges of climate change, pest infestations, and low crop yields[cite: 91, 93, 114].

[![Platform](https://img.shields.io/badge/Orchestration-LangFlow%201.9.6-blueviolet)](https://docs.langflow.org/)
[![Model](https://img.shields.io/badge/LLM-IBM%20Granite--8B--Code--Instruct-blue)](https://www.ibm.com/granite)
[![Cloud](https://img.shields.io/badge/Cloud-IBM%20watsonx.ai-0f62fe)](https://www.ibm.com/watsonx)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## 📌 Project Overview & Problem Statement

[cite_start]Modern agriculture is increasingly vulnerable to unpredictable weather patterns, rapid pest infestations, and low overall crop yields[cite: 91, 93]. [cite_start]Traditional advisory setups are frequently segmented, slow, and fail to provide personalized advice calibrated to a farmer's precise soil composition or localized climate conditions[cite: 92]. 

[cite_start]**Agri-Doctor** addresses these limitations by substituting conventional single-prompt chatbots with an autonomous, collaborative **Multi-Agent Architecture**[cite: 42, 403]. [cite_start]The solution uses specialized agent routing and large language model reasoning to process real-time environmental metadata and produce structured, understandable field actions[cite: 60, 68, 74].

---

## 🛠 Technology Stack

* [cite_start]**Orchestration Layer:** `LangFlow Engine` (Visual graph routing executed locally at `localhost:7860`)[cite: 39, 424].
* [cite_start]**Cloud Infrastructure:** `IBM watsonx.ai Platform` (Hosted via the Asia-Pacific regional instance `https://au-syd.ml.cloud.ibm.com`)[cite: 426, 428].
* [cite_start]**Core LLM Engine:** `ibm/granite-8b-code-instruct`[cite: 427].
  * [cite_start]*Configuration:* Temperature: `0.1`, Top P: `0.9` (Tuned for precise, hallucination-free technical advice)[cite: 106].
* [cite_start]**User Interface:** `Streamlit / React Dashboard` concept integrated via LangFlow API nodes[cite: 65, 139].

---

## 📐 System Architecture & Workflow

[cite_start]The platform functions as a sequential multi-agent orchestration pipeline that filters technical data into immediate, operational field actions[cite: 105, 434]:

1. [cite_start]**Data Ingestion (`ChatInput`):** Captures crop issues, soil observations, or land criteria from the farmer[cite: 66, 131].
2. [cite_start]**Officer 1 (`Plant Pathology Expert`):** Evaluates biological indicators to isolate plant diseases or nutrient deficiencies, outputting scientific organic or chemical countermeasures[cite: 435, 436].
3. [cite_start]**Officer 2 (`Agricultural Extension Officer`):** Automatically intercepts Officer 1's scientific findings and converts them into simple, non-technical, localized steps[cite: 441, 442, 443].
4. [cite_start]**Delivery (`ChatOutput`):** Renders the final 24–48 hour field action plan within the user dashboard interface[cite: 442, 446].

---

## 🚀 Future Roadmap

1. [cite_start]**IoT Sensor Integration:** Stream live soil moisture metrics, ambient pH, and microclimate telemetry directly into the active LangFlow graph via webhooks[cite: 506, 507].
2. [cite_start]**Voice & Multilingual Support:** Implement natural language voice pipelines to process and reply in regional vernacular dialects for rural accessibility[cite: 508, 509].
3. [cite_start]**Multimodal Computer Vision:** Embed live vision processing components to map leaf photo uploads directly onto a custom image classification database[cite: 510, 511].
4. [cite_start]**Dynamic Live RAG Systems:** Connect the retriever nodes directly to real-time government mandi portals and university research vectors[cite: 512, 513].

---

## 💻 Installation & Local Setup

### Prerequisites
* Windows 10/11 or Linux environment
* Python 3.10+ installed
* [cite_start]Valid IBM watsonx.ai Account Credentials (`API Key` and `Project ID`) [cite: 429]

### 1. Clone the Repository
```bash
git clone [https://github.com/ursbestfriend/IBMskiilbuild-Langflow-Agri-Doctor.git](https://github.com/ursbestfriend/IBMskiilbuild-Langflow-Agri-Doctor.git)
cd IBMskiilbuild-Langflow-Agri-Doctor
