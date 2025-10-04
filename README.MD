# 🎮 Flood-It! Game Analytics Dashboard  

A data analytics dashboard built with **game event data** to analyze player behavior, level performance, and conversion across the **Flood-It!** free mobile game.  

🔗 **[View the interactive dashboard on Looker Studio →](https://lookerstudio.google.com/reporting/506c75d3-9105-44ff-9ddb-aad1a6819208)**  
<p align="center">
  <a href="https://lookerstudio.google.com/reporting/506c75d3-9105-44ff-9ddb-aad1a6819208" target="_blank">
    <img src="https://github.com/ntmh12/game-analysis/blob/main/FloodIt_Analytics_Preview.png" />
  </a>
</p>

---

### 🎯 Key Metrics Tracked
- Player Sessions & Active Users  
- Retention Rate and Churn Analysis  
- Conversion Funnel (from **level_start → level_complete**)  

---

## 📦 Data Preparation  

- Queried Firebase Analytics (Flood-It! demo dataset) via BigQuery using the public table firebase-public-project.analytics_153293282.events_*  

- Derived additional analytical features such as:

    - Session duration using the time difference between the first and last event per user per day.

    - Event flags (level_start, level_up, level_complete) to track player progression.
    - Built retention tables to calculate month-over-month user retention using cohort logic.

This ETL workflow supports scalable, flexible, and near real-time analytics for player behavior insights.  

---

## 🧰 Tools & Technologies  

- **BigQuery**  
- **Looker Studio (Data Studio)** 

---

## ✅ Key Takeaways  

- Most players churn after **1–2 sessions**, highlighting an opportunity to improve onboarding.  
- **Completion rate** improves significantly among players who reach level 3 or higher.  
- Visualizing player journeys through funnels helps identify where engagement drops.  

---

**The end!** 🚀
