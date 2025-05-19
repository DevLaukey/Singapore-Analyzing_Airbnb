# Analyzing Airbnb Listings in Singapore


## Table of Contents

- [Overview](#overview)
  - [Project Motivation](#project-motivation)
  - [Key Insights](#key-insights)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Analysis](#exploratory-analysis)
  - [Predictive Modeling](#predictive-modeling)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results and Visualizations](#results-and-visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This project provides a comprehensive analysis of the Airbnb market in Singapore, examining trends, pricing patterns, popular locations, and key factors that influence rental prices and occupancy rates. Using data science techniques and visualization tools, we explore the dynamics of Singapore's short-term rental ecosystem.

### Project Motivation

Singapore, as a major global tourism hub, has a vibrant and competitive Airbnb market. This analysis aims to:

- 🏙️ Identify neighborhood hotspots and pricing disparities across Singapore
- 💰 Understand the factors that most significantly impact rental prices
- 🗓️ Analyze seasonal trends and booking patterns
- ⭐ Examine the relationship between amenities, reviews, and listing success
- 📊 Develop predictive models for pricing strategy optimization

### Key Insights

- Central Singapore districts command the highest average nightly rates ($X), while outlying areas offer more budget-friendly options
- Properties with views of Marina Bay see a premium of approximately X% over similar properties without views
- Listings with at least 10 reviews demonstrate X% higher occupancy rates than newer listings
- Superhosts command a price premium of approximately X% over non-superhosts for comparable properties
- Seasonal demand peaks during [specific periods], with prices increasing by up to X%

## Data Sources

This analysis utilizes data from:

- Airbnb Inside: Singapore dataset (includes listings, calendar, and reviews data)
- Singapore Tourism Board visitor statistics
- Urban Redevelopment Authority (URA) planning area boundaries
- Additional demographic and economic indicators from Singapore Department of Statistics

## Methodology

### Data Cleaning

- Handled missing values in price, amenities, and review columns
- Standardized location data and mapped to official planning areas
- Removed outliers based on price, minimum nights, and review counts
- Converted categorical variables to appropriate formats
- Normalized text fields (descriptions, reviews) for sentiment analysis

### Exploratory Analysis

- Geographic distribution of listings and price heatmaps
- Temporal analysis of pricing fluctuations and booking patterns
- Correlation analysis between listing features and pricing/occupancy
- Sentiment analysis of reviews to identify key satisfaction drivers
- Clustering analysis to identify market segments and listing types

### Predictive Modeling

- Linear regression models to predict optimal pricing
- Random forest classification to identify factors contributing to superhost status
- Time series forecasting for seasonal demand patterns
- Natural language processing to quantify the impact of listing descriptions

## Getting Started

### Prerequisites

This project requires the following dependencies:

- Python 3.9+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Jupyter Notebook or Lab
- GeoPandas
- Plotly

### Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/singapore-airbnb-analysis.git
```

2. Navigate to the project directory:

```bash
cd singapore-airbnb-analysis
```

3. Create and activate a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

4. Install required packages:

```bash
pip install -r requirements.txt
```

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```
