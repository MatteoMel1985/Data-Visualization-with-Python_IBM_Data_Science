![Skills_Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-PY0221EN-Coursera/images/image.png)  

<h1 align="center">IBM Data Visualization with Python</h1>

This repository contains a structured collection of Jupyter Notebooks and a Dash application developed while working through the IBM **Data Visualization with Python** learning path. The materials demonstrate how to transform raw datasets into clear analytical visuals by using pandas, Matplotlib, Seaborn, Folium, Plotly, and Dash.

The main focus of the repository is the analysis of automobile sales during recession and non-recession periods. The final assignment is divided into two main artefacts: a visual analysis notebook created with Matplotlib, Seaborn, and Folium, and an interactive dashboard application built with Dash and Plotly.

<h1 align="center"><i>Notebooks Overview</i></h1>

* [**Final Assignment Part 1 – Automobile Sales Visual Analysis**](DV0101EN-Final-Assign-Part1.ipynb)

This is one of the two main files of the repository. It analyses historical automobile sales data to understand how sales, advertising expenditure, GDP, consumer confidence, seasonality, unemployment, and vehicle type behave during recession and non-recession periods. The notebook applies pandas grouping operations, Matplotlib line charts, Seaborn comparative plots, scatter plots, bubble plots, pie charts, and an optional Folium map to answer the assignment tasks.

* [**Final Assignment Part 2 – Automobile Sales Statistics Dashboard**](DV0101EN-Final-Assign-Part-2-Questions.py)

This is the second main file of the repository. It implements an interactive Dash dashboard for automobile sales statistics. The application uses dropdown menus, callback functions, and Plotly Express charts to switch between yearly statistics and recession-period statistics. The dashboard displays line charts, bar charts, and pie charts describing automobile sales, vehicle-type behaviour, advertising expenditure, and the effect of unemployment on sales.

* [**Dataset Preprocessing and Exploration with pandas**](Jupyter%20Notebooks/DV0101EN-Exercise-Dataset-Preprocessing-Exploring-with-Pandas.ipynb)

This notebook introduces the preparation stage of visual analytics. It uses the Canadian immigration dataset to practise importing data into pandas, inspecting rows and columns, setting indexes, selecting data with labels and positions, filtering records, sorting values, and preparing a clean DataFrame for visualisation.

* [**Introduction to Matplotlib and Line Plots**](Jupyter%20Notebooks/DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots_.ipynb)

This notebook introduces Matplotlib as a standard Python visualisation library. It demonstrates how to create line plots from pandas Series and DataFrames, customise titles and axes, and analyse immigration trends over time, including examples such as Haiti, India, China, and the top countries contributing to immigration to Canada.

* [**Plotting Directly with Matplotlib**](Jupyter%20Notebooks/DV0101EN-Exercise-Plotting-directly-with-Matplotlib.jupyterlite.ipynb)

This notebook extends the practical use of Matplotlib by creating line plots, scatter plots, bar plots, histograms, pie charts, and subplot layouts. It also demonstrates how to customise plot appearance through labels, legends, grids, axis limits, markers, annotations, and multi-chart figures.

* [**Area Plots, Histograms, and Bar Charts**](Jupyter%20Notebooks/DV0101EN-Exercise-Area-Plots-Histograms-and-Bar-Charts_.ipynb)

This notebook focuses on three important families of statistical graphics. Area plots are used to visualise cumulative trends, histograms are used to analyse frequency distributions, and bar charts are used to compare categorical totals. The exercises apply both scripting and artist-layer approaches to immigration data.

* [**Pie Charts, Box Plots, Scatter Plots, and Bubble Plots**](Jupyter%20Notebooks/DV0101EN-Exercise-Pie-Charts-Box-Plots-Scatter-Plots-and-Bubble-Plots.ipynb)

This notebook explores visual methods for proportions, distributions, relationships, and multi-dimensional comparisons. It uses pie charts to show part-to-whole composition, box plots to compare distributions and outliers, scatter plots to show relationships between variables, and bubble plots to add a third numerical dimension through marker size.

* [**Waffle Charts, Word Clouds, and Regression Plots**](Jupyter%20Notebooks/DV0101EN-Exercise-Waffle-Charts-Word-Clouds-and-Regression-Plots.ipynb)

This notebook introduces more specialised visualisation techniques. It demonstrates how waffle charts represent proportional contributions, how word clouds summarise text frequency visually, and how Seaborn regression plots combine scatter points with fitted trend lines to analyse relationships over time.

* [**Creating Maps and Visualizing Geospatial Data**](Jupyter%20Notebooks/DV0101EN-Exercise-Creating-maps-visualizing-geospat.ipynb)

This notebook introduces geospatial visualisation with Folium. It demonstrates how to create interactive maps, customise tile styles, place markers, use marker clusters, and build choropleth maps to represent geographical variation in a dataset.

* [**Basic Plotly Charts**](Jupyter%20Notebooks/4.3_Plotly_Basics.ipynb)

This notebook introduces interactive visualisation with Plotly. It covers Plotly Graph Objects and Plotly Express, creating scatter plots, line plots, bar charts, histograms, bubble plots, pie charts, and sunburst charts. It also applies these chart types to an airline dataset to practise exploratory visualisation in an interactive environment.

* [**Practice Assignment Part 1 – Analysing Wildfire Activities in Australia**](Jupyter%20Notebooks/Practice_Assignment_Part1.ipynb)

This practice assignment applies the visualisation workflow to Australian wildfire data. It investigates estimated fire area, estimated fire brightness, regional fire activity, vegetation fire pixels, fire radiative power, confidence levels, and regional locations. The notebook uses pandas plots, Matplotlib, Seaborn, pie charts, histograms, scatter plots, stacked distributions, and Folium maps.

<h1 align="center"><i>Technical Methodologies</i></h1>

## 1. Data Preparation for Visualisation

The notebooks begin by preparing datasets for visual analysis with pandas. This includes loading CSV files, inspecting columns and data types, filtering rows, grouping data, aggregating values, and reshaping tables where necessary. These steps are essential because effective visualisation depends on clean, well-structured data.

Several notebooks use operations such as `groupby()`, `sum()`, `mean()`, `value_counts()`, and `reset_index()` to transform raw datasets into chart-ready summaries. These techniques make it possible to compare categories, analyse trends over time, and prepare data for dashboards and maps.

## 2. Line Plots

Line plots are used to visualise trends over time or ordered sequences. In the notebooks, they are especially useful for analysing changes in automobile sales across years, monthly sales patterns, and long-term fluctuations during recession and non-recession periods.

Line charts are effective when the main objective is to show movement, direction, increase, decrease, or seasonality across a continuous timeline.

## 3. Area Plots

Area plots extend line charts by filling the space beneath the plotted lines. They are used to emphasise the magnitude of change over time and to compare cumulative trends across multiple categories.

In the visualisation labs, area plots help show how values evolve across years while giving the chart a stronger visual sense of volume and contribution.

## 4. Histograms

Histograms are used to examine the distribution of numerical variables. They divide values into intervals, or bins, and show how frequently observations fall into each interval.

The notebooks use histograms to understand the spread of data, identify common ranges, and detect possible skewness or unusual patterns in numerical variables.

## 5. Bar Charts

Bar charts are used to compare values across categories. In these notebooks, they are applied to compare vehicle types, sales values, unemployment-related effects, and other grouped categories.

Bar charts are particularly useful when the goal is to rank categories, compare totals or averages, and make differences between groups immediately visible.

## 6. Pie Charts

Pie charts are used to show part-to-whole relationships. In the final dashboard, pie charts are used to represent the share of advertising expenditure by vehicle type.

This type of chart is most useful when the number of categories is limited and the purpose is to communicate proportional contribution rather than precise numerical comparison.

## 7. Box Plots

Box plots are used to summarise the distribution of numerical data across different categories. They show the median, quartiles, spread, and possible outliers.

In the notebooks, box plots help compare distributions between groups and reveal whether specific categories have higher or lower values, wider variation, or unusual observations.

## 8. Scatter Plots

Scatter plots are used to explore relationships between two numerical variables. Each point represents an observation, making it possible to identify patterns, clusters, trends, and possible outliers.

The notebooks use scatter plots to analyse whether two variables appear to move together and whether a visual relationship may exist between them.

## 9. Bubble Plots

Bubble plots extend scatter plots by adding a third variable through the size of each point. This allows the chart to represent more information without changing the basic two-axis structure.

They are useful when the analysis requires comparing two numerical variables while also showing the relative magnitude of another measure.

## 10. Waffle Charts

Waffle charts are used to represent proportions in a grid-based format. They provide an alternative to pie charts by showing part-to-whole relationships through small, countable blocks.

In the notebooks, waffle charts are used to make proportional comparisons more visually engaging and easier to interpret at a glance.

## 11. Word Clouds

Word clouds are used to visualise the frequency of words in a text dataset. Words that appear more often are displayed with greater visual prominence.

The notebooks use word clouds as a text visualisation technique, helping to identify dominant terms and themes within unstructured textual data.

## 12. Regression Plots

Regression plots combine scatter plots with a fitted trend line. They are used to visualise the general relationship between two numerical variables and to show whether the relationship appears positive, negative, or weak.

In the visualisation workflow, regression plots help connect exploratory visual analysis with predictive thinking by showing how one variable may explain changes in another.

## 13. Plotly Interactive Visualisations

The Plotly notebook introduces interactive visualisation techniques. Plotly charts allow users to hover over data points, zoom into sections, pan across the chart, and explore values dynamically.

This makes Plotly especially useful for dashboards and analytical reports where users need more flexibility than static charts can provide.

## 14. Dash Dashboard Development

The final assignment uses Dash to build an interactive web dashboard for automobile sales analysis. The dashboard includes dropdown menus, user input controls, callback functions, and dynamically updated charts.

The Dash application allows users to switch between yearly statistics and recession-period statistics. Depending on the selected option, the dashboard displays different combinations of line charts, bar charts, and pie charts.

## 15. Dashboard Callbacks and Interactivity

Dash callbacks are used to connect user interface components with visual outputs. In the dashboard, callbacks control whether the year selector is enabled or disabled and determine which charts are displayed based on the selected report type.

This introduces an important dashboard design principle: visualisations should respond to user choices and display only the information relevant to the selected analytical context.

## 16. Geospatial Visualisation with Folium

The geospatial notebooks introduce map-based visualisation with Folium. Folium is used to create interactive maps, add markers, display geographical points, and visualise spatial patterns.

These techniques are useful when the dataset contains location-based information and the analysis requires understanding where events, values, or observations are geographically concentrated.

## 17. Choropleth Maps

Choropleth maps are used to colour geographical regions according to a numerical value. In the notebooks, this technique is applied to visualise differences across areas, such as regional totals or state-level values.

Choropleth maps are especially effective when the goal is to compare geographical regions and identify spatial patterns at a broader level.

## 18. Marker Maps and Spatial Points

Marker maps display individual locations as points on a map. They are useful for showing exact positions, highlighting specific observations, and allowing users to interact with location-based data.

The notebooks demonstrate how map markers can make geospatial datasets more intuitive by connecting data records directly to their real-world locations.

## 19. Matplotlib-Based Static Visualisation

Many notebooks use Matplotlib as the foundation for static visualisation. Matplotlib provides detailed control over chart structure, including figure size, titles, axis labels, legends, colours, and layout.

It is used throughout the repository to create line plots, bar charts, histograms, pie charts, scatter plots, and other core visualisations.

## 20. pandas Built-In Plotting

Some visualisations are created directly from pandas DataFrames. pandas plotting provides a convenient way to generate charts from tabular data without needing extensive chart configuration.

This approach is useful for quick exploratory analysis, especially when the data has already been grouped, filtered, or aggregated.

## 21. Visual Storytelling and Analytical Communication

Across the notebooks, visualisation is used not only to display data but also to communicate insights. Each chart type serves a specific purpose: line charts show trends, bar charts compare categories, pie charts show proportions, box plots reveal distributions, scatter plots explore relationships, and maps display geographical patterns.

Together, these methods demonstrate how Python visualisation tools can transform raw datasets into clear analytical narratives, helping users understand patterns, compare groups, and communicate findings effectively.

<h1 align="center"><i>Skills Demonstrated</i></h1>

* Loading, inspecting, and preparing datasets with pandas.
* Creating line charts, area plots, histograms, bar charts, pie charts, box plots, scatter plots, and bubble plots.
* Comparing numerical values across time periods, categories, and geographical regions.
* Using grouping and aggregation to summarise raw data for visual analysis.
* Applying Matplotlib for static visualisation and fine-grained chart customisation.
* Using Seaborn for statistical visualisation and regression plots.
* Creating waffle charts and word clouds for proportional and textual data.
* Building interactive maps with Folium, including markers, marker clusters, and choropleth maps.
* Creating interactive charts with Plotly Express and Plotly Graph Objects.
* Developing an interactive dashboard with Dash layouts, dropdowns, callbacks, and dynamic chart rendering.
* Analysing automobile sales trends during recession and non-recession periods.
* Applying visual analytics to immigration, airline, wildfire, geospatial, and automobile datasets.

<h1 align="center"><i>Technologies Used</i></h1>

<table align="center">
<tr>
<td>
<i>

* Python
* Jupyter Notebook / JupyterLab
* pandas
* NumPy
* Matplotlib
* Seaborn
* Folium
* Plotly
* Dash
* pywaffle
* WordCloud
* PIL

</i>
</td>
</tr>
</table>

<h1 align="center"><i>Overall Summary</i></h1>

Together, these notebooks and the dashboard script provide a practical introduction to data visualisation with Python. They begin with the fundamentals of preparing datasets and creating static charts, then progress towards statistical visualisation, geospatial mapping, interactive Plotly figures, and dashboard development with Dash. The repository demonstrates how visualisation can be used not only to make data more readable, but also to reveal trends, compare categories, understand distributions, detect relationships, and communicate insights effectively.

The final assignments apply these techniques to automobile sales data, with a particular focus on recession and non-recession periods. The supporting labs strengthen the same skills through immigration, airline, wildfire, and geospatial datasets, making the repository a broad and practical reference for students learning how to turn raw data into meaningful visual narratives.

# Author
# ***[Matteo Meloni](https://www.linkedin.com/in/matteo-meloni-40a357154/)***
