# Final Project Deliverable 1 Presentation

## Selected Topic
World Happiness Report

## Reason why we selected this topic
While exploring potential machine learning projects, we were discouraged by how gloom the datasets were and the World Happiness Report seemed like an obvious choice. We also knew that it would be a perfect dataset due to the fact that it contains 8 variables for us to use in machine learning exploration.

## Description of source of data

We found the dataset on Kaggle - it has a Usability rate of 9.71 and contains 20 columns and 149 rows. The data was found by interviewing 1,000 people in each of the participating countries. As such, the data, other than GDP and healthy life expectancy, are subjective. The data types consist of integers for all columns except country name.

## Questions we hope to answer with the data
- We hope to find which variable is the most impactful when measuring happiness in each country and how the different variables compare to each other. 
- Do the subjective measures of happiness have a greater impact than GDP?
- Possibly, we wish to look at the progression of countries’ happiness through the ten year collection of data the World Happiness Report maintains.

## Description of the communication protocols
- Below is a general outline but for the most part we will be dividing the responsibility equally.
- MARIANNE - Square: The team member in the square role will be responsible for the repository.
- MAREIKE - Triangle: The member in the triangle role will create a mockup of a machine learning model. This can even be a diagram that explains how it will work concurrently with the rest of the project steps.
- ERIK - Circle: The member in the circle role will create a mockup of a database with a set of sample data, or even fabricated data. This will ensure the database will work seamlessly with the rest of the project.

## Explanation of Machine Learning
We decided to use three models to see which varibales impacted a countries happiness measure the most. We then conducted all three examples with a second dataframe which removed the outlier of the first attempt. This outlier was logged GDP, we were interested in seeing which variables (generosity, freedom to make life choices, perception of corruption social support and healthy life expectancy) other than money had the greatest impact.

In the first run using GDP, GDP was the greatest contributing in decision tree and random forest models, which had the highest accuracy. Linear regression found healthy life expectancy to be the variable of greatest importance. The second time without we found more variance per model.
For Linear Regression:
- Healthy life expectancy stayed as the with the greatest contributing impact. 
- Our accuracy rate, more noticably, went up from .62 to .75.
- All varibale also had a positive impact on the outcome whereas in the original they had varied effects.
For Decicision Tree:
- social support and then healthy life expectancy  were found to be the variables of greatest impact, with an accuracy of .9981
Random Forest 
- Like decision tree social support followed by healthy expectancy as the most impactful variable. The accuracy was measured at .9983
