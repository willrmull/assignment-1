# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

Classification or Regression: Regression as we are working with quantitative data 
Inference or Prediction: Inference as we are trying to explain what is happening and not what will happen
Size of Observation Dataset: 200
Number of Predictors: 4

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

Classification or Regression: Classification as they are looking for a categorical result (success or fail) 
Inference or Prediction: Prediction as they want to know whether a future habitat corridor will be a success
Size of Observation Dataset: 30
Number of Predictors: 11

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

Classification or Regression: Regression as we are working with quantitative data
Inference or Prediction: Prediction as we want to estimate what will happen in the future
Size of Observation Dataset: 52
Number of Predictors: 4

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

Advantages:
- Can fit to wider ranges of data
- Can capture complex non linear relationships better than less flexible ones

Disadvantages: 
- Harder to interpret
- Require more data
- Prone to overfitting

More Flexible Preferred: 
- When we are interested in making accurate predictions and have a large amount of data
- If we want to capture complex relationships 

Less Flexible Preferred: 
- If we are just interested in inference having a restrictive model can make things more interpretable.  

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

Differences: 
- Parametric models assumes that relationship between the parameters and the response variables follows a specific functional relationship. 
- Non-Parametric models don't make assumptions about the functional form of the data and instead try and fit it without being too rigid or loose.

Advantages:
- Easier to interpret
- Require less data

Disadvantages:
- Make strong assumptions about the functional form of f
- Likely to perform worse when prioritizing prediction accuracy

-