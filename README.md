# Madrid-District-EDA
Exploratory Data Analysis (EDA) of Madrid's urban zoning and demographics using Python (Pandas &amp; Matplotlib)
# Madrid Airbnb Data Analysis 🏠

## Project Overview
This project performs a statistical analysis of the Airbnb market in Madrid. The goal is to understand the drivers behind listing prices, with a specific focus on location (distance to center/airport) and property amenities.

By merging and processing multiple datasets (property details, location, host info, and reviews), this analysis provides actionable insights into the short-term rental market dynamics in the Spanish capital.

*Developed as a Capstone Project for the Data Analytics program at **Nuclio Digital School**.*

## Business & Analytical Questions
* **Location Value:** How does the distance to *Puerta del Sol* (city center) impact the price per guest? Is there a specific radius where prices drop significantly?
* **Amenity Impact:** Do essential amenities like Air Conditioning or WiFi correlate with higher listing prices?
* **Host Status:** Does being a "Superhost" command a price premium, or is it purely a reputation metric?
* **Airport Proximity:** How do prices fluctuate based on distance to Adolfo Suárez Madrid-Barajas Airport?

## Methodology
The workflow follows a structured Data Analytics pipeline:

1.  **Data Integration:** Merged 5 disjointed CSV datasets (`property`, `location`, `host`, `reviews`, `conditions`) into a single master dataframe.
2.  **Data Cleaning:**
    * Handled missing values and standardized column formats.
    * Removed pricing outliers to ensure robust statistical averages.
3.  **Feature Engineering:** Created categorical variables for distance ranges (e.g., "0-5km", "5-10km") to facilitate segmented analysis.
4.  **Exploratory Data Analysis (EDA):** Used Matplotlib and Seaborn to visualize distributions and correlations.

## Key Insights
* **The "Center Premium":** A strong negative correlation was observed between distance to the city center and price. The highest value listings are concentrated within a **2km radius** of Puerta del Sol.
* **Connectivity Standard:** Listings with WiFi showed a distinct price distribution, suggesting connectivity is a baseline expectation for competitive pricing.
* **Airport Influence:** Properties very close to the airport show specific pricing dynamics, likely catering to a different traveler segment (short layovers) compared to city tourists.

## Repository Structure
```text
madrid-urban-analysis/
│
├── data/                  # Contains the 5 raw CSV datasets
├── airbnb_analysis.ipynb  # Main Jupyter Notebook with code & visualizations
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
