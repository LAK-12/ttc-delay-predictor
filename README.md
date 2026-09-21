# WiseCommute - ML-Powered TTC Delay & Route Reliability Planner

I use the TTC in Toronto almost every day, and one thing I’ve noticed is that the fastest route on paper is not always the route that gets you there on time.

This project explores whether historical TTC delay data can be used to predict delays, compare route reliability, and eventually recommend the best route and departure time for a user.

The main question behind the project is:

**Which route is most likely to get you there on time?**

## Why I’m Building This

Since I rely on the TTC regularly, delays and unreliable travel times are a real problem I deal with. I wanted to use that everyday experience as the basis for a machine learning project and see whether historical patterns could help make trip planning more reliable.

## Goals

- Predict TTC delay duration
- Estimate the risk of a significant delay
- Compare route reliability
- Recommend when a user should leave based on their desired arrival time

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Roadmap

1. Explore and clean TTC delay data
2. Build baseline machine learning models
3. Compare and evaluate model performance
4. Add GTFS route and schedule data
5. Rank routes using predicted delay risk
6. Recommend departure times
7. Later add real-time service alerts and optional RAG-based explanations

## Status

Currently working on exploratory data analysis and preparing the data for the first prediction models.
