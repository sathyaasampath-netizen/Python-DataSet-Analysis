# Python-DataSet-Analysis
Air Quality Dataset Analysis, EPA 2021 Vehicle Fuel Economy Analysis, Recipe Review Ratings Prediction, SleepTrackingToolKit
# 🛌 Sleep Tracking Toolkit

**Part1-SleepTrackingToolkit** is a lightweight Python package for analyzing daily sleep patterns using duration and quality scores.  
It allows you to record multiple sleep segments per day, compute meaningful metrics, and detect patterns across days.

---

## 📊 Features
- **DailySleepRecord** class to store date and segments of sleep (duration, quality).
- Compute:
  - Total sleep duration
  - Average quality score
  - Average sleep score (weighted by duration & quality)
  - Restfulness detection (duration + quality thresholds)
- **Analytics utilities**:
  - Overall average sleep duration
  - Best sleep day (highest score)
  - Detect under-sleep days
  - Detect sudden spikes in duration
  - Duration trend analysis (up / down / same)
  - Average score across all days
- **Utils**:
  - Normalize quality values
  - Convert scores into labels (Excellent, Good, Fair, Poor)
  - Compute sleep score from duration + quality

---

## 🔧 Tech Stack
- Python 3.10+
- Pure Python (no external dependencies required)
- `pytest` for testing

---


This repo contains three Jupyter notebooks:

- **Part2.ipynb** — Air Quality dataset: loading, cleaning, and EDA (pandas), dataset shape/features, summaries.
- **part3.ipynb** — EPA 2021 Vehicle Fuel Economy: specs, MPG metrics, engine/drivetrain analyses.
- **Part4Python.ipynb** — Recipe Review Ratings Prediction: full ML workflow (cleaning, EDA, features, models, metrics).


