# DoctorAI-QA
MedGPT-HealthQ is a GPT-OSS model fine-tuned on a medical dataset using LoRA and Unsloth, providing fast, reasoning-based answers to healthcare questions. Supports interactive testing via Colab or Gradio; intended for educational and demo purposes.

---
base_model: unsloth/gpt-oss-20b-unsloth-bnb-4bit
tags:
- text-generation-inference
- transformers
- unsloth
- gpt_oss
- trl
license: apache-2.0
language:
- en
---

# 🩺 MedGPT-HealthQ

**Developed by:** syedazah777  
**License:** Apache-2.0  
**Fine-tuned from:** unsloth/gpt-oss-20b-unsloth-bnb-4bit  

MedGPT-HealthQ is a GPT-OSS model **fine-tuned on healthcare datasets** using LoRA and [Unsloth](https://github.com/unslothai/unsloth) for fast, reasoning-based question answering. It provides **accurate, human-readable answers** to healthcare questions and is designed for **educational and demonstration purposes**.

---

## ⚡ Features

- Fine-tuned on healthcare data for **disease, symptoms, and health advice Q&A**  
- Fast reasoning using **LoRA** + Unsloth optimizations  
- Interactive testing via **Colab** or **Gradio**  
- Supports multiple healthcare topics like diabetes, hypertension, heart health, and more  

---

## 📝 How It Works

1. The model uses the **GPT-OSS architecture** for natural language understanding.  
2. Fine-tuned with **LoRA adapters** on healthcare datasets to improve domain-specific answers.  
3. Users can input questions via **Gradio/Colab interface** and receive fast, accurate responses.  
4. Outputs are designed to be **informative and easy to understand** for educational purposes.  

---

## 🔗 Try It Live

Run an interactive demo directly in **Colab** or via **Gradio**:  
[👉 Hugging Face Model Link](https://huggingface.co/syedazah777/finetuned_healthcare_gpt)  

> Replace the prompt with any healthcare question and see the model in action!

---

## 📸 Screenshots / Demo

![Gradio Interface](https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20made%20with%20love.png)  
*Gradio interface showing healthcare Q&A*

---

## ⚠️ Notes

- Model trained with **LoRA** for efficiency  
- Intended for **educational and demonstration purposes only**  
- Always **consult medical professionals** for real healthcare advice  

---

## 🌟 Acknowledgements

- [Unsloth](https://github.com/unslothai/unsloth) for the fine-tuning framework  
- Hugging Face for **datasets and TRL support**  
- Open-source community for GPT-OSS contributions
