# Social-media-productivity-analysis
$\text{This study analyzes how excessive social media use negatively impacts student productivity by fragmenting attention and worsening mental health, with implications for human capital development.}$

$\text{Chinyelu Phil-Ebosie}$

$\text{Data Science in Econ Class }$

$\text{April 2026 }$

# Dataset
$\text{The dataset used in this notebook is a synthetically generated dataset designed to simulate realistic global digital behavior patterns among students aged 15–25.}$

$\text{Each record represents one student and includes:}$

$\text{demographic attributes}$

$\text{socioeconomic context}$

$\text{internet access and usage}$

$\text{social media behavior}$

$\text{academic indicators}$

$\text{psychological outcomes }$

# Project Overview

$\text{Questions}$

$\text{Does social media reduce productivity}$

$\text{Do attention span and mental health significantly affect productivity score?}$

$\text{Does social media use reduce attention span minutes?}$

$\text{Does it increase stress level, anxiety score, or depression score?}$


# Methodology
$\text{Data Cleaning and Preparation:}$

$\text{Removed irrelevant variables to streamline the analysis, reducing the dataset from 48 columns to 29 using .Created a new categorical variable to group social media usage into low, medium, and high levels by binning hours into defined ranges. }$

$\text{Statistical Modeling:}$
$\text{Applied linear regression to identify which variables had the strongest impact on productivity}$

$\text{Mapping:}$
$\text{Used `ggplot2` and the maps package to visualize social media usage across counties }$

$\text{Visualization:}$
$\text{Leveraged `ggplot2`to build scatter plots and other visualizations to examine relationships between variables, such as how social media usage influences productivity.}$

# Key Findings

# 1. Map

A global heat map illustrating the average daily hours spent on social media across different countries. This visualization highlights regional trends in digital engagement, identifying North America and Oceania as areas with the highest average consumption.

<img width="431" height="238" alt="Global Social Media Consumption" src="https://github.com/user-attachments/assets/9295e051-7ec0-42b6-957a-9a514f39995c" />


# 2. Linear Regression Model: Analyzing which variable has the most effect on productivity

The linear regression model shows that both attention span and social media usage are statistically significant predictors of productivity `p < 0.001`. Attention span has a strong positive effect on productivity `β = 0.133` , meaning higher attention spans are associated with higher productivity levels. In contrast, social media hours have a significant negative effect `β = -0.213`, indicating that increased social media use is associated with lower productivity.

The model explains about 40.8% of the variation in productivity `R² = 0.4079`, suggesting a moderate explanatory power. The overall model is highly significant `F-statistic p < 2.2e-16`, confirming that the predictors collectively improve the model fit.

Residuals are fairly centered around zero, indicating a reasonable model fit with some variability in prediction error.

<img width="1002" height="720" alt="Screenshot 2026-04-30 222950" src="https://github.com/user-attachments/assets/2c82af56-ae9e-4d41-a593-f5bd3e36ab58" />

# 3. Scatterplot: relationship between social media hours and productivity score

This scatter plot visualizes the inverse relationship between daily social media consumption and productivity. Utilizing a linear regression model, the analysis highlights a downward trend in productivity as social media usage increases. The data is segmented into two-hour 'buckets' to better visualize distribution and identify outliers or missing values within the dataset.


<img width="431" height="238" alt="Relationship with social media and productivity" src="https://github.com/user-attachments/assets/32461030-9b4d-40a2-9180-05557453059d" />


# 4. FaceBox Plot: Distribution of Depression Scores by Social Media Usage and Gender

The faceted boxplot analysis examining the impact of social media usage levels on depression scores, disaggregated by gender. The visualization reveals a uniform increase in median depression scores as social media consumption rises, suggesting a consistent trend across all identified gender groups


<img width="960" height="816" alt="Screenshot 2026-05-01 164640" src="https://github.com/user-attachments/assets/3d6bf166-16de-4a22-b9a2-fae8ea8975b1" />

