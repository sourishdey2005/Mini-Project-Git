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


<img width="438" height="429" alt="image" src="https://github.com/user-attachments/assets/c408d28e-bb80-4d3e-8707-80a2204a31fb" />
Distribution & Peaks: Most pollutants exhibit a right-skewed distribution, where typical concentrations are moderate, but frequent extreme spikes occur, particularly for PM10 and PM2.5.Strong Correlations: A very high correlation between PM2.5 and PM10 ($r=0.91$) and moderate ties with NO2 and CO suggest shared sources like vehicle emissions and road dust.Seasonal Volatility: The monthly trend follows a sharp U-shaped curve, with air quality reaching hazardous peaks in November (AQI near 400) and improving significantly during the July–August monsoon.Multi-Year Trends: The time-series data confirms a repetitive annual cycle of severe winter pollution episodes, with AQI levels frequently hitting the maximum cap of 500 across all five years.


<img width="528" height="504" alt="image" src="https://github.com/user-attachments/assets/2e9b9b06-3e84-470a-9788-6c4fed7ef156" />
AQI Category Prevalence: A majority of the days fall under the Moderate (36%) and Very Poor (25.2%) categories, while only 1.4% of the recorded period experienced Good air quality.

Particulate Dominance: PM2.5 and PM10 show a nearly perfect correlation (r = 0.91), identifying them as the primary drivers of AQI and indicating shared emission sources like road dust and combustion.

Seasonal Peaks: The monthly trend follows a drastic U-shaped curve, with air quality worsening sharply in November (reaching a mean AQI near 400) and improving significantly during the monsoon months of July and August.

Extreme Events: The time-series data reveals a repetitive annual pattern of severe winter pollution, with AQI levels frequently hitting the maximum cap of 500 between October and January each year.

Gaseous Interdependence: NO2 shows moderate-to-strong correlations with PM2.5 (r = 0.64) and CO (r = 0.50), pointing to a consistent baseline of vehicular and industrial emissions.

Pollutant Variability: Histograms indicate a right-skewed distribution for all pollutants, where chronic pollution is punctuated by frequent, extreme spikes that far exceed national safety standards.




<img width="1001" height="470" alt="image" src="https://github.com/user-attachments/assets/f100543f-4439-465e-9c12-f58315e6fcd3" />
AQI Distribution: The air quality is predominantly poor, with 36% of days categorized as Moderate and 25.2% as Very Poor, while Good air quality accounts for a negligible 1.4% of the period.Particulate Correlation: There is an extremely high correlation between $PM_{2.5}$ and $PM_{10}$ ($r = 0.91$), indicating these pollutants originate from the same primary sources and are influenced by the same atmospheric conditions.Seasonal Trends: AQI follows a sharp U-shaped seasonal curve, peaking dangerously in November (mean AQI $\approx 400$) and reaching its lowest levels during the July–August monsoon washout.Source Indicators: Moderate correlations between $NO_2$, $CO$, and Particulate Matter ($r \approx 0.50$ to $0.66$) identify combustion (vehicles and biomass burning) as a consistent baseline contributor to local pollution.Particle Size Dynamics: The $PM_{2.5}/PM_{10}$ ratio frequently fluctuates between fine particle dominance (smoke/combustion) and coarse particle dominance (dust), with notable spikes in fine particles during winter months.Annual Cycles: Time-series data confirms a repetitive multi-year pattern where AQI levels frequently hit the 500 (Severe) maximum cap during the winter stagnation period each year.




<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/2a057147-defd-4552-a09d-8add2df2c4a7" />

AQI Distribution & SeverityDominant Categories: Only 1.4% of days recorded "Good" air quality, while the majority fell into Moderate (36%) and Very Poor (25.2%) categories.Extreme Events: The time-series data shows a recurring annual cycle where AQI levels hit the 500 (Severe) cap during winter months (October–January).Skewed Pollutants: Histograms for $PM_{2.5}$, $PM_{10}$, and $NO_2$ show a heavy right-skew, indicating that while "typical" days exist, extreme pollution spikes are frequent and severe.Seasonal & Temporal TrendsU-Shaped Monthly Cycle: Air quality is at its worst in November (mean AQI $\approx 380$) and best during the monsoon washout of July–August (mean AQI $\approx 100$).Particle Ratios: The $PM_{2.5}/PM_{10}$ ratio highlights periods of fine particle dominance (smoke/combustion) primarily in winters, with coarse particle dominance (dust) occurring in drier summer months.Pollutant InteractionsParticulate Linkage: An extremely high correlation between $PM_{2.5}$ and $PM_{10}$ ($r=0.91$) confirms they are driven by the same atmospheric conditions and sources.Combustion Tracers: Moderate correlations between $NO_2$, $CO$, and particulates ($r \approx 0.50$–$0.66$) identify vehicular exhaust and biomass burning as consistent baseline contributors.Independent Gases: $SO_2$ and $O_3$ (Ozone) show negligible or negative correlations with other pollutants, suggesting they are driven by independent industrial processes or photochemical reactions rather than general traffic.



<img width="547" height="458" alt="image" src="https://github.com/user-attachments/assets/28249a87-c24c-496e-aeb4-95eb4c654576"/>
Air Quality Categories: The pie chart reveals that only 1.4% of days experienced "Good" air quality. The majority of the period was dominated by Moderate (36%) and Very Poor (25.2%) conditions, with Severe days accounting for 9.4%.Temporal Extremes: The AQI time series and histogram show a persistent annual pattern where values frequently hit the 500 (Severe) cap during winter months.Pollutant Skewness: All pollutant histograms exhibit a heavy right-skew, indicating that while average concentrations exist, the region is prone to frequent, extreme pollution spikes.2. Seasonal and Source TrendsMonthly Cycle: The "Monthly AQI Trend" demonstrates a sharp U-shaped curve, with air quality at its cleanest in July and August (mean AQI $\approx$ 100) and at its most hazardous in November (mean AQI approaching 400).Particle Characterization: The $PM_{2.5}/PM_{10}$ ratio indicates frequent Fine Particle Dominance (ratios $> 0.6$) during winter, pointing to combustion/smoke sources, while summer months often lean toward Coarse Particle Dominance due to dust.Industrial vs. Traffic: Analysis by month suggests a significant shift in dominance, with industrial indicators peaking mid-year and traffic-related tracers remaining a steady baseline.3. Correlation and InterdependenceParticulate Linkage: There is a near-perfect correlation between $PM_{2.5}$ and $PM_{10}$ ($r=0.91$), identifying them as the primary drivers of the AQI.Combustion Tracers: $NO_2$ shows strong correlations with $NH_3$ ($r=0.66$) and $PM_{10}$ ($r=0.66$), confirming shared emission sources like vehicular exhaust and biomass burning.Independent Pollutants: $SO_2$ and $O_3$ (Ozone) show negligible or negative correlations with other pollutants. The scatter plot specifically highlights an inverse relationship between $NO_2$ and $O_3$, a classic characteristic of urban photochemical smog where $NO_x$ "titrates" or breaks down local ozone.



<img width="584" height="455" alt="image" src="https://github.com/user-attachments/assets/a31de7c4-2abc-47e7-b2f5-5adce747dc5d" />

The provided diagrams for Delhi - Punjabi Bagh (2020–2024) show that air quality is predominantly Moderate to Very Poor, characterized by extreme winter AQI spikes (near 500) and a strong 0.91 correlation between PM2.5 and PM10.


<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/b455ea36-714e-484a-89e4-686a38b1a03b" />
AQI Distribution and SeverityCategory Dominance: The air quality is predominantly poor, with Moderate (36%) and Very Poor (25.2%) being the most frequent categories, while "Good" days account for a negligible 1.4%.Extreme Pollution Events: The time-series data shows a repetitive annual cycle where AQI levels frequently hit the 500 (Severe) cap during winter months.Pollutant Skewness: Histograms for $PM_{2.5}$, $PM_{10}$, and $NO_2$ all show a heavy right-skew, indicating that extreme pollution spikes are common occurrences rather than rare outliers.2. Seasonal and Source DynamicsMonthly AQI Cycle: Air quality follows a sharp U-shaped curve, peaking dangerously in November (mean AQI $\approx 380$) and reaching its lowest point during the monsoon in July–August.Particle Characterization: The $PM_{2.5}/PM_{10}$ ratio indicates periods of Fine Particle Dominance (smoke/combustion) during winter, while drier months often lean toward Coarse Particle Dominance.Industrial vs. Traffic: Analysis by month shows that industrial indicators peak mid-year (May), whereas traffic-related tracers remain a steady baseline throughout the year.3. Correlation and Chemical InteractionsParticulate Linkage: There is a near-perfect correlation between $PM_{2.5}$ and $PM_{10}$ ($r = 0.91$), identifying them as the primary joint drivers of Delhi's AQI.Combustion Tracers: Strong correlations between $NO_2$, $NH_3$ ($r = 0.66$), and $CO$ ($r = 0.50$) point toward shared emission sources such as vehicular exhaust and biomass burning.Secondary Pollutant Behavior: Scatter plots confirm an inverse relationship between $NO_2$ and Ozone ($O_3$), a hallmark of urban photochemical smog where nitrogen oxides actively break down ground-level ozone.


<img width="552" height="455" alt="image" src="https://github.com/user-attachments/assets/4d139451-5961-4fd4-9b7b-5fe5637b6eaa" />
The AQI graph for Delhi (2020–2024) shows extreme daily fluctuations with recurring winter spikes, often reaching hazardous levels. These seasonal peaks are driven by stubble burning, temperature inversions, and festival emissions. While 2020 saw lower values due to lockdowns, pollution quickly rebounded, highlighting persistent structural air quality challenges.



<img width="574" height="455" alt="image" src="https://github.com/user-attachments/assets/5addbb4a-8496-44f7-9256-7f2d6683dc7b" />
The month‑over‑month AQI change highlights strong seasonal variation in Delhi’s air quality. October and November show sharp increases (over +125%), reflecting post‑monsoon crop residue burning and winter inversion effects that trap pollutants. In contrast, February, March, June–August record negative changes, indicating relative improvement due to rainfall and atmospheric dispersion. Overall, the chart underscores critical autumn–winter deterioration in AQI, while summer and monsoon periods provide temporary relief.


<img width="543" height="476" alt="image" src="https://github.com/user-attachments/assets/3752697f-9f24-4868-b9c0-333526cab498" />
The number of “Severe” AQI days in Delhi fluctuates considerably across 2020–2024, reflecting episodic pollution crises. After 27 severe days in 2020, the count rose to 37 in 2021, dipped to 19 in 2022, and then surged to a peak of 44 in 2023. Although 2024 shows some reduction (35 days), the overall trajectory indicates persistent and worsening air quality stress, with 2023 standing out as the most hazardous year. This variability suggests that while meteorological factors and temporary interventions may reduce severity in certain years, structural drivers like vehicular emissions, crop residue burning, and industrial activity continue to dominate Delhi’s pollution profile.


<img width="552" height="455" alt="image" src="https://github.com/user-attachments/assets/2f0654a8-55a6-4ab6-8511-65254a440e60" />
The cumulative pollutant load shows clear seasonal concentration patterns in Delhi. Peaks in January, November, and December reflect winter stagnation and stubble burning, with PM2.5 and PM10 dominating the pollutant mix. Mid‑year months (June–August) record the lowest loads, largely due to monsoon rainfall and atmospheric cleansing. The stacked profile highlights particulate matter as the primary contributor, while gaseous pollutants (NO2, SO2, NH3, CO, O3) add secondary stress. Overall, the chart emphasizes wintertime pollution crises and the relative relief provided by monsoon dispersion.



<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/cb6fcad2-86ce-4285-b200-56807e41aefe" />
Only about 20% of AQI values fall below 100, meaning safe air quality is rare. Half the readings are under 200, but still unhealthy, while nearly 80% are below 400, in the “very poor” range. Extreme episodes exceed 600 AQI, showing Delhi’s air is chronically hazardous with frequent severe spikes.



<img width="986" height="528" alt="image" src="https://github.com/user-attachments/assets/3466d925-92f4-4f04-8a69-fc642fee3e20" />
The variance in gaseous pollutant concentrations shows NO₂ with the widest spread and highest median, indicating strong fluctuations linked to traffic and combustion sources. SO₂ and O₃ display moderate variability, reflecting episodic industrial activity and photochemical reactions. NH₃ has the narrowest distribution, suggesting relatively stable but consistently present emissions from agriculture and waste. Overall, the plot highlights NO₂ as the most volatile pollutant, while NH₃ remains steady yet significant in Delhi’s air quality profile.




<img width="615" height="455" alt="image" src="https://github.com/user-attachments/assets/af07a2be-563d-4d49-a535-a009eb807bbf" />
The monthly trend at Delhi–Punjabi Bagh shows a clear seasonal cycle. Values are highest in January, steadily decline to their lowest around August (monsoon dispersion), and then rise sharply to peak in November, before a slight drop in December. This pattern reflects winter inversion and stubble burning impacts driving late‑year pollution spikes, contrasted with monsoon‑driven cleansing in mid‑year months.




<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/47884030-b1cd-41b9-891b-7b1fe20c9f02" />
November consistently emerges as the peak pollution month in Delhi, with AQI values ranging between 100 and 600 across 2020–2024. The medians remain well above 300, confirming chronic “very poor to severe” conditions. 2023 shows the highest spread and extreme outliers, while 2022 records relatively lower central values. Overall, the year‑on‑year comparison highlights persistent November crises, with variability driven by meteorology and stubble burning intensity, but no sustained improvement trend.



<img width="606" height="512" alt="image" src="https://github.com/user-attachments/assets/f23ef978-a944-426e-b00d-ead502142ae5" />
The scatter‑regression analysis shows that AQI is most sensitive to PM2.5 during winter (season 3), with a steep slope indicating that even moderate PM2.5 concentrations drive AQI into hazardous ranges. Summer and monsoon seasons (seasons 1 and 2) exhibit flatter slopes, reflecting atmospheric dispersion and rainfall effects that reduce AQI response. Post‑monsoon (season 0) shows intermediate sensitivity, consistent with crop residue burning. Overall, the chart highlights season‑dependent amplification of PM2.5 impacts, with winter posing the greatest health risk due to inversion and stagnant conditions.


<img width="841" height="470" alt="image" src="https://github.com/user-attachments/assets/84c59645-d267-458a-b6d8-6f823d4744c5" />
  
The O₃/NO₂ ratio shows a sharp seasonal spike in May, reaching ~5 on average and extending up to 10 in variability. This indicates heightened photochemical activity and oxidative capacity during pre‑monsoon summer, driven by strong solar radiation and stagnant atmospheric conditions. Across other months, the ratio remains low (~0.5–2), reflecting limited ozone formation relative to NO₂. Overall, the chart highlights May as the critical month for photochemical smog potential, with implications for respiratory health and urban air chemistry.



<img width="567" height="435" alt="image" src="https://github.com/user-attachments/assets/b9f189d7-9815-452c-9881-9ecefd76e157" />
AQI sensitivity analysis shows PM2.5 as the dominant driver, with elasticity close to 1.0, followed by PM10 at slightly lower but still high influence. Other pollutants—CO, NO₂, O₃, SO₂, NH₃—register much lower sensitivities (<0.3), indicating their secondary role in AQI fluctuations. This confirms that particulate matter, especially fine particles, is the primary determinant of Delhi’s air quality severity, while gaseous pollutants contribute comparatively less to AQI variability.



<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/f2bc1028-e5e9-452b-b955-e76105c31d38" />
The seasonal hysteresis between PM2.5 and CO shows a looping pattern across months, indicating that their relationship is not linear but season‑dependent. During winter months, both PM2.5 and CO rise sharply due to combustion sources and stagnant atmospheric conditions, while monsoon months show reduced values with a different trajectory. The loop highlights that pollutant interactions follow distinct paths during increase and decrease phases, reflecting meteorological influences and emission dynamics. This confirms that Delhi’s pollution cycle is cyclical and seasonally reinforced, with winter posing the greatest combined particulate and CO burden.



<img width="594" height="616" alt="image" src="https://github.com/user-attachments/assets/e4cd1c51-b79f-4269-a3eb-fe4ed1517e70" />
The bivariate hexbin analysis shows a negative chemical coupling between NO₂ and O₃. High densities cluster at elevated NO₂ with low O₃, reflecting titration effects where NO₂ suppresses ozone formation. Conversely, higher O₃ values occur when NO₂ concentrations are lower, consistent with photochemical production under sunlight. The marginal histograms confirm skewed distributions: NO₂ is concentrated at higher ranges, while O₃ peaks at moderate levels. Overall, the plot highlights the inverse relationship and chemical trade‑off between traffic‑driven NO₂ emissions and ozone buildup in Delhi’s atmosphere.


<img width="986" height="528" alt="image" src="https://github.com/user-attachments/assets/6f02c8df-0ddd-44ce-9502-8189c164340d" />
The multi‑resolution decomposition reveals three distinct layers of AQI dynamics in Delhi. Short‑term (weekly) fluctuations show sharp spikes, reflecting episodic events like firecrackers, dust storms, or traffic surges. Mid‑term (monthly) cycles capture seasonal transitions, with clear peaks in winter and troughs during monsoon months. The long‑term trend remains persistently elevated, confirming that despite temporary dips, Delhi’s baseline air quality is chronically poor. Together, the decomposition highlights how episodic shocks overlay seasonal cycles on a worsening long‑term trajectory, underscoring the need for both immediate and structural interventions.



<img width="556" height="455" alt="image" src="https://github.com/user-attachments/assets/52d2d083-2d56-4e35-bb75-61cb1af2f773" />
Atmospheric persistence analysis shows correlations starting high (~0.88) at a 1‑day lag and steadily decaying to ~0.65 by day 14. This indicates that predictive power of AQI and pollutant patterns weakens over two weeks, with short‑term conditions strongly linked but longer horizons increasingly uncertain. The trend highlights the limited memory of Delhi’s atmosphere, reinforcing the need for frequent monitoring and short‑range forecasting rather than reliance on extended predictions.



<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/5675e75a-75c9-4da5-ba4e-6fff143e0894" />
The scatter analysis shows that secondary inorganic aerosol (SIA) formation potential strongly correlates with PM2.5, especially in late‑year months. December (red points) records the highest PM2.5 values, often exceeding 400–500 µg/m³, alongside elevated SIA proxies (>100), indicating intense wintertime aerosol buildup. Mid‑year months (June–August) cluster at lower ranges (PM2.5 <150, SIA proxy <50), reflecting monsoon cleansing. Overall, the plot highlights seasonal amplification of PM2.5 through SIA processes, with winter posing the greatest risk of particulate pollution due to chemical coupling and stagnant atmospheric conditions.


<img width="1176" height="836" alt="image" src="https://github.com/user-attachments/assets/7208c1ee-1a82-44ab-a339-0d06f65b9d25" />
The daily AQI calendar from 2020–2024 highlights recurring seasonal episodes of extreme pollution. November and December consistently show the darkest intensities, with AQI often exceeding 400–600, confirming winter as the most hazardous period. Mid‑year months (June–August) display lighter shades, reflecting monsoon‑driven cleansing. Year‑to‑year variation exists, but the overall pattern is stable: Delhi’s air quality deteriorates sharply in late autumn and winter, while summer and monsoon provide temporary relief. This visualization underscores the cyclical nature of pollution crises, concentrated in specific seasonal windows.



<img width="613" height="464" alt="image" src="https://github.com/user-attachments/assets/6793b79f-666a-49ef-aaab-43a526d8ebe8" />
The monthly AQI distributions show heavier density peaks in early months (Jan–Apr), with values frequently clustering above 300–500, confirming wintertime severity. Mid‑year months (May–Aug) shift toward lower ranges, reflecting monsoon dispersion, while late‑year months (Oct–Dec) again broaden into high AQI zones, often exceeding 600. The ridgeline evolution highlights a cyclical pollution pattern, with winter and post‑monsoon episodes driving the worst air quality, and monsoon providing the only sustained relief.



<img width="594" height="590" alt="image" src="https://github.com/user-attachments/assets/b63a0b44-8c62-480e-9655-2117e2be92d7" />
The scatter with regression confirms a strong positive correlation between PM2.5 and PM10, meaning particulate pollution sources in Delhi often emit both fine and coarse particles simultaneously. The regression line shows a consistent upward trend, with higher PM2.5 values tightly associated with elevated PM10. Marginal histograms reveal skewed distributions, with PM2.5 clustering in the 100–300 µg/m³ range and PM10 extending beyond 400 µg/m³. This relationship underscores that particulate matter is co‑emitted and mutually reinforcing, making source control (traffic, construction, biomass burning) critical for reducing overall AQI severity.


<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/c1a5823f-f0cc-4683-94bc-b8b72b6ccbf0" />
The density distributions show extreme AQI events concentrated in winter and post‑monsoon months (Oct–Jan), with wide violins extending beyond 600 AQI, reflecting frequent hazardous episodes. Mid‑year months (Jun–Aug) have narrower shapes and lower medians, indicating cleaner air during monsoon dispersion. Transitional months (Mar–Apr, Sep) show moderate spreads. Overall, the visualization confirms Delhi’s air quality is seasonally skewed, with winter months dominated by severe and extreme pollution events, while monsoon provides the only sustained relief.


<img width="695" height="701" alt="image" src="https://github.com/user-attachments/assets/086f1d71-3b6c-4e03-a63d-b081592730f2" />
The hexbin distribution of PM2.5 vs PM10 reveals two dominant regimes. Points above the red diagonal line indicate smoke‑dominated episodes, where fine particles (PM2.5) outweigh coarse dust. Below the line, dust dominance is evident, with PM10 concentrations exceeding PM2.5. The densest clusters lie near the threshold, showing frequent mixed conditions in Delhi’s atmosphere. Overall, the phase‑space highlights how seasonal shifts toggle between smoke (winter combustion, stubble burning) and dust (summer storms, construction), both contributing heavily to AQI severity.


<img width="866" height="393" alt="image" src="https://github.com/user-attachments/assets/d66078b0-6b7e-49cc-854a-d6c7a7a6fa33" />
The time‑lagged correlation remains weak (between –0.06 and +0.06) across all lags, confirming that NO₂ and O₃ are only loosely coupled in Delhi’s atmosphere. At lag 0, the near‑zero correlation reflects their simultaneous but opposing chemistry: NO₂ titrates ozone while sunlight drives O₃ formation. Slight shifts at positive and negative lags suggest delayed photochemical responses, but the overall flat profile highlights that short‑term temporal alignment between NO₂ and O₃ is minimal, reinforcing their inverse relationship observed in static coupling plots.



<img width="819" height="842" alt="image" src="https://github.com/user-attachments/assets/cd1e7850-2369-422a-b033-b2a0048c2163" />
The correlation network shows a tight cluster among CO, NO₂, NH₃, and particulate proxies (M1, M2, AQ), reflecting shared combustion and urban emission sources. Their strong interlinkages suggest co‑variation and mutual reinforcement in driving AQI. In contrast, O₃ and SO₂ sit more peripherally, with weaker ties to the core group, highlighting their distinct chemical pathways (photochemical formation for O₃, industrial origins for SO₂). Overall, the network emphasizes that Delhi’s air quality is dominated by a highly interconnected set of combustion‑related pollutants, while secondary pollutants operate more independently.



<img width="578" height="435" alt="image" src="https://github.com/user-attachments/assets/465f28d6-aa31-4085-afa3-367d08cf2063" />
The spectral analysis reveals a dominant low‑frequency peak, indicating strong periodic cycles in Delhi’s pollution—likely seasonal or monthly drivers such as winter inversion and monsoon cleansing. Beyond this, the spectrum flattens, with only minor fluctuations at higher frequencies, showing that short‑term random spikes (e.g., firecrackers, dust storms) contribute less to overall variance. This confirms that Delhi’s air quality is governed primarily by large‑scale, recurring seasonal rhythms, rather than high‑frequency noise.




<img width="571" height="432" alt="image" src="https://github.com/user-attachments/assets/470a1a03-5e34-4259-8d80-0838b2353de1" />
The box plots clearly show seasonal stratification of air quality. Winter months (Jan, Nov, Dec) have the highest medians and widest spreads, with frequent outliers above 600 AQI, reflecting hazardous episodes. Summer months (Jun–Aug) display much lower medians and tighter ranges, indicating cleaner air due to monsoon dispersion. Transitional months (Mar–Apr, Sep–Oct) sit in between, with moderate variability. Overall, the visualization confirms that Delhi’s pollution is cyclical, peaking in winter and easing during monsoon, with extreme events concentrated in late autumn and early winter.


<img width="571" height="432" alt="image" src="https://github.com/user-attachments/assets/6282c254-26aa-47ee-93be-ac8b86a96a87" />
The scatter of y(t) vs y(t+1) shows a clear positive alignment, meaning high values at time t are strongly associated with high values at time t+1. This reflects short‑term persistence in the system, where pollutant or AQI levels carry over from one day to the next rather than resetting independently. The clustering along the diagonal indicates stability with gradual changes, reinforcing that Delhi’s air quality exhibits strong day‑to‑day autocorrelation, making short‑range forecasting reliable but long‑range predictions more uncertain.


<img width="552" height="435" alt="image" src="https://github.com/user-attachments/assets/9e2d0498-fbf9-436d-ac46-38f577d87bad" />
The density clusters concentrate in the lower‑left region, showing that most haze episodes occur at relatively moderate particle levels. The diagonal red threshold line marks a balance point: values above it suggest fine particle (PM2.5) dominance, while values below it indicate coarse particle (PM10) dominance. The distribution shows that Delhi’s atmosphere frequently oscillates around this boundary, with mixed smoke‑dust conditions being common. Overall, the phase‑space highlights how haze composition shifts seasonally between combustion‑driven fine particles and dust‑driven coarse particles, reinforcing the dual nature of particulate pollution.



<img width="623" height="512" alt="image" src="https://github.com/user-attachments/assets/86902ed8-8d40-410c-bded-2fa634c7afa9" />
The scatter with seasonal regressions shows distinct source signatures.

Winter (blue): Steeper slopes, indicating strong industrial contributions (SO₂ from coal and power plants) alongside vehicular NO₂.

Summer (orange): Flatter slopes, reflecting reduced industrial activity and stronger dispersion, with vehicular NO₂ dominating.

Monsoon (green): Weak correlations due to rainfall cleansing, diluting both pollutants.

Post‑monsoon (red): Slopes rise again, highlighting combined vehicular and industrial emissions during stagnant atmospheric conditions.




<img width="835" height="528" alt="image" src="https://github.com/user-attachments/assets/6822a518-92fb-404f-b826-091358b04bf4" />
The site’s chemical profile shows NH₃ as the dominant pollutant, with values peaking highest among all species. This reflects strong contributions from waste, agriculture, and localized emissions. PM2.5 and PM10 sit at mid‑range levels, confirming particulate matter as a persistent burden. NO₂ and CO also register moderately, pointing to vehicular influence. In contrast, SO₂ is lowest, suggesting limited coal or industrial combustion in this locality. Overall, Punjabi Bagh’s fingerprint highlights a mixed pollution source profile, but with ammonia and particulates as the defining markers of air quality stress.



<img width="600" height="435" alt="image" src="https://github.com/user-attachments/assets/e8ea6225-4d28-4520-8590-1ed921e59e75" />
The cumulative deviation line from 2020–2025 shows persistent oscillations with annual peaks and troughs, reflecting how policy interventions and external shocks shift air quality away from its mean baseline. Sustained upward deviations suggest periods of worsening pollution despite controls, while downward trends mark episodes of improvement or effective measures. The long‑term trajectory indicates that while short‑term fluctuations are frequent, policy impacts accumulate gradually, requiring multi‑year consistency to bend the curve toward cleaner air. This makes the chart a valuable diagnostic for evaluating whether interventions are producing lasting structural change rather than temporary relief.



<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/f4be5d37-1fd1-474d-a656-ddfc26dd3a53" />
The raincloud visualization combines density, box, and scatter to show seasonal contrasts in AQI.

Winter: Highest medians and widest spreads, with frequent outliers above 600 AQI, confirming severe pollution episodes.

Post‑monsoon: Elevated distributions, reflecting stagnant atmospheric conditions and crop‑residue burning.

Summer: Lower medians and tighter ranges, indicating cleaner air due to dispersion.

Monsoon: Narrowest spread and lowest values, highlighting rainfall’s cleansing effect.

Overall, the plot demonstrates that Delhi’s air quality is seasonally skewed, with winter and post‑monsoon periods driving extreme pollution, while monsoon provides the only sustained relief.



<img width="1162" height="1007" alt="image" src="https://github.com/user-attachments/assets/d7008b38-908a-4f41-b68f-c6dd17832aea" />
  
The hierarchical clustering reveals two dominant pollutant groupings:

Particulate cluster (PM2.5, PM10, CO): Strong correlations (PM2.5–PM10 at 0.91, CO–PM2.5 at 0.52) highlight shared combustion and dust sources.

Gas cluster (NO₂, NH₃, SO₂, O₃): Weaker and mixed correlations, with NO₂–SO₂ slightly negative (–0.11) and NH₃–SO₂ nearly zero, reflecting distinct industrial, vehicular, and agricultural pathways.

The dendrogram structure emphasizes that particulates form a tightly bound subsystem, while gaseous pollutants are more loosely connected, often acting independently. This separation underscores the need for dual‑track policy interventions



<img width="560" height="415" alt="image" src="https://github.com/user-attachments/assets/208c69e6-db67-4a41-84cc-e82a0d97f5b6" />
The distribution of points leaning toward the O₃ axis indicates that ozone often dominates the pollutant mix relative to NO₂ and PM2.5. This reflects strong photochemical activity, especially in summer months when sunlight drives ozone formation. Points closer to the PM2.5–NO₂ edge highlight combustion‑driven episodes (traffic, biomass burning), while the spread across the triangle shows how pollutant proportions shift seasonally. Overall, the ternary fingerprint underscores that Delhi’s air quality alternates between particulate/vehicular dominance and ozone‑driven chemistry, depending on atmospheric conditions.


<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/b2591cec-3586-4358-a679-7a7e40c538bf" />
  
The violins show seasonal extremes in AQI density.

January and November stand out with broad distributions and frequent outliers above 600 AQI, marking recurrent hazardous episodes.

Summer months (May–August) display narrower violins and lower medians, reflecting cleaner air due to dispersion and monsoon cleansing.

Transitional months (March–April, September–October) show moderate spreads, capturing the buildup before winter stagnation.

Overall, the visualization reinforces the cyclical nature of Delhi’s pollution, with winter/post‑monsoon periods driving extreme events, while monsoon provides the only sustained relief.









































 
