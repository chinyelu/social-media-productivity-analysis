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

$\text{Removed irrelevant variables to streamline the analysis, reducing the dataset from 48 columns to 29 using .Created a new categorical variable to group social media usage into low, medium, and high levels by binning hours into defined ranges.}$

$\text{Statistical Modeling:}$

$\text{Applied linear regression to identify which variables had the strongest impact on productivity.}$

$\text{Mapping:}$

$\text{Used `ggplot2` and the maps package to visualize social media usage across counties.}$

$\text{Visualization:}$

$\text{Leveraged `ggplot2`to build scatter plots and other visualizations to examine relationships between variables, such as how social media usage influences productivity.}$

# Key Findings

$\text{The linear regression model shows that both attention span and social media usage are statistically significant predictors of productivity `p < 0.001`. Attention span has a strong positive effect on productivity `β = 0.133`, meaning higher attention spans are associated with higher productivity levels. In contrast, social media hours have a significant negative effect `β = -0.213`, indicating that increased social media use is associated with lower productivity.}$

$\text{The model explains about 40.8% of the variation in productivity `R² = 0.4079`, suggesting a moderate explanatory power. The overall model is highly significant `F-statistic p < 2.2e-16`, confirming that the predictors collectively improve the model fit.}$

$\text{Residuals are fairly centered around zero, indicating a reasonable model fit with some variability in prediction error.}$



