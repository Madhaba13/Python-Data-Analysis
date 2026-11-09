# NYC Airbnb Data Analysis -- Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a New York City
Airbnb listings dataset using Python. The goal is to understand the
short-term rental market by exploring listing prices, room types,
neighbourhoods, host activity, customer reviews, and property
availability.

The analysis focuses on identifying patterns and potential business
insights that can help hosts, property managers, and business
stakeholders make more informed pricing and listing decisions.

## Business Problem

Airbnb hosts and property managers need to understand how location, room
type, reviews, and availability relate to listing prices and market
demand.

This project explores questions such as:

-   How are Airbnb listing prices distributed?
-   Which room types are most common?
-   How do listing prices vary across NYC boroughs and neighbourhoods?
-   Which areas have the highest number of listings?
-   What relationship exists between price and customer reviews?
-   How does listing availability vary across room types and locations?
-   Are there unusually high or low prices that may affect analysis?

## Project Objectives

-   Understand the structure and quality of the dataset.
-   Perform data cleaning and handle missing values.
-   Explore numerical and categorical variables.
-   Identify price patterns and outliers.
-   Compare listings across neighbourhoods and room types.
-   Examine review activity and listing availability.
-   Present findings that may support business decisions.

## Dataset Information

The dataset contains **20,770 rows and 22 columns**.

It includes information about Airbnb listings across the five New York
City boroughs:

-   Manhattan
-   Brooklyn
-   Queens
-   Bronx
-   Staten Island

### Important Columns

  -----------------------------------------------------------------------
  Column                              Description
  ----------------------------------- -----------------------------------
  `id`                                Unique listing identifier

  `name`                              Listing name

  `host_id`                           Host identifier

  `host_name`                         Host name

  `neighbourhood_group`               NYC borough

  `neighbourhood`                     Neighbourhood within the borough

  `latitude`, `longitude`             Listing location coordinates

  `room_type`                         Type of accommodation

  `price`                             Listing price

  `minimum_nights`                    Minimum nights required

  `number_of_reviews`                 Total number of reviews

  `last_review`                       Date of the most recent review

  `reviews_per_month`                 Average reviews per month

  `calculated_host_listings_count`    Number of listings associated with
                                      the host

  `availability_365`                  Available days in a year

  `number_of_reviews_ltm`             Reviews in the last twelve months

  `rating`                            Listing rating field

  `bedrooms`, `beds`, `baths`         Property accommodation details
  -----------------------------------------------------------------------

## Technologies and Libraries

-   **Python** -- Data analysis
-   **Pandas** -- Data loading, manipulation, and cleaning
-   **NumPy** -- Numerical operations
-   **Matplotlib** -- Data visualization
-   **Seaborn** -- Statistical visualization
-   **Jupyter Notebook** -- Interactive analysis

## Project Workflow

1.  **Data Loading:** Import the dataset using Pandas.
2.  **Initial Inspection:** Review dataset dimensions, columns, data
    types, and sample records.
3.  **Data Cleaning:** Check missing values, duplicates, incorrect data
    types, and inconsistent values.
4.  **Statistical Analysis:** Use descriptive statistics to understand
    numerical variables.
5.  **Univariate Analysis:** Explore individual variables such as price,
    room type, and availability.
6.  **Bivariate Analysis:** Compare variables such as price by room
    type, borough, and review activity.
7.  **Outlier Analysis:** Investigate extreme values, particularly in
    listing prices.
8.  **Data Visualization:** Use histograms, count plots, box plots, and
    other charts to communicate patterns.
9.  **Business Insights:** Summarize findings and potential business
    implications.

## Initial Dataset Observations

-   The dataset contains 20,770 records and 22 columns.
-   It covers the five NYC boroughs.
-   Entire home/apartment and private room listings make up most of the
    records.
-   The median listed price is 125, and the 75th percentile is 199 (in
    the dataset's price units).
-   Some price values are extremely high compared with the typical
    listing price, so outliers should be investigated before drawing
    conclusions.
-   Some records contain missing values, including missing prices and
    location-related fields.

*These are initial observations from the raw dataset. Further analysis
and validation are required before making business conclusions. The
dataset's currency and collection date should be confirmed from its
original source.*

## Key Business Questions to Explore

-   Which borough has the largest number of Airbnb listings?
-   Which room type is most popular among hosts?
-   Which neighbourhoods have higher listing prices?
-   How does the price distribution differ between room types?
-   Do listings with more reviews show different pricing patterns?
-   Which hosts manage the largest number of listings?
-   Which listings have the highest availability?
-   What factors appear to be associated with listing prices?

## Potential Business Value

The analysis can help:

-   **Hosts:** Understand local competition and evaluate pricing
    strategies.
-   **Property managers:** Compare listing performance across
    neighbourhoods.
-   **Business stakeholders:** Identify market patterns and
    accommodation trends.
-   **Analysts:** Use data-driven visualizations to communicate
    findings.

Note: This is exploratory analysis. Relationships observed in the
dataset do not necessarily establish causation or prove actual booking
demand or revenue.

## How to Run the Project

### 1. Clone the repository

``` bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

### 2. Install the required libraries

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

``` bash
jupyter notebook
```

### 4. Open the notebook

Open the project `.ipynb` file and run the cells in sequence.

## Suggested Repository Structure

``` text
NYC-Airbnb-EDA/
│
├── datasets.csv
├── analysis.ipynb
├── README.md
```

## Conclusion

This project demonstrates an end-to-end exploratory data analysis
workflow using Python. By examining listing prices, room types,
locations, reviews, and availability, the analysis aims to uncover
useful patterns in the New York City Airbnb market and translate data
into meaningful business insights.

## Author

**Rudra Madhaba Dalabehera**

-   GitHub: [Add your GitHub profile link](https://github.com/)

------------------------------------------------------------------------

If you find this project useful, feel free to explore the notebook and
share your feedback.
