# Network-Analysis

## Overview
This project conducts a comprehensive analysis of historical international football match data, aiming to explore team performance and network structures within the context of competitive football. The dataset is processed into node and edge tables, facilitating insights into team interactions and competitiveness.

## Introduction
The primary objective of this project is to investigate international football matches from 1872 to 2024. A network is constructed where teams are represented as nodes, and match outcomes are depicted as edges, allowing for a detailed examination of team dynamics.

## Dataset Description
The project utilizes the following datasets:
- **results.csv**: Contains detailed information about matches, including dates, participating teams, and scores.
- **shootouts.csv**: Includes data on matches that were decided by penalty shootouts.
- **goalscorers.csv**: Lists individual goal scorers for each match.

*Note: Historical team names are standardized throughout the dataset to ensure consistency.*

## Methodology
1. **Data Preprocessing**: The dataset is filtered to exclude friendly matches, and statistical analyses are conducted to create edge and node tables.
2. **Network Analysis**: The NetworkX library is employed for constructing the network and performing community detection.
3. **Visualization**: The resulting network is visualized, and data is exported for further analysis.

## Results
The analysis uncovers significant insights into team interactions, community structures, and competitive dynamics present in international football.
