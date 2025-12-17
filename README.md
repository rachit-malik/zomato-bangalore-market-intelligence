# ${\color{red}Zomato}$ Zomato Bangalore Market Intelligence Case Study  
## An End-to-End Data Analytics Project (Ask → Act)

**Author:** Rachit Malik  
**Role:** Data Analyst  
**Tools Used:** R (R Markdown), Power BI, GitHub  
**Dataset Source:** Kaggle (Zomato Bangalore Restaurants Dataset)

---

## About This Project

This repository documents a **complete end-to-end data analytics case study**, designed using the **Google Data Analytics framework**, applied to the Bangalore restaurant ecosystem using Zomato data.

The project is intentionally written so that:
- A beginner can **learn how to structure and execute a real analytics project**
- A recruiter can **quickly evaluate analytical, technical, and business skills**
- A stakeholder can **understand insights and recommendations without code**

**Objective:**  
To help restaurant investors make a **data-driven, low-risk decision** on:
- Where to open a restaurant
- What cuisine to serve
- What price point and operational model to follow

---

## Index (Click to Navigate)

- [1. Business Problem & Scenario](#1-business-problem--scenario)
- [2. Analytics Framework Used](#2-analytics-framework-used)
- [3. Dataset Information](#3-dataset-information)
- [4. Data Preparation & Cleaning (R)](#4-data-preparation--cleaning-r)
- [5. Feature Engineering](#5-feature-engineering)
- [6. Analysis & Insights](#6-analysis--insights)
- [7. Power BI Dashboard Architecture](#7-power-bi-dashboard-architecture)
- [8. Key Findings](#8-key-findings)
- [9. Business Recommendations](#9-business-recommendations)
- [10. Skills Demonstrated](#10-skills-demonstrated)

---

## 1. Business Problem & Scenario

Bangalore is one of the most competitive food markets in India, with thousands of restaurants opening and shutting down every year.

Most restaurant failures happen not because of bad food alone, but due to:
- Poor location choice
- Incorrect pricing strategy
- Ignoring customer behavior
- Weak operational infrastructure

### The Challenge
Investors often rely on intuition or trends. This project replaces intuition with **evidence-based decision making**.

### My Role
I acted as a **Data Analyst / Market Auditor**, using historical Zomato data to identify:
- Market saturation
- Demand patterns
- Characteristics of top-performing restaurants

---

## 2. Analytics Framework Used

This project follows the **Google Data Analytics lifecycle**:

1. Ask – Define the business problem  
2. Prepare – Understand and source the data  
3. Process – Clean and transform the data  
4. Analyze – Identify trends and patterns  
5. Share – Visualize and communicate insights  
6. Act – Provide business recommendations  

Each phase is explicitly documented to make the workflow **reproducible and educational**.

---

## 3. Dataset Information

### Data Source
The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants

### Dataset Description
The dataset contains information on Bangalore-based restaurants, including:
- Restaurant name and location
- Cuisines offered
- Cost for two
- Ratings and votes
- Online ordering and table booking availability
- Restaurant type (delivery, dine-out, cafes, pubs, etc.)

![](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/assets/Screenshot%202025-12-15%20013645.png?raw=true)

1[](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/assets/Screenshot%202025-12-15%20013634.png?raw=true)

### Important Note on Data Availability
Due to GitHub file size limitations, **the original raw dataset is not uploaded to this repository**.

Instead:
- The dataset can be downloaded directly from Kaggle
- Cleaned and transformed CSV files generated using R are included (or can be regenerated using the R Markdown file)

This ensures:
- Legal compliance
- Lightweight repository size
- Full reproducibility

---

## 4. Data Preparation & Cleaning (R)

All data preparation was performed using **R and R Markdown** to ensure transparency and reproducibility.

### Key Cleaning Steps
- Removed duplicate restaurant entries
- Handled missing values in ratings and cost columns
- Standardized cuisine names
- Normalized restaurant types
- Filtered invalid or non-informative records

### Why R Markdown? 
[Rmarkdownfile](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/final%20zomato%20analysis.Rmd)
[html Rmarkdowm](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/final-zomato-analysis.html)
- Combines code, explanation, and output
- Makes analysis auditable
- Shows analytical thinking, not just results

---

## 5. Feature Engineering

Additional analytical features were created to support deeper insights:

- Popularity metric based on total votes
- Quality metric using average rating
- Price segmentation using cost for two
- Top 1% restaurant classification based on vote percentile

### Final Analytical Tables Exported from R
- `zomato_clean_data.csv`
- `zomato_radar_profile.csv`
- `top_cuisines.csv`
- `top_liked_dishes.csv`

These tables were later used directly in Power BI.

---

## 6. Analysis & Insights

### Market Overview
- Total Restaurants: ~51,000
- Average City Rating: ~3.7 / 5
- Average Cost for Two: ~₹555
- Total Votes: ~15 million

### Key Analytical Questions Answered

#### Where should a new restaurant open?
- Identified locations with high demand but lower average ratings
- Highlighted opportunity zones with reduced competitive pressure

#### What price point performs best?
- Mid-priced restaurants attract the highest engagement
- Premium pricing succeeds only with strong operational support

#### Which cuisines dominate the market?
- North Indian and Chinese cuisines are highly saturated
- Differentiation and execution quality matter more than novelty

#### Do operational features matter?
- Table booking availability strongly correlates with top-tier success
- Online ordering alone does not guarantee higher ratings

---

## 7. Power BI Dashboard Architecture

### Page 1: Market Strategy
Objective: Identify location and business model opportunities

- Geo Map:
  - Bubble size represents votes (popularity)
  - Color gradient represents ratings (quality)
- Scatter plot of cost vs rating by restaurant type
- Slicers for location, price range, online ordering, and table booking
![page_1](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/assets/Screenshot%202025-12-17%20064051.png?raw=true)
---

### Page 2: Operational Deep Dive
Objective: Compare average restaurants with top 1% performers

- Scale gap visualization showing votes and cost differences
- Technology adoption comparison
- Competitor table with conditional formatting on ratings
![page2](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/assets/Screenshot%202025-12-17%20064101.png?raw=true)
---

### Page 3: Menu Intelligence
Objective: Identify winning product mix

- Bar chart of most common cuisines
- Word cloud of dishes mentioned in highly rated restaurants
![page3](https://github.com/rachit-malik/zomato-bangalore-market-intelligence/blob/main/assets/Screenshot%202025-12-17%20064504.png?raw=true)
---

## 8. Key Findings

- Top-performing restaurants receive nearly ten times more customer engagement
- High ratings are supported by infrastructure, not food quality alone
- Booking systems, visibility, and customer experience drive long-term success

---

## 9. Business Recommendations

- Target locations with high demand but weaker quality indicators
- Focus on mid-range pricing with strong engagement potential
- Prioritize table booking infrastructure early
- Execute popular dishes consistently rather than over-experimenting
- Compete on experience and accessibility, not price wars

---
## 10. Skills Demonstrated

- Business problem framing
- Data cleaning and transformation in R
- Analytical and statistical thinking
- Power BI dashboard design
- Data storytelling and communication
- End-to-end project ownership

---

## Final Note

This project demonstrates that successful analytics is not about tools alone,  
but about asking the right questions and converting data into decisions.

If you found this project useful, feel free to star the repository.
