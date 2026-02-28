# Tableau--marriage-rate-analysis
💍 Marriage Rate Analysis: Excel + Tableau


## Dataset used
- <a href="https://github.com/Donovandonz/Tableau--marriage-rate-analysis/blob/main/marriages_state_age.csv">RAW.Marriage-rate-datasets</a>

## 📋 Project Overview
This project analyzes marriage rate trends using Excel for data processing and Tableau for interactive visualization. The analysis explores patterns across different marriage rate trends over time, age pyramid, state comparison, heat matrix by state and age group.

## 🔧 Tools Used
- **Excel**: Data cleaning, preprocessing, and preliminary analysis
- **Tableau**: Interactive dashboard creation and visualization


## 📊 Dashboard Components

### 1️⃣ Marriage Rate Trends Over Time

- **Time period analyzed**: 2017 to 2022
- **Peak years**: 2021-2022 show the highest marriage rates in the dataset

**Gender-Specific Breakdown:**

| Year | Male Rate | Female Rate | Gender Gap |
|------|-----------|-------------|------------|
| 2021 | 57.94 | 53.35 | 4.59 |
| 2022 | 61.10 | 56.75 | 4.35 |

- **Year-over-year growth (2021→2022)**:
  - **Male**: +5.4% increase (from 57.94 to 61.10)
  - **Female**: +6.4% increase (from 53.35 to 56.75)


### 2️⃣ Age Pyramid Distribution

| Age Group | Female Population | Male Population | Total Population | Gender Ratio (M:F) |
|-----------|-------------------|------------------|------------------|-------------------|
| <20 | 51,626 | 15,166 | 66,792 | 0.29:1 |
| 20-24 | 337,949 | 215,658 | 553,607 | 0.64:1 |
| 25-29 | 498,421 | 521,056 | 1,019,477 | 1.05:1 |
| 30-34 | 177,545 | 246,683 | 424,228 | 1.39:1 |
| 35-39 | 75,437 | 102,127 | 177,564 | 1.35:1 |
| 40-44 | 36,837 | 48,423 | 85,260 | 1.31:1 |
| 45-49 | 22,455 | 27,404 | 49,859 | 1.22:1 |
| 50-54 | 13,843 | 18,205 | 32,048 | 1.32:1 |
| 55-59 | 7,975 | 13,705 | 21,680 | 1.72:1 |
| 60-64 | 4,266 | 9,075 | 13,341 | 2.13:1 |
| 65+ | 2,786 | 11,638 | 14,424 | 4.18:1 |
| **TOTAL** | **1,229,140** | **1,229,140** | **2,458,280** | **1:1** |


**Key Population Insights:**

1. **Population peaks**: Both genders peak in the **25-29 age bracket** (1,019,477 total people) and this is the ideal age of marriage


### 3️⃣ State-by-State Comparison: Johor & Selangor Spotlight

**TOP 2 STATES: Johor and Selangor Dominate Marriage Rates**

In 2022 both states show dramatically higher marriage rates than the national average, with Selangor taking the lead.

**TOP 2 STATES: Selangor Takes the Lead**

| State | Gender | Age Group | State Rate | National Avg | Difference | Overall Rank |
|-------|--------|-----------|------------|--------------|------------|--------------|
| **SELANGOR** | Female | 25-29 | **158.9** | 56.75 | ▲ **+102.15** (280% higher) | 🥇 **#1 OVERALL** |
| **SELANGOR** | Male | 25-29 | **95.5** | 61.10 | ▲ **+34.4** (156% higher) | 🥈 #2 Overall |
| **JOHOR** | Female | 25-29 | **152.3** | 56.75 | ▲ **+95.55** (268% higher) | 🥉 #3 Overall |
| **JOHOR** | Male | 25-29 | **85.7** | 61.10 | ▲ **+24.6** (140% higher) | #4 Overall |




### 4️⃣ Heat Matrix: State × Age Group
- **Visualization type**: Marriage rates cross-tabulated by state (rows) and age group (columns)
- **Color scale**: the higher the cells = higher marriage rates

**Heat Matrix - Top Cells (2022 Data):**

| Rank | State | Age Group | Gender | Rate | vs National Avg | Color Intensity |
|------|-------|-----------|--------|------|-----------------|-----------------|
| **#1** | **SELANGOR** | **25-29** | **Female** | **158.9** | ▲ 280% higher | 🟥🟥🟥🟥🟥 Extreme |
| **#2** | **SELANGOR** | **25-29** | **Male** | **95.5** | ▲ 156% higher | 🟥🟥🟥🟥 Very High |
| **#3** | **JOHOR** | **25-29** | **Female** | **152.3** | ▲ 268% higher | 🟥🟥🟥🟥 Very High |
| **#4** | **JOHOR** | **25-29** | **Male** | **85.7** | ▲ 140% higher | 🟥🟥🟥 High |
| *Ref* | National | 25-29 | Male | 61.10 | Baseline | 🟩 Average |
| *Ref* | National | 20-29 | Female | 56.75 | Baseline | 🟩 Average |


## 🔍 Key Insights Summary

### 🥇 **Selangor is the New #1**
- **Female 25-29 in Selangor (158.9)** is the absolute highest rate in your entire dataset
- This is **2.8x higher** than the national female average
- Male rates in Selangor (95.5) are also the highest among males

### 🥈 **Johor Strong Second**
- Female 25-29 rate of **152.3** is remarkably high (#3 overall)
- Male rate of **85.7** is strong but lower than Selangor's 95.5

### 📊 **State Comparison at a Glance**

| Metric | Selangor | Johor | National |
|--------|----------|-------|----------|
| **Female 25-29 Rate** | **158.9** 🥇 | 152.3 🥈 | 56.75 |
| **Male 25-29 Rate** | **95.5** 🥇 | 85.7 🥈 | 61.10 |
| **F:M Ratio** | 1.66:1 | 1.78:1 | 0.93:1 |
| **Combined Rate (M+F)** | **254.4** | **238.0** | 117.85 |

### 🔄 **Pattern Reversal Confirmed**
| Location | Gender with Higher Rate | Ratio (F:M) | Pattern |
|----------|------------------------|-------------|---------|
| **National Average** | 🔵 Males higher | 0.93:1 | Traditional |
| **Selangor** | 🔴🔴 Females MUCH higher | 1.66:1 | REVERSED |
| **Johor** | 🔴🔴 Females MUCH higher | 1.78:1 | REVERSED |


## Dashboard Preview
-<a href="https://github.com/Donovandonz/Tableau--marriage-rate-analysis/blob/main/Marriage-rate-dashboard.png">Marriage-rate-dashboard</a>
<img width="1638" height="783" alt="Marriage-rate-dashboard" src="https://github.com/user-attachments/assets/1308af5b-5b9e-4a51-b303-5e03fd20b169" />
