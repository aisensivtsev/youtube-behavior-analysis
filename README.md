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
<<<<<<< HEAD
- Year-over-year activity comparisons
- Aggregated CSV outputs
- Search Behaviour Analysis
- Year-over-year activity comparisons
- Content Theme Analysis
- Aggregated CSV outputs

## Repository Structure

youtube-behavior-analysis/
│
├── data/ # Local raw data (ignored by Git)
│
├── data_processed/ # Aggregated, privacy-safe outputs
│ ├── watch_counts_by_year.csv
│ ├── search_counts_by_year.csv
│ └── top_channels_top15.csv
│
├── notebooks/ # Main analysis notebook
│ └── youtube_behavior_analysis.ipynb
│
├── README.md # Project documentation
├── CITATIONS.md # Sources and references
├── AI_USE_STATEMENT.md # Description of AI assistance
└── .gitignore # Protects private data

>>>>>>> fcb7f02 (Finalize documentation, AI statement, reflection, and analysis outputs)
## How to Run
1. Place Takeout JSON files inside `data_raw/`
2. Open `/notebooks/youtube_behavior_analysis.ipynb`
3. Run all cells from top to bottom

## Privacy
Raw activity data is excluded using `.gitignore`. Only aggregated,
non-identifiable outputs are published.
