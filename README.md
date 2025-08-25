# Mission-Launches-Analysis
Mission Launch Data Cleaning, Analysis, and Visualization using Power Query

## 📖 Objective
The objective of this project is to **analyze missile launches across different organizations**.  
The focus was on identifying key patterns such as which organization launched the most, the year with the highest number of launches, and the most costly launches over time.  

## 🛠️ Tools & Technologies
- **Excel:** For importing the dataset and initial structuring of the data.  
- **Power Query:** For data cleaning and transformation, including handling null values and removing unnecessary columns.  
- **Power BI:** For creating interactive dashboards and visualizing key insights.  

## 📊 Dataset
- **Source:** mission_launches.csv
- **Structure:** Contains details:
- Index
- Organization
- Location
- Date
- Detail
- Rocket Status
- Price
- Mission Status
  
## 🔎 Process
1. **Data Cleaning**  
   - Replaced null values with appropriate values.  
   - Removed irrelevant or redundant columns.  
   - Standardized formats for consistent analysis.  

2. **Data Transformation**  
   - Structured the dataset for time-series and categorical analysis.  
   - Created calculated fields for cost comparisons and launch frequency.  

3. **Analysis & Visualization**  
   - Identified the organizations with the most launches.  
   - Determined the year with the highest number of launches.  
   - Compared launch costs over time.  
   - Highlighted the most expensive launches and their organizations.  

## 📈 Results
- The organization with the highest number of launches was clearly identified.  
- The year with the most launches was highlighted as a peak in missile activity.  
- Cost analysis showed significant variation across organizations and over time.  
- Interactive dashboards allow filtering by year, organization, and launch cost.

## 📂 Repository Structure
-	Raw dataset -> mission_launches.csv
-	Power BI Dashboard -> Missions Dashboard.pbix / Missions Dashboard PDF.pdf
-	Data Insights Presentation -> PT Mission Launches Analysis.pdf
