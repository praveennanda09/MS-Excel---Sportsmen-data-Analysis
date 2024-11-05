# Sportsmen Dashboard Creation in Microsoft Excel

## Overview
This project involves creating an interactive dashboard in Microsoft Excel to visualize and analyze data about athletes. The dataset contains detailed information about each athlete, including personal details, country, sport, and various attributes such as weight, eye color, and salary. This dashboard provides insights into the demographics, athletic details, and financial aspects of the athletes, allowing users to gain a quick understanding of the dataset at a glance.

## Dataset
The dataset includes the following columns:

| Column          | Description                                        |
|-----------------|----------------------------------------------------|
| MEMBER ID       | Unique identifier for each athlete                 |
| FULL NAME       | Full name of the athlete                           |
| PREFIX          | Prefix (e.g., Mr., Ms., Dr.)                       |
| FIRSTNAME       | First name of the athlete                          |
| LASTNAME        | Last name of the athlete                           |
| BIRTHDATE       | Birth date of the athlete                          |
| MONTH           | Birth month                                        |
| ZODIAC          | Zodiac sign based on birthdate                     |
| GENDER          | Gender of the athlete                              |
| COUNTRYCODE     | ISO country code                                   |
| COUNTRY NAME    | Country name                                       |
| LANGUAGE        | Primary language spoken                            |
| EMAIL           | Contact email address                              |
| WEIGHT          | Athlete's weight (kg)                              |
| EYECOLOR        | Eye color of the athlete                           |
| BLOODTYPE       | Blood type of the athlete                          |
| SPORT LOCATION  | Sport location type (Indoor/Outdoor)               |
| SPORTS          | Type of sport the athlete is involved in           |
| SALARY          | Annual salary of the athlete                       |

### Example Rows
| MEMBER ID | FULL NAME           | PREFIX | FIRSTNAME | LASTNAME   | BIRTHDATE | MONTH | ZODIAC  | GENDER | COUNTRYCODE | COUNTRY NAME | LANGUAGE | EMAIL                    | WEIGHT | EYECOLOR | BLOODTYPE | SPORT LOCATION | SPORTS        | SALARY |
|-----------|----------------------|--------|-----------|------------|-----------|-------|---------|--------|-------------|--------------|----------|--------------------------|--------|----------|-----------|----------------|---------------|--------|
| 1         | Ms. Annie Abbott     | Ms.    | Annie     | Abbott     | 26-09-1997| Sep   | Libra   | Female | US          | USA          | English  | abbott.annie@xyz.org     | 94     | Green    | A−        | INDOOR         | Cycling Track| 80727  |
| 2         | Ms. Aurelie Liesuchke| Ms.    | Aurelie   | Liesuchke  | 27-09-1997| Sep   | Aquarius| Female | US          | USA          | English  | liesuchke.aurelie@xyz.org| 84.2   | Brown    | O−        | INDOOR         | Boxing       | 87471  |
| ...       | ...                  | ...    | ...       | ...        | ...       | ...   | ...     | ...    | ...         | ...          | ...      | ...                      | ...    | ...      | ...       | ...            | ...           | ...    |

## Dashboard Features
The Excel dashboard includes a variety of charts, tables, and interactive elements to provide insights into the dataset. Key dashboard elements include:

1. **Demographics Overview**:
   - **Gender Distribution**: Visual representation of the gender ratio.
   - **Country Representation**: Pie chart of athletes from different countries.
   - **Zodiac Sign Distribution**: Bar chart showcasing the count of athletes by zodiac signs.

2. **Athletic and Sport Analysis**:
   - **Sport Types**: Count of athletes involved in each type of sport.
   - **Sport Location Analysis**: Distribution of indoor vs. outdoor sports.
   - **Eye Color**: Visualization of eye color distribution among athletes.

3. **Salary and Financial Insights**:
   - **Salary Range Analysis**: Histogram or bar chart representing salary distribution.
   - **Average Salary by Sport**: Breakdown of average salary per sport.
   - **Top Earners**: Table highlighting athletes with the highest salaries.

4. **Additional Metrics**:
   - **Average Weight by Gender**: Comparison of average weight for male and female athletes.
   - **Blood Type Distribution**: Bar chart showing the frequency of each blood type.

5. **Interactive Filters**:
   - **Country Filter**: Filter athletes by country to view specific details.
   - **Sport Filter**: Filter athletes based on their sport type.
   - **Gender Filter**: Toggle between male and female athletes for targeted analysis.

## Steps to Create the Dashboard
1. **Data Preparation**:
   - Import the dataset into Microsoft Excel and clean any missing or inconsistent data.
   - Format the data as an Excel Table to facilitate filtering and sorting.
   
2. **Creating Visualizations**:
   - **Pie Charts** for gender and country representation.
   - **Bar Charts** for zodiac sign distribution, sport type, and eye color.
   - **Histograms** for salary distribution.
   - **Line or Scatter Plots** if additional trend analysis is needed.
   
3. **Using Excel Formulas**:
   - Apply formulas such as `AVERAGEIF`, `COUNTIF`, and `SUMIF` to calculate metrics like average salary by sport and average weight by gender.
   
4. **Setting Up Interactive Elements**:
   - Utilize **Slicers** for country, gender, and sport type filtering.
   - Use **Pivot Tables** to dynamically display data, linked to slicers for seamless filtering.
   
5. **Final Touches**:
   - Design a clean, user-friendly layout for the dashboard.
   - Add labels, titles, and data legends to ensure clarity in each visualization.
   - Apply conditional formatting where necessary (e.g., for highlighting top earners).

## Usage Instructions
1. **Open the Dashboard**: Open the Excel file and navigate to the Dashboard sheet.
2. **Apply Filters**: Use the interactive filters to view specific subsets of the data.
3. **Analyze Data**: Observe the various charts and tables to gain insights into the athlete dataset.
4. **Export**: Export specific views or data segments as needed for reports or presentations.

## Conclusion
This Excel dashboard provides a comprehensive tool for visualizing and analyzing a diverse range of data attributes related to athletes. It enables easy exploration of demographics, athletic details, and financial insights, making it valuable for stakeholders who want a quick yet in-depth overview of the sportsmen dataset.

---

