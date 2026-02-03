# Whisper Urdu Speech Recognition Evaluation

This repository evaluates a **fine-tuned OpenAI Whisper model for Urdu speech recognition** using a processed Common Voice Urdu dataset from Hugging Face. The project focuses on measuring transcription accuracy using standard ASR evaluation metrics and is part of a Final Year Project (FYP).

---

## 📂 Dataset
- **Source:** `UmarRamzan/common-voice-urdu-processed` (Hugging Face)
- **Language:** Urdu
- **Split Used:** Test set

---

## 🤖 Model
- **Architecture:** OpenAI Whisper
- **Type:** Fine-tuned for Urdu
- **Loaded From:** Hugging Face

---

## 📏 Evaluation Metrics
The following standard speech recognition metrics were used:
- **Word Error Rate (WER)**
- **Character Error Rate (CER)**

Metrics were computed using the `evaluate` and `jiwer` libraries.

---

## 📊 Results

**Evaluation on Full Test Set:**

- **Word Error Rate (WER):** 26.76%
- **Character Error Rate (CER):** 8.83%

---

## 🛠️ Libraries Used
- `datasets`
- `evaluate`
- `jiwer`
- `numpy`
- `pandas`

---

## ▶️ Usage
Run the provided Python script to:
1. Load the Urdu dataset
2. Perform speech-to-text inference using Whisper
3. Compute WER and CER scores

---

## 🎓 Purpose
This repository supports the experimental evaluation component of a **Final Year Project (FYP)** focused on Urdu speech recognition and low-resource language modeling.
