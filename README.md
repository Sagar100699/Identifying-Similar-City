# Identifying-Similar-City
This project builds a city similarity recommendation engine to support A/B testing for Swiggy's Smart Delivery Slots feature. Instead of comparing the experiment city against all cities, the model identifies the most similar cities based on historical business metrics, enabling a more reliable control group for measuring experiment outcomes.

# 🛍️ Swiggy: Identifying Similar City  – Mini Capstone

## 📌 Problem Statement

## Business Context

Swiggy plans to launch a new feature called Smart Delivery Slots, which allows users to schedule food deliveries during peak hours.

Before launching this feature nationwide, the Product team wants to run an A/B experiment in one city.

However, simply comparing the experiment city against the entire country would lead to biased results because every city has different customer behavior, restaurant density, pricing, and conversion rates.

To accurately measure the impact of the experiment, the team needs to identify a control city that closely resembles the experiment city.

For this project, Kolkata has been selected as the experiment city.

Your task is to identify the five most similar cities to Kolkata using historical business metrics.


## Objective:

Build a recommendation engine that identifies cities that are most similar to Kolkata based on available business metrics.

To achieve this:

1. Prepare the dataset.
2. Normalize all numerical features.
3. Use the K-Nearest Neighbors (KNN) algorithm to measure similarity between cities.
4. Identify the Top 5 cities most similar to Kolkata.
5. Visualize the results and explain why these cities are good candidates for a control group
