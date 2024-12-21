# FALL2024TIDYVERSE

yli1048
## Tidyverse
### The tidyverse is a collection of R packages designed for data science. It provides a cohesive framework for data manipulation, visualization, and analysis. The core packages within the tidyverse include:

#### 1. ggplot2: 
For data visualization, allowing users to create complex graphics with a simple and consistent syntax.

#### 2. dplyr: 
For data manipulation, offering a set of verbs for data frame operations like filtering, summarizing, and joining.

#### 3. tidyr: 
For tidying data, helping to reshape and organize data sets for easier analysis.

#### 4. readr: 
For reading and writing data, facilitating the import and export of data from various formats.

#### 5. purrr: 
For functional programming, providing tools for working with lists and functions in a more efficient way.

#### 6. tibble: 
A modern take on data frames, providing a simpler and more user-friendly alternative.

#### 7. stringr: 
For string manipulation, making it easier to work with text data.

#### 8. forcats: 
For working with categorical data, allowing users to manage and reorder factor levels.


We will demonstrate examples of using the Tidyverse library to clean data and create visualizations.

The Tidyverse is an incredibly valuable collection of packages designed to enhance data manipulation and visualization. It includes several core packages that provide powerful tools for data analysis, making it easier to clean, transform, and graphically represent data. The examples provided here illustrate just a fraction of the extensive functionalities that Tidyverse offers, showcasing its versatility and usefulness in data science workflows.
=======

Andreina - Data set exploration with tidyverse. The data set was from fivethirtyeight, on alcohol consumptions in different countries from 2010. 
Article: https://fivethirtyeight.com/features/dear-mona-followup-where-do-people-drink-the-most-beer-wine-and-spirits/
Extended by Marco Castro to include  `group_by`, `mutate`, `ungroup` and `separate_wider_delim`
Data source: https://github.com/fivethirtyeight/data/tree/master/alcohol-consumption
=======

Brandon Chung - Sample Vignette of TidyVerse package: dplyr. Examples of the functions Mutate(), Select(), Filter(), and Summarise(). 
Data source: https://www.kaggle.com/datasets/aayushmishra1512/faang-complete-stock-data?select=Google.csv
=======

Chi Hang (Philip) Cheung
Data source: https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset
TidyVerse function: examples of string_detect and ggplot2
Extended by Inna Yedzinovich and Yanyi Li
=======

Stephanie Chiang - `SC_vignette.md`
Vignette: Dplyr's `rowwise()` and Custom Functions
Data source: Using FiveThirtyEight's [Unisex Names dataset](https://github.com/fivethirtyeight/data/tree/master/unisex-names)
=======

Marco Castro
Sample Vignette on map, map_df, map2, and pmap functions
Package: Purrr
Data source: https://www.kaggle.com/datasets/bhadramohit/agriculture-and-farming-dataset
File: MC-Purrr-Vignette.Rmd
Extended by Brandon Chung (modify and modify_if)
=======

Nakesha Fray: Vignette of tidyverse using readr, tidy, dplyr, and ggplot. Data Source: Where People Go To Check The Weather by Walt Hickey: https://fivethirtyeight.com/features/weather-forecast-news-app-habits/

=======
Ariba Mandavia: This vignette provides a comprehensive example of using dplyr for data manipulation and ggplot2 for data visualization with a real-world dataset!
Data Source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
Extended by Shri Tripathi
=======


Erick Hadi
Tidyverse: How to do simple data analysis using Tidyverse.
Data: https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset/data 
=======

Shri Tripathi
Data source: https://github.com/Shriyanshh/Week-9-TidyVerse-GitHub-CREATE-assignment/blob/main/HappinessAlcoholConsumption.csv
https://www.kaggle.com/datasets/marcospessotto/happiness-and-alcohol-consumption
TidyVerse function: dplyr, tidyr, ggplot2
=======

Ariba Mandavia: 
## Extended Examples

- Extended Chi Hang(Philip) Cheung's example to include:
  - A summary and visualization of phone generations extracted from `Device.Model`.
  - A keyword-based analysis and visualization of devices containing "Pixel" or "Galaxy".
=======


Ying Fang Lee: 
## Extended Examples
- Extended Brandon Chung Dplyr Vignette's example to include:
  - ggplot to visualize the trend with a scatter plot
=======



Andreina Arias

Extended on Stephanie Chang code, by using tidyverse functions to find the max and min used name.
