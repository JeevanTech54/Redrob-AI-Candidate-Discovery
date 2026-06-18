# Redrob-AI-Candidate-Discovery
AI-powered candidate discovery and ranking system using semantic embeddings, behavioral signals, and hybrid scoring for intelligent recruiter recommendations.
# Intelligent Candidate Discovery & Ranking System

## Redrob Hackathon 2026

### Overview

This project was developed for the Redrob Intelligent Candidate Discovery & Ranking Challenge.

The objective is to identify highly relevant candidates for a Senior AI Engineer role by combining semantic understanding, behavioral intelligence, and hybrid ranking techniques.

Unlike traditional keyword-based search systems, this solution focuses on understanding candidate intent, experience, and recruiter-readiness.

---

## Dataset Overview

The dataset contains:

* 100,000 candidate profiles
* Career histories
* Skills and certifications
* Professional summaries
* Behavioral signals
* Recruiter engagement metrics

---

## Solution Architecture

Job Description

↓

Semantic Understanding

↓

Candidate Profile Construction

↓

Embedding Similarity

↓

Behavioral Signal Analysis

↓

Career Relevance Scoring

↓

Experience Fit Evaluation

↓

Hybrid Ranking Engine

↓

Top 100 Candidate Recommendations

---

## Semantic Matching

Candidate profiles are transformed into rich textual representations using:

* Current role
* Professional summary
* Skills
* Career history
* Experience

Sentence Transformers (`all-MiniLM-L6-v2`) are used to generate embeddings for both the job description and candidate profiles.

Cosine similarity is then used to measure semantic relevance.

---

## Behavioral Intelligence Layer

The ranking engine incorporates recruiter-focused behavioral features:

* Recruiter Response Rate
* Open To Work Status
* Profile Completeness
* GitHub Activity
* Saved By Recruiters
* Experience Alignment

These signals help estimate candidate availability and hiring readiness.

---

## Hybrid Scoring Formula

Final Score

= 0.55 × Semantic Similarity

* 0.15 × Career Relevance

* 0.10 × Recruiter Response Rate

* 0.05 × Profile Completeness

* 0.05 × GitHub Activity

* 0.05 × Recruiter Interest

* 0.05 × Experience Fit

---

## Technologies Used

* Python
* Pandas
* NumPy
* Sentence Transformers
* Scikit-Learn
* FAISS
* Google Colab

---

## Results

The system successfully identified candidates with strong experience in:

* Search Systems
* Retrieval Systems
* Recommendation Systems
* Ranking Systems
* Production Machine Learning

while incorporating recruiter engagement and behavioral readiness signals.

---

## Future Improvements

* Learning-to-Rank Models
* Cross-Encoder Re-ranking
* LLM-Based Candidate Reasoning
* Online Feedback Loops
