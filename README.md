# Analisis Transaksi Transjakarta (April 2023) - Dummy Data
> **Learning Project** : In this project, I performed an end-to-end analysis process, including gathering business requirements, data cleaning, exploratory data analysis, statistical analysis, and developing interactive dashboards using Tableau. 

## 🔗 Project Outcome

📎Raw data source: [Kaggle Dataset](https://www.kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction)

🖼️Presentation Slides (In Indonesian): [Canva](https://canva.link/uvieriu6f8qzg36)

📊Analytics Dashboard: [Tableau](https://public.tableau.com/app/profile/nadia.syailendra8148/viz/TransjakartaDashboard_17757520465640/TransjakartaDashboard)


## Business Understanding

Unlike private businesses, most public transport systems aren’t trying to maximize profit — their primary goal is mobility. It’s about moving people efficiently, safely, and affordably. [[1]](https://www.yieldtactics.com/en/insights/rm-public-transport)

This aligns with TransJakarta mission and values to provide an integrated transportation services that make life in Jakarta easier and more enjoyable. [[2]](https://transjakarta.co.id/tentang/visi-misi-dan-nilai)


## Problem Statement

Analyze corridor route, direction route and peak hours in TransJakarta transaction on April 2023.

Objective: This analysis will be used by Transjakarta operators to enhance operations, making them more efficient and comfortable. 


## Key Questions

1. Which corridor route has the highest passenger volume?
2. Do corridor routes tend to be busier in the outbound or inbound direction?
3. When do peak hours occur?
4. At which stops do the most passengers board?
5. What is the age distribution of TransJakarta passengers?
6. Is the average travel time faster on weekends compared to weekdays?


## Tools

Programming Language: Python (Pandas)

Analytics Dashboard: Tableau

Presentation Slides: Canva


## Result

1. Which corridor route has the highest passenger volume?\
Cibubur - Balai Kota corridor route

2. Do corridor routes tend to be busier in the outbound or inbound direction?\
The outbound and inbound routes have nearly equal (consistent) passenger volumes

3. When do peak hours occur?\
5:00 AM – 9:00 AM and 4:00 PM – 9:00 PM.

4. At which stops do the most passengers board?\
Halte Penjaringan bus stop

5. What is the age distribution of TransJakarta passengers?\
The average is 35.

6. Is the average travel time faster on weekends compared to weekdays?\
Based on hypothesis T-test to compare average travel times on weekends versus weekdays yielded a p-value of 0.04 < 0.05. This means that there is no significant difference between travel on weekdays vs weekend.

## Conclusion

Transjakarta passengers are residents of the Greater Jakarta area (Jabodetabek) living in densely populated neighborhoods.

They choose Transjakarta as their preferred mode of transport for commuting to work on weekdays or traveling on weekends.

The average passenger is of working age, specifically between 35 and 36 years old.


## Recommendations

Planning bus allocations based on corridor routes and peak hours to ensure passenger comfort and prevent overcrowding at bus stops and on the buses themselves.

Expanding feeder or Microtrans services to better reach densely populated residential areas, with subsequent integration into the nearest BRT stations.

Maintaining the high-quality Transjakarta service that connects passengers to their daily lives.