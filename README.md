## Know Your Consumer: Optimizing Strategies for Online Retail 

### Repository Overview

This repository contains data regarding online shoppers purchasing intention from the UCI machine learning repository.  
The goal is to use machine learning models to accurately predict the likelihood of purchasing given a series of information about the customer's actions within the website.

---

### Dataset

The dataset: The dataset we selected tracked real-time user interactions for online shopping. Capturing the behavior of over 12,000 visitors in a 1-year period, this data provides a window into online shopping habits. Users fall into two categories: those who made a purchase and those who did not. Approximately 84.5% of the records did not complete a transaction and 15.5% of the records did complete a transaction. The imbalanced nature of the data accurately reflects the challenge of online shopping cart abandonment we are aiming to address. This real-world data will be utilized by our predictive model to identify key patterns in user behavior that differentiate purchasers from non-purchasers.

In total, there were 18 features in the dataset. Administrative and Administrative Duration, Informational and Informational Duration, and Product Related and Product Duration represent the number of different types of pages visited by the visitor in that session and the total time spent in each of these page categories. Bounce rate, Exit Rate, and Page Value are metrics measured by Google Analytics for each page in the e-commerce site. Bounce rate refers to the percentage of visitors who leave the website from the very first page, while exit rate is the percentage of visitors who leave your website from any given webpage. Page value is the average page value of the pages that are browsed by the shopper before completing a transaction. Special day is the closeness of the site visiting time to a special day such as a holiday. The categorical features include the operating system and browser the shopper used, the location from where the browsing session was started, the traffic source by which the online shopper reached the shopping site, the type of visitor (new, returning, or other), whether or not the day of the browsing is weekend and the month of the browsing date. The last feature, revenue, labels whether or not the session resulted in a purchase.

---

### Repository Structure

```
ML_Final/
│
├── EDA_Online_Shoppers.ipynb            # Initial working EDA document with initial models
│
├── FinalProject_Section3_Team3.ipynb    # Final Notebook including EDA, feature engineering and final models
│
├── Shopper_Models.ipynb                 # Initial model comparison and tuning
│
├── online_shoppers_intention.csv        # Dataset from UCI ML Repository 
│
```

---

### Project Summary 

Our goal was to accurately identify metrics and features that held strong predictive value in determing if customer visits would result in a purchase or not. Using feature engineering to understand interactions between variables and a Random Forest model to predict purchases based on provided metrics, we were able to achieve 90% accuracy in determining consumer intention while also identifying key features in order to make recommendations to e-commerce brands. 

---

### Contributing

For any questions, comments, issues or contributions, please feel free to open an issue on the Github repository. 

---

### Authors

- **Halladay Kinsey**
- **Vivian Perng**
- **Daniel Grant**

---

### Clone the Repository

To clone this repository, open your terminal or command prompt and run the following command:

```bash
git clone https://github.com/halliekinsey/ML_Final.git
```
---

### Acknowledgments

We would like to express our gratitude to the UCI Machine Learning Repository for providing the dataset, and to our professors and mentors for their guidance throughout the project.

---

**Repository Link**: [Know Your Consumer: Optimizing Strategies for Online Retail GitHub Repository](https://github.com/halliekinsey/ML_Final)
