# Data Exploration and Visualization of Car Sales on ebay ! [image-2.png](attachment:image-2.png)
[Source of Picture]

## Mid-term-Project March 2023 For the Ironhack, Berlin
## By Evans and Festus
## Dataset: Auto Sales ebay Germany Random 50k!
## Using Python and Business Intelligence


##  Table of Contents
1. [Description of the dataset](#2)

1. [Goals of the project¶](#3)

2. [Data Gathering and Methodology](#4)
   
3. [Data Analytics and Conclusion](#5) 
   
4. [References](#6)

# Goals of the project

## **Do data cleaning:**
    - identify and remove where applicable the outliers, missing data, duplicates, columns to drop
    - decide on the interesting features to keep
## **Carry out EDA and provide dataset summary:** 
    - Mean prices
    - max prices 
    - mode i.e most frequent car model
## **Investigate the underlying patterns and data structure:** 
    - Commonly listed brands
    - distribution of brands?
    - price variation between: 
        - relatively newer cars and older cars
        - fuel type
        - transmission type
        - car brands
        - milage of the car
        - unrepaired_damage
    - correlations between the numerical features:
        - Price
        - power_ps 
        - milage in Km
## **Assess the impact of Ab Testing:**
    - Viewership of the cars
## **Business Inteligence - Build a Tableau Dashboard:**
    - Are their any meaningful KPIs?
    - show impact of AB testing of such KPI.
    - comparing the transmission types, fuel types brands and prices
    - filter by top 3 model, brand, fuel types etc 
    - show an important insight/pattern about the sale of cars
    - design a clean and well readable charts that have titles, labels etc. 
## **Reveal the bigger picture:** 
     - Relate the data to the opportunity for sellers and buyers.
     - Recommnedation about the AB testing whether to launch or not to launch it.
     - Conclusion.
     

#  Description of the dataset
The dataset used to complete this project was scraped in 2016 from ebay-Kleinanzeigan (Germany).
The data was made available publicly on the Kaggle by the user 'orgesleka'. 

The dataset contains seventeen columns with over 37 thousand rows of private used car listings for sale; 
the column headings and their descriptions are listed here:

**date_crawled:** When an ad was first crawled; all field-values are taken from this date.
name: Name of the car.

**price_EUR:** Listed price for the car.

**ab_test:** Whether the listing is included in an A/B test.

**vehicle_type:** The vehicle type.

**registration_year:** The year the car was first registered.

**transmission:** The transmission type.

**power_ps:** The power of the car in PS (PferdStarkeis, similar to horse power).

**model:** Car model name.

**odometer_km:** approximate kilometers the car has driven.

**registration_month:** The month the car was first registered.

**fuel_type:** Vehicle fuel type.

**brand:** Car brand.

**unrepaired_damage:** If the car has damage which is not yet repaired.

**date_created:** The date the eBay listing was created.

**postal_code:** The postal code for the location of the vehicle.

**last_seen_online:** When the crawler saw this ad last online.



# Data Gathering and Methodology

1. Selected Python libraries will be used for EDA and for data wrangling. 
2. Dataset is publicly available in [kaggle](https://www.kaggle.com/datasets/sijovm/used-cars-data-from-ebay-kleinanzeigen) in the format comma-separated value (CSV) file, a tabular format contained in [a zipped file](https://www.kaggle.com/datasets/sijovm/used-cars-data-from-ebay-kleinanzeigen/download?datasetVersionNumber=1)

3. Tableau will be used for visualizations and Dashboard design. 

# Data Analytics and Conclusion


#  References
https://www.kaggle.com/datasets/shaunoilund/auto-sales-ebay-germany-random-50k-cleaned
