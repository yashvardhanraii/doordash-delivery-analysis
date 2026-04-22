# DoorDash Delivery Efficiency Analysis

## Objective
Use my own delivery data to understand where and when I should work to maximise deliveries per hour and avoid low-efficiency shifts.

---

## Project Overview
- Analysed historical DoorDash delivery data in Brisbane.  
- Focused on delivery gaps, timing, and location performance.  
- Used data to move away from guesswork and make better decisions about when and where to dash.  

---

## Key Question
When and where should I dash to maximise delivery efficiency?

---

## Key Insights
- Kelvin Grove, Nundah, and Everton Park consistently performed best, averaging around 6 deliveries per hour.  
- The most efficient time window was 10:00–14:00 (late morning to lunch).  
- Thursday and Friday delivered the highest overall throughput.  
- The Brisbane CBD performed significantly worse, mainly due to parking issues, walking distance, and higher driver competition.  
- Delivery efficiency varied depending on when I chose to work, showing how important shift timing is.  

---

## What I took from this
- Choosing the right location matters as much as working more hours.  
- Midday shifts are more productive than evenings for my setup.  
- Avoiding low-efficiency areas like the CBD can improve overall output.  
- Small changes in timing and location can have a noticeable impact on total deliveries.  

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
- Calculated delivery gaps between consecutive orders.  
- Estimated deliveries per hour across different dimensions.  
- Compared performance by region, hour of day, day of week, and combined patterns.  

---

## Final Outcome
This analysis helped me build a clear, data-driven dashing strategy by focusing on high-performing areas and time periods instead of relying on trial and error.

The results reflect my own working style as a motorbike rider who prefers morning shifts, but the same approach can be applied to improve delivery efficiency in similar conditions.
