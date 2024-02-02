# Fiber Photometry Data Analysis for Ucn

## Introduction
This repository contains analysis pipeline for fiber photometry experiments conducted to monitor the activity of UCN Edinger Wesphal populations in vivo. 
The code includes two part.  
1. Fiberphotometry data anlysis.
  - Z score analysis
  - Area under curve calculation (todo)
3. Behavior data analysis based on Ethovision generated files.

## File Structure
The dataset is stored in a tdt system generated file format
- Get it with a dropbox link: https://www.dropbox.com/scl/fo/j7iapyj3py4270dp5hp26/h?rlkey=iacwu25nmztyd709aomkzg564&dl=0

## Requirements
To analyze the data, you will need Python installed on your machine, along with the following libraries:
- Tdt 
- NumPy
- Pandas
- Matplotlib
- SciPy
- os
- Statistics

Ensure these are installed by running:
```bash
pip install tdt numpy pandas matplotlib scipy os statistics

