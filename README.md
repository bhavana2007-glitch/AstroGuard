# 🚀 AstroGuard AI

## AI-Powered Asteroid Hazard Detection & Monitoring System

**AstroGuard AI** is a Machine Learning-based asteroid hazard detection system designed to analyze Near-Earth Object (NEO) data and classify asteroids based on their potential hazard status.

The project demonstrates how Machine Learning can be applied to large-scale astronomical datasets to support the identification and screening of potentially hazardous asteroids.

AstroGuard AI combines **data preprocessing, Machine Learning classification, model evaluation, and an interactive AI-powered web interface** into a single project.

---

## 🌌 Project Overview

Asteroids and Near-Earth Objects are continuously observed by astronomers because some objects can pass relatively close to Earth's orbit.

With a large number of asteroid observations available, manually analyzing every object can be challenging. Machine Learning can help identify patterns within historical asteroid data and provide an automated classification of objects.

**AstroGuard AI** addresses this problem by training a Machine Learning model on historical asteroid observations and predicting whether an asteroid is classified as potentially hazardous.

### Project Workflow

```text
                    ┌─────────────────────┐
                    │   Asteroid Dataset  │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Data Preprocessing  │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Feature Preparation │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ ML Model Training   │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │   Classification    │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Model Evaluation    │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Hazard Prediction   │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ AstroGuard AI Demo  │
                    └─────────────────────┘
```

---

# 🎯 Problem Statement

The continuous discovery and monitoring of Near-Earth Objects generates large amounts of astronomical data.

Traditional analysis of such datasets can require significant time and effort. There is a need for intelligent computational approaches that can analyze asteroid characteristics and assist in identifying potentially hazardous objects.

### Problem

> How can Machine Learning be used to analyze large-scale Near-Earth Object data and classify asteroids according to their potential hazard status?

### Proposed Solution

AstroGuard AI uses a supervised Machine Learning approach to learn patterns from historical asteroid observations and classify objects into hazardous and non-hazardous categories.

The system provides a computational screening approach that can assist in asteroid analysis and monitoring.

---

# 💡 Objectives

The major objectives of AstroGuard AI are:

- To analyze a large Near-Earth Object dataset.
- To preprocess and prepare astronomical data for Machine Learning.
- To identify useful features for asteroid classification.
- To train a Machine Learning classification model.
- To classify asteroids according to their hazard status.
- To evaluate the model using multiple performance metrics.
- To provide an interactive interface for demonstrating the system.
- To explore the application of AI in astronomical monitoring.

---

# ✨ Key Features

### 🛰️ Asteroid Classification

Uses Machine Learning to classify asteroid observations according to their potential hazard status.

### 📊 Large Dataset Processing

Works with a large historical Near-Earth Object dataset containing hundreds of thousands of records.

### 🤖 Machine Learning

Uses supervised learning to identify patterns in asteroid-related features.

### 📈 Model Evaluation

Evaluates the trained model using:

- Accuracy
- Precision
- Recall
- F1 Score

### 🌐 Interactive Web Application

Provides an interactive AstroGuard AI interface for demonstrating the project.

### 🧪 Google Colab Implementation

The Machine Learning workflow can be explored and reproduced through the provided Google Colab notebook.

### 🎥 Project Demonstration

A project presentation and ML demonstration video are also provided.

---

# 📂 Dataset

AstroGuard AI uses a historical Near-Earth Object dataset containing asteroid observations from **1910–2024**.

The dataset contains:

```text
Total Records     : 338,199
Number of Features: 9
```

### Class Distribution

| Class | Number of Records |
|---|---:|
| Non-Hazardous | 295,037 |
| Potentially Hazardous | 43,162 |
| **Total** | **338,199** |

The dataset contains more non-hazardous than potentially hazardous objects. Therefore, evaluating the model using only accuracy would not provide a complete picture of its performance.

For this reason, AstroGuard AI also considers **precision, recall, and F1-score**.

---

# 🔬 Machine Learning Pipeline

The project follows a standard Machine Learning pipeline.

## 1. Data Collection

Historical asteroid and Near-Earth Object data is used as the input dataset.

## 2. Data Preprocessing

The dataset is examined and prepared before training.

Typical preprocessing operations include:

- Handling data values
- Selecting relevant features
- Preparing the target variable
- Converting data into a suitable format
- Splitting the dataset

## 3. Feature Preparation

Asteroid-related attributes are used as input features for the classification model.

## 4. Train-Test Split

The dataset was divided into:

| Dataset | Records |
|---|---:|
| Training Set | 270,559 |
| Testing Set | 67,640 |
| **Total** | **338,199** |

## 5. Model Training

The Machine Learning model learns patterns between asteroid characteristics and the target hazard classification.

## 6. Prediction

The trained model predicts the hazard classification for unseen asteroid records.

## 7. Evaluation

The model is evaluated using multiple classification metrics.

---

# 📊 Model Performance

The trained model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| **Accuracy** | **91.86%** |
| **Precision** | **73.31%** |
| **Recall** | **56.92%** |
| **F1 Score** | **64.08%** |

### Performance Interpretation

**Accuracy – 91.86%**

The model correctly classified approximately 91.86% of the test observations.

**Precision – 73.31%**

Among the objects predicted as potentially hazardous, approximately 73.31% were correctly classified.

**Recall – 56.92%**

The model identified approximately 56.92% of the potentially hazardous objects in the test set.

**F1 Score – 64.08%**

The F1 score provides a balance between precision and recall and is particularly useful when evaluating classification problems with imbalanced classes.

---

# ⚠️ Why Recall Matters

Asteroid hazard detection is different from an ordinary classification problem.

A false negative means that a potentially hazardous object could be classified as non-hazardous.

Therefore, **recall is an important metric** for this type of application.

AstroGuard AI does not claim to replace professional astronomical monitoring systems. Instead, it demonstrates how Machine Learning can be used as an additional computational screening and analysis approach.

---

# 🧠 What Makes AstroGuard AI Unique?

AstroGuard AI focuses on combining **Machine Learning + astronomical data + an interactive AI-powered interface**.

The uniqueness of the project lies in the complete workflow rather than simply displaying asteroid information.

### Key aspects include:

#### 1. Large-Scale Astronomical Data

The model is trained using a dataset containing **338,199 asteroid records**, allowing the project to demonstrate ML processing on a substantial dataset.

#### 2. ML-Based Hazard Classification

Instead of relying only on manually defined rules, the system learns patterns from historical data.

#### 3. Focus on Near-Earth Objects

The project specifically targets the classification of potentially hazardous Near-Earth Objects.

#### 4. Multiple Evaluation Metrics

The project evaluates the model using accuracy, precision, recall and F1-score instead of relying only on accuracy.

#### 5. End-to-End ML Workflow

The project covers the complete process:

```text
Dataset
   ↓
Preprocessing
   ↓
Feature Preparation
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation
   ↓
Interactive Demonstration
```

#### 6. Interactive Demonstration

The Machine Learning concept is presented through an interactive AstroGuard AI application rather than remaining only as a notebook-based experiment.

---

# 🌐 Live Demo

Experience the AstroGuard AI application:

👉 **[AstroGuard AI – Live Demo](https://astroguard.ai.studio/)**

---

# 🧪 Google Colab

The complete Machine Learning implementation and experimentation are available through Google Colab.

👉 **[Open AstroGuard AI – Google Colab](https://colab.research.google.com/drive/1BQr7JU7U11Ts9Xj8IJ95X-RqhRjEw0y5?usp=sharing)**

The notebook contains the Machine Learning workflow, including:

- Dataset loading
- Data analysis
- Data preprocessing
- Model preparation
- Model training
- Predictions
- Evaluation

---

# 🎥 ML Video Presentation

The project presentation and ML demonstration video are available here:

👉 **[AstroGuard AI – ML Video Presentation](https://drive.google.com/drive/folders/1h0GZEhQuy25LZsuzZG-wn0CjZxk-os06?usp=sharing)**

---

# 🛠️ Technologies Used

## Programming Language

- Python

## Machine Learning

- Scikit-learn
- Pandas
- NumPy

## Development & Experimentation

- Google Colab
- Google AI Studio

## Web Application

- AstroGuard AI interactive web interface

## Dataset

- Near-Earth Object / asteroid dataset
- Historical observations from 1910–2024

---

# 🏗️ System Architecture

```text
                    USER
                      │
                      ↓
            ┌──────────────────┐
            │ AstroGuard AI UI │
            └────────┬─────────┘
                     │
                     ↓
            ┌──────────────────┐
            │ Asteroid Input   │
            │ / Data Analysis  │
            └────────┬─────────┘
                     │
                     ↓
            ┌──────────────────┐
            │ Data Processing  │
            └────────┬─────────┘
                     │
                     ↓
            ┌──────────────────┐
            │ ML Classification│
            │     Model        │
            └────────┬─────────┘
                     │
                     ↓
             ┌───────────────┐
             │   Prediction  │
             └───────┬───────┘
                     │
                     ↓
          ┌─────────────────────┐
          │ Hazard Classification│
          └─────────────────────┘
```

---

# 📈 Evaluation Metrics

AstroGuard AI uses the following metrics.

## Accuracy

Measures the percentage of total predictions that are correct.

```text
Accuracy = Correct Predictions / Total Predictions
```

## Precision

Measures how many predicted hazardous objects were actually hazardous.

```text
Precision = TP / (TP + FP)
```

## Recall

Measures how many actual hazardous objects were correctly detected.

```text
Recall = TP / (TP + FN)
```

## F1 Score

Provides a balance between precision and recall.

```text
F1 = 2 × (Precision × Recall) / (Precision + Recall)
```

---

# 🔍 Challenges Addressed

The project considers several challenges associated with asteroid classification.

### Large Dataset

Processing hundreds of thousands of observations requires efficient data handling.

### Class Imbalance

The number of non-hazardous objects is significantly larger than the number of potentially hazardous objects.

### False Negatives

Missing a potentially hazardous object is more concerning than an ordinary classification error, making recall an important metric.

### Astronomical Data Complexity

Asteroid observations contain multiple parameters that may influence classification.

### Model Generalization

The model must learn patterns from training data and apply them to previously unseen observations.

---

# 🔮 Future Enhancements

AstroGuard AI can be further improved in several ways.

## 🌍 Real-Time Data

Integrate live Near-Earth Object data from reliable astronomical data sources.

## 🛰️ Real-Time Monitoring

Continuously monitor newly observed Near-Earth Objects.

## 📡 Automated Alerts

Generate alerts when an object meets predefined risk criteria.

## 📈 Orbital Visualization

Display asteroid trajectories and orbital paths using interactive visualizations.

## ⚠️ Risk Scoring

Instead of only providing a binary classification, the system could generate a continuous risk score.

Example:

```text
Low Risk       → 🟢
Moderate Risk  → 🟡
High Risk      → 🟠
Critical Risk → 🔴
```

## 🤖 Model Comparison

Compare multiple Machine Learning algorithms to determine which approach provides better performance.

## 🧠 Improved Recall

Experiment with class-balancing techniques and advanced models to improve the detection of potentially hazardous objects.

## 📱 Mobile Interface

Develop a mobile-friendly version for easier monitoring.

## 🔔 Notification System

Provide automated notifications when potentially hazardous objects are identified.

---

# 📌 Limitations

AstroGuard AI is an academic Machine Learning project and should not be considered an operational asteroid-warning system.

The model's predictions depend on the quality and characteristics of the dataset used during training.

The current model should therefore be considered a **Machine Learning research and demonstration system**, not a replacement for professional astronomical observation and planetary-defense systems.

---

# 📁 Suggested Repository Structure

```text
AstroGuardAI/
│
├── README.md
│
├── data/
│   └── asteroid_dataset.csv
│
├── notebooks/
│   └── AstroGuard_AI.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   ├── prediction.py
│   └── evaluation.py
│
├── results/
│   ├── confusion_matrix.png
│   ├── metrics.png
│   └── predictions.csv
│
├── screenshots/
│   ├── home.png
│   ├── prediction.png
│   └── results.png
│
└── requirements.txt
```

---

# ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/bhavana2007-glitch/AstroGuardAI.git
```

Move into the project directory:

```bash
cd AstroGuardAI
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Run the project according to the instructions provided in the source files.

---

# 📦 Requirements

A typical environment for the Machine Learning implementation includes:

```text
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

The exact dependencies may vary depending on the final implementation.

---

# 🚀 How to Use

### Step 1

Open the AstroGuard AI application:

**https://astroguard.ai.studio/**

### Step 2

Explore the available asteroid analysis functionality.

### Step 3

Use the provided input/data to perform the classification.

### Step 4

Observe the predicted asteroid hazard classification.

### Step 5

For the underlying ML implementation, open the Google Colab notebook.

---

# 👩‍💻 Project Team

## Bhavana S

Computer Science and Engineering

## Sahana A

Computer Science and Engineering

---

# 🎓 Academic Project

**Project:** AstroGuard AI  
**Domain:** Artificial Intelligence & Machine Learning  
**Application Area:** Space Technology / Asteroid Monitoring  
**Type:** Machine Learning Classification Project

---

# 🔗 Project Resources

| Resource | Link |
|---|---|
| 🌐 Live Demo | [AstroGuard AI](https://astroguard.ai.studio/) |
| 🧪 ML Notebook | [Google Colab](https://colab.research.google.com/drive/1BQr7JU7U11Ts9Xj8IJ95X-RqhRjEw0y5?usp=sharing) |
| 🎥 ML Presentation | [Google Drive](https://drive.google.com/drive/folders/1h0GZEhQuy25LZsuzZG-wn0CjZxk-os06?usp=sharing) |

---

# ⭐ Conclusion

AstroGuard AI demonstrates the potential of Machine Learning in the field of astronomical data analysis.

By processing a large Near-Earth Object dataset and applying Machine Learning classification, the project explores an intelligent approach to identifying potentially hazardous asteroids.

The project brings together:

```text
🚀 Astronomy
      +
🤖 Artificial Intelligence
      +
📊 Machine Learning
      +
🌐 Interactive Technology
      =
🛰️ AstroGuard AI
```

> **AstroGuard AI — Smarter asteroid analysis through Machine Learning.** 🚀🛰️

---

## ⭐ If you find this project interesting

Give the repository a ⭐ and explore the implementation, ML notebook, and live demonstration.
