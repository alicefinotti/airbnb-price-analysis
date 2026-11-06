# Airbnb Price Analysis
## Overview

Exploratory statistical analysis of **74,111 Airbnb listings across six U.S. cities**, investigating how rental prices and customer reviews vary with property characteristics, location, amenities, and host attributes.

## Methodology

The analysis was conducted in **R** on a dataset containing 26 variables, applying:

- **Descriptive statistics** to examine distributions and compare rental characteristics across cities and property types.
- **Correlation analysis** to investigate relationships between prices, accommodation capacity, and property characteristics.
- **Conditional probability analysis** to examine the prevalence of amenities across different price categories.
- **Data visualization** using histograms, boxplots, scatter plots, and bar charts to identify and communicate patterns.

## Key Findings

- **Location:** San Francisco exhibited the highest average rental prices, while Chicago had the lowest.
- **Property size:** Accommodation capacity showed a positive correlation with rental price (r = 0.568), while the price per guest tended to decrease for larger properties.
- **Amenities:** Listings with more amenities were generally associated with higher prices and a greater number of reviews.
- **Host characteristics:** Verified hosts tended to receive more reviews and slightly higher ratings.

The analysis is exploratory: the relationships identified are statistical associations rather than evidence of causality, particularly given the potential confounding effects between property characteristics.

## Repository Contents

- `analysis.R` — R code for statistical analysis and visualizations
- `final report.pdf` — Detailed methodology, results, and conclusions
- `Appendix-graphs.pdf` — Supporting plots and visualizations
