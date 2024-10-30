# Datasets for Project: Hospitality Analysis

This folder contains various datasets used for analyzing different aspects of the hospitality industry. Each dataset serves a specific purpose in understanding operations, bookings, and room availability. Below is a detailed description of each file included in this directory.

## Datasets

### 1. `dim_dare.csv`
- **Description**: This dataset provides information about different types of dormitories available in the hospitality sector. It includes attributes such as dormitory type, capacity, and facilities offered.
- **Key Columns**:
  - `dormitory_id`: Unique identifier for each dormitory.
  - `dormitory_type`: Type of dormitory (e.g., mixed, female, male).
  - `capacity`: Maximum number of guests that can be accommodated.

### 2. `dim_hostel.csv`
- **Description**: Contains detailed information about hostels, including location, amenities, pricing, and ratings.
- **Key Columns**:
  - `hostel_id`: Unique identifier for each hostel.
  - `hostel_name`: Name of the hostel.
  - `location`: Geographic location of the hostel.
  - `price_per_night`: Average price per night for a bed.
  - `amenities`: List of amenities provided by the hostel.

### 3. `dim_rooms.csv`
- **Description**: This dataset outlines the different room types available in the hospitality establishment, including configurations and associated costs.
- **Key Columns**:
  - `room_id`: Unique identifier for each room type.
  - `room_type`: Type of room (e.g., single, double, suite).
  - `price`: Price per night for the room.

### 4. `fact_agg_booking.csv`
- **Description**: Aggregated data on bookings made over a specific period, summarizing key metrics such as total bookings, revenue, and occupancy rates.
- **Key Columns**:
  - `booking_date`: Date of booking.
  - `total_bookings`: Total number of bookings made.
  - `total_revenue`: Total revenue generated from bookings.

### 5. `fact_bookings.csv`
- **Description**: A detailed record of individual bookings, including customer information, room types, and booking dates.
- **Key Columns**:
  - `booking_id`: Unique identifier for each booking.
  - `customer_id`: Unique identifier for each customer.
  - `room_id`: Identifier for the booked room.
  - `check_in_date`: Check-in date for the booking.
  - `check_out_date`: Check-out date for the booking.

### 6. `new_data_august.csv`
- **Description**: This is a recent dataset that includes updated information about bookings and room availability for the month of August. It helps to analyze current trends and customer behavior.
- **Key Columns**:
  - `booking_id`: Unique identifier for each booking.
  - `room_id`: Identifier for the booked room.
  - `booking_date`: Date when the booking was made.
  - `availability_status`: Status indicating whether the room is available or booked.

## Usage
These datasets can be utilized for various analyses, including but not limited to:
- Exploring booking trends over time.
- Understanding customer preferences and behaviors.
- Analyzing room occupancy rates.
- Evaluating the performance of different hostels and dormitories.

Feel free to reach out if you have any questions or require further information regarding the datasets!
