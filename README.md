# ReviewPulseAI

### Developer Profile

GitHub Profile: https://github.com/jagadeeshguptha9546

### Project Repository

Repository: https://github.com/jagadeeshguptha9546/ReviewPulseAI/tree/main

---

## Overview

ReviewPulseAI is a sentiment analysis pipeline built for processing Yelp review data using modern data engineering and machine learning tools. The project demonstrates how streaming technologies and distributed computing frameworks can be combined to analyze customer feedback at scale.

The system utilizes Apache Kafka for data ingestion, Apache Spark for data processing and machine learning, and MLflow for experiment tracking and model management.

---

## Project Objectives

The primary goals of this project are:

* Process Yelp review data in a streaming environment.
* Perform sentiment classification on customer reviews.
* Explore distributed data processing using Apache Spark.
* Track machine learning experiments using MLflow.
* Build an end-to-end analytics pipeline from data ingestion to prediction.

---

## System Architecture

### Data Ingestion Layer

The project uses Apache Kafka to stream Yelp review data.

Features include:

* Kafka producer implementation
* Topic-based message streaming
* Review text and rating extraction
* Basic error handling mechanisms
* Controlled message publishing

---

### Data Processing Layer

Apache Spark is used to process incoming review data and prepare features for machine learning models.

Text preprocessing includes:

* Tokenization
* Stop-word removal
* Feature extraction
* TF-IDF feature weighting

---

### Machine Learning Layer

The project implements multiple sentiment classification models:

* Logistic Regression
* Random Forest

The trained models are evaluated and tracked using MLflow.

---

### Prediction Interface

A command-line application is included to generate sentiment predictions using trained models.

Supported modes:

* Interactive review prediction
* Batch prediction from files
* Ensemble prediction output

---

## Technology Stack

| Component            | Technology          |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Streaming       | Apache Kafka        |
| Data Processing      | Apache Spark        |
| Machine Learning     | Spark MLlib         |
| Experiment Tracking  | MLflow              |
| Dataset              | Yelp Review Dataset |

---

## Workflow

```text
Yelp Dataset
      ↓
Kafka Producer
      ↓
Kafka Topic
      ↓
Spark Processing
      ↓
Feature Engineering
      ↓
Model Training
      ↓
MLflow Tracking
      ↓
Sentiment Prediction
```

---

## Current Repository Contents

```text
ReviewPulseAI/
│
├── sentiment-cli.py
├── kafka_producer.py
├── spark.ipynb
├── Report.pdf
├── README.md
└── .gitignore
```

---

## Key Learning Areas

This project provides practical exposure to:

* Real-time data streaming
* Distributed data processing
* Natural Language Processing (NLP)
* Machine Learning model training
* Experiment tracking and model management
* End-to-end data engineering workflows

---

## Future Improvements

Planned enhancements include:

* Converting the project into a more modular structure
* Improving documentation and code organization
* Adding advanced NLP models such as DistilBERT
* Building a Streamlit dashboard
* Deploying the application for public use
* Implementing aspect-based sentiment analysis

---

## Acknowledgment

This repository is based on an existing open-source sentiment analysis implementation using Yelp review data. It is being studied, reorganized, and extended as part of my learning journey in Machine Learning, Data Engineering, and Natural Language Processing.
