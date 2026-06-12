# Cyclistic Bike Share Analysis

## Project Overview

This project analyzes 5.6 million bike-share trips from Cyclistic, a bike-sharing company operating in Chicago. The objective is to understand the behavioral differences between annual members and casual riders and provide data-driven recommendations to increase membership conversion.

---

## Business Task

Cyclistic's marketing team aims to increase the number of annual members because they generate more stable and long-term revenue.

This project answers the following business question:

**How can Cyclistic convert casual riders into annual members?**

---

## Dataset

### Dataset Summary

* Records: 5,622,419 trips
* Columns: 11
* Period: January – December

### Key Features

* Ride ID
* Bike Type
* Rider Type (Member / Casual)
* Start Time
* End Time
* Start Station
* End Station
* Start Coordinates
* End Coordinates

---

## Tools Used

* Python (Pandas, NumPy)
* SQL
* Excel
* Power BI

---

## Data Cleaning Process

The following data preparation steps were performed:

* Removed duplicate records
* Checked missing values
* Standardized date and time formats
* Created new variables:

  * Ride Duration
  * Day of Week
  * Month
  * Hour
* Validated data consistency before analysis

---

## Exploratory Data Analysis (EDA)

The analysis focused on:

* Trip volume by rider type
* Ride duration comparison
* Weekly riding patterns
* Hourly riding trends
* Bike type preferences
* Monthly and seasonal demand trends

---

## Dashboard Preview

<img width="1343" height="707" alt="Cyclistic Dashboard" src="https://github.com/user-attachments/assets/667d0571-da3b-48e1-ab60-b595877bc349" />

### Dashboard Highlights

* Total Trips: 5.62 Million
* Members: 63.38%
* Casual Riders: 36.62%
* Most Popular Bike Type: Electric Bike
* Peak Demand Season: Summer & Early Fall

---

## Key Findings

### 1. Members Generate More Trips

Members account for approximately 63% of all rides, indicating a higher level of engagement and service usage.

### 2. Casual Riders Prefer Weekends

Casual riders record the highest number of trips on Saturdays and Sundays, suggesting recreational and leisure-oriented usage.

### 3. Casual Riders Have Longer Ride Durations

The average trip duration of casual riders is significantly higher than that of members, indicating that casual riders often use the service for longer journeys.

### 4. Different Peak Usage Hours

* Members peak during commuting hours (morning and evening rush hours).
* Casual riders peak in the afternoon.

### 5. Electric Bikes Are the Most Popular

Electric bikes represent the largest share of total rides and are preferred by both customer groups.

### 6. Strong Seasonal Demand

Demand increases substantially during summer and early fall and decreases during winter months.

---

## Business Recommendations

### 1. Target High-Value Casual Riders

Identify casual riders with high ride frequency and long ride durations and offer personalized membership discounts.

### 2. Launch Weekend Membership Campaigns

Promote membership plans during weekends when casual rider activity is at its highest.

### 3. Expand Electric Bike Availability

Increase the number of electric bikes at high-demand stations to improve customer experience.

### 4. Develop Corporate Membership Programs

Partner with companies and organizations to provide membership plans for employees and encourage commuting by bike.

### 5. Increase Seasonal Marketing Efforts

Run promotional campaigns during summer and early fall to maximize membership conversions.

---

## Project Files

### Power BI Dashboard (.pbix)

Download the Power BI dashboard file:

[Download PBIX File](https://drive.google.com/file/d/1I21GV4eTteu-NLOLdu1s0BzqwwcJXkAy/view?usp=drive_link)

### Dataset

Download the cleaned dataset:

[Download Dataset](https://drive.google.com/file/d/14Pw7kLcOWjXs-kzRhS0sE0m1Yp_aIYT_/view?usp=drive_link)

---

## Project Structure

```text
cyclistic-bike-share-analysis/
│
├── README.md
│
├── Python/
│   └── EDA_using_Python.ipynb
│
├── Dashboard/
│   └── dashboard.pbix
│
├── Presentation/
│   └── Cyclistic_Presentation.pptx
│
├── Documents/
│   ├── Business_Task.pdf
│   └── Project_Summary.pdf
│
└── Data/
    └── cleaned_dataset.csv
```

---

## Conclusion

This analysis reveals clear behavioral differences between annual members and casual riders. Members use the service more frequently and primarily for commuting purposes, while casual riders tend to ride longer and prefer weekends.

By targeting high-potential casual riders, expanding electric bike availability, and implementing strategic membership campaigns, Cyclistic can increase annual membership conversion and support long-term business growth.
