# European Soccer Match Classification

## Project Overview

This is a **Level 2 classification project** using the European Soccer Database.

The project will focus on predicting football match outcomes while working with a relational SQLite database containing multiple connected tables.

The main goal is to practise a more realistic machine learning workflow involving database exploration, SQL based data extraction, data cleaning, feature preparation, classification modelling, validation, and reusable Python code.

## Data Source

This project uses the European Soccer Database compiled by Hugo Mathien.

Source:
https://www.kaggle.com/datasets/hugomathien/soccer

The dataset contains match, player, team, player-attribute, team-attribute,
league, country, betting-odds and match-event data.

The original dataset documentation identifies Football-Data as a source
for betting odds and SOFIFA as a source for FIFA player and team attributes.

The dataset remains subject to the terms and conditions of its original
source. The MIT license in this repository applies to the project source
code and does not grant additional rights to the dataset or its underlying
contents.

## Initial Project Structure

```text
football-match-classification/
├── data/
│   └── database.sqlite
├── notebooks/
│   ├── 01_database_exploration.ipynb
│   ├── 02_eda.ipynb
│   └── 03_model_experimentation.ipynb
├── src/
├── models/
└── README.md