# Doordash Delivery Efficiency Analysis

Data analytics project analysing my historical DoorDash delivery data in Brisbane to identify where and when I deliver most efficiently.

This project uses real delivery timestamps to examine patterns in delivery throughput and help determine the most effective regions and time periods to dash.

## Tools
Python, Pandas, Plotly, Jupyter Notebook

## Framework
This project follows the **QDAVI (Question, Data, Analysis, Visualisation, Insight)** framework to structure the analysis.

## Main Question
Where and when should I dash to maximise delivery efficiency based on my historical data?

## What I analysed
- Delivery efficiency based on time gaps between consecutive deliveries
- Average deliveries per hour by region
- Delivery efficiency across hours of the day
- Delivery performance across days of the week
- Region–hour, region–day, and hour–day combinations to identify strong delivery periods

## Key insights
- Kelvin Grove, Nundah, and Everton Park showed the highest delivery efficiency, averaging around **6 deliveries per hour**.
- Delivery efficiency was strongest during the **late morning and lunch period (10:00–14:00)**.
- **Thursday and Friday** showed the highest delivery throughput across the week.
- The **Brisbane CBD showed lower efficiency**, likely due to parking constraints, walking distance to restaurants, and higher driver competition.
- Several patterns varied depending on when I chose to dash, highlighting the importance of personal dashing schedules when analysing this data.

## Example Visualisations

### Average Deliveries per Hour by Region
![Delivery Efficiency by Region](region_efficiency.png)

### Average Deliveries per Hour by Hour of Day
![Delivery Efficiency by Hour](hour_efficiency.png)

### Average Deliveries per Hour by Day of Week
![Delivery Efficiency by Day](day_efficiency.png)

### Region and Hour Delivery Efficiency Heatmap
![Region Hour Heatmap](region_hour_heatmap.png)

## Final Outcome
Based on the analysis, the most effective strategy based on my historical delivery patterns is to dash in **Kelvin Grove, Nundah, or Everton Park** during the **late morning and lunch period (10:00–14:00)**, particularly on **Thursday and Friday**.

These findings are based on my own delivery history and reflect my working style as a **motorbike rider who prefers morning shifts**. Drivers with similar working conditions may also benefit from focusing on these regions and time periods.
