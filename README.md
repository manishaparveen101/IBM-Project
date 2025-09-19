# IBM-Project
# 🎓 EduTutor AI – Personalized Learning Assistant

EduTutor AI is an educational assistant powered by **IBM Granite models** from Hugging Face.
It provides **concept explanations** and **quiz generation** to make learning easier and more interactive.
The project is built with **Python, Hugging Face Transformers, and Gradio**, and can be run easily in **Google Colab**.

---

## 🚀 Features

* 📘 **Concept Explanation** – Get detailed explanations of any topic with examples.
* 📝 **Quiz Generator** – Automatically generate 5 quiz questions with answers (MCQ, True/False, Short Answer).
* 🌐 **Interactive UI** – Simple tab-based interface built with Gradio.
* ⚡ **AI-powered Responses** – Uses *ibm-granite/granite-3.2-2b-instruct* for reliable and efficient outputs.

---

## 🏗️ Architecture

* **Frontend:** Gradio (Tabbed UI with Concept Explanation & Quiz Generator).
* **Backend:** Python with Hugging Face Transformers & Torch.
* **Model:** IBM Granite 3.2 2B Instruct (Hugging Face).

---

## 📦 Setup Instructions

### Prerequisites

* Python 3.8+
* Google Colab (T4 GPU recommended)
* Libraries: `transformers`, `torch`, `gradio`

### Installation

```bash
!pip install transformers torch gradio
```

### Run the Application

1. Open the notebook in Google Colab.
2. Install dependencies using the above command.
3. Run the Python script (`edu_tutor_ai.py`).
4. Launch the Gradio app – a public shareable link will be generated.

---

## 📂 Folder Structure

```
EduTutorAI/
│── edu_tutor_ai.py       # Main application code
│── requirements.txt      # Dependencies
│── screenshots/          # Output screenshots
│── README.md             # Documentation
```

---

## 📸 Screenshots

### 📘 Concept Explanation

<img src="screenshots/screenshot_26.png" width="500"/>  

### 📝 Quiz Generator

<img src="screenshots/screenshot_27.png" width="500"/>  

---

## ⚠️ Known Issues

* First model load takes time.
* Responses may vary due to randomness in generation.
* Requires internet connection to download model.

---

## 🔮 Future Enhancements

* Add flashcards and summaries.
* Allow uploading PDFs/notes for quiz generation.
* Multi-language support.

---

## 👩‍💻 Team Members

* MANISHA PARVEEN J
* SHRUTIKA R
* KANIMOZHI BHARATHY M
* ATHIYA ZAINAB K
* DEEPIKA A

---

✨ *EduTutor AI – Making learning smarter with AI!*

---
