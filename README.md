# MindMelody

ML-driven cognitive music recommendation system that uses EEG, stress, and behavioral datasets to generate personalized productivity-focused music recommendations in real time.

---

## Overview

MindMelody is an AI-powered recommendation platform designed to explore how cognitive and emotional signals can influence music selection and productivity.

The system integrates machine learning models with multi-source datasets to predict optimal BPM-based music recommendations based on cognitive load, stress indicators, and emotional patterns.

Developed during Datathon as an exploration of AI-assisted personalization and human-centered machine learning systems.

---

## Motivation

Music has a measurable impact on focus, stress, mood, and productivity. However, most recommendation systems rely only on listening history or user preferences.

MindMelody explores how machine learning and cognitive data can be used to create adaptive music recommendation systems that respond dynamically to mental state and productivity needs.

---

## Problem

Traditional music recommendation systems:
- prioritize listening behavior over cognitive state
- do not adapt to stress or focus levels in real time
- lack personalized productivity optimization

This creates a gap between entertainment-based recommendations and functional productivity-focused recommendations.

---

## Solution

MindMelody combines EEG signals, stress/emotion indicators, and Spotify metadata into a unified ML pipeline that predicts music recommendations tailored to cognitive load and productivity requirements.

The system:
- processes multiple cognitive and behavioral datasets
- trains machine learning models for prediction
- maps cognitive state to BPM-based recommendation outputs
- generates adaptive productivity-oriented music suggestions

---

## ML Pipeline Overview

Dataset Integration → Data Cleaning → Feature Engineering → Model Training → Cognitive State Prediction → BPM Recommendation Output

---

## Key Features

- Multi-dataset ML integration pipeline
- Cognitive load prediction system
- BPM-based recommendation engine
- Productivity-focused recommendation logic
- Real-time inference workflow simulation
- Personalized music recommendation outputs

---

## AI & Machine Learning Highlights

- Integrated 5 datasets including Spotify, EEG, stress, and emotion indicators
- Built ML models using Random Forest and Linear Regression
- Achieved prediction performance up to R² = 0.70
- Designed inference workflow translating cognitive state into recommendation outputs
- Applied AI-assisted personalization techniques for adaptive recommendations

---

## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Machine Learning
- Data Processing Pipelines
- Recommendation Systems

---

## Model Architecture

Input Data:
- EEG signals
- Stress indicators
- Emotion datasets
- Spotify metadata

Processing Flow:

Data Aggregation → Feature Engineering → Model Training → Prediction Engine → Recommendation Mapping

---

## Machine Learning Models

- Random Forest Regressor
- Linear Regression
- Feature correlation analysis
- Data normalization and preprocessing workflows

---

## Results

- Achieved up to R² = 0.70 in predictive modeling
- Successfully integrated 5 heterogeneous datasets
- Built functioning cognitive-state recommendation workflow
- Demonstrated feasibility of AI-assisted productivity music systems

---

## Running the Project

```bash
pip install -r requirements.txt
python main.py
```

---

## Future Improvements

- Real-time EEG device integration
- Reinforcement learning-based adaptive recommendations
- LLM-powered mood interpretation
- Spotify API live playlist generation
- User feedback loop optimization
- Expanded personalization engine

---

## Technical Notes

- Focused on cognitive-state-based recommendation logic rather than entertainment recommendation
- Designed as an experimental ML workflow exploring human-centered AI systems
- Models optimized for recommendation feasibility and interpretability

---

## Team

Built during Datathon by a student team focused on AI-powered personalization and machine learning applications.
