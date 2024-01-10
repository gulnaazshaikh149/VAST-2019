# VAST-2019 Crowdsourcing for Situational Awareness
This project entails a thorough analysis of seismic events in the fictional city of St. Himark during April, utilizing a government-released application to assess earthquake intensities across various areas, with data cleaning and visualization executed through Tableau and Python, culminating in crucial insights and conclusions.

VAST 2019's Mini Challenge 1 focuses on a disaster in St. Himark post-earthquake. Authorities investigate damage and required resources, aided by a pre-earthquake reporting app facilitating government engagement and emergency response prioritization.

Our analysis aims to determine:
1. How would you prioritize neighborhoods for response? Which parts of the city are hardest hit? 
2. Compare the reliability of neighborhood reports. Which neighborhoods are providing reliable reports? 

We'll utilize the mc1-reports-data.csv file, encompassing individual reports of shaking/damage categorized by neighborhood and time. Citizens can submit reports in 5-minute increments due to server design, possibly delayed during blackouts.

The dataset includes:
Timestamps (formatted as YYYY-MM-DD hh:mm:ss)
Neighborhood locations experiencing trembling or damage
Categorical values {shake_intensity, sewer_and_water, power, roads_and_bridges, medical, buildings} representing shaking intensity and damage severity (from 0 to 10; missing data accepted).

With St. Himark's map and provided shake maps, we'll visualize data using Tableau, exploring trends and answering key questions.
# Map of St. Himark
![image](https://github.com/gulnaazshaikh149/VAST-2019/assets/88612483/201d4197-e171-4dc0-9dec-d440c525147e)
# Pre Quake Shake Map
![image](https://github.com/gulnaazshaikh149/VAST-2019/assets/88612483/4a7ef9cd-ce50-4daf-ad19-5b3d6eb599ac)
# Major Quake Shake Map
![image](https://github.com/gulnaazshaikh149/VAST-2019/assets/88612483/b841a7ec-99d3-4263-a548-103f2b08d10c)
# Visualization Dashboard
![image](https://github.com/gulnaazshaikh149/VAST-2019/assets/88612483/9057a7f8-f4a0-4fc9-8b00-07cf617542a8)
# Result
In summary, using Tableau, we visualized data for VAST 2019 - Mini Challenge 1 questions on situational awareness. We identified Location 3 (Old Town) as the most affected area, differing from public perceptions. While Location 8 (Scenic Vista) had numerous reports, the earthquake intensity was lower, highlighting perception-based data anomalies. Comparing reliability, Locations 8 and 9 had misaligned reports, while Location 3 displayed consistency between public perception and actual shake intensity.
