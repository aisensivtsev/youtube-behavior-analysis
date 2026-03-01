# YouTube Behavior Analysis (Google Takeout)

## Overview
This project analyzes YouTube watch history and search history exported
from Google Takeout. The goal is to transform non-tabular JSON data into
a structured dataset and explore behavioral patterns over time.

## Objectives
- Convert raw JSON activity logs into tabular data
- Analyze viewing patterns by time and date
- Identify most watched channels
- Compare activity across years
- Produce privacy-safe analytical outputs

## Dataset
Source: Google Takeout (YouTube Watch & Search History)

Raw files are excluded from this repository for privacy reasons.

## Workflow
1. Load JSON exports
2. Normalize nested data
3. Feature engineering (time-based variables)
4. Visualization and analysis
5. Export aggregated results

## Key Outputs
- Viewing patterns by hour and weekday
- Top watched channels
- Year-over-year activity comparisons
- Aggregated CSV outputs

## How to Run
1. Place Takeout JSON files inside `data_raw/`
2. Open `/notebooks/youtube_behavior_analysis.ipynb`
3. Run all cells from top to bottom

## Privacy
Raw activity data is excluded using `.gitignore`. Only aggregated,
non-identifiable outputs are published.
