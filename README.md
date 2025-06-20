# 🤖 AI-Powered Adverse Event Detection from PubMed Literature

This project demonstrates how Artificial Intelligence (AI) and Natural Language Processing (NLP) can be applied in Pharmacovigilance (PV) to extract adverse events (AEs) from biomedical literature.

---

## 📌 Objective

To build a pipeline that:
- Fetches abstracts from PubMed based on a drug + AE query
- Preprocesses and tokenizes the abstracts using NLP
- Detects potential adverse events using a predefined AE list
- Visualizes the frequency of detected AEs

---

## 🔧 Tools & Libraries

- Python
- Google Colab / Jupyter Notebook
- BioPython (Entrez API)
- spaCy (NLP)
- Matplotlib (Visualization)
- Pandas (DataFrame management)

---

## 📚 Dataset Source

Abstracts are fetched dynamically using PubMed Entrez API.  
Search term used: `"paracetamol adverse events"`

---

## 🚀 Workflow

1. **Phase 1–2**: Environment setup and PubMed abstract fetching
2. **Phase 3**: NLP-based text preprocessing
3. **Phase 4**: AE keyword matching and detection
4. **Phase 5**: AE frequency visualization

---

## 📊 Sample Output

| Abstract_Index | AE_Detected               |
|----------------|---------------------------|
| 1              | ["nausea", "liver damage"] |
| 2              | ["dizziness", "rash"]     |

---

## 📈 AE Frequency Chart

*(Insert screenshot of output plot here)*

---

## 🔬 Real-World Relevance

This project simulates:
- Literature monitoring automation
- Signal detection support
- AI-assisted PV workflows

---

## 🧪 How to Run

1. Upload `AI_PV_Complete_Project.ipynb` to [Google Colab](https://colab.research.google.com)
2. Replace `"your_email@example.com"` with your real email
3. Click **Runtime > Run all**

---

## 👨‍⚕️ Created By

**Kaushal Joel Jillella**  
Pharmacovigilance Enthusiast | NLP Explorer  
[LinkedIn Profile](https://linkedin.com/in/koushal-joel-jillella-b29689338)

---

> ⚠️ This is an educational/portfolio project and not intended for regulatory use.
