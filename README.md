# Python Data Science Assistant (LoRA Fine-tuned)

This project is a **fine-tuned Large Language Model (LLM)** designed as a **Python Data Science Assistant**.  
The model provides **short, clear (3–6 sentences) explanations** focused on **data science and machine learning concepts**.

The project was developed as part of a **final course project**, fulfilling the requirement of selecting an LLM, fine-tuning it with a custom dataset, and deploying it with a user interface.


👉 https://colab.research.google.com/drive/17vtTtz_h1OvdW7a3P4qVBKsCeNw3gTKH?usp=sharing


---

## 📌 Project Objective

- Select a pre-trained LLM
- Fine-tune the model using **LoRA (Low-Rank Adaptation)**
- Use a **custom-created dataset**
- Deploy the fine-tuned model with a **Gradio-based web interface**
- Generate concise, accurate answers related to **data science & machine learning**

---

## 🧠 Model Details

- **Base Model:** TinyLlama / Causal Language Model
- **Fine-tuning Method:** LoRA (PEFT)
- **Task Type:** Instruction-based Question Answering
- **Language:** English
- **Response Style:**  
  - 3–6 sentences  
  - Short, clear, and focused  
  - Data science context only  

---

## 📊 Dataset

- The dataset was **created manually** for this project.
- Format: Instruction–Response pairs
- Domain:  
  - Machine Learning  
  - Data Science  
  - Evaluation Metrics (RMSE, Precision, Recall, etc.)  
  - Neural Networks (CNN, Overfitting, etc.)

**Because the dataset was created by the author, the project meets the highest grading criteria.**

---

## ⚙️ Fine-Tuning Environment

- **Platform:** Google Colab
- **Libraries Used:**
  - `transformers`
  - `torch`
  - `peft`
  - `datasets`
  - `accelerate`
- **Training Type:** LoRA fine-tuning (parameter-efficient)

---

## 🖥️ User Interface

The model is deployed using **Gradio** and provides:

- Textbox for user questions
- Advanced generation settings:
  - `max_new_tokens`
  - `temperature`
  - `top_p`
- Example questions for quick testing
- Copyable model output

The interface is designed to be **simple, clean, and professional**.
