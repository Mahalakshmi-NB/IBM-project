# 🏥 Health AI: Intelligent Healthcare Assistant  

HealthAI is a Generative AI–powered healthcare assistant built using **IBM Granite models** from Hugging Face.  
It provides smart, easy-to-understand healthcare help with features such as:  
- Patient Chat  
- Disease Prediction  
- Treatment Plan Suggestions  

The project is deployed on **Google Colab** for fast, accessible, and secure medical guidance.  

---

## 🚀 Features
- 🤖 Uses IBM Granite (`granite-3.2-2b-instruct`) model  
- 💬 Patient-friendly chatbot  
- 🧾 Disease prediction and treatment planning  
- 🌐 Runs directly in Google Colab with GPU support  
- 🎛️ Easy UI with **Gradio**  

---

## 📋 Pre-requisites  
Before running this project, make sure you are familiar with:  
- [Gradio Framework](https://www.gradio.app/guides/)  
- [IBM Granite Models](https://huggingface.co/ibm-granite)  
- [Python Programming](https://docs.python.org/3/)  
- [Git & Version Control](https://git-scm.com/docs/git)  
- [Google Colab T4 GPU](https://www.geeksforgeeks.org/python/how-to-use-gpu-in-google-colab/)  

---

## ⚙️ Installation & Setup  

1. Open [Google Colab](https://colab.research.google.com/).  
2. Create a new notebook and change runtime to **T4 GPU**.  
3. Install required dependencies:  
   ```bash
   !pip install transformers torch gradio -q
