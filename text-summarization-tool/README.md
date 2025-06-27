# 📝 Text Summarization Tool

Welcome to the **Text Summarization Tool** repository! This Python-based application provides both **extractive** and **abstractive** text summarization methods using simple graphical user interfaces (GUIs) built with Tkinter.

## 🔍 Features

### ✂️ Extractive Summarizer
- Selects important sentences from the original text.
- Uses spaCy for natural language processing.
- Lets you choose the number of sentences in the summary.

### ✨ Abstractive Summarizer
- Generates new sentences that capture the meaning of the original text.
- Built using Hugging Face Transformers with the T5 model.
- Automatically summarizes large text blocks into shorter paraphrased versions.

---

## 🚀 Installation & Setup

Follow these steps to run the summarization tools on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/arnabkundu03/text-summarization-tool.git
cd text-summarization-tool/text-summarization-tool
```
### 2. Set Up a Virtual Environment (Optional but Recommended)

```python -m venv venv```
# Activate the virtual environment:
# On Windows:
```venv\Scripts\activate```
# On macOS/Linux:
```source venv/bin/activate```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Download spaCy Language Model

```bash
python -m spacy download en_core_web_sm
```

### ▶️ How to Run -->
### ✅ Extractive Summarizer

```bash
python Extractive.py
```
I) Paste your input text in the GUI.
II) Enter the number of summary sentences.
III) Click Summarize to generate an extractive summary.

### ✅ Abstractive Summarizer

```bash
python Abstractive.py
```
I) Paste your input text in the GUI.
II) Click Summarize to generate an abstractive summary using the T5 model.

### 🧩 Technologies Used

1. ```transformers``` (T5 model for abstractive summarization)
2. ```torch```
3. ```spacy``` (for NLP and extractive summarization)
4. ```tkinter``` (for GUI)
5. ```collections```, ```heapq```, and standard libraries

You can find the full list of dependencies in the ```requirements.txt``` file.
