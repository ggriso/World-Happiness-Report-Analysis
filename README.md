# World-Happiness-Report-Analysis

Performing data preparation, cleaning, EDA, geospatial analysis (JSON shapefile), regression analysis, cluster analysis (k-means), and time-series analysis with Python. Employing Seaborn, Matplotlib and Plotly to create appropriate visualisations.

## Does money make happiness? Insights from the World Happiness Report (2019-2023)

### Context

The World Happiness Report is an annual publication that explores the factors contributing to human well-being, the happiness ratings of countries and the importance of measuring happiness. Experts use responses from people in more than 140 nations to rank the world’s ‘happiest’ countries. Respondents are asked to rate their lives on a scale from 0 (worst) to 10 (best) using the Cantril Ladder. 

In this analysis, we want to explore how different factors contributed to happiness across various countries over the past 5 years (2019-2023). In particular, we are interested in the role played by economic prosperity in determining happiness.

### Data Source

The datasets are part of a collection called [World Happiness Reports 2013 – 2023](https://www.kaggle.com/datasets/joebeachcapital/world-happiness-report-2013-2023?resource=download) on Kaggle. We will analyse the reports from 2019 to 2023. The data is available under the [Community Data License Agreement - Permissive - Version 1.0](https://cdla.dev/permissive-1-0/).

The JSON shapefile we need for the geospatial analysis is available in the project folder, under the folder "03 Scripts".

For the time-series analysis, we decided to use a different dataset with more data points. You can find it at [Nasdaq Data](https://data.nasdaq.com/databases/ZILLOW).

### Questions to explore

- How does the distribution of happiness scores vary across different regions and years?
- Is there a correlation between GDP per capita and happiness scores?
- Which other factors have the strongest impact on happiness scores?
- Which countries consistently maintain high or low happiness rankings over the years?
- What recommendations can be made to policymakers to improve overall well-being in different parts of the world?

### Project Folder Structure

The project files are organized into the following folders:
- **01 Project Management:** includes the Project Brief and the Data License Agreement.
- **02 Data:** divided into two subfolders:
  1. Original Data: contains the original data frames.
  2. Prepared Data: holds cleaned and wrangled data frames, ready for analysis.
- **03 Scripts:** contains Jupyter notebooks with the corresponding code.
- **04 Analysis:** holds the Data Sourcing Report.
- **05 Sent to Client:** contains the dashboard plan.

### Tableau Storyboard to showcase analysis results

Here's the [link](https://public.tableau.com/app/profile/giada.griso/viz/Doesmoneymakehappiness/Story1#1) to the storyboard created in Tableau. This storyboard doesn’t contain every step we took as part of the analysis — only those relevant to the final results.
