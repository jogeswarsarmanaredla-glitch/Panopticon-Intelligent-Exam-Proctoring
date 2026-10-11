# Panopticon — Intelligent Exam Proctoring AI

## Overview
Panopticon is an exploratory machine-learning prototype that analyzes
exam-related telemetry and system events to predict supplied event labels.

## Features
- Timestamp alignment of telemetry and system events
- Missing-data inspection
- Feature engineering
- Random Forest classification
- Chronological train, validation, and test splits
- Model evaluation and visualization

## Technology Stack
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Google Colab

## Dataset
The project uses video telemetry and system-event CSV files.

Before publishing, document the dataset source and explain how the
is_cheating labels were created. Do not upload datasets without
permission to redistribute them.

## Running the Project
1. Install the dependencies in requirements.txt.
2. Open the notebook in Google Colab.
3. Upload the required CSV files when prompted.
4. Run the notebook cells in order.
5. Review the generated evaluation metrics and plots.

## Evaluation
The model is evaluated using chronological training, validation,
and test partitions. The decision threshold is selected using
validation data.

Add the final verified metrics from your completed notebook run.

## Limitations
- The dataset contains a small number of labelled events.
- The labels have not been independently verified.
- High scores do not establish real-world cheating detection.
- This is an exploratory classifier, not a validated proctoring system.

## Responsible Use
Predictions should not be used alone to accuse or penalize students.
Real-world use would require independent validation, privacy protections,
bias assessment, and human review.
