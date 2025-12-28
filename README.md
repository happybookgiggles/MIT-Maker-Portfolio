# MIT-Maker-Portfolio
**Student:** Jazmine Gu  
**Kaggle:** https://www.kaggle.com/happybookgiggles  
**Contact:** jgu@raleighcharterhs.org  
**MIT Applicant**

## Project 1: Learning Systems from Scratch to Application

No high-level ML libraries used for core algorithms.

### Algorithms Implemented:
- **Linear/Logistic Regression** - MSE/cross-entropy loss, gradient descent, convergence analysis
- **Neural Networks** - Backpropagation with chain rule derivation, vanishing gradient analysis
- **Naive Bayes** - Bayesian probability, Laplace smoothing, log-space calculations
- **Gaussian Mixture Models** - EM algorithm, soft assignments, likelihood maximization
- **Hidden Markov Models** - Forward-backward algorithm, Baum-Welch, numerical stability
- **Reinforcement Learning** - Q-learning (Bellman equations), Policy iteration (MDPs)

## Verification
All code represents my original implementations developed on Kaggle. ChatGPT assisted only with debugging syntax errors. No AI tools generated mathematical insights or algorithmic designs.

## Project 2: Hybrid LSTM-RF Violin Emotion Analysis

### System Architecture:
- **Feature Extraction** - MFCCs, chroma, spectral features from 3-second windows
- **Hybrid Model** - Bidirectional LSTM (temporal) + Random Forest (interpretable); 70% LSTM + 30% RF weighted combination

- **Dataset:** 90 self-recorded violin clips + 360 augmented samples
- **Explainability:** SHAP analysis showing emotion-specific feature importance
- **R² Score:** 0.9014 with soft emotion labels (Happy, Sad, Angry)
