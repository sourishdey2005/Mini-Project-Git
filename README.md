<img width="1600" height="618" alt="image" src="https://github.com/user-attachments/assets/507ef7e5-3ff6-4903-90e0-d141ef14fec7" />
1. Particulate Matter Distribution ($PM_{2.5}$ and $PM_{10}$)Observation: Both graphs show a heavy right-skewed distribution (long tails to the right).Interpretation: While the most frequent (modal) concentrations for $PM_{2.5}$ are around $50$–$100$ µg/m³, there are significant "outlier" events extending beyond $400$ µg/m³.Research Insight: This indicates that while "moderate" days exist, Punjabi Bagh frequently experiences extreme pollution episodes, likely corresponding to winter smog and stubble burning periods.2. Nitrogen Dioxide ($NO_2$) and Ammonia ($NH_3$)$NO_2$ Trends: The peak frequency is centered around $25$–$50$ µg/m³. The distribution is tighter than PM, suggesting that vehicular and industrial emissions (the primary sources of $NO_2$) are more consistent throughout the year compared to the episodic nature of dust or biomass burning.$NH_3$ Trends: Displays a bimodal or broad-peaked distribution around $10$–$30$ µg/m³.Research Insight: The presence of $NH_3$ in Delhi is often linked to waste decomposition and fertilizers from neighboring agricultural zones. The spread suggests a steady background level of ammonia.3. Sulphur Dioxide ($SO_2$)Observation: This graph has the sharpest, most concentrated peak at very low levels (mostly below $20$ µg/m³).Interpretation: $SO_2$ levels in Delhi are generally well within safe limits. The rare spikes (the long thin tail reaching $100$+) likely represent specific industrial plumes or heavy-sulphur fuel burning incidents.4. Carbon Monoxide (CO)Note: As per your dataset description, this is the only pollutant measured in mg/m³.Observation: The distribution is highly concentrated between $0.5$ and $1.5$ mg/m³.Research Insight: High CO levels are a classic indicator of incomplete combustion (traffic congestion and biomass fires). The fact that the tail extends to $6$ mg/m³ indicates localized "hotspots" of high traffic density or nearby waste burning.5. Ozone ($O_3$)Observation: A peak at low concentrations ($10$–$30$ µg/m³) with a very long tail extending toward $120$ µg/m³.Interpretation: Ground-level ozone is a secondary pollutant formed by the reaction of $NO_x$ and VOCs in sunlight. The tail represents peak summer afternoons when solar radiation is highest, leading to photochemical smog.




<img width="896" height="682" alt="image" src="https://github.com/user-attachments/assets/e3ab3397-d389-46ad-aa18-0c1d97c96103" />
 Distribution Analysis (Histograms & KDE)The histograms show the frequency of pollutant concentrations. A common theme across almost all pollutants in Delhi is right-skewness (positive skew), meaning that while lower concentrations are common, there are frequent extreme pollution "events."Particulate Matter ($PM_{2.5}$ & $PM_{10}$): These show the widest spread. $PM_{10}$ peaks around $100$–$200$ $\mu g/m^3$, but the tail extends toward $800$ $\mu g/m^3$. This indicates that Delhi's air quality is characterized by chronic high levels with severe episodic spikes (likely winter smog).Gaseous Pollutants ($NO_2$, $NH_3$, $SO_2$): These show tighter distributions. $SO_2$ is particularly low and stable (mostly under $20$ $\mu g/m^3$), suggesting that localized industrial sulfur emissions are not the primary driver of poor AQI in Punjabi Bagh.Carbon Monoxide (CO): Measured in $mg/m^3$, the peak is near $1.0$. The long tail indicates localized incomplete combustion, such as traffic congestion or waste burning.

<img width="850" height="470" alt="image" src="https://github.com/user-attachments/assets/95bdfdca-451b-4d18-91ea-5e58575742f7" />


The provided diagrams offer a detailed look at the air quality profile for Delhi (Punjabi Bagh) from 2020 to 2024.

1. Distribution and Concentration
The histograms reveal that most pollutants follow a right-skewed distribution, where lower concentrations are frequent but extreme "outlier" events are common. PM 
10
​
  and PM 
2.5
​
  show the highest variability, with PM 
10
​
  levels frequently exceeding 400 µg/m³ and extending up to 800 µg/m³. In contrast, SO 
2
​
  remains consistently low (mostly below 20 µg/m³), indicating it is a minor contributor to Delhi's overall AQI compared to other gases.

2. Pollutant Interdependence
The correlation heatmap highlights a very strong relationship between PM 
2.5
​
  and PM 
10
​
  (r=0.91), confirming they share identical emission sources or are equally affected by atmospheric stagnation. Moderate-to-strong correlations between NO 
2
​
 , NH 
3
​
 , and CO (r ranging from 0.50 to 0.66) suggest a significant common contribution from combustion activities, likely vehicular exhaust and biomass burning. Notably, Ozone (O 
3
​
 ) and SO 
2
​
  show near-zero or negative correlations with other pollutants, identifying them as independent variables driven by different chemical or industrial processes.

3. Seasonal AQI Trends
The "Monthly AQI Trend" line graph illustrates a distinct "U-shaped" seasonal pattern. Air quality is at its worst in November, with mean AQI levels spiking near 400, coinciding with winter temperature inversions and post-monsoon crop residue burning. A secondary, smaller peak occurs around April/May. Conversely, the cleanest air is recorded during the monsoon months of July and August, where AQI levels drop to their annual minimum (around 100) due to rain-induced "washout" of pollutants.




<img width="990" height="789" alt="image" src="https://github.com/user-attachments/assets/7e0202b2-44e7-48b0-b5c2-9593a0175f21" />
Pollutant Distribution and ExtremesThe histograms indicate that most pollutants in Delhi follow a right-skewed distribution, meaning while lower concentrations are more frequent, severe pollution events are common. Particulate matter levels are particularly extreme, with $PM_{10}$ concentrations peaking between $100$ and $200$ µg/m³ but frequently extending toward $800$ µg/m³. Similarly, $PM_{2.5}$ shows significant density in the $50$–$100$ µg/m³ range with long tails reaching over $400$ µg/m³. In contrast, $SO_2$ levels remain consistently low and stable, generally staying below $20$ µg/m³.Pollutant InterdependenceThe correlation heatmap reveals a very strong relationship between $PM_{2.5}$ and $PM_{10}$ ($r = 0.91$), indicating they likely originate from the same sources, such as combustion and road dust. Moderate-to-strong correlations are also observed between $NO_2$, $NH_3$, and $CO$ (ranging from $0.41$ to $0.66$), which points toward shared emission drivers like vehicular exhaust and biomass burning. Conversely, Ozone ($O_3$) and $SO_2$ show negligible or negative correlations with other pollutants, suggesting their levels are influenced by independent chemical reactions or specific industrial sources rather than general urban traffic patterns.Seasonal AQI TrendsThe line graph of monthly AQI trends illustrates a distinct seasonal cycle, with air quality reaching its worst levels in November, where the mean AQI spikes near $400$. A secondary, smaller peak is visible around April and May. Conversely, the cleanest air is recorded during the monsoon months of July and August, when AQI levels drop to their annual minimum of approximately $100$, likely due to the "washout" effect of rainfall on atmospheric pollutants.



<img width="986" height="547" alt="image" src="https://github.com/user-attachments/assets/e6b9fd35-eaa1-43a1-aba5-66560985b574" />

The following points summarize the air quality data for Delhi - Punjabi Bagh (2020–2024):Distribution & Peaks: Most pollutants exhibit a right-skewed distribution, where typical concentrations are moderate, but frequent extreme spikes occur, particularly for $PM_{10}$ and $PM_{2.5}$.Strong Correlations: A very high correlation between $PM_{2.5}$ and $PM_{10}$ ($r=0.91$) and moderate ties with $NO_2$ and $CO$ suggest shared sources like vehicle emissions and road dust.Seasonal Volatility: The monthly trend follows a sharp U-shaped curve, with air quality reaching hazardous peaks in November (AQI near 400) and improving significantly during the July–August monsoon.Multi-Year Trends: The time-series data confirms a repetitive annual cycle of severe winter pollution episodes, with AQI levels frequently hitting the maximum cap of 500 across all five years.



 
