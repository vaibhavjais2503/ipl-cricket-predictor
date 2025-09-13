# IPL Cricket Predictor 🏏

A machine-learning model that predicts the outcome or win probability of IPL matches given match conditions using historical data.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Model](#model)  
- [Requirements](#requirements)  
- [Contributing](#contributing)  
- [License](#license)

---

## About

This project uses data from past IPL seasons to train a predictive model that estimates the probability of a team winning given information such as batting team, bowling team, city, overs completed, wickets lost, target, etc. The model is deployed as a Python application (e.g. via Streamlit or a notebook) for users to interactively predict match outcomes.

---

## Features

- Predict win probability of the batting team  
- Support for match-level features (team names, venue, etc.)  
- Uses historical IPL data from `matches.csv` and `deliveries.csv`  
- Model saved in file `pipe.pkl`  
- Interactive interface (if using Streamlit or similar)  

---

## Dataset

- **matches.csv** — contains summary of each match (team names, result, etc.)  
- **deliveries.csv** — ball-by-ball data, used for detailed features (runs, extras, etc.)  

Make sure both files are present in the repository.

---

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/vaibhavjais2503/ipl-cricket-predictor-new.git
   cd ipl-cricket-predictor-new
