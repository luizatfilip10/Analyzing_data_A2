# Analyzing Data Assignment 2: Story feature analysis using Simple Linear Regression
Luiza Teodora Filip s5183685

## Description
This project analyzes storytelling features in posts from the ChangeMyView dataset. 
The goal is to determine whether specific narrative elements (such as agency, curiosity, or suspense) can predict the overall strength of a story.

Using simple linear regression, each story feature is tested individually to evaluate its relationship with the overall story score.

## Dataset
The dataset (data_full_story.csv) contains real comments and posts from the ChangeMyView subreddit.

Variables include:
- story_score: overall strength of the story (0–1 scale)
- agency_score: degree of character agency (1–5 scale)
- event_score: quality of event sequencing (1–5 scale)
- world_score: degree of world building (1–5 scale)
- curiosity_score: level of curiosity created (1–5 scale)
- surprise_score: presence of surprising elements (1–5 scale)
- suspense_score: level of suspense (1–5 scale)

## Methodology
The analysis in the notebook follows these steps:

1. Exploratory data analysis using scatterplots
2. Simple Linear Regression for each story feature
3. Visualization of regression lines
4. Residual analysis
5. Normality testing using the Shapiro-Wilk test
6. Comparison of model performance using the R² score

## Results 
Overall, the results suggest that event sequencing and agency are the most influential storytelling features in predicting story strength.
