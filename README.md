# Singapore-Resale-Flat-Prices-Predicting

Problem Statement: Develop a machine learning model and deploy a user-friendly web application to predict resale prices of flats in Singapore, leveraging historical transaction data to aid potential buyers and sellers in estimating property values.

NAME : RAMYA KRISHNAN A

BATCH: DW75DW76

DOMAIN : DATA SCIENCE

DEMO VIDEO URL : https://www.linkedin.com/posts/ramyakrishnan19_exciting-project-announcement-singapore-activity-7149269987692548096-JBgb?utm_source=share&utm_medium=member_desktop

Linked in URL : www.linkedin.com/in/ramyakrishnan19

# Overview

The project involves the development of a machine learning model and the creation of a user-friendly web application. The primary objective is to predict the resale prices of flats in Singapore using historical transaction data. The model aims to assist both potential buyers and sellers by providing accurate estimates of the resale value for a given flat. The project encompasses data collection and preprocessing, feature engineering, model selection and training, evaluation, and the deployment of the web application on a suitable platform. The anticipated outcome is a well-trained machine learning model accessible through a user-friendly interface, facilitating informed decision-making in the competitive Singapore housing market.

# Libraries for preprocessing

    import pandas as pd
    import glob
    import json
    import requests
    import streamlit as st
    from geopy.distance import geodesic

# Libraires for ML Processing

    import pandas as pd
    import numpy as np
    import statistics
    import warnings
    warnings.filterwarnings('ignore')
    import seaborn as sns
    import matplotlib.pyplot as plt
    from sklearn.preprocessing import StandardScaler
    from sklearn.model_selection import train_test_split
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
    from sklearn.model_selection import GridSearchCV
    import pickle

# Domain

The project is situated in the real estate domain, focusing on the resale market in Singapore. It addresses the challenges faced by individuals who seek to estimate the resale value of their flats.

# Project Structure

# Home:

Overview: A brief introduction to the project's objectives and scope.

Domain: Insights into the real estate domain in Singapore.

Technology Used: Overview of the technologies and tools employed in the project.

Images: Visuals showcasing key aspects of the project.

<img width="1440" alt="Screenshot 2024-01-06 at 10 40 26 AM" src="https://github.com/Ramya19rk/-Singapore-Resale-Flat-Prices-Predicting/assets/145639838/1beb2233-04de-49df-b1e8-c8805ba8cc1a">


# Resale Price:

Form Structure: A user-friendly form containing input fields for street name, block number, floor area, lease commence date, and storey range.

Predict Sales Price: Clicking this button triggers the machine learning model to predict the resale price based on the provided input.

<img width="1440" alt="Screenshot 2024-01-06 at 10 40 37 AM" src="https://github.com/Ramya19rk/-Singapore-Resale-Flat-Prices-Predicting/assets/145639838/39498472-113b-4135-b4de-1a7d31854845">


# Usage

To use the web application:

Select "Resale Price" from the menu.

Fill in the required details in the form.

Click the "Predict Sales Price" button.

Obtain the predicted resale price for the flat in Singapore.



