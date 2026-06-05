# Speech Analysis and Error Detection System

An AI-powered speech analysis system designed to detect pronunciation and articulation errors in Malayalam speech. The system leverages OpenAI Whisper, phoneme-level analysis, and custom error detection algorithms to assist speech therapists in identifying speech disorders and providing objective assessments.

## Overview

Traditional speech assessment methods are often manual, time-consuming, and subject to human bias. This project automates the process by transcribing speech, analyzing phoneme-level pronunciation, and identifying articulation errors such as substitutions, omissions, additions, and distortions.

The system is specifically designed for Malayalam speech therapy applications and aims to support clinicians with faster and more consistent evaluations. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Features

- Malayalam speech recognition using Whisper
- Automated pronunciation error detection
- Phoneme-level speech analysis
- Detection of:
  - Substitution errors
  - Omission errors
  - Addition errors
  - Distortion errors
- IPA-based phonetic transcription
- Audio augmentation for dataset balancing
- Interactive Gradio-based user interface
- Therapist-assisted speech assessment support

## Technology Stack

- Python
- OpenAI Whisper
- Gradio
- IPA Tokenization
- Levenshtein Distance Algorithm
- Speech Processing Libraries
- Audio Data Augmentation

## System Workflow

1. User records or uploads speech.
2. Whisper transcribes the audio.
3. Audio is converted into IPA phoneme sequences.
4. Phoneme comparison is performed using Levenshtein Distance.
5. Error types are identified and classified.
6. Results are displayed through the Gradio interface.

## Error Types Detected

### Substitution
One phoneme is replaced by another.

### Omission
A required phoneme is missing.

### Addition
An extra phoneme is inserted.

### Distortion
Incorrect articulation of a phoneme, including:
- Vowel Length Distortion
- Retroflex-Dental Distortion
- Voicing Distortion
- Nasal Place Distortion

## Results

- Word Error Rate (WER): **8.38%**
- Phoneme Transcription Accuracy: **80%+**
- Speech Error Detection Accuracy: **70%**

The results demonstrate the potential of AI-assisted speech therapy tools for objective and scalable speech assessment. :contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

## Applications

- Speech Therapy
- Clinical Assessment
- Pronunciation Training
- Educational Speech Tools
- Early Detection of Speech Disorders
## Screenshots

### Home Page
![Home Page](Screenshot%202026-03-05%20203537.png)
## Future Enhancements

- Support for additional Indian languages
- Real-time speech analysis
- Larger clinical datasets
- Deep learning-based error classification
- Therapist dashboard and reporting tools

## Team

- Athira K
- Elizabeth Reji
- Farhan A N
- Jean Roger

## Guide

Prof. Sandeep Chandran

## License

This project is developed for academic and research purposes.
