# Jane Street competition 2024

## Overview

## Setup
1. Clone the repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset using the Kaggle API:
   ```bash
   kaggle competitions download -c 
   ```

## Usage
- Run the data preprocessing:
  ```bash
  python scripts/preprocess.py
  ```
- Train the model:
  ```bash
  python scripts/train.py
  ```
- Generate predictions for submission:
  ```bash
  python scripts/predict.py
  ```
