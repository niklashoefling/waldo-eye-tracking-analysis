# Visual Search Strategy Analysis in "Where's Waldo" Images

## Project Overview
This repository contains a small-scale exploratory case study conducted as part of the "Foundations of Academic Research" curriculum. The project investigates human visual search strategies when solving "Where's Waldo" (Where's Wally) puzzles, utilizing high-precision eye-tracking data from 8 participants across 3 stimuli.

The primary research objective is to evaluate the **"Reading-Pattern Hypothesis"**—the theory that humans apply a systematic top-down, left-to-right scanning strategy (analogous to reading text) when faced with dense visual search tasks.

## Key Features
* **Data Preprocessing:** Cleaning and filtering raw eye-tracking time-series and interval metrics exported from Tobii Pro Lab.
* **Hypothesis Testing:** Statistical evaluation of scanpaths using Spearman rank-correlation across all participant–stimulus combinations, with a one-sample t-test and Cohen's d to formally test whether directional trends differ significantly from zero.
* **Phase Segmentation:** Chronological tertile-based segmentation to analyze gaze height distribution across early, middle, and late search phases.
* **Heatmap Analysis:** Programmatic analysis of pre-computed heatmap images to quantify area coverage and vertical attention distribution per participant.

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open and run `Waldo_all_recordings.ipynb` top to bottom in Jupyter.

## Tech Stack
* **Language:** Python
* **Data Analysis & Statistics:** Pandas, NumPy, SciPy
* **Visualization:** Matplotlib, Seaborn
* **Image Processing:** Pillow
