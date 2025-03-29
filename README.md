# Awesome-LLM-Patient-Simulators <span style="font-size: 0.8em; color: #555;">✨</span>

[![Awesome LLM Patient Simulators](https://img.shields.io/static/v1?label=&message=Awesome+LLM+Patient+Simulators&color=1e88e5&style=flat-square&logo=awesomelists)](https://github.com/HuberyGG/Awesome-LLM-Patient-Simulators)
[![Last Commit](https://img.shields.io/github/last-commit/HuberyGG/Awesome-LLM-Patient-Simulators?color=4caf50&style=flat-square)](https://github.com/HuberyGG/Awesome-LLM-Patient-Simulators/commits/main)
[![GitHub Stars](https://img.shields.io/github/stars/HuberyGG/Awesome-LLM-Patient-Simulators?style=social&color=ff4081)](https://github.com/HuberyGG/Awesome-LLM-Patient-Simulators)

<div style="font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif; line-height: 1.6; color: #333; max-width: 900px; margin: 0 auto; padding: 0 20px;">

This repository provides a curated collection of research papers on **Large Language Models (LLMs)** for patient simulation in healthcare, covering:

- 🏥 Virtual patient interactions  
- 🎓 Clinical training applications  
- 🔍 Diagnostic reasoning systems  
- 🧠 Mental health simulations  

</div>

## Table of Contents <span style="font-size: 0.8em; color: #666;">📋</span>

<div style="background-color: #f5f7fa; padding: 15px; border-radius: 8px; margin: 15px 0; font-size: 0.95em;">

- [Fundamental Research](#-fundamental-research)
- [Methodology](#-methodology)
  - [Agent Systems](#-agent)
  - [NLP Techniques](#-nlp)
  - [Generative Models](#generative-models)
  - [Transformer Architectures](#-transformer-models)
  - [Prompt Engineering](#-prompt-engineering)
- [Applications](#-application)
  - [General Medical Education](#-general-medicine-education)
  - [Psychiatric Medicine](#-psychiatric-medicine)
  - [Clinical Decision Support](#-clinical-decision-support)
- [Challenges](#-challenges)
  - [Bias & Ethical Considerations](#-bias--ethics)

</div>

---

## 🔍 Fundamental Research <span style="font-size: 0.8em; color: #666;">📚</span>

<div style="margin: 20px 0;">

### (2021/05) Lessons Learned from the Usability Evaluation of a Simulated Patient Dialogue System  
[Springer Link](https://link.springer.com/article/10.1007/s10916-021-01737-4) | [Data](https://pvdial.limsi.fr/data/PG-logs-eval.zip) | [Demo](http://vps-9069f76a.vps.ovh.net)  
*Developed a virtual patient dialogue system for medical students to practice.*

### (2021/12) The simulated patient method: Design and application in health services research  
[Science Direct](https://linkinghub.elsevier.com/retrieve/pii/S1551741121001625)  
*Explores the design and application of the simulated patient method in health services research, particularly in pharmacy practice.*

### (2023/03) The Role of ChatGPT, Generative Language Models, and Artificial Intelligence in Medical Education: A Conversation With ChatGPT and a Call for Papers  
[JMIR Med Educ](https://mededu.jmir.org/2023/1/e46885) | [pdf](https://mededu.jmir.org/2023/1/e46885/PDF) | [Call for Papers](https://mededu.jmir.org/announcements/365)  
*Explores the potential application of ChatGPT and other generative language models in medical education, including virtual patient simulation.*

### (2025/02) From ChatGPT to DeepSeek: Can LLMs Simulate Humanity?  
[arXiv](http://arxiv.org/abs/2502.18210) | [pdf](https://arxiv.org/pdf/2502.18210) | [Data](https://jmir.org/api/download?alt_name=jmir_v27i1e59435_app1.docx&filename=2ff26f0a7b3db530e6e1a74bd2a50323.docx)  
*Analyses LLMs' ability to simulate human behavior, discussing key limitations (e.g., bias, lack of incentives) and future alignment strategies.*

</div>

---

## 🛠️ Methodology <span style="font-size: 0.8em; color: #666;">⚙️</span>

<div style="margin: 20px 0;">

### 🤖 Agent

#### (2024/01) Towards Conversational Diagnostic AI  
[arXiv](https://arxiv.org/abs/2401.05654)  
*Introduces **AMIE**, an AI-driven system powered by LLMs that simulates virtual patient-doctor interactions for clinical education, enhancing diagnostic reasoning and medical history-taking skills.*

#### (2024/06) AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator  
[arXiv](http://arxiv.org/abs/2402.09742) | [Project](https://github.com/LibertFan/AI_Hospital)  
*Introduces AI Hospital, a **multi-agent framework** for evaluating large language models in simulated medical interactions.*

#### (2024/10) AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow  
[arXiv](https://arxiv.org/abs/2409.18924) | [Code](https://www.catalyzex.com/paper/aipatient-simulating-patients-with-ehrs-and/code) | [Data](https://paperswithcode.com/dataset/mimic-iii)  
*Presents a novel **agentic workflow** combining **EHR** knowledge graphs with Reasoning-RAG architecture.*

#### (2024/12) LLMs Can Simulate Standardized Patients via Agent Coevolution  
[arXiv](http://arxiv.org/abs/2412.11716) | [Project](https://github.com/ZJUMAI/EvoPatient)  
*Introduces the **EvoPatient framework**, which utilizes **multi-agent coevolution** to enable large language models to simulate standardized patients and autonomously improve diagnostic and interaction processes.*

#### (2025/02) Scaffolding Empathy: Training Counselors with Simulated Patients and Utterance-level Performance Visualizations  
[arXiv](http://arxiv.org/abs/2502.18673)  
*Introduces a LLM-based multi-agent system (SimPatient) with dynamic cognitive modeling and real-time feedback to enhance motivational interviewing (MI) training through interactive patient simulations.*

### 💬 NLP

#### (2024/05) Automated Generation of High-Quality Medical Simulation Scenarios Through Integration of Semi-Structured Data and Large Language Models  
[arXiv](https://arxiv.org/abs/2404.19713) | [pdf](https://arxiv.org/pdf/2404.19713)  
*Introduces a semi-structured data and LLM-integrated framework to automate the generation of medical simulation scenarios, significantly reducing development time while maintaining clinical and educational relevance.*

#### (2025) RasPatient Pi: A Low-Cost Customizable LLM-Based Virtual Standardized Patient Simulator  
[Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-75147-9_9) | [Project](https://github.com/cgrevisse/raspatientpi)  
*Presents **RasPatient Pi**, a low-cost, customizable virtual standardized patient simulator based on Large Language Models (LLMs).*

### 🎨 Generative Models

#### (2024/04) Leveraging Large Language Model as Simulated Patients for Clinical Education  
[arXiv](http://arxiv.org/abs/2404.13066)  
*Introduces **CureFun**, an **integrated framework** that utilizes LLMs as simulated patients for clinical education, enhancing student-patient dialogues, providing real-time evaluations, and improving medical training through realistic, AI-driven interactions.*

#### (2025/03) Augmenting Insufficiently Accruing Oncology Clinical Trials Using Generative Models: Validation Study  
[JMIR](https://www.jmir.org/2025/1/e66821) | [Data](https://jmir.org/api/download?alt_name=jmir_v27i1e66821_app1.pdf&filename=1b8ee696dd8ab5638b213dcf7d139fb8.pdf)  
*Explores the use of generative models to augment oncology clinical trials with insufficient patient accrual, validating their effectiveness in simulating additional patient data to improve trial outcomes.*

### 🖼️ Transformer Models

#### (2024/08) MedDiT: A Knowledge-Controlled Diffusion Transformer Framework for Dynamic Medical Image Generation in Virtual Simulated Patient  
[arXiv](http://arxiv.org/abs/2408.12236) | [pdf](http://arxiv.org/pdf/2408.12236v1)  
*Introduces MedDiT, a knowledge-controlled diffusion transformer framework designed to dynamically generate medical images for virtual simulated patients.*

### ✏️ Prompt Engineering

#### (2025/01) Application of Large Language Models in Medical Training Evaluation—Using ChatGPT as a Standardized Patient: Multimetric Assessment  
[JMIR](https://www.jmir.org/2025/1/e59435) | [pdf](https://www.jmir.org/2025/1/e59435/PDF)  
*Optimized ChatGPT for medical standardized patient simulation via prompt engineering, enhancing clinical accuracy and realism.*

</div>

---

## 🏥 Application <span style="font-size: 0.8em; color: #666;">🩺</span>

<div style="margin: 20px 0;">

### 🩺 General Medicine Education

#### (2023/08) The Role of Large Language Models in Medical Education: Applications and Implications  
[JMIR](https://mededu.jmir.org/2023/1/e50945) | [pdf](https://mededu.jmir.org/2023/1/e50945/PDF)  
*Shows LLMs can simulate patient encounters for medical education but lack nonverbal communication and may exhibit biases.*

#### (2024/01) Virtual Standardized LLM-AI Patients for Clinical Practice  
From [Annual Review of CyberTherapy and Telemedicine](https://www.researchgate.net/publication/387328695_ANNUAL_REVIEW_OF_CYBERTHERAPY_AND_TELEMEDICINE_2024#page=172)  
*Explores the use of virtual standardized AI patients powered by LLMs to enhance clinical practice and therapy training.*

#### (2024/07) Roleplay-doh: Enabling Domain-Experts to Create LLM-simulated Patients via Eliciting and Adhering to Principles  
[arXiv](http://arxiv.org/abs/2407.00870) | [Project](https://roleplay-doh.github.io/)  
*Introduces Roleplay-doh, a tool that enables domain experts to collaboratively create realistic AI patient simulations by providing qualitative feedback.*

#### (2024/08) A Language Model-Powered Simulated Patient With Automated Feedback for History Taking: Prospective Study  
[JMIR](https://mededu.jmir.org/2024/1/e59213)  
*Presents a language model-powered simulated patient designed to enhance history-taking skills in medical education, providing automated feedback to improve student performance in clinical settings.*

#### (2024/09) Enhancing Medical Interview Skills Through AI-Simulated Patient Interactions: Nonrandomized Controlled Trial  
[JMIR](https://mededu.jmir.org/2024/1/e58753)  
*Demonstrates that AI-simulated patient interactions effectively enhance medical interview skills in a nonrandomized controlled trial, highlighting their potential for clinical training.*

#### (2025/01) Enhancing Patient-Centric Communication: Leveraging LLMs to Simulate Patient Perspectives  
[arXiv](http://arxiv.org/abs/2501.06964)  
*Explores LLM-based patient simulation via **persona prompts**, showing higher accuracy for educated groups but biases against underserved populations.*

#### (2025/03) MedSimAI: Simulation and Formative Feedback Generation to Enhance Deliberate Practice in Medical Education  
[arXiv](http://arxiv.org/abs/2503.05793)  
*Introduces **MedSimAI**, an AI-driven platform designed to enhance medical education by providing realistic simulations and formative feedback.*

### 🧠 Psychiatric Medicine

#### (2023/05) LLM-empowered Chatbots for Psychiatrist and Patient Simulation: Application and Evaluation  
[arXiv](https://arxiv.org/pdf/2305.13614) | [pdf](https://arxiv.org/pdf/2305.13614)  
*Demonstrates ChatGPT's feasibility in powering psychiatric patient and doctor chatbots, validated through real clinician-patient evaluations of diagnostic dialogue quality.*

#### (2024/10) PATIENT-Ψ: Using Large Language Models to Simulate Patients for Training Mental Health Professionals  
[arXiv](http://arxiv.org/abs/2405.19660) | [pdf](http://arxiv.org/pdf/2405.19660v3)  
*Introduces PATIENT-Ψ, an LLM-based patient simulation system for training mental health professionals in cognitive behavioral therapy.*

#### (2025/01) PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents  
[arXiv](http://arxiv.org/abs/2501.01594) | [pdf](http://arxiv.org/pdf/2501.01594v1)  
*Presents PSYCHE, a multi-faceted patient simulation framework designed to evaluate psychiatric assessment conversational agents, assessing their performance in realistic patient interactions for mental health evaluations.*

### ⚕️ Clinical Decision Support

#### (2024/11) Large language models improve clinical decision making of medical students through patient simulation and structured feedback: a randomized controlled trial  
[PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/) | [Data](https://pmc.ncbi.nlm.nih.gov/articles/PMC11605890/#_ad93_)  
*Demonstrates that AI-simulated medical history conversations, particularly when combined with structured feedback, can enhance clinical decision-making skills in medical students.*

</div>

---

## ⚠️ Challenges <span style="font-size: 0.8em; color: #666;">🚨</span>

<div style="margin: 20px 0;">

### 🎭 Bias & Ethics

#### (2024/07) The Role of Humanization and Robustness of Large Language Models in Conversational Artificial Intelligence for Individuals With Depression: A Critical Analysis  
[JMIR](https://www.jmir.org) | [pdf](https://example.com/pdf)  
*Analyzes LLMs' humanization and robustness in depression-focused AI, revealing emotional understanding gaps and proposing enhancement strategies.*

</div>

---

## ⭐ Star History <span style="font-size: 0.8em; color: #666;">📈</span>

<div style="text-align: center; margin: 30px 0;">

<a href="https://star-history.com/#HuberyGG/Awesome-LLM-Patient-Simulators&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=HuberyGG/Awesome-LLM-Patient-Simulators&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=HuberyGG/Awesome-LLM-Patient-Simulators&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=HuberyGG/Awesome-LLM-Patient-Simulators&type=Date" style="max-width: 100%; height: auto; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);" />
  </picture>
</a>

</div>
