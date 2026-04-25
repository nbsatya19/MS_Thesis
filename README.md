# MS Thesis - Parkinson's Disease Detection

Deep learning models for detecting Parkinson's Disease using handwriting analysis, speech patterns, gait analysis, and finger tapping measurements.

## Overview

This repository contains the thesis code and trained models for Parkinson's Disease detection across four modalities: handwriting, speech, gait, and finger tapping.

## Project Structure

```
MS_Thesis/
├── models/           # Saved trained models
├── notebooks/        # Analysis and experiments
├── data/            # Dataset directories
├── scripts/         # Preprocessing and utility scripts
└── src/             # Main code modules
```

## Usage

The repository includes functions to reproduce results using the saved models. Each modality has its own model and evaluation script.

To replicate results:

```python
from models import load_model
import evaluation

# Load pre-trained model
model = load_model('path/to/saved/model')

# Run inference and reproduce results
results = evaluation.evaluate(model, test_data)
```

## Modalities

- Handwriting analysis
- Speech patterns
- Gait analysis
- Finger tapping

## Requirements

See requirements.txt for dependencies.

## Installation

```bash
pip install -r requirements.txt
```
