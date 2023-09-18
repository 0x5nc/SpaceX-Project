# SpaceX Rocket Landing Predictions

## Table of Contents
1. [Outline](#outline)
2. [Executive Summary](#executive-summary)
3. [Introduction](#introduction)
4. [Section 1: Methodologies and Data Details](#section-1)
5. [Section 2: Landing Outcomes Analysis](#section-2)
6. [Section 3: Launch Sites Overview](#section-3)
7. [Section 4: Visual Analysis](#section-4)
8. [Section 5: Classifier Performance](#section-5)
9. [Conclusions](#conclusions)

## Outline
The presentation provides an outline of the upcoming sections.

## Executive Summary
- Methodologies used include:
  - Data Collection through API and Web Scraping
  - Data Wrangling
  - Exploratory Data Analysis using SQL and Visualization
  - Interactive Visual Analytics with Folium
  - Machine Learning Predictions
- The section also provides a summary of the results from various analyses.

## Introduction
- Discusses the background and context of the project.
- Highlights the cost savings of SpaceX due to the reusability of the Falcon 9's first stage.
- The primary goal of this project is to predict if the Falcon 9's first stage will land successfully using a machine learning pipeline.
- Outlines problems to address:
  - Determining factors for rocket landing success.
  - Understanding the relationship between features that determine successful landing.

## Section 1: Methodologies and Data Details
- An overview of the executive summary and methodologies used.
- Details on data collection:
  - Sourcing data from SpaceX REST API
  - Web scraping details from Wikipedia
- In-depth discussion on data wrangling, including:
  - Generating dummy variables
  - Dropping irrelevant columns
- Comprehensive details on exploratory data analysis, interactive visual analytics, and predictive analysis.

## Section 2: Landing Outcomes Analysis
- Discusses the filtering and grouping of landing outcomes between specific dates.

## Section 3: Launch Sites Overview
- Provides an overview of SpaceX launch sites, located on the coasts of the USA (Florida and California).
- Visual markers pinpointing the launch sites.
- Discusses the proximity of launch sites to specific landmarks.

## Section 4: Visual Analysis
- Features visualizations such as:
  - Pie charts showcasing success percentages and ratios for each launch site.
  - Scatter plots illustrating the relationship between payload sizes and launch outcomes.

## Section 5: Classifier Performance
- Analysis of the performance of different classifiers, with a primary focus on the Decision Tree algorithm.
- Presentation of a confusion matrix for the Decision Tree classifier, showcasing its accuracy.

## Conclusions
- Key observations include:
  - Lighter payloads have better performance metrics compared to heavier ones.
  - The success rate of launches has seen an upward trajectory from 2013 to 2020.
  - Specific orbits and launch sites boast higher success rates than others.
  - The Decision Tree classifier is determined to be the most effective algorithm for the dataset.
