# 🏅 Olympics Data Analysis Dashboard (1896 - 2016)

An interactive data analysis dashboard built using **Streamlit** that uncovers deep insights from **120+ years of Olympic history**. This project visualizes athlete trends, medal performances, gender participation shifts, and much more through rich, interactive visualizations.



##  Project Objective

To analyze historical Olympic data (1896–2016) and build an interactive dashboard that helps:

- Visualize medal tallies by country/year
- Track participation trends of athletes, nations, and sports
- Understand gender-based evolution and sport-wise age trends
- Enable dynamic country-level performance insights



##  Problem Statement

While Olympic data spans over a century, it's **underutilized** due to:
- Lack of accessible, centralized dashboards
- Manual and static reports offering limited insights
- No comparative sport/gender/country-based breakdowns

This project solves that by delivering a **clean, interactive dashboard** that makes Olympic data accessible and insightful.



##  Features & Functionalities

✅ **Medal Tally**  
- View by Year and Country (dynamic filtering & tables)

✅ **Overall Analysis**  
- Editions, Hosts, Sports, Nations, Athletes  
- Nation/Event/Athlete growth over time  
- Most successful athletes by sport  
- Event heatmap across years  

✅ **Country-wise Analysis**  
- Medal tally trend line  
- Sport-wise heatmap of medals  
- Top 10 athletes for selected country  

✅ **Athlete-wise Analysis**  
- Age distribution by medal type  
- Gold medalist age trends across sports  
- Height vs. Weight scatterplot (with medal & gender filters)  
- Male vs. Female participation trends over time  

---

## Outcomes

- Analyzed **120+ years** of Olympic data with over **35,000 athlete entries**
- Identified **USA** as a consistent top performer across years and sports
- Revealed over **300% growth** in **female participation** since the 1980s
- Mapped **sport-wise age trends** — younger medalists in **Gymnastics**, older in **Shooting**
- Visualized **dynamic medal trends** by country and sport using interactive charts

---

##  Tools & Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Streamlit** (for dashboard UI)
- **CSV datasets**: `athlete_events.csv`, `noc_regions.csv`

---

## Challenges Faced

- Cleaning inconsistencies across historical data formats
- Handling missing country-region mappings
- Designing a scalable dashboard with multiple visual layers
- Resolving performance issues in rendering large heatmaps

---

## How to Run

* git clone https://github.com/Pallavi-Adhikary/Olympics-Data-Analysis-Dashboard-1896-2016-
* cd Olympics-Data-Analysis-Dashboard-1896-2016-
* pip install -r requirements.txt
* streamlit run app.py
