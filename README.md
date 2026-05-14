# Deep Learning for Hotel Booking Cancellation Prediction

## Overview

This project focuses on predicting hotel booking cancellations using deep learning models. Hotel booking cancellations are an important problem in the hospitality industry because they can affect revenue, room availability, staff planning, and overall hotel operations.

The aim of this project is to build and compare different deep learning architectures that can predict whether a hotel booking will be cancelled or not based on customer booking information.

The project uses a structured hotel booking dataset and applies data preprocessing, exploratory data analysis, class balancing, model training, hyperparameter tuning, and performance evaluation.

---

## Project Title

**A Comparative Evaluation of Deep Learning Architectures for Structured Hotel Booking Cancellation Prediction**

---

## Objective

The main objective of this project is to predict hotel booking cancellations using deep learning techniques.

The project compares three deep learning architectures:

- 1D Convolutional Neural Network (1D CNN)
- Deep Neural Network (DNN)
- CNN + DNN Hybrid Model

The models are evaluated to identify which architecture performs best for structured hotel booking cancellation prediction.

---

## Problem Statement

Hotel cancellations can create financial and operational challenges for hotels. Unexpected cancellations may lead to revenue loss, poor room management, staffing issues, and inaccurate demand forecasting.

Traditional machine learning methods may not always capture complex relationships between booking features such as lead time, customer type, deposit type, market segment, and special requests.

Deep learning models can automatically learn complex patterns from structured data, making them suitable for predicting whether a booking is likely to be cancelled.

---

## Dataset

The dataset used in this project is the hotel booking dataset, which contains:

- **119,390 booking records**
- **32 features**
- Numerical and categorical booking information
- Binary cancellation status

The target variable is:

```python
is_canceled
