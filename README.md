# Meharry Medical College PhD in Data Science
## Practice Qualifying Exam

### Instructions
- **Answer all questions.**
- **Show all work and reasoning.**
- **You may use calculators and statistical tables where stated.**
- **Total exam time:** 4 hours.

---

## Section 1: Mathematics and Statistical Theory

1. *(Short Answer)* Define the bias-variance tradeoff in statistical learning. Explain with an example in supervised machine learning.
2. **(Problem)** Given a random variable X with probability density function
    f(x) = (1/2) · exp(-|x|), for all real numbers x (Laplace distribution), calculate the mean and variance of X.
3. *(Proof)* Prove that the Central Limit Theorem holds for a sequence of i.i.d. random variables with finite mean and variance. State any necessary conditions.

---

## Section 2: Machine Learning and Artificial Intelligence

1. *(Essay)* Describe the difference between supervised, unsupervised, and reinforcement learning. Give a biomedical data application for each.
2. *(Problem)* You are given a dataset of patient health records. Outline the steps for building and validating a predictive model to forecast diabetes onset, including feature engineering and model selection.
3. *(Short Answer)* What are the ethical concerns regarding algorithmic bias in AI, particularly within biomedical data science? Provide one example and propose a mitigation strategy.

---

## Section 3: Advanced Data Analytics and Predictive Modeling

1. *(Problem)* A logistic regression model is trained to predict cancer risk. The model’s confusion matrix is:

|                   | Predicted Positive | Predicted Negative |
|-------------------|-------------------|-------------------|
| True Positive     | 45                | 5                 |
| True Negative     | 10                | 40                |

- Calculate precision, recall, and F1-score.

2. *(Short Answer)* Explain the difference between parametric and non-parametric models with respect to big data applications.

3. *(Problem)* Given a time-series of sensor data from wearable health devices, design an anomaly detection pipeline using machine learning methods. Justify your choice of algorithms.

---

## Section 4: Database Design and Big Data

1. *(Essay)* Discuss key principles of database normalization. Why is normalization important in biomedical databases?
2. *(Problem)* Design a relational database schema for storing multi-modal biomedical images linked to patient records. Include at least three tables and relevant fields.
3. *(Short Answer)* Compare NoSQL and SQL solutions for managing large genomic datasets. Which would you prefer in a clinical informatics setting, and why?

---

## Section 5: Research Methods and Ethical Practice

1. *(Essay)* Explain the importance of reproducibility and transparency in computational biomedical research.
2. *(Short Answer)* How do privacy laws (such as HIPAA) impact data science research using patient records? List at least two required safeguards.
3. *(Problem)* You are tasked with forming a research question and designing a basic study using Meharry’s cloud computing resources and supercomputing network for cardiovascular genomics analysis. State aims, methods, and expected results.

---

# Solution Key

## Section 1: Mathematics and Statistical Theory

1. **Bias-Variance Tradeoff:**  
   Bias is the error due to erroneous or overly simplistic assumptions in the learning algorithm, while variance is the error due to sensitivity to fluctuations in the training set.  
   *Example:* Linear regression for a complex, non-linear dataset often results in high bias (underfitting). Deep neural networks may have low bias but high variance (overfitting).

2. **Laplace Distribution:**  
   For \(f(x) = \frac{1}{2}e^{-|x|}\), Mean = 0, Variance = 2.

3. **Central Limit Theorem (CLT):**  
   For i.i.d. random variables with finite mean \(\mu\) and variance \(\sigma^2\), the distribution of the normalized sample mean approaches the standard normal distribution as the number of samples \(n\) increases.  
   *Conditions:* Independence, identical distribution, finite mean and variance.

---

## Section 2: Machine Learning and Artificial Intelligence

1. **Supervised, Unsupervised, Reinforcement Learning:**  
   - *Supervised*: Uses labeled data (e.g., diabetes prediction from patient records).  
   - *Unsupervised*: Discovers structures in unlabeled data (e.g., clustering patients by gene expression).  
   - *Reinforcement*: Learns optimal actions via reward signals (e.g., robotic surgical assistance).

2. **Predictive Model Steps:**  
   - Data cleaning and preprocessing  
   - Feature engineering and selection  
   - Split data into training/testing sets  
   - Model selection (e.g., logistic regression, random forest)  
   - Validation (cross-validation, ROC analysis)  
   - Interpretation of results

3. **Algorithmic Bias in AI:**  
   AI models can propagate bias from training data (such as racial or gender biases).  
   *Example:* An algorithm trained on non-diverse data misclassifies minorities.  
   *Mitigation:* Use diverse datasets, employ bias audits, apply fairness-aware algorithms.

---

## Section 3: Advanced Data Analytics and Predictive Modeling

1. **Confusion Matrix Calculations:**  
   - Precision: \( \frac{TP}{TP+FP} = \frac{45}{45+10} = 0.818 \)  
   - Recall: \( \frac{TP}{TP+FN} = \frac{45}{45+5} = 0.9 \)  
   - F1 Score: \( \frac{2 \times 0.818 \times



