# Airbnb Exploratory Data Analysis
## Project Overview
This project presents an Exploratory Data Analysis(EDA) of the Airbnb NYC 2019 dataset. The objective of this analysis is to uncover meaningful business insights related to pricing, availability, room types, neighbourhood trends, and customer review activity across New York City.

The project focuses on transforming raw Airbnb listing data into actionable business insights using Python-based data analysis and visualization techniques. The analysis includes data understanding, data cleaning, univariate, bivariate, and multivariate analyses, and business-oriented insights from these analyses and visualizations. 

## Business Objective
The primary business objective is to analyze Airbnb listing behaviour in New York City and identify factors influencing pricing patterns, occupancy, demand, and customer engagement. 
The analysis aims to 
- Understand the pricing distribution across room types and neighbourhoods
- Identify high-demand market segments
- Analyze occupancy-related patterns using availability
- Detect opportunities for business growth
- Generate actionable insights for hosts and platform optimization

## Dataset information
- Dataset Name: Airbnb NYC 2019 Dataset
- Records: ~48000 Airbnb listings
- Features: Listing details, host information, pricing, reviews, availability, room types, neighbourhood data

## Tools and Technology Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Git and GitHub

## Key Analysis
- Univariate, Bivariate, and Multivariate Analysis
- Feature Engineering (Occupancy & Revenue Proxy)
- Data Cleaning and Outlier Handling

## Project Workflow
1. Data Understanding
   - Dataset overview
   - Shape and Structure analysis
   - Variable understanding
   - Missing value identification
   - Duplicate Value identification
2. Data Wrangling
   - Handling Missing Values
   - Handling duplicate values
   - Data type conversion
  
## Exploratory Data Analysis
### Univariate Analysis
- Price Distribution
- Room type distribution
- Availability trends
- Review activity
### Bivariate Analysis
- Price vs room type
- Price vs neighbourhood
- Availability vs reviews
-

### Multivariate Analysis
- Correlation heatmap
- Pair plot analysis
- Room type vs neighbourhood vs availability
- Heatmaps
- Revenue proxy analysis

## Key Insights
###1. Positive Growth Indicators
- Entire Homes command premium prices and show strong demand in major boroughs such as Manhattan and Brooklyn.
- Manhattan and Brooklyn demonstrate high revenue potential due to strong pricing power and customer engagement
- Mid-range accommodation maintains better review activity and high occupancy than high-priced listings.
- Listings with high review activity tend to exhibit lower availability, supporting higher occupancy.
- Multiple room types with a wider range of prices serve a diverse customer segment.

###2. Negative Growth Indicators
- Manhattan and Brooklyn are highly concentrated in premium listings which increases the host competition and reduce booking frequency.
- Very high-priced listings may receive fewer bookings.
- Listings with high availability indicate less demand and low occupancy.
- A higher minimum night requirement restrains bookings for short-term travellers.
- A limited number of listings in Queens, Bronx, and Staten Island may reduce platform expansion opportunities.

## Visualizations Included
The project contains around 20 meaningful visualizations, including:
  - Histograms
  - Count Plots
  - Scatter Plots
  - Heatmaps
  - Boxplots
  - Pair plots
  - Revenue Analysis charts
Each visualization follows
- Purpose of the chart
- Key insights
- Positive and/or negative business insights

## Project Structure
airbnb_EDA/
│
├── data/
│   └── Airbnb NYC 2019.csv
│
├── notebooks/
│   └── Airbnb_Booking_Analysis_EDA.ipynb
│
├── visuals/
│
└── README.md

## How to Run the Project
### Clone Repository
git clone https://github.com/nibedita-26/airbnb_EDA.git
### Open Notebook
Open the notebook using:
- Google Colab
- Jupyter Notebook
### Install Dependencies
pip install pandas numpy matplotlib seaborn
### Run the Notebook
Execute all cells sequencially

The dataset is loaded directly from the GitHub repository using the raw datset URL for reproducibility.

## Conclusion
This project demonstrates how Exploratory Data Analysis(EDA) can be used to extract actionable insights from marketplace data. The findings highlight the importance of pricing optimization, occupancy management, customer engagement and geographic segmentation in improving the Airbnb marketplace performance.

The project also showcases practical skills in:
- Data cleaning
- Business anslysis
- Data visualization

## Author
Nibedita Sahoo




