# Visual Search Strategy Analysis in "Where's Waldo" Images

## Project Overview
This repository contains a small-scale exploratory case study conducted as part of the "Foundations of Academic Research" curriculum. The project investigates human visual search strategies when solving "Where's Waldo" (Where's Wally) puzzles, utilizing high-precision eye-tracking data.

The primary research objective is to validate the **"Reading-Pattern Hypothesis"**—the theory that humans independently apply a systematic top-down, left-to-right scanning strategy (analogous to reading text) when faced with dense visual search tasks, rather than searching chaotic or circular paths.

## Key Features
* **Data Preprocessing:** Cleaning and filtering raw eye-tracking time-series and interval metrics exported from Tobii Pro Lab.
* **Hypothesis Testing:** Statistical evaluation of scanpaths using Spearman rank-correlation to mathematically capture directional trends over time.
* **Macro-Pattern Visualization:** Chronological phase-segmentation (terziles) and rolling averages to filter micro-saccadic noise and isolate global search trajectories.
* **Predictive Modeling:** An exploratory Random Forest Classifier using scikit-learn to evaluate how aggregate gaze metrics (fixation density, vertical structure, spatial variance) relate to search efficiency.

## Tech Stack
* **Language:** Python
* **Data Analysis & Statistics:** Pandas, NumPy, SciPy
* **Visualization:** Matplotlib, Seaborn
