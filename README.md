# AI/ML Internship Tasks
This repository contains the tasks completed during my AI/ML Internship. Each task demonstrates the application of Machine Learning, Natural Language Processing (NLP), and Deep Learning techniques.

## Task 1: Exploring and Visualizing the Iris Dataset
### Objective
To load, inspect, and visualize the Iris dataset to understand data trends and feature distributions.

### Dataset Used
The Iris Dataset (loaded via Seaborn), containing 150 samples of three iris species.

### Models/Techniques Applied
- Data inspection using Pandas (`head`, `info`, `describe`).
- Data Visualization using Matplotlib and Seaborn.
- Plots: Scatter Plot, Histograms, and Box Plots.

### Key Results
- Setosa is easily distinguishable from other species based on petal measurements.
- Petal length and width are highly correlated.
- Some outliers were identified in the sepal width feature.


## Task 5: Mental Health Support Chatbot (Fine-Tuned)
### Objective
To build an empathetic conversational agent using a fine-tuned LLM for providing emotional wellness support.

### Dataset Used
Wikitext-2 (via Hugging Face Datasets), used for domain-specific language modeling and fine-tuning.

### Models/Techniques Applied
Model: Microsoft DialoGPT-Medium (Conversational Transformer).

### Architecture: Hybrid system combining Neural Sequence Generation with Heuristic Intent Mapping.

### Optimization: Fine-tuned using Hugging Face Trainer API with torch.no_grad() for fast inference.

### Key Results
- The bot successfully recognizes emotional states and responds with empathy.
- Hybrid logic (Intent Mapping) prevents repetitive or irrelevant AI-generated answers.
- Optimized generation parameters reduced latency for near-instant responses.
