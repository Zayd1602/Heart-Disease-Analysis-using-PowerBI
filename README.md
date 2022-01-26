<h1>Heart Disease Analysis using Power BI <img width=125 align=right src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white"></h1>

## Problem Statement

Healthcare system facilitates the treatment of patients with the support of wearable, smart, and handheld devices, as well as many other devices. These devices are producing a huge bulk of data which makes it harder for the medical professional to make sense of the data for future prognosis. It takes a lot of time to read the numerical data and can lead to misinterpretation and false prognosis. The current scenario faces a lack of meaningful clinical intelligence available at the point of care. Poor data visualization is also one of the factors which creates one of the biggest overarching problems in the healthcare industry.

## Solution

Power BI is an interactive data visualization software which is responsible for creating, striking, engaging, and meaningful data visualizations that can help to break down even the most complex and convoluted healthcare problems into manageable component parts, giving providers a new level of insight into how to deliver the highest quality care to patients while succeeding with their strategic goals.

## Description

Here, I’ve used the Heart Disease dataset from UCI to identify the key factors responsible for heart disease.

We can see that the visual has two tabs, namely – Key influencers and Top segments and two slicers.

<details><summary><b>Key Influencers</b></summary> 
   
   1. The key influencers tab displays the key factors affecting the value selected. In our case, the top factor that results in positive diagnosis of Heart Disease is Exercise Induced Angina. 
   2. On the other side there may be a column chart or a scatter plot showing the distribution of the selected factor.
   3. We can see a ring around each influencer’s bubble, which represents the approximate percentage of data that influencer contains. The more of the bubble the ring circles, the more data it contains.
   4. We can select different factors to observe their effect on the diagnosis of disease.
</details>
 
<details><summary><b>Top Segments</b></summary>   
   
   1. The top segments tab displays the top segments that are identified by Power BI from the dataset for the metric selected.
   2. It initially shows the overview of all the segments. These segments are ranked by the heart disease detected (True/False) and the number of patients (population size). The higher the bubble the more the percentage of disease detected (True/False). 
   3. The size of the bubble represents the number of patients within the segment.
   4. We can select a bubble which then displays the details of the segment.
</details>
   
- The visualizations are filtered between Disease Detected to be True or False.
- Slicers are a way of filtering. They narrow the portion of the dataset that is shown in the other report visualizations. 
  So, I’ve made two slicers one for filtering from the range of age, and another for filtering from different gender or both.

<div>
   <p>Following is an attempt to create the Obstacle Avoiding robot using 2 gear motors. The front distance is being measured by the ultrasonic sensor.</p>
  
  >Note: We aren't using a servo motor to measure the right and left distance here
   
## Conclusion
