# Ski_Resorts
**Data Cleaning and Preparation**
1. Procurement of Data:

The dataset was sourced from Kaggle and initially contained raw data that required significant cleaning to be usable for analysis and visualization.

2. Column Adjustments:

Percentages Conversion: Percentages in columns such as 'Beginners Runs', 'Intermediate Runs', 'Advanced Runs', and 'Expert Runs' were converted into integers for easier manipulation and analysis.

Height and Elevation Columns: Columns like 'Summit height', 'Vertical Drop', and 'Base Elevation' were stripped of non-numeric characters and converted into integers.
Date Formatting: 'Projected Opening' and 'Projected Closing' columns were cleaned to extract the relevant dates and converted into a standard datetime format.

3. Handling Missing Data:

Dropped rows where essential columns like 'Beginners Runs' and 'Expert Runs' had missing values to ensure data integrity in the analysis.

4. Filtering Resorts:

Focused the analysis on a select list of prominent ski resorts, such as Vail, Aspen, Breckenridge, Telluride, Steamboat, Copper Mountain, Keystone Resort, Jackson Hole, and Mammoth Mountain, to compare these specific resorts more effectively.

**Data Visualization Experiments**
1. Resort Elevation Comparison:

Created a bar chart to visualize the base elevation and vertical drop of selected ski resorts. The chart illustrated the differences in elevation among the chosen resorts, with stacked bars showing both base elevation and vertical drop.

2. Resorts Run Distribution:

A pie chart was generated for each resort to showcase the distribution of ski runs by difficulty level (Beginners, Intermediate, Advanced, and Expert). This helped in visualizing which resorts had more challenging runs versus beginner-friendly ones.
Each pie chart included a center circle for aesthetics and a legend to indicate the run type distribution.

3. Total Snowfall Analysis:

Bar charts were plotted to show the total snowfall across different years for the selected resorts. The average snowfall was highlighted with horizontal lines to provide a benchmark comparison between the resorts.

Specific resorts like Copper Mountain, Vail, Jackson Hole, Steamboat, and Breckenridge were analyzed in greater detail, with individual graphs showing year-over-year snowfall patterns.

**Tableu Visualization**

The primary objective of this project was to utilize the provided data to generate various visualizations that would assist in determining the ideal ski resort destination. 

1. Pie Charts: The initial visualization involved creating pie charts to depict the distribution of run types—beginner, intermediate, advanced, and expert—across different resorts. This was achieved by consolidating the relevant columns into a pivot table, enabling a clear and comparative representation of the run type percentages for each resort.

2. Bar Chart: The subsequent step involved developing a bar chart to illustrate the overall summit height and vertical drop of each resort. This visualization not only highlights the elevation but also provides insight into the steepness of the terrain, which is a critical factor in evaluating the skiing experience.

3. Snowfall Analysis: The final chart in this series focused on displaying the average snowfall in inches for each resort. This chart is particularly useful for those seeking to understand which resorts typically experience heavier or lighter snowfall, thus aiding in the decision-making process.

*In depth snowfall analysis* 

1. Snowfall Days Analysis: The first chart in this dashboard delves deeper into snowfall data by analyzing the number of days with snowfall over the past ten years. This analysis provides a more granular view of snowfall patterns, which can be crucial for planning purposes.

2. Annual Snowfall Trends: The final visualization presented a text table showing the annual snowfall in inches over the past decade. While the average snowfall was previously displayed, this table allows users to track snowfall trends over the years, helping them discern whether snowfall has been increasing or decreasing in the years leading up to their planned visit.

**Conclusion**
The project’s aim was to clean and prepare the dataset for presentation in Tableau, allowing for an informed decision on which ski resort to choose based on various factors like elevation, run difficulty, and historical snowfall data. The visualizations created in Jupyter Notebook served as a preliminary analysis tool before finalizing the presentation in Tableau.


link to tableu: https://public.tableau.com/app/profile/matthew.sanders7744/viz/Skiresorts_17249549439060/Dashboard1

https://public.tableau.com/app/profile/matthew.sanders7744/viz/Skiresorts-snowfall/Story2?publish=yes