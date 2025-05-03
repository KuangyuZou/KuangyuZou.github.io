---
layout: post
title: "Airline Rating Recommendation Project"
date: 2025-05-02
author: Kuangyu Zou
categories: Project
---

Over three months (October–December 2023), I led the development of an Airline Rating Recommendation System using more than 23,000 passenger reviews. I began by ingesting raw review data—cleaning missing entries, normalizing timestamps, and categorizing metadata (e.g., seat class, route, airline). Through exploratory analysis, I visualized rating distributions over time, computed correlation matrices to pinpoint top drivers of satisfaction (including seat comfort, cabin service, and punctuality), and identified seasonal sentiment trends.

Next, I transformed text feedback into quantitative features using CountVectorizer, extracting the most informative unigrams and bigrams. I complemented this with sentiment scoring (via a lexicon-based approach) and engineered additional variables such as review length and term diversity. These steps produced a rich feature set of over 150 variables.

For modeling, I chose ElasticNet regression to balance interpretability and regularization. I performed a grid search with five‑fold time‑series cross‑validation to tune the alpha and l1_ratio hyperparameters, ultimately minimizing out‑of‑sample error. The finalized model achieved a mean squared error of 4.22 on hold‑out data. Finally, I translated the model insights into strategic recommendations—prioritizing cabin upgrades, staff training, and targeted marketing for peak travel seasons—to help airlines enhance the overall passenger experience.

