# Olympics-Data-Analysis-Dashboard(1896-2016)

# Project Overview
This project is a deep-dive into the historical Olympics dataset to analyze medal trends, athlete performance, country-level dominance, and overall evolution of the games from 1896 to 2016. The data was cleaned, preprocessed, and visualized through an interactive dashboard.

# Business Problem
The Olympic Games are a rich source of data; but the raw dataset is unstructured and overwhelming. Analysts, sports historians, and enthusiasts often struggle to answer basic questions like:

* Which country performed the best in a specific year?

* How have the number of sports, athletes, or nations evolved?

* Which sport has produced the most medals for a country?

* What’s the age range of gold medalists in different sports?


# Tools & Technologies
**Languages:** Python

**Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Plotly

**Dashboard:** Streamlit

**Dataset:** athlete_events.csv, noc_regions.csv


# Features & Functionalities

 **Medal Tally**  
  - Dynamic medal tally view by **Year** and **Country**

  **Overall Analysis**  
  - Key stats: **Editions**, **Hosts**, **Sports**, **Athletes**  
  - Growth of **Nations**, **Events**, and **Athletes** over time  
  - **Most successful athletes** by sport  
  - **Event heatmap** by year

   **Country-wise Analysis**  
  - Country's **medal trend** over years (line graph)  
  - Heatmap showing **dominant sports** by country  
  - **Top 10 athletes** from each country

   **Athlete-wise Analysis**  
  - **Age distribution** by medal type  
  - **Gold medal age** analysis across sports  
  - **Height vs. Weight** plots with medal and gender filters  
  - Male vs. Female **participation trend** over years

#  Outcomes

- Analyzed **120+ years** of Olympic data with over **35,000 athlete entries**
- Identified **USA** as a consistent top performer across years and sports
- Revealed over **300% growth** in **female participation** since the 1980s
- Mapped **sport-wise age trends** — younger medalists in **Gymnastics**, older in **Shooting**
- Visualized **dynamic medal trends** by country and sport using interactive charts

 

# Challenges Faced

- Cleaned **duplicate and inconsistent data**, especially around **NOC codes** and **medal entries**  
- Handled **missing values** in athlete demographics like age, height, and weight  
- Designed **clear and readable visuals** for datasets spanning **120+ years** and thousands of records



# Learnings

- Strengthened skills in **data preprocessing**, **EDA**, and building dashboards using real-world datasets  
- Gained experience in delivering **insightful visualizations** suitable for **non-technical users**  
- Learned to **clean and manage complex datasets** for analysis-ready use  

# Future Improvements

- Add filters for **Summer/Winter Olympics** and **continent-based** breakdowns  
- **Predictive insights**  can be integrated using **machine learning** for advanced analysis


#  How to Run

* git clone https://github.com/Pallavi-Adhikary/Olympics-Data-Analysis-Dashboard-1896-2016 
* cd /Olympics-Data-Analysis-Dashboard-1896-2016 
* pip install -r requirements.txt
* streamlit run app.py
