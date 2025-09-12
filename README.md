# framing-and-sentiment-telegram
Framing, propaganda, and sentiment analysis of pro-Ukrainian and pro-Russian Telegram channels around the 2025 Zelensky–Trump meeting.

This repository contains the code and analysis pipeline for my Master’s thesis, which investigates how pro-Ukrainian and pro-Russian Telegram channels framed the 2025 Zelensky–Trump meeting and how audiences responded in their comments. It combines manual coding of frames and propaganda techniques, transformer-based sentiment analysis, and BERTopic topic modeling to explore narrative construction and audience emotional dynamics.


# Thesis Code: Telegram Discourse & Sentiment Analysis

This repository contains the code and reproducible workflows for my Master's thesis:

> **Framing Conflict and Shaping Sentiment: Telegram Discourses Around the 2025 Zelensky–Trump Meeting**

## 📖 Overview

The project integrates:
- **Framing & Propaganda Analysis** — manual coding with a custom scheme
- **Sentiment Analysis** — fine-tuned RuBERT model (`blanchefort/rubert-base-cased-sentiment`)
- **Topic Modeling** — BERTopic clustering for thematic structure
- **Visualization** — figures for pre/post-event framing, sentiment timelines, and topic maps

## 📂 Repository Structure
- `notebooks/` — step-by-step Jupyter notebooks for data processing, model training, and visualization
- `src/` — modular Python scripts for re-usable functions
- `data/` — (optional) raw and processed datasets (add `.gitignore` if sensitive)
- `outputs/` — generated results and figures

## 🚀 Reproducibility

Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
