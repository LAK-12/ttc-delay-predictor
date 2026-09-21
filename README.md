# TTC Delay-Aware Route Planner

This project explores using machine learning and historical TTC transit data to predict delays and eventually recommend more reliable routes and departure times.

## Goals
- Predict expected TTC delay
- Estimate delay risk
- Compare reliability of alternative routes
- Recommend departure times based on predicted reliability

## Project Roadmap
Phase 1: Exploratory data analysis
Phase 2: Data cleaning and feature engineering
Phase 3: Baseline delay prediction
Phase 4: Model comparison and evaluation
Phase 5: GTFS route generation
Phase 6: Reliability-aware route ranking
Phase 7: Real-time data and service alerts
Phase 8: Optional RAG explanation layer

## Project Structure
- `data/raw/`: Original TTC datasets.
- `data/processed/`: Cleaned or transformed datasets.
- `notebooks/`: Exploratory analysis notebooks.
- `src/`: Project source packages for data, features, models, routing, and RAG.
- `models/`: Generated model files.
- `tests/`: Tests.
- `config/`: Project configuration.

## Setup
```bash
python -m venv .venv
```

Windows:
```bash
.venv\Scripts\activate
```

macOS/Linux:
```bash
source .venv/bin/activate
```

```bash
pip install -r requirements.txt
```
