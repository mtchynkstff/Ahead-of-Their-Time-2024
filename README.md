## Introduction
This notebook analyzes the performance trends in the men's and women's **100-meter and 200-meter dash** in the Summer Olympic Games. The goal is to understand:

* How fast each medalists' time is compared to the model's **expected result** for that Olympic year
* Which medalist **overperformed** their expected result the most compared to all other competitors in the same event
* To **predict** the expected result for Gold, Silver, and Bronze in the 2024 Olympic Games 100-meter and 200-meter dash

This notebook was forked and based on Omri Goldstein's work on [Kaggle](https://www.kaggle.com/code/drgilermo/ahead-of-their-time). The updates to his notebook are the following:

* Added results from the Summer 2020 Olympic Games
* Plotted the data and fitted an exponential curve for **each medal**
* Removed outlier results from early Summer Olympic Games to better fit model
* **Predicted** the results for the 2024 men's and women's 100-meter and 200-meter dash

For a more detailed analysis of this project, you can read my blog post on [Medium](https://medium.com/@randomforestforthetrees/ahead-of-their-time-using-regression-analysis-to-examine-and-predict-olympic-track-field-24685853b48e).
