# Hotel Booking Cancellation Prediction

A supervised machine learning project for predicting whether a hotel booking will be cancelled based on customer, booking, room, and stay-related features.

## Overview

The objective of this project is to predict the cancellation status of hotel bookings.

The target variable is:

- `0` — Booking not cancelled
- `1` — Booking cancelled

The project follows an end-to-end tabular machine learning workflow covering exploratory data analysis, data preprocessing, feature encoding, model comparison, hyperparameter tuning, and final model selection.

## Dataset

The dataset consists of:

- `train.csv` — Training data containing the target variable
- `test.csv` — Test data without the target variable
- `sample_submission.csv` — Sample submission format

### Features

| Feature | Description |
|---|---|
| `id` | Index/identifier column |
| `adults` | Number of adults in the booking |
| `children` | Number of children |
| `weekends` | Number of weekend days in the booking |
| `weekdays` | Number of weekday days in the booking |
| `meal_type` | Meal type selected by the customer |
| `room_type` | Room type selected |
| `arrival` | Customer arrival date |
| `lead_time` | Number of days between booking and arrival |
| `segment` | Booking type/segment |
| `repeat` | Whether the customer has previously booked the hotel |
| `price` | Average price per room |
| `requests` | Number of special requests |
| `booking_status` | Target: 1 = cancelled, 0 = not cancelled |

## Project Workflow

```text
Data Loading
     ↓
Data Understanding
     ↓
Exploratory Data Analysis
     ↓
Missing Value Analysis
     ↓
Duplicate & Outlier Analysis
     ↓
Feature Preprocessing
     ↓
Categorical Encoding
     ↓
Numerical Scaling
     ↓
Train / Validation Split
     ↓
Model Comparison
     ↓
Hyperparameter Tuning
     ↓
Final Model Selection
     ↓
Retraining
     ↓
Test Prediction
