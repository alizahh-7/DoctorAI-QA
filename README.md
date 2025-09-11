# DoctorAI-QA
DoctorAI-Q is a GPT-OSS model fine-tuned on a medical dataset using LoRA and Unsloth, providing fast, reasoning-based answers to healthcare questions. Supports interactive testing via Colab or Gradio; intended for educational and demo purposes.

![Healthcare QA Demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExODdjMzl2b3h5eHlxOWF4enZrMW02YjhucjI3cHdzODAwMG1pYmRudyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/5k5vZwRFZR5aZeniqb/giphy.gif)

---

# 🩺 DoctorAI-QA

**Developed by:** syedazah777  
**License:** Apache-2.0  
**Fine-tuned from:** unsloth/gpt-oss-20b-unsloth-bnb-4bit  

MedGPT-HealthQ is a GPT-OSS model **fine-tuned on healthcare datasets** using LoRA and [Unsloth](https://github.com/unslothai/unsloth) for fast, reasoning-based question answering. It provides **accurate, human-readable answers** to healthcare questions and is designed for **educational and demonstration purposes**.

---

## 🔗 Model & Weights

- **Hugging Face Model:** [MedGPT-HealthQ](https://huggingface.co/syedazah777/finetuned_healthcare_gpt)  
- **Base Model:** `unsloth/gpt-oss-20b-unsloth-bnb-4bit`  
- **License:** Apache-2.0  

Weights are fully available in the Hugging Face repo for reproducibility and testing.

---

## ⚡ Features

- Fine-tuned on healthcare data for **disease, symptoms, and health advice Q&A**  
- Fast reasoning using **LoRA** + Unsloth optimizations  
- Interactive testing via **Colab** or **Gradio**  
- Covers multiple healthcare topics: diabetes, hypertension, heart health, medications, lifestyle advice and more  

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

## 🧪 Testing Instructions

### Option 1: Colab
1. Open this notebook: `[Insert Colab Notebook Link Here]`  
2. Replace the prompt in the code with your own healthcare question. Example:  
```python
question = "What are the early symptoms of diabetes?"

---

## 📸 Screenshots / Demo

![Gradio Interface](https://raw.githubusercontent.com/unslothai/unsloth/main/images/unsloth%20made%20with%20love.png)  
*Gradio interface showing healthcare Q&A*

### Running the Demo
1. Open the Colab notebook: [Open in Colab](your-colab-link-here)
2. Go to the **Runtime → Run all** menu (or run the Gradio cell manually).
3. After the Gradio cell runs, click the public URL shown in the output to open the demo.

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

---

## Visuals

<img width="1761" height="719" alt="Screenshot 2025-09-11 174035" src="https://github.com/user-attachments/assets/ced5d774-8000-410d-8935-f6f615e809cb" />
<img width="1707" height="732" alt="Screenshot 2025-09-11 173704" src="https://github.com/user-attachments/assets/cbaa3e72-973a-441b-aafb-341dc27da5c8" />

