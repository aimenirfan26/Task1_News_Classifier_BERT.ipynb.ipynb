# 📰 Task 1: News Topic Classifier Using BERT

## 📌 Description  
Fine-tuned BERT model to classify news headlines into **World**, **Business**, **Sports**, and **Sci/Tech** using HuggingFace and Gradio.  

---

## 📖 Extended Description  
This project explores **Natural Language Processing (NLP)** using **BERT (Bidirectional Encoder Representations from Transformers)**.  
The model is trained and fine-tuned on the **AG News dataset**, which contains thousands of labeled news headlines.  

### 🔹 Key Features
- ✅ Preprocessing and tokenization with HuggingFace `transformers`.  
- ✅ Fine-tuning BERT for **multi-class classification**.  
- ✅ Evaluation using **accuracy** and **F1 score**.  
- ✅ Interactive testing with **Gradio app** (enter a headline → see predicted category).  

### 🔹 Example Output
**Input:**  
`"Apple announces new AI-powered iPhone with advanced features."`  

**Output:**  
`Predicted Category: Sci/Tech | Confidence: 0.91`  

---

## ⚙️ Tech Stack
- Python 🐍  
- PyTorch 🔥  
- HuggingFace Transformers 🤗  
- Gradio 🎨  

---

## 🚀 Future Improvements
- Add support for showing **top-3 predictions** with probabilities.  
- Deploy on **HuggingFace Spaces** or **Streamlit Cloud**.  
- Train with larger datasets for better accuracy.  

---

✍️ *This project was developed as part of an internship task to learn transformer models and text classification.*
