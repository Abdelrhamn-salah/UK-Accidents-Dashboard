# UK-Accidents-Dashboard

## Overview
The **Road Accident Dashboard** is an interactive analytical tool designed to explore accident trends, severity levels, and contributing factors across the UK. By leveraging visual insights and dynamic filtering, users can identify patterns, assess risks, and make informed decisions regarding road safety.

## Key Features
### Data Visualizations
- **Casualties by Road Type**: A bar chart illustrating the total number of casualties for each type of road.
- **Casualties by Conditions**:
  - **Weather Conditions**: A donut chart categorizing casualties based on weather factors (e.g., fog, rain, clear conditions).
  - **Road Surface Conditions**: A donut chart analyzing how surface conditions (e.g., wet, dry, icy) impact accident severity.
- **Geospatial Map**: A UK-wide map marking accident locations for spatial analysis.
- **Key Performance Indicators (KPIs)**:
  - **Total Accidents**: Overall count of reported accidents.
  - **Total Casualties**: Aggregate number of individuals affected.
  - **Accident Severity Breakdown**: A KPI widget categorizing accidents into fatal, serious, and slight.
- **Trend Analysis**:
  - Line charts or sparklines for each KPI, enabling year-over-year (YoY) comparisons.

### Filters & Interactivity
1. **Year Selection Filter**: Compare statistics across different years to observe trends and fluctuations.
2. **Accident Severity Filter**: Focus on specific severity levels (fatal, serious, slight) to analyze their distribution.
3. **Cross-Filtering**: Interactive selection—clicking on elements (e.g., "Single Carriageway" in the bar chart) updates all related visualizations dynamically.

### Data  
The dataset used for this analysis consists of road accident records containing information such as accident date, location, weather conditions, road type, and other contributing factors. Before making the data ready for visualization in the dashboard, the following preprocessing steps were performed:  

- **Handling Missing Values**
- **Removing Duplicates**
- **Date Standardization**:  
  - The `Accident Date` column had different date formats which were Standardized into one format
- **Text Standardization**:  
  - The categorical values in columns such as `Weather_Conditions`, `Road_Type`, and `Light_Conditions` were cleaned by converting them to title case, stripping extra spaces, and standardizing separators.  
- **Categorical Value Mapping**:  
  - Certain values in `Road_Surface_Conditions` were renamed for consistency, e.g., `"Wet or damp"` → `"Wet"`, `"Frost or ice"` → `"Icy"`, `"Flood over 3cm. deep"` → `"Flooded"`.  
  - District names with misspellings were corrected, e.g., `"Stevege"` → `"Stevenage"`, `"Blaeu Gwent"` → `"Blaenau Gwent"`.  

### Dashboard Link
Access the dashboard here: [Road Accident Dashboard](https://public.tableau.com/views/AccidentsDashboard_17425088688960/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
