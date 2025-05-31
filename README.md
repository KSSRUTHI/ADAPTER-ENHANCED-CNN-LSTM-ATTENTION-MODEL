# Brain Cognitive Emotion Analysis

## Overview
This project processes EEG and EOG data for cognitive and emotional state analysis. The notebook performs data loading, preprocessing, cleaning, and visualization to prepare data for machine learning.

## Requirements
- Python 3.7+
- Libraries: numpy pandas scipy scikit-learn imbalanced-learn seaborn matplotlib
  
## Sample Files Structure
/data/
eeg_features.mat
eog_features.mat
labels.mat
/outputs/
preprocessed_features.csv
cleaned_features.csv
brain_cognitive_emotion.ipynb


## Usage
1. Place .mat files in /data/
2. Run notebook cells sequentially
3. Processed data saves to /outputs/

## Key Features
- Handles missing data
- Standardizes features
- Removes outliers (z-score)
- Visualizes correlations

## Next Steps
- Apply ML models
- Feature selection
- Deep learning approaches
