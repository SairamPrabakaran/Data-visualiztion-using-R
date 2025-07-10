# Data-visualiztion-using-R
Weather and Crime Patterns Analysis
This project explores how weather conditions relate to crime patterns in a specified region by analyzing two datasets: one containing detailed crime records, and another covering meteorological observations. Using data visualization and statistical insights, the goal is to reveal trends, patterns, and potential seasonal effects in both weather and criminal activity.

📁 Datasets Used
Crime Data: Includes crime category, date, and outcome status.

Weather Data: Includes daily readings of:

Temperature (average, min, max)

Precipitation (Precmm)

Humidity

Dew Point Temperature

Wind Intensity

Other atmospheric observations

📌 Project Objectives
Clean and preprocess raw weather data (handle missing values and remove irrelevant columns).

Visualize and understand seasonal patterns in temperature, humidity, and precipitation.

Investigate relationships between weather variables through correlation analysis.

Explore crime trends across time and their potential associations with weather factors.

Provide data-driven insights for urban planners, law enforcement, and policymakers.

🔧 Data Preprocessing
Columns with entirely missing data (PreselevHp, SnowDepcm) were removed.

Columns with minor missing values (Precmm, lowcloct, SunD1h) were imputed using mean values to maintain dataset integrity.

📊 Exploratory Analysis
🔥 Temperature Patterns
Density Plot of Avg Temperature (°C):

Slightly bell-shaped distribution with a left skew.

One clear outlier (very low temperature).

Violin Plot of Min and Max Temperatures:

Wider range in minimum temperatures.

Greater IQR and more outliers in the min temp distribution.

Scatter Plot: Avg Temperature vs. Wind Intensity:

Displays a scattered cloud of points.

No clear linear relationship detected.

🎛️ Interactive Dashboard Features
Interactive Correlation Heatmap:

Users can select variables dynamically.

Enables exploration of relationships between weather variables.

🧠 Insights from the Heatmap:
Darker colors indicate stronger correlations (positive = yellow, negative = blue).

Strong Positive Correlations:

Between dew point temperature and humidity.

Between temperature metrics (avg, min, max).

Multicollinearity Warning:

High correlations between similar temperature measures could affect regression performance.

Seasonal Grouping:

Variables cluster differently in summer vs. winter months.

📅 Seasonal Analysis: Weather Trends
🌡️ Temperature:
Warmest months: July–September (Months 7–9), peaking in Month 8.

Coldest months: November–January (Months 11–1), with the lowest in Month 12.

🌧️ Precipitation:
Most rainfall: Seen in Month 8.

Drier period: During colder months (November–January).

💧 Humidity and Dew Point:
Humidity shows inconsistent variation, but dew point trends closely with temperature.

Highest dew point in Month 8, aligning with the warmest and wettest month.

💡 Key Takeaways
Seasonal cycles strongly influence temperature, dew point, and precipitation.

Month 8 (likely August) consistently stands out as the hottest, most humid, and wettest.

Visualization tools like violin plots and interactive heatmaps are crucial for identifying trends and relationships.

Preprocessed and cleaned weather data enables reliable statistical inference and insight generation.

🛠️ Technologies Used
Tool/Library	Purpose
Python	Main programming language
Pandas	Data cleaning and manipulation
Matplotlib	Static plotting
Seaborn	Advanced visualizations
Plotly/Dash	Interactive visualizations (optional)
Jupyter Notebook	Exploratory data analysis environment

📈 Future Enhancements
Integrate crime trends more directly with weather data (e.g., heatmaps of crime vs. temperature).

Build predictive models (e.g., decision trees, regression) to forecast crime based on weather.

Improve dashboard UI for easier exploration of trends and comparisons.

📚 Conclusion
Understanding the interplay between weather conditions and crime patterns provides valuable insights for planning and safety efforts. This analysis presents an effective starting point for further investigation into how seasonal and environmental factors may influence human behavior.
