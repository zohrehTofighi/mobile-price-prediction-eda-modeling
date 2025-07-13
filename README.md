# mobile-price-prediction-eda-modeling

##  Project Summary

This project aims to predict the price range of mobile phones using supervised machine learning techniques. It includes detailed exploratory data analysis (EDA) and model training using classification algorithms.


## INFORMATION About Dataset

✔️ Battery_power = Total energy a battery can store in one time measured in mAh.

✔️ Blue = Has bluetooth or not. | 1: Has, 0: doesn't have

✔️ Clock_speed = Speed at which microprocessor executes instructions.

✔️ Dual_sim = Has dual sim support or not | 1: support, 0: doesn't support

✔️ Fc = Front Camera mega pixels.

✔️ Four_g = Has 4G or not. | 1: Has, 0: doesn't have

✔️ Int_memory = Internal memory in gigabytes.

✔️ M_dep = Mobile Depth in cm.

✔️ Mobile_wt = Weight of mobile phone.

✔️ N_cores = Number of cores of processor.

✔️ Pc = Primary Camera mega pixels.

✔️ Px_height = Pixel Resolution Height.

✔️ Px_width = Pixel Resolution Width.

✔️ Ram = Random Access Memory in Mega Bytes.

✔️ Sc_h = Screen Height of mobile in cm.

✔️ Sc_w = Screen Width of mobile in cm.

✔️ Talk_time = Longest time that a single battery charge will last when you are.

✔️ Three_g = Has 3G or not. | 1: Has, 0: Doesn't have

✔️ Touch_screen = Has touch screen or not. | 1: Has, 0: Doesn't have

✔️ Wifi = Has wifi or not. | 1: Has, 0: Doesn't have

✔️ Price_range = This is the target variable. | 3: Very High Cost, 2: High Cost, 1: Medium Cost, 0: Low Cost

## Libraries Used

pandas, numpy, matplotlib, seaborn, sklearn


## Workflow

# EDA:

Checked for null values

Analyzed distributions of key features

Plotted relationships between features and price range

# Feature Engineering:

No explicit feature creation, but exploratory insights were used to inform modeling

# Modeling:

Trained and evaluated classification models (Random Forest, etc.)

Used accuracy score for evaluation

## Visualizations

RAM vs Price Range (RAM is strongly correlated)

Correlation heatmaps

Count plots of features like 4G, dual sim, front/back camera, etc.

## Insights

RAM is the most important factor for predicting price range

Features like 4G, internal memory, and screen resolution also influence the price significantly
