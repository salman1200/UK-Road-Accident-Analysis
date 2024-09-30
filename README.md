# UK Road Accident Analysis Dashboard

## Project Overview

This Power BI dashboard provides an in-depth analysis of road accidents in the UK. The data is structured around various metrics related to casualties, accident severity, vehicle types involved, and location specifics. The primary objective of this dashboard is to present the data in a way that allows stakeholders to easily understand trends and patterns in road accidents, thus aiding in decision-making, policy formulation, and further safety measures.

![UK Road Accident Analysis](/Dashboard.png)

## Data Sources

The dataset used in this analysis includes multiple dimensions related to road accidents, such as:
- Casualty and accident figures (fatal, serious, slight)
- Vehicle types involved
- Time and seasonality impacts
- Road types and conditions
- Geographic distribution of accidents

### Key Columns in the Dataset:
- **Total CY Casualties**: Represents the cumulative number of casualties for the current year.
- **Total CY Accidents**: Shows the total number of accidents that have occurred during the current year.
- **CY Fatal/Serious/Slight Accidents**: This breakdown categorizes accidents based on their severity.
- **Casualties by Vehicle Type**: Distribution of casualties by the type of vehicle involved (e.g., car, van, truck, bike, bus, agricultural vehicle).
- **Casualties by Road Type**: Shows accidents based on different road types such as single carriageway, dual carriageway, roundabout, one-way streets, and slip roads.
- **Urban vs. Rural and Daylight vs. Darkness Casualties**: Provides insights into whether accidents happen more in urban or rural areas and whether they occur in daylight or darkness.

## Dashboard Features

### 1. **Summary Metrics**
The top row of the dashboard highlights the key metrics for understanding the overall situation:
- **Total CY Casualties**: This card shows the total number of casualties for the current year (CY), along with a percentage change from the previous period.
- **Total CY Accidents**: The number of accidents occurring in the current year, with a similar percentage comparison against the previous period.
- **CY Fatal, Serious, and Slight Accidents**: Provides a quick look at the breakdown of accident severity.

### 2. **Casualties by Vehicle Type**
This visual categorizes the casualties based on vehicle type, making it clear which types of vehicles are involved in most accidents. The visual includes:
- **Cars** with the highest number of casualties.
- **Bikes**, **Vans/Trucks**, and **Buses** also show significant figures.
- Other categories like **Agricultural vehicles** and **Other types** are also presented.

### 3. **CY Casualties vs. Previous Year Casualties**
A line chart compares the monthly trend of casualties in the current year versus the previous year. This visual helps identify whether there has been an increase or decrease in casualties throughout the months. Key observations can be made for spikes in specific months, indicating seasonal trends.

### 4. **Urban vs. Rural Casualties**
This doughnut chart provides insight into the distribution of accidents by location type:
- **Urban areas** account for the majority of casualties, as indicated by 61.23%.
- **Rural areas** contribute to 38.77% of casualties, which is also significant for addressing safety measures in these regions.

### 5. **Casualties by Road Type**
A bar chart illustrates the number of casualties based on different road types:
- **Single carriageways** show the highest number of casualties, followed by dual carriageways and roundabouts.
- **Slip roads** and **One-way streets** have significantly fewer casualties, reflecting lower usage or better safety measures.

### 6. **Daylight vs. Darkness Casualties**
This pie chart compares the accidents occurring during daylight (72.98%) versus darkness (27.02%). This information could be critical for understanding the impact of visibility and lighting conditions on road safety.

### 7. **Casualties by Location (Map Visualization)**
A map visual pinpoints the exact locations of casualties across the UK. This feature allows users to interact with and zoom into specific areas to see the density of accidents. High-density areas may need special attention for traffic safety improvements or further analysis of underlying causes.

## Insights and Business Value

1. **Accident Severity Trends**: The dashboard shows a significant decrease in fatal accidents (33.29%) and serious accidents (16.18%), highlighting improved safety measures in place. However, the slight accidents still form the bulk of the data and should be further analyzed.
   
2. **Vehicle Type Focus**: Most casualties involve **cars**, which implies that further safety measures could be directed towards improving vehicle safety features or stricter enforcement of traffic laws for this category.

3. **Time and Location Patterns**: The higher casualty figures in **urban areas** and during **daylight hours** reveal interesting patterns. This might seem counterintuitive as rural roads are often considered more dangerous. However, the data suggest that higher traffic volumes in cities may lead to more accidents despite lower speeds.

4. **Policy Implications**: The data visualized in this report can assist policymakers in identifying the most dangerous roads and times of day, focusing on **urban centers** and specific vehicle types that contribute most to accidents.

## Power BI Features Used

- **Card Visuals**: To display key metrics such as total casualties and accidents.
- **Line Chart**: Used to compare casualties month over month between two years.
- **Doughnut and Pie Charts**: To show percentages of casualties by location type (Urban/Rural) and time of day (Daylight/Darkness).
- **Bar Charts**: Used for a detailed breakdown of casualties by road type.
- **Map Visuals**: For geo-mapping the locations of road accidents, using **Microsoft Bing Maps** for interactive exploration.
  
## Conclusion

This dashboard provides a comprehensive view of road accidents in the UK, helping stakeholders understand accident patterns and trends. The insights can support better decision-making in traffic safety, infrastructure planning, and targeted awareness campaigns to reduce road casualties further.


