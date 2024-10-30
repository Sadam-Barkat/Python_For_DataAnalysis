# Project: Hospitality Analysis

## Overview
The **Hospitality Analysis** project aims to analyze various aspects of hospitality management, including bookings, room availability, and hostel dimensions. This project utilizes multiple datasets to derive insights that can help improve operational efficiency and customer satisfaction in the hospitality industry.

## Datasets
This project includes the following datasets:

1. **dim_dare.csv**: Contains data on different types of dormitories available in the hospitality sector.
2. **dim_hostel.csv**: Provides information about hostels, including location, amenities, and pricing.
3. **dim_rooms.csv**: Details the room types available, their configurations, and associated costs.
4. **fact_agg_booking.csv**: Aggregated data on bookings made over a specific period, summarizing key metrics such as total bookings and revenue.
5. **fact_bookings.csv**: A detailed record of individual bookings, including customer information, room types, and dates.
6. **new_data_august.csv**: A recent dataset that includes updated information about bookings and room availability for the month of August.

## Project Structure
Project_Hospitality_Analysis/ │ ├── datasets/ │ ├── dim_dare.csv │ ├── dim_hostel.csv │ ├── dim_rooms.csv │ ├── fact_agg_booking.csv │ ├── fact_bookings.csv │ └── new_data_august.csv │ └── analysis/ ├── data_preprocessing.py ├── exploratory_analysis.py └── visualization.py

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sadam-Barkat/4-Project_Hospitality_Analysis.git
   cd Project_Hospitality_Analysis
