# DoorDash Delivery Efficiency Analysis

## Objective
Use my own delivery data to figure out **where and when I should work to maximise deliveries per hour** and avoid low-efficiency shifts.

---

## Project Overview
- Analysed historical DoorDash delivery data (Brisbane)  
- Focused on delivery gaps, timing, and location performance  
- Used data to replace guesswork with a clearer dashing strategy  

---

## Key Question
👉 When and where should I dash to maximise delivery efficiency?

---

## Key Insights
- Kelvin Grove, Nundah, and Everton Park consistently performed best, averaging **~6 deliveries per hour**  
- The most efficient time window was **10:00–14:00 (late morning to lunch)**  
- **Thursday and Friday** delivered the highest overall throughput  
- The **Brisbane CBD performed significantly worse**, mainly due to parking issues, walking distance, and higher competition  
- Delivery efficiency varied a lot depending on when I chose to work, showing how important shift timing is  

---

## What I took from this
- Choosing the right **location matters as much as working more hours**  
- Midday shifts are far more productive than evenings for my setup  
- Avoiding low-efficiency areas like the CBD can significantly improve overall output  
- Small changes in timing and location can have a big impact on total deliveries  

---

## Visualisations

### Average Deliveries per Hour by Region
![Delivery Efficiency by Region](region_efficiency.png)

### Average Deliveries per Hour by Hour of Day
![Delivery Efficiency by Hour](hour_efficiency.png)

### Average Deliveries per Hour by Day of Week
![Delivery Efficiency by Day](day_efficiency.png)

### Region and Hour Delivery Efficiency Heatmap
![Region Hour Heatmap](region_hour_heatmap.png)

---

## Tools
- Python  
- Pandas  
- Plotly  
- Jupyter Notebook  

---

## Approach
- Calculated delivery gaps between consecutive orders  
- Estimated deliveries per hour across different dimensions  
- Compared performance by:
  - Region  
  - Hour of day  
  - Day of week  
  - Combined patterns (region + time)  

---

## Final Outcome
This analysis helped me build a **clear, data-driven dashing strategy**, focusing on high-performing areas and time periods instead of relying on trial and error.

The results reflect my own working style (motorbike + morning shifts), but the same approach can be applied to optimise delivery performance in similar conditions.
