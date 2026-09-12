# USA Crime Analysis & Business Intelligence

## 📌 Overview

This project is a **Business Intelligence and Data Warehouse project** focused on analyzing crime statistics across the United States.

The objective is to study the number of crimes by **crime type** and **U.S. state**, and to analyze crime levels in relation to two main socioeconomic indicators:

* Population
* Poverty rate

The project includes data extraction, ETL processes, data warehouse modeling, calculations, and data visualization.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze crime statistics across U.S. states.
* Compare different types of crimes between states.
* Analyze **robberies, aggravated assaults, and murders**.
* Calculate crime indicators based on state population.
* Analyze crime statistics in relation to poverty levels.
* Identify differences in crime levels between U.S. states.
* Build a structured data warehouse for analytical purposes.
* Create visualizations to facilitate data interpretation.

---

## 📊 Data Sources

The project uses several datasets containing information about U.S. states, population, poverty, and crime statistics.

### Input Database

The input database contains the following tables:

* `poverty`
* `population_by_state`
* `total_robberies_by_state`
* `total_aggravated_assaults_by_state`
* `total_murders_by_state`

These datasets provide the information required for the ETL and analytical processes.

### Output Database

The processed data is organized into analytical tables, including:

* `static_state_population`
* `static_state_poverty`

---

## 🏗️ Data Warehouse Modeling

A data warehouse approach was used to organize the data for analytical purposes.

The project includes **star-schema modeling**, with tables designed to facilitate the analysis of crime statistics according to:

* U.S. state
* Population
* Poverty
* Crime type

The modeling process transforms the source data into structured analytical datasets.

---

## 🔄 ETL Process

The project implements ETL workflows to extract, transform, and load the data.

### ETL Pipeline

The main steps include:

1. **Extract**

   * Retrieve population, poverty, and crime datasets.

2. **Transform**

   * Clean and prepare the data.
   * Combine information from different sources.
   * Calculate crime indicators.
   * Calculate crime percentages based on population and poverty.

3. **Load**

   * Store the transformed data in analytical tables.
   * Prepare datasets for visualization and analysis.

The project includes separate ETL processes for analyzing crime statistics according to **population** and **poverty rate**.

---

## 📈 Crime Indicators

Several indicators are calculated to facilitate comparisons between states.

### Crime by Population

Crime statistics are analyzed relative to the population of each state.

For example, the project calculates the percentage of murders relative to the population.

### Crime by Poverty Rate

Crime statistics are also analyzed in relation to the poverty rate of each state.

This allows the project to explore the relationship between socioeconomic conditions and crime levels.

---

## 📊 Data Analysis & Visualization

The project uses several types of visualizations to analyze and communicate the results.

The implemented visualizations include:

* Tables
* Histograms
* Murder percentage histograms
* Treemaps
* Maps
* Funnel charts
* Pie charts
* Donut charts

These visualizations provide different perspectives on crime distribution across U.S. states.

---

## 🔎 Main Analyses

The analysis focuses on:

### Crime Distribution by State

Comparison of crime levels across U.S. states.

### Crime Distribution by Type

Analysis of:

* Robberies
* Aggravated assaults
* Murders

### Crime Relative to Population

Crime indicators are normalized according to state population to allow more meaningful comparisons between states with different population sizes.

### Crime and Poverty

The project also examines crime statistics according to the percentage of poverty in each state.

---

## 🛠️ Technologies & Tools

The project is based on Business Intelligence and data integration concepts, including:

* **ETL**
* **Data Warehouse**
* **Star Schema**
* **Data Transformation**
* **Data Analysis**
* **Data Visualization**
* **Talend / TMap**

---

## 📁 Project Structure

```text
usa-crime-analysis-bi/
│
├── data/
│   ├── poverty/
│   ├── population/
│   └── crime/
│
├── etl/
│   ├── population/
│   └── poverty/
│
├── database/
│   ├── input/
│   └── output/
│
├── visualizations/
│
├── documentation/
│
└── README.md
```

> The folder structure can be adapted depending on the files included in the final GitHub repository.

---


## 🎓 Academic Project

This project was developed as part of an academic **Business Intelligence / Data Warehousing** project.

The work covers the complete analytical workflow, from source data and ETL processes to data modeling and visualization.

---

## ⭐ Key Concepts

**Business Intelligence · Data Warehouse · ETL · Star Schema · Data Integration · Data Analysis · Crime Analytics · Data Visualization · Population Analysis · Poverty Analysis**
