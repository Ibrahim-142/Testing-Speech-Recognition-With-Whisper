Whisper Urdu Speech Recognition Evaluation

This repository evaluates a fine-tuned OpenAI Whisper model for Urdu speech recognition using a processed Common Voice Urdu dataset sourced from Hugging Face. The work focuses on measuring transcription quality using standard ASR evaluation metrics.

Dataset

Source: UmarRamzan/common-voice-urdu-processed (Hugging Face)

Language: Urdu

Split Used: Full test set

Model

Architecture: OpenAI Whisper (fine-tuned for Urdu)

Loading Source: Hugging Face pretrained model

Evaluation Metrics

The model was evaluated using industry-standard speech recognition metrics:

Word Error Rate (WER)

Character Error Rate (CER)
Metrics were computed using the evaluate and jiwer libraries.

Results

📊 Evaluation on Full Test Set

WER: 26.76%

CER: 8.83%

Tools & Libraries

datasets

evaluate

jiwer

numpy

pandas

Usage

Run the provided Python script to load the dataset, generate predictions using the Whisper model, and compute WER and CER scores.
