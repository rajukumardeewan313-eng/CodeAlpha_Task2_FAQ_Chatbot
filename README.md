
# 🤖 FAQ Chatbot | CodeAlpha Internship Task 2

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green?style=for-the-badge)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-orange?style=for-the-badge)
![CodeAlpha](https://img.shields.io/badge/CodeAlpha-Internship-purple?style=for-the-badge)

---

## 📌 About The Project

An intelligent **FAQ Chatbot** built using **Natural Language Processing (NLP)** techniques without any external NLP libraries. The chatbot matches user questions with the most relevant FAQ using a custom-built **TF-IDF Vectorization** and **Cosine Similarity** algorithm — all implemented from scratch using pure Python.

---

## ✨ Features

- 🔍 NLP-based question matching using TF-IDF + Cosine Similarity
- 🧠 Built from scratch — no external NLP libraries needed
- 💬 23 built-in FAQs about Python & Programming concepts
- ⚡ Quick question suggestion buttons
- 🔗 Related questions displayed after each answer
- 📊 Match confidence percentage shown for every response
- 🎨 Modern dark-themed GUI using Tkinter
- 🖱️ Clickable related question buttons for easy navigation

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Tkinter | Desktop GUI (built-in Python library) |
| TF-IDF (custom) | Text vectorization |
| Cosine Similarity (custom) | Question matching algorithm |
| Math module | Vector calculations |
| String module | Text preprocessing |

---

## 🧠 How It Works

1. **Preprocessing** — User input is lowercased, punctuation removed, and stopwords filtered out
2. **TF-IDF Vectorization** — Each FAQ and user query is converted into a numerical vector
3. **Cosine Similarity** — The query vector is compared with all FAQ vectors
4. **Best Match** — The FAQ with the highest similarity score above the threshold is returned
5. **Related Questions** — Top 2 other matching FAQs are shown as suggestions

---

## 📂 Project Structure

```
CodeAlpha_Task2_FAQ_Chatbot/
│
├── faq_chatbot.py        # Main chatbot code (NLP + GUI)
└── README.md             # Project documentation
```

---

## ▶️ How To Run

### 1. Clone the Repository
```bash
git clone https://github.com/rajukumardeewan313-eng/CodeAlpha_Task2_FAQ_Chatbot.git
cd CodeAlpha_Task2_FAQ_Chatbot
```

### 2. No Installation Needed!
All libraries used are built into Python:
```
tkinter  ✅ built-in
math     ✅ built-in
string   ✅ built-in
re       ✅ built-in
```

### 3. Run the Chatbot
```bash
python faq_chatbot.py
```

---

## 💬 Example Questions You Can Ask

| Question | Category |
|---|---|
| What is Python? | Python Basics |
| How do I install Python? | Python Setup |
| What is a virtual environment? | Python Tools |
| What is pip? | Python Tools |
| What is the difference between a list and a tuple? | Data Structures |
| What is a dictionary in Python? | Data Structures |
| What is a lambda function? | Python Functions |
| What is object-oriented programming? | OOP |
| What is a class in Python? | OOP |
| What is inheritance in Python? | OOP |
| What are Python decorators? | Advanced Python |
| What is exception handling? | Error Handling |
| What is a generator in Python? | Advanced Python |
| What is list comprehension? | Python Shortcuts |
| What is NLP? | NLP / AI |
| What is cosine similarity? | NLP Algorithm |
| What is tokenization? | NLP |
| What is stopword removal? | NLP |
| What is Tkinter? | GUI |
| What is a REST API? | Web |

---

## 📊 Match Score Guide

| Score | Meaning |
|---|---|
| Above 30% | 🟢 Strong match |
| 15% – 30% | 🔵 Moderate match |
| Below 15% | ⚪ Weak match |

---

## 🏢 Internship Details

| Detail | Info |
|---|---|
| Organization | CodeAlpha |
| Domain | Python Programming |
| Task Number | Task 2 |
| Project | FAQ Chatbot |
| Intern Name | Raju Kumar |

---

⭐ **If you found this helpful, please give it a star!** ⭐



📧 Gmail: rajukumardeewan313@gmail.com
| 💼 LinkedIn | [linkedin.com/in/raju-kumar-ai]...

