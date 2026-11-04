
# AI-Assisted Injury Prediction and Rehabilitation Monitoring

## About the Project

This project demonstrates how Artificial Intelligence (AI) and Machine Learning (ML) can be used in biomechanics to estimate injury risk and monitor rehabilitation progress.

The system uses movement-related and training-related factors to estimate potential injury risk. It also provides basic rehabilitation metrics to track recovery.

## Objectives

- Estimate injury risk using machine learning.
- Analyse training load and fatigue.
- Identify factors associated with potential injuries.
- Monitor rehabilitation progress.
- Calculate range of motion, strength symmetry and exercise adherence.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Random Forest Classifier

## Project Features

### 1. AI-Based Injury Prediction

The model considers:
- Training load
- Sudden increase in training load
- Fatigue level
- Movement mechanics score
- Previous injury history

A Random Forest Classifier is trained to classify the estimated injury risk as Low or High.

### 2. Rehabilitation Monitoring

The rehabilitation module calculates:

- Range of Motion (ROM)
- Strength Symmetry
- Exercise Adherence

These measurements help demonstrate how recovery progress can be monitored.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/AI-Injury-Prediction-Rehabilitation.git
```

2. Open the project folder:

```bash
cd AI-Injury-Prediction-Rehabilitation
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Run the Python program:

```bash
python main.py
```

## Dataset

This demonstration generates a synthetic dataset for machine learning.

It does not use real patient records or clinically validated injury labels.

## Applications

- Sports injury prevention
- Physiotherapy
- Athlete performance monitoring
- Home-based rehabilitation
- Movement analysis

## Limitations

The model is an educational prototype, not a clinically validated prediction system. Its results should not be used for medical diagnosis or treatment decisions.

Real-world implementation would require validated datasets, clinical testing and expert supervision.

## Future Scope

- Integration with wearable sensors.
- Real-time movement tracking using cameras.
- Deep learning-based pose estimation.
- Mobile application for rehabilitation monitoring.
- Integration with physiotherapy platforms.

## Author

Group 13

**Topic:** AI in Biomechanics

**Project:** AI-Assisted Injury Prediction and Rehabilitation Monitoring
