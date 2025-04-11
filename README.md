# Project-Principal-Component-Analysis-on-Life-Insurance-and-Real-Estate


---
Title: Principal Component Analysis on Life Insurance and Real Estate.

Date: 2022/3/12

Course:Multivariate Analysis

---


## Life Insurance Brand PCA

### 1. Choose the Number of Components 

According to the output of PCA, the cumulative proportion of variance reaches a plateau after **2 components**, indicating that two principal components are sufficient to explain the majority of the data variance.

Also, the scree plot shows a noticeable "elbow" after the second component, further supporting the selection of 2 components.

### 2. Factor Interpretation

#### - **Factor 1: Brand Attractiveness**

- X1: Recall without prompting  
- X3: Preferred brand impression  
- X5: Brand trust  
- X7: Distinctive brand character  
- X8: Used the brand  

**Interpretation**:  
This component reflects brands that are naturally memorable and positively evaluated in terms of trust, uniqueness, and usage experience. The more a brand is recalled and favored without assistance, the higher its **perceived attractiveness**.

#### - **Factor 2: Small Brand Recognition**

- X2: Recognition with prompting (negative loading)  
- X9: Most frequently used brand (positive loading)  

**Interpretation**:  
Although certain brands are less recognized unless prompted (lower visibility), they may have a strong core of loyal users. This indicates **small brands with high loyalty** — not widely known, but consistently used by a specific group.

---

## Real Estate Brokerage Brand PCA

### 1. Choose the Number of Components 

Similar to the insurance dataset, the scree plot and eigenvalue rule suggest selecting **2 components**.

### 2. Factor Interpretation

#### - **Factor 1: Brand Reputation**

- X1: Recall without prompting  
- X3: Brand preference  
- X5: Trust in brand  
- X7: Brand character  

**Interpretation**:  
This factor represents overall brand image or reputation, where higher recall, trust, and uniqueness are associated with more favorable evaluations.

#### - **Factor 2: Small Brand Awareness**

- X2: Recognition with prompting (negative loading)  
- X6: Most trusted brand (positive loading)  

**Interpretation**:  
This factor captures the **recognition and trust** of lesser-known brands. While these brands are not spontaneously recalled, they may still be strongly trusted by specific users, showing a pattern of **niche loyalty**.

---

## Conclusion

Across both datasets:

- **Factor 1 consistently reflects general brand image**, shaped by trust, uniqueness, and recall.
- **Factor 2 highlights smaller brands**, which may not dominate in recognition but sustain high loyalty within a niche.

This analysis offers valuable insights for marketers: **Brand strength isn’t just about visibility — loyalty among a focused group matters too.**

