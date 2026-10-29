# Steam Games Analysis

An exploratory study of pricing, visibility, and player ratings in the Steam game catalog, using Python and pandas.

🚧 **Status:** Project setup. Analysis and findings will be added as the study progresses.

## Overview

This project will investigate how game prices, genres, release dates, and review counts relate to player ratings.

The study will cover data quality assessment, cleaning, exploratory analysis, and interpretation of results. Data visualizations will be incorporated as the project develops.

## Research Questions

- How are prices and review counts distributed across the catalog?
- Do higher-priced games receive better player ratings?
- Does the relationship between price and ratings persist across genres and release periods?
- Are games with more reviews also better rated?
- Which genres combine accessible prices with high player ratings?
- How sensitive are rankings and conclusions to different minimum review thresholds?
- Which highly rated games have relatively few reviews under clearly defined selection criteria?

## Planned Approach

- Inspect the dataset structure, data types, missing values, and duplicate records.
- Document cleaning decisions and the number of games included in each analysis.
- Calculate total reviews and the percentage of positive reviews.
- Compare groups using descriptive statistics, aggregations, and pivot tables.
- Explore correlations and differences across price ranges, genres, and release periods.
- Compare game-level averages with review-weighted ratings.
- Repeat key comparisons using different review thresholds to assess the stability of findings.
- Present conclusions alongside their limitations.

## Dataset

Source: [Steam Games Dataset 2025 — Kaggle](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset/versions/2)

The study will use the cleaned March 2025 snapshot. Dataset documentation and attribution will be included in the repository.

## Tools

- Python
- pandas
- NumPy
- SciPy
- Jupyter Notebook

Visualizations will be added using Matplotlib as the study develops.

## Interpretation and Limitations

- Review counts will be used as an indicator of visibility, not as a direct measure of sales.
- Positive review percentages describe the opinions of reviewers, not all players.
- Recorded prices represent the dataset snapshot and may differ from prices paid by reviewers.
- Older games have had more time to accumulate reviews.
- Games may belong to multiple genres.
- Observed relationships will not be interpreted as evidence of causation.

## Learning Context

This independent project applies concepts from the University of Michigan's *Introduction to Data Science in Python* course.

The study will later be extended with visualizations informed by *Applied Plotting, Charting & Data Representation in Python*.
