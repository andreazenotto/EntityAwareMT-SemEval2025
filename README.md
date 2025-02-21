# Entity-Aware Machine Translation - SemEval 2025

## Overview
Entity-Aware Machine Translation (EntityAwareMT) is a project developed for SemEval 2025, aiming to improve the translation of named entities in multilingual contexts. The project integrates a lightweight Large Language Model (LLM) with Named Entity Recognition (NER) and Retrieval Augmented Generation (RAG) to enhance translation accuracy.

## Features
- **Multilingual Support:** Translates across 10 languages (Italian, Spanish, French, German, Arabic, Japanese, Chinese, Korean, Thai, Turkish).
- **Named Entity Recognition (NER):** Detects and classifies named entities in the source text.
- **Retrieval Augmented Generation (RAG):** Fetches contextually appropriate translations from external knowledge bases.
- **Entity Linking:** Uses Wikidata to ensure entity consistency across languages.
- **Evaluation Metrics:** Translation quality assessed using COMET and M-ETA.

## Dataset
The project is evaluated using the **Mintaka dataset**, a multilingual question-answering dataset based on Wikidata.

## Benchmarking
The system is benchmarked against several state-of-the-art models, including:
- m2m100 (418M, 1.2B)
- LLaMA 3.1 8B-Instruct
- Qwen 2.5 (3B, 7B-Instruct)
- Gemma 2-9B-it (our primary model)

## Results
- **M-ETA Score:** Our approach significantly improves entity translation accuracy.
- **COMET Score:** Demonstrates competitive general translation quality.

## Authors
- Vincenzo Catalano (Politecnico di Torino)
- Andrea Zenotto (Politecnico di Torino)
- Ruben Tetamo (Politecnico di Torino)
