# Real-Time Influence of Reddit on Cryptocurrency Prices

## 1. Overview
This project aims to analyze the real-time influence of Reddit on the prices of cryptocurrencies, particularly focusing on speculative coins. The goal is to visualize how public sentiment and opinion on Twitter can impact the value of cryptocurrencies, providing insights into the dynamics of market speculation.

## 2. Introduction and Motivation
The cryptocurrency market is known for its high volatility and sensitivity to public opinion. Tweets from influential personalities, news, and even rumors can cause significant fluctuations in the prices of cryptocurrencies. This project is motivated by the need to understand the extent to which Twitter sentiment influences cryptocurrency prices. By analyzing real-time data from Twitter and correlating it with cryptocurrency price movements, I aim to provide valuable insights for investors, analysts, and enthusiasts in the crypto space.

## 3. Objective

The primary objective of this project is to build a comprehensive data pipeline that:

    • Collects real-time tweets related to specific cryptocurrencies.
    • Stores the collected data in a structured format.
    • Analyzes the sentiment of the tweets.
    • Correlates the sentiment analysis with real-time cryptocurrency price data.
    • Visualizes the impact of Twitter sentiment on cryptocurrency prices through interactive dashboards.

## 4. Project Components

#### **1. Data sources**
i. **Twitter API**: For collecting real-time tweets related to selected cryptocurrencies.
ii. **Cryptocurrency Price API**: For fetching real-time price data of the selected cryptocurrencies.

#### **2. Data storage**
  i. **PostgreSQL**: A relational database to store the collected tweets and cryptocurrency price data.
  ii. **Airflow**: For orchestrating the ETL (Extract, Transform, Load) processes and ensuring timely data collection and storage.

#### **3. Data Analysis**
i. **Sentiment Analysis**: Using natural language processing (NLP) techniques to analyze the sentiment of the collected tweets.
ii. **Correlation Analysis**: Correlating the sentiment scores with the real-time price data of cryptocurrencies to identify patterns and insights.

#### **4. Visualization**
i. **Dashboards**: Creating interactive dashboards to visualize the impact of Twitter sentiment on cryptocurrency prices.

## 5. Milestones and Timeframes

The project will be completed in 3 phases, with the following milestones:

Phase 1: Project Setup and Data Collection

	• Set up the project repository and initialize the infrastructure.
	• Obtain API access to Twitter and cryptocurrency price data.
	• Implement scripts for collecting real-time tweets and price data.
	• Store the collected data in PostgreSQL.
	• Set up Airflow for automating data collection.

Phase 2: Data Cleaning and Sentiment Analysis

	• Clean and preprocess the collected tweet data.
	• Implement sentiment analysis using NLP techniques.
	• Store the sentiment analysis results in PostgreSQL.
	• Validate the sentiment analysis results for accuracy.

Phase 3: Correlation Analysis and Initial Visualization

	• Perform correlation analysis between tweet sentiment and cryptocurrency prices.
	• Develop initial visualizations to identify patterns and insights.
	• Refine the data models and analysis based on initial findings.

## Conclusion

This capstone project will provide a detailed analysis of the real-time impact of Twitter sentiment on cryptocurrency prices, offering valuable insights into the speculative nature of the market.

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/1lXY_Wlg)
