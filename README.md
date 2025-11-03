# 🚗 Electric Vehicle Analysis

A comprehensive data analysis project exploring various aspects of electric vehicles including performance metrics, pricing, efficiency, and charging capabilities.

## Project Overview

This project analyzes electric vehicle data to uncover insights about:
- Vehicle performance (acceleration, top speed, range)
- Battery efficiency and capacity
- Pricing trends across different segments
- Charging capabilities
- Market distribution by body style and powertrain

## Dataset

The dataset contains information about various electric vehicles with the following key columns:
- **Brand & Model**: Vehicle identification
- **Performance**: Acceleration (0-100 km/h), Top Speed, Range
- **Battery**: Battery pack capacity, Efficiency
- **Charging**: Fast charging capabilities
- **Specifications**: Powertrain, Body Style, Segment, Seats
- **Pricing**: Price in Euros

## Installation & Setup

### Prerequisites
- Python 3.7+
- Google Colab or Jupyter Notebook

### Analysis Features
1. Data Exploration

    Dataset loading and basic information

    Descriptive statistics

    Missing values analysis

2. Count Plots

    Powertrain Distribution: Analysis of AWD, RWD, FWD vehicles

    Body Style Analysis: Distribution across SUV, Sedan, Hatchback, etc.

3. Performance Analysis

    Range Analysis: Vehicle range comparison across models

    Acceleration: 0-100 km/h performance metrics

    Top Speed: Maximum speed capabilities

4. Battery & Efficiency

    Range vs Battery Pack: Relationship between battery size and range

    Efficiency Analysis: Energy consumption per kilometer

    Fast Charging: Charging speed comparisons

5. Economic Analysis

    Price vs Range: Value analysis across different price points

    Segment Pricing: Price distribution across vehicle segments

    Brand Analysis: Average pricing by manufacturer

### Key Visualizations

    Bar plots for range, acceleration, and charging analysis

    Scatter plots for correlation studies

    Count plots for categorical data distribution

    Box plots for price distribution analysis

    Correlation heatmaps for feature relationships

### Insights

    Range of vehicle is proportional to Battery Pack Capacity
    Price of vehicle is proportional battery pack capacity
    EV's which cost less have higher acceleration(0-100 Km/Hr) time in order to maximize range
    High performance EV's have lower efficiency
    
