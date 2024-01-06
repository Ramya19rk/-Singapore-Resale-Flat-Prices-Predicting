# Singapore-Resale-Flat-Prices-Predicting

Problem Statement: Develop a machine learning model and deploy a user-friendly web application to predict resale prices of flats in Singapore, leveraging historical transaction data to aid potential buyers and sellers in estimating property values.

NAME : RAMYA KRISHNAN A

BATCH: DW75DW76

DOMAIN : DATA SCIENCE

DEMO VIDEO URL : 

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

