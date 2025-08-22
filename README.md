Team Project 1: The Urban Sprawl Enigma: A Data Detective Mission
================
Econ 122
August 22, 2025

### The Urban Sprawl Enigma: A Data Detective Mission

**Project Description:**

Welcome, Urban Analysts! 🕵️ Your mission is to form a team and
investigate a classic city planning mystery: **the relationship between
urban sprawl and air quality.** You will act as data detectives, using
the tools and techniques you’ve learned to determine which aspects of a
city’s growth have the most significant impact on its environmental
health. Your goal is to uncover the truth hidden within the data and
present your findings.

------------------------------------------------------------------------

### Course Concepts to Apply

This project is a perfect opportunity to apply the foundational skills
from Part I of the course:

- **Week 1: Foundations & Reproducibility:** You will use **R** and **R
  Markdown** to create a single, reproducible report that documents your
  entire investigation. All your code and analysis should be contained
  within this dynamic document, and you will use **Git and GitHub** to
  manage your project and collaborate with your team.

- **Week 2: Data Wrangling:** You’ll face the challenge of combining
  multiple, disparate datasets. You will use the **`dplyr`** and
  **`tidyr`** packages to filter, select, and join different data
  sources to create a unified data frame for your analysis.

- **Week 3: Exploratory Data Analysis (EDA):** The key to this project
  is asking the right questions. You will use **`ggplot2`** to create
  visualizations that explore the relationships between city growth
  metrics (like population density, housing prices, or new construction)
  and air quality metrics (like AQI or specific pollutant levels).

- **Week 4: Advanced Data Wrangling & Feature Engineering:** You will
  likely need to handle time-series data, extracting months or years
  from dates to analyze trends. You may also need to create new
  variables, such as a “commuter ratio” (e.g., number of registered cars
  per household), to better explain your findings.

------------------------------------------------------------------------

#### Dataset Summary

- **`environmental_data.csv`** This dataset is a time-series record of
  the city’s Air Quality Index (AQI) and other pollutant levels.
- **`transporatation_data.csv`:** This data covers key metrics like
  public transit ridership and the number of registered vehicles.
- **`population_data.csv`** This dataset contains information on
  population density and median household income, broken down by
  district.
- **`temperature_data.csv`** This dataset tracks temperature over time.
- **`housing_data.csv`:** This dataset tracks new housing starts and
  average housing prices over time.

------------------------------------------------------------------------

##### Importing CSV Files with the `readr` Package

The `readr` package is highly optimized and makes intelligent guesses
about column types, making it a great choice for data loading.

``` r
# First, ensure the package is installed.
# Uncomment the line below and run it once to install 'readr'.
# install.packages("readr")

# Load the 'readr' package into your R session.
library(readr)

# Use the 'read_csv' function to import the data.
# The file "your_file_name.csv" must be in your current working directory,
# or you must provide the full file path.
data_readr <- read_csv("your_file_name.csv")
```

------------------------------------------------------------------------

### Team Deliverables

Your team will be responsible for submitting the following:

**R Markdown Report:** A comprehensive, reproducible report that
documents your entire investigation process from data cleaning to final
insights. The report should tell the story of your data. I will be
grading not only on correctness of the analysis but by how easily it is
to digest

1.  `TP1.Rmd` - Your `Rmd` file that has all the code
2.  `TP1.md` - The report file that displays all output and figures

Here are some guidelines for the report

- No code visible
- All figures and tables properly labeled
- An explanation of your analysis that reads like a report and not lab
  notes

------------------------------------------------------------------------

### Guiding Questions for Your Investigation

To get started, consider these questions:

- What is the overall trend of air quality in the city over time?

- What is the connection between air quality and the other variables on
  the data set?

- Can you calculate the correlation between the variables to quantify
  the relationship?

- Is there a logical story that explains the trends of air quality over
  time?

Good luck, and remember: The data is out there, waiting to tell its
story! 🔍
