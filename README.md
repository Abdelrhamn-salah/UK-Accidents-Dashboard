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

### [Data](https://drive.google.com/file/d/1EHmRmi-Ffhu_OEdCkupn9zWuHKIufxYl/view) 
The dataset used for this analysis consists of road accident records covering details such as accident date, location, weather conditions, road type, and other contributing factors. Before preparing the data for visualization, the following preprocessing steps were performed:

- **Handling Missing Values**: Rows with missing data were removed to ensure completeness.
- **Removing Duplicates**: Duplicate records were dropped to maintain data integrity.
- **Date Standardization**:  
  - The `Accident Date` column had inconsistent formats, which were standardized into a single `DD/MM/YYYY` format.
- **Text Standardization**:  
  - Categorical values (e.g., `Weather_Conditions`, `Road_Type`, `Light_Conditions`) were cleaned by converting them to title case, stripping extra spaces, and unifying separators.  
- **Categorical Value Mapping**:  
  - `Road_Surface_Conditions` values were standardized for clarity (e.g., `"Wet or damp"` → `"Wet"`, `"Frost or ice"` → `"Icy"`).  
  - Misspelled district names were corrected (e.g., `"Stevege"` → `"Stevenage"`, `"Blaeu Gwent"` → `"Blaenau Gwent"`).  


### Dashboard Link
Access the dashboard here: [Road Accident Dashboard](https://public.tableau.com/views/AccidentsDashboard_17425088688960/Dashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


