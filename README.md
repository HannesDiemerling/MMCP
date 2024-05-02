# MMCP
**Project Status:** In Development

A repository for a Multimodal Conversational Pipeline.

This repository contains the code for a research project focused on developing a multimodal conversational pipeline. 
This pipeline aims to analyze and interpret both verbal and nonverbal cues within dyadic conversations, enabling the generation of contextually relevant responses and realistic facial animations. 
The project is currently under active development, and the codebase is in construction.

**Project Summary:**

The research explores the creation of a system that can effectively understand and participate in two-way conversations. 
The core objective is to train a neural network model capable of processing both spoken words and movements to generate appropriate responses.

**Technical Approach:**

The project utilizes a multimodal training pipeline that leverages various technologies and techniques, including:

* **MediaPipe:** Extracts facial and pose landmarks from video data to capture nonverbal cues.
* **Principal Component Analysis (PCA):** Reduces the dimensionality of facial and pose data while retaining essential information about movement dynamics.
* **Whisper and WhisperX:** Transcribes spoken words into text and provides accurate word-level timestamps.
* **BERT:** Generates context-relevant embedding vectors for spoken words to capture semantic and temporal context.
* **Transformer Model:** Predicts future movements and spoken words based on a context window of past movements and spoken words.

**Pipeline Definition:**

The training pipeline focuses on capturing the temporal context of facial dynamics and spoken words within dyadic conversations. Key steps include:

1. **Landmark Extraction and Normalization:** MediaPipe extracts facial and pose landmarks, which are then normalized to account for individual differences in size and shape. 
2. **Dimensionality Reduction:** PCA is applied to both facial and pose data separately to reduce dimensionality while preserving key movement information.
3. **Speech Transcription and Embedding:** Whisper and WhisperX transcribe spoken words and provide timestamps, while BERT generates context-relevant embeddings for these words.
4. **Dynamic Prediction:** A transformer model uses a context window of past movements and spoken words to predict future movements and spoken words for both conversation participants.

**Future Development:**

The repository will be updated as the project progresses. Future development plans include:

* Implementing the code for a the full pipeline.
* Training and publishing the prediction model.
