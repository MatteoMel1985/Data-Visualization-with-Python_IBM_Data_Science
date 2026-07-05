![Skills_Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-PY0221EN-Coursera/images/image.png)  

<h1 align="center">IBM Data Visualization with Python</h1>

This repository contains a structured collection of Jupyter Notebooks and a Dash application developed while working through the IBM **Data Visualization with Python** learning path. The materials demonstrate how to transform raw datasets into clear analytical visuals by using pandas, Matplotlib, Seaborn, Folium, Plotly, and Dash.

The main focus of the repository is the analysis of automobile sales during recession and non-recession periods. The final assignment is divided into two main artefacts: a visual analysis notebook created with Matplotlib, Seaborn, and Folium, and an interactive dashboard application built with Dash and Plotly.

<h1 align="center"><i>Repository Structure</i></h1>

```text
.
├── DV0101EN-Final-Assign-Part1.ipynb
├── DV0101EN-Final-Assign-Part-2-Questions.py
└── Jupyter Notebooks/
    ├── 4.3_Plotly_Basics.ipynb
    ├── DV0101EN-Exercise-Area-Plots-Histograms-and-Bar-Charts_.ipynb
    ├── DV0101EN-Exercise-Creating-maps-visualizing-geospat.ipynb
    ├── DV0101EN-Exercise-Dataset-Preprocessing-Exploring-with-Pandas.ipynb
    ├── DV0101EN-Exercise-Introduction-to-Matplotlib-and-Line-Plots_.ipynb
    ├── DV0101EN-Exercise-Pie-Charts-Box-Plots-Scatter-Plots-and-Bubble-Plots.ipynb
    ├── DV0101EN-Exercise-Plotting-directly-with-Matplotlib.jupyterlite.ipynb
    ├── DV0101EN-Exercise-Waffle-Charts-Word-Clouds-and-Regression-Plots.ipynb
    └── Practice_Assignment_Part1.ipynb
```

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

<h1 align="center"><i>Technical Methodologies and Mathematical Foundations</i></h1>

## 1. Data Preparation for Visual Analytics

The notebooks begin by loading structured datasets into pandas DataFrames and preparing them for analysis. This includes inspecting column names, selecting relevant variables, filtering records, grouping categories, and creating new aggregated tables.

From a mathematical perspective, a dataset can be represented as a matrix:

$$
X = \begin{bmatrix}
x_{11} & x_{12} & \dots & x_{1p} \\
x_{21} & x_{22} & \dots & x_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
x_{n1} & x_{n2} & \dots & x_{np}
\end{bmatrix}
$$

where each row represents an observation and each column represents a feature. Visualisation transforms selected columns of this matrix into graphical encodings such as position, length, area, colour, and size.

## 2. Grouping and Aggregation

Many notebooks use `groupby()` operations to summarise data by year, region, vehicle type, recession period, month, or continent. Aggregation reduces many individual observations into interpretable summary values.

For example, the mean of a variable is calculated as:

$$
\bar{x} = \frac{1}{n}\sum_{i=1}^{n}x_i
$$

while the total value for a group is calculated as:

$$
S = \sum_{i=1}^{n}x_i
$$

These operations are essential for creating line charts, bar charts, pie charts, and dashboard metrics that compare meaningful categories instead of raw individual records.

## 3. Time-Series Visualisation with Line Charts

Line charts are used throughout the repository to analyse changes over time, such as automobile sales by year, GDP during recession and non-recession periods, immigration trends, monthly vehicle sales, and wildfire activity across years and months.

A time series can be represented as an ordered sequence:

$$
\{(t_1, y_1), (t_2, y_2), \dots, (t_n, y_n)\}
$$

where $t$ is time and $y$ is the measured value. The line chart connects these ordered observations to reveal trends, peaks, declines, seasonality, and structural changes.

## 4. Bar Charts and Categorical Comparison

Bar charts are used to compare numerical values across discrete categories, such as vehicle types, recession status, regions, destination states, or countries. The height or length of each bar is proportional to a value such as average sales, total flights, total immigrants, or mean fire brightness.

If a category $c_j$ contains observations $x_1, x_2, \dots, x_n$, its plotted value may be a count, total, or average:

$$
\text{bar height}(c_j) = \frac{1}{n_j}\sum_{i=1}^{n_j}x_i
$$

This makes bar charts useful for comparing groups and identifying categories with unusually high or low values.

## 5. Histograms and Frequency Distributions

Histograms are used to study the distribution of numerical variables, such as immigration counts or mean estimated fire brightness. A histogram divides the range of a variable into bins and counts how many observations fall into each interval.

For a bin $B_j = [a_j, b_j)$, the frequency is:

$$
f_j = \#\{x_i : a_j \leq x_i < b_j\}
$$

Histograms help reveal skewness, concentration, dispersion, and multimodal patterns in a dataset.

## 6. Pie Charts and Part-to-Whole Analysis

Pie charts are used to represent proportions, such as advertising expenditure by period, advertising expenditure by vehicle type, or immigration grouped by continent. Each slice represents a share of a total:

$$
p_i = \frac{x_i}{\sum_{j=1}^{k}x_j}
$$

where $p_i$ is the proportion of category $i$. This method is most useful when the goal is to understand composition rather than precise ranking.

## 7. Box Plots and Distributional Summary

Box plots summarise the distribution of a numerical variable through quartiles, medians, and outliers. The box usually spans from the first quartile $Q_1$ to the third quartile $Q_3$, while the line inside the box represents the median.

The interquartile range is:

$$
IQR = Q_3 - Q_1
$$

Values beyond the usual whisker boundaries may be treated as potential outliers:

$$
x < Q_1 - 1.5(IQR) \quad \text{or} \quad x > Q_3 + 1.5(IQR)
$$

This makes box plots useful for comparing distributions between groups, such as immigration patterns across countries or decades.

## 8. Scatter Plots, Correlation, and Relationship Analysis

Scatter plots are used to examine the relationship between two numerical variables, such as consumer confidence and automobile sales, vehicle price and sales, or fire confidence and radiative power. Each point represents one observation:

$$
(x_i, y_i)
$$

The strength and direction of a linear relationship can be measured using the Pearson correlation coefficient:

$$
r = \frac{\sum_{i=1}^{n}(x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^{n}(x_i - \bar{x})^2}\sqrt{\sum_{i=1}^{n}(y_i - \bar{y})^2}}
$$

A positive value indicates that both variables tend to increase together, while a negative value indicates that one variable tends to decrease as the other increases.

## 9. Bubble Plots and Multi-Dimensional Encoding

Bubble plots extend scatter plots by using the size of each marker to represent a third numerical variable. If $s_i$ is the bubble size, it can be scaled from a variable $z_i$:

$$
s_i = k \cdot z_i
$$

where $k$ is a scaling factor. This allows a single chart to encode horizontal position, vertical position, and magnitude at the same time.

## 10. Waffle Charts and Proportional Grids

Waffle charts represent proportions by dividing a rectangle into a grid of equally sized cells. If the chart contains $N$ total cells and a category has proportion $p_i$, the number of cells assigned to that category is approximately:

$$
n_i = \text{round}(p_i \cdot N)
$$

This provides a visually intuitive way to compare contributions to a total, such as immigration shares between countries.

## 11. Word Clouds and Text Frequency

Word clouds visualise the frequency of words in a text corpus. After tokenising and cleaning the text, each word is counted:

$$
f(w) = \text{number of occurrences of word } w
$$

Words with higher frequencies appear larger in the final visual. Although word clouds are less precise than bar charts, they are useful for quick qualitative summaries of dominant terms.

## 12. Regression Plots and Trend Lines

Regression plots combine scatter points with a fitted line. In the notebooks, Seaborn regression plots are used to visualise long-term trends and relationships between variables.

The simplest regression model has the form:

$$
\hat{y} = b_0 + b_1x
$$

where $\hat{y}$ is the predicted value, $b_0$ is the intercept, and $b_1$ is the slope. The fitted line is usually estimated by minimising the residual sum of squares:

$$
RSS = \sum_{i=1}^{n}(y_i - \hat{y}_i)^2
$$

Regression plots are useful because they show both the individual observations and the general direction of the relationship.

## 13. Geospatial Visualisation with Folium

Folium is used to create interactive maps based on latitude and longitude coordinates. A geographical point can be represented as:

$$
(\phi, \lambda)
$$

where $\phi$ is latitude and $\lambda$ is longitude. The notebooks use Folium maps, markers, feature groups, marker clusters, circle markers, and choropleth maps to display spatial information.

In a choropleth map, a numerical variable is mapped to colour intensity across geographical regions. This helps reveal spatial concentration and variation.

## 14. Interactive Visualisation with Plotly

Plotly is used to create interactive charts such as scatter plots, line plots, bar charts, histograms, bubble plots, pie charts, and sunburst charts. Unlike static charts, Plotly visualisations allow users to hover, zoom, pan, and inspect data dynamically.

A Plotly chart maps DataFrame columns to visual properties such as:

```python
x → horizontal position
y → vertical position
color → category or magnitude
size → third numerical variable
```

This makes Plotly especially useful for exploratory analysis, where interaction helps the user inspect patterns more deeply.

## 15. Dashboarding with Dash

The final Python script uses Dash to build an interactive dashboard. Dash applications are structured around layouts and callbacks. The layout defines the visible user interface, while callbacks define how outputs change when inputs change.

Mathematically, a callback can be understood as a function:

$$
\text{Output} = f(\text{Input}_1, \text{Input}_2, \dots, \text{Input}_n)
$$

In this project, dropdown selections determine whether the dashboard displays yearly statistics or recession-period statistics. The selected input dynamically updates the charts shown in the output container.

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
