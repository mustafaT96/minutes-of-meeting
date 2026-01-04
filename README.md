## Minutes of Meeting Generator using LLMs

### Overview
This project demonstrates an end-to-end AI pipeline that converts meeting audio into structured Minutes of Meeting (MoM). It combines speech-to-text transcription with large language model–based summarisation to automatically extract key discussion points, decisions, and action items from spoken conversations.

The goal of this project is to showcase how LLMs can be integrated into practical productivity workflows rather than used in isolation.

---

## Problem Statement
Meetings are time-consuming, and manually writing accurate minutes is error-prone and inconsistent. Important decisions or action items are often missed, especially in longer discussions.

This project addresses that problem by automating the process of:
- transcribing spoken meetings
- summarising discussions
- generating structured, readable meeting minutes

---

## What the System Does
The system takes a recorded meeting as input and produces structured minutes that include:
- a concise meeting summary
- key discussion points
- identified decisions
- actionable next steps

The output is designed to be readable, consistent, and suitable for sharing with stakeholders.

---

## High-Level Architecture
The pipeline follows these steps:
- Audio input is provided as a meeting recording
- Speech-to-text is used to generate a transcript
- The transcript is processed using a large language model
- Structured Minutes of Meeting are generated as the final output

This notebook focuses on clarity of flow and correctness of results rather than premature optimisation.

---

## Technologies Used
- Python
- Speech-to-Text model for transcription
- Large Language Models for summarisation and structuring
- Jupyter Notebook for experimentation and prototyping

The project is designed to be model-agnostic and can be extended to support different providers or deployment environments.

---

## Project Structure
- **Mom_Product.ipynb**: Main notebook containing the full pipeline logic
- **.env.example**: Example environment configuration (no secrets included)
- **pyproject.toml**: Dependency and project configuration
- **assets/screenshot.jpg**: Example output or UI snapshot
- **Sample audio file**: Demo input for testing the pipeline

---

## Why This Project Matters
Automating meeting documentation is a common real-world use case across enterprises, startups, and consulting teams. This project demonstrates practical AI engineering skills such as:
- designing multi-step AI workflows
- integrating multiple AI components into a single pipeline
- structuring LLM outputs for real business use

---

## Future Improvements
Planned enhancements include:
- refactoring the notebook into modular Python components
- adding a lightweight API or UI layer (FastAPI or Gradio)
- handling long meetings through chunking and aggregation
- adding basic evaluation and quality checks for generated minutes
- deploying the pipeline in a cloud environment

---

## Disclaimer
This project is a demonstration and uses sample audio and placeholder configuration values. No sensitive data or production credentials are included.
