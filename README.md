# A/B Test Analysis – E-commerce Recommender System

### Project Overview

This project analyzes an A/B test conducted in an international e-commerce platform to evaluate the impact of a new recommender system on user behavior and business performance.

---

### Experiment Description

* **Test name:** recommender_system_test
* **Groups:**

  * A (control group)
  * B (new recommender system)
* **Period:** Dec 7, 2020 – Jan 1, 2021
* **Region:** European Union
* **Goal:** increase conversion at each funnel stage by at least 10%

---

### Dataset

The analysis is based on:

* User events (login, product views, cart, purchases)
* Newly registered users
* Experiment participants
* Marketing events

---

### Workflow

* Data cleaning and preprocessing
* Experiment validation (user consistency, contamination check)
* Funnel analysis
* Metric analysis:

  * Conversion rate
  * Average order value (AOV)
  * Revenue per user
* Outlier detection and removal
* Statistical testing:

  * Proportion z-test
  * Mann–Whitney U test

---

### Key Findings

* No improvement was observed across funnel stages
* Conversion rate in Group B was approximately **11% lower**
* No statistically significant difference in average order value
* Revenue per user was **17%–22% lower in Group B** (statistically significant)

---

### Conclusion

The new recommender system negatively impacted business performance.
The test should be stopped, and **Group A should be considered the winner**.

---

### Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* SciPy

---

### Author

Developed by **Caren Gusmao**
