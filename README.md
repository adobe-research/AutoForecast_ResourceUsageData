# AutoForecast_ResourceUsageData

This dataset accompanies our CIKM 2022 paper:

> Mustafa Abdallah, Ryan Rossi, Kanak Mahadik, Sungchul Kim, Handong Zhao, and Saurabh Bagchi. 2022. AutoForecast: Automatic Time-Series Forecasting Model Selection. In Proceedings of the 31st ACM International Conference on Information & Knowledge Management (CIKM '22). Association for Computing Machinery, New York, NY, USA, 5–14. https://doi.org/10.1145/3511808.3557241

In this, we develop techniques for fast automatic selection of the best forecasting model for a new *unseen* time-series dataset, without having to first train (or evaluate) all the models on the new time-series data to select the best one. In particular, we develop a forecasting meta-learning approach called ***AutoForecast*** that allows for the quick inference of the best time-series forecasting model for an unseen dataset. Our approach learns both forecasting models performances over time horizon of same dataset and task similarity across different datasets. The experiments demonstrate the effectiveness of the approach over state-of-the-art (SOTA) single and ensemble methods and several SOTA meta-learners (adapted to our problem) in terms of selecting better forecasting models (i.e., 2X gain) for unseen tasks for univariate and multivariate testbeds.

This dataset is for Adobe’s computing cluster usage for production workloads. This dataset records CPU and Memory usage for 50 different services running in Adobe production clusters collected for 15 days from May 1 to May 15, 2021. 

The entire corpus of datasets (others are curated from existing sources) and our code and models can be found at:
https://drive.google.com/drive/folders/1K1w1Ida5Cr15b5Fhidax-i-fNpWZjvet

- Joint Purdue and Adobe Research Team
  
-- Mustafa Abdallah, Saurabh Bagchi (Purdue)

-- Ryan Rossi, Kanak Mahadik, Sungchul Kim, Handong Zhao (Adobe Systems)
