# WordlePredictiveInsights

## Overview
WordlePredictiveInsights is an intricate project developed to harness the extensive user-generated data from the popular social media game, Wordle. The project aims to develop predictive models and extract valuable insights into various factors influencing the game's score distribution, reported results, and the difficulty of word solutions.

## 📘 Project Structure
The project is divided into two main parts:
1. **Regression Analysis:** Exploration and expansion of Wordle datasets to investigate the relationship between time, popularity, and the number of reported results.
2. **Gameplay Simulation:** Development of a predictive model that simulates Wordle gameplay in hard mode, utilizing Monte-Carlo methods for accuracy and consistency.

## 🔍 Key Insights
- The exponential regression model, expressed as \(y(t) = 292004 \cdot e^{-0.01724t} + 18000\), was identified as the most accurate for predicting the number of reported results over time.
- The word "EERIE" was categorized as relatively hard, with a predicted score distribution of (0.0, 0.2, 6.1, 31.2, 43.8, 16.0, 7.0) for March 1st, 2023.
- Challenging words typically contain duplicate and rare letters, and a word's difficulty level does not influence the number of submissions in hard mode.

## Conclusion and Further Reading
Our study underscores the significant potential of leveraging user-generated data to develop insightful predictive models and gain a deeper understanding of the dynamics influencing the Wordle game. Through a detailed exploration of the relationship between time, popularity, and reported results, we discerned that the exponential regression model, with time as a pivotal predictor variable, yielded the most accurate predictions. Moreover, we pioneered a predictive model simulating Wordle gameplay in hard mode, unveiling that challenging words predominantly contain duplicate and rare letters, although their difficulty level does not impact the number of submissions.

The findings of our study lay a robust foundation for subsequent research endeavors on Wordle and exemplify the immense potential and versatility of data-driven methodologies in examining popular online games. For an in-depth exploration of our methodologies, comprehensive approaches, and detailed results, please refer to the PDF file located in the current directory of this repository. The project was participated in the 2022 Mathematical Contest in Modeling (MCM).
