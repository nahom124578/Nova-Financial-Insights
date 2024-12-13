# Exploratory Data Analysis (EDA) on Financial News Dataset

## Overview

This project focuses on performing an in-depth **Exploratory Data Analysis (EDA)** on a large financial news dataset to extract key insights that can help Nova Financial Solutions enhance its data-driven decision-making. The analysis will cover various aspects such as **descriptive statistics**, **text analysis**, **time series analysis**, and **publisher analysis**. The goal is to explore trends, sentiment, topics, and patterns within the dataset to uncover actionable insights for financial forecasting and investment strategies.

## Objectives

The primary objectives of this EDA are:

1. **Descriptive Statistics**:
   - Obtain basic statistics for textual lengths (e.g., headline length).
   - Count the number of articles per publisher to identify which publishers are most active.
   - Analyze the publication dates to discover trends over time, such as increased news frequency on particular days or during specific events.

2. **Text Analysis (Sentiment Analysis & Topic Modeling)**:
   - Perform sentiment analysis on headlines to gauge sentiment (positive, negative, neutral) associated with financial news.
   - Use natural language processing (NLP) techniques to identify common keywords or phrases, potentially extracting topics or significant events (like "FDA approval", "price target", etc.).

3. **Time Series Analysis**:
   - Analyze how the publication frequency varies over time, looking for spikes in article publications related to specific market events.
   - Study the analysis of publishing times to uncover if there’s a specific time of day when most news is released, which could be crucial for traders and automated trading systems.

4. **Publisher Analysis**:
   - Identify the publishers contributing the most to the news feed and explore whether there is a difference in the type of news they report.
   - If email addresses are used as publisher names, identify unique domains to check if certain organizations contribute more frequently.

## Methodology

### Descriptive Statistics

1. **Headline Length**: 
   - Calculate the length of each headline and provide basic statistics such as mean, median, and standard deviation for headline lengths.
   - Visualize the distribution of headline lengths.

2. **Article Count per Publisher**:
   - Count the number of articles published by each publisher and rank them.
   - Identify the most active publishers and create a visual distribution.

3. **Publication Date Analysis**:
   - Analyze the publication date of each article and identify trends such as increased frequency on specific days or during major market events.
   - Visualize trends in article publication over time.

### Text Analysis

1. **Sentiment Analysis**:
   - Perform sentiment analysis using NLP libraries such as **TextBlob** or **spaCy**.
   - Categorize sentiment into **positive**, **negative**, or **neutral** and summarize the overall sentiment distribution across headlines.

2. **Topic Modeling**:
   - Use techniques like **Latent Dirichlet Allocation (LDA)** to identify common keywords or phrases across the dataset.
   - Extract significant events or topics such as "FDA approval", "price target", or other financial terms.

### Time Series Analysis

1. **Publication Frequency over Time**:
   - Track the number of articles published over time and look for any patterns or spikes, especially during significant market events (e.g., stock market crashes, earnings announcements).
   - Visualize the frequency of article publication using time series plots.

2. **Time of Publication**:
   - Analyze the time of day when most articles are published to detect if there are peak times when news is more likely to be released.

### Publisher Analysis

1. **Active Publishers**:
   - Count the articles published by each publisher and rank the publishers based on activity.
   - Identify the most frequent publishers and analyze any patterns in their reporting.

2. **Publisher Domain Analysis**:
   - If publishers are identified by email addresses, extract the domains to find which organizations contribute more frequently to the news feed.

## Tools and Technologies

- **Python**: The primary programming language for data manipulation, analysis, and visualization.
- **pandas**: For data manipulation and statistical analysis.
- **spaCy/TextBlob**: For sentiment analysis and topic modeling.
- **matplotlib/seaborn**: For data visualization and plotting.
- **nltk**: For text analysis and topic modeling (LDA).
- **datetime**: For handling and analyzing publication dates and times.
- **collections**: For publisher frequency and other text-based analysis.


