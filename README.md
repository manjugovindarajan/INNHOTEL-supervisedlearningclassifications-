# INNHOTEL-supervisedlearningclassifications-

## context
A significant number of hotel bookings are called-off due to cancellations or no-shows for various reasons.Such revenue-diminishing losses are particularly high on last-minute cancellations.

The cancellation of bookings impact a hotel on various fronts:

Loss of resources (revenue) when the hotel cannot resell the room.
Additional costs of distribution channels by increasing commissions or paying for publicity to help sell these rooms.
Lowering prices last minute, so the hotel can resell a room, resulting in reducing the profit margin.
Human resources to make arrangements for the guests.

## Objective
INN Hotels Group has a chain of hotels in Portugal, they are facing problems with high number of booking cancellations. Analyze data provided to find which factors have a high influence on booking cancellations, build a predictive model that can predict which booking is going to be canceled in advance, and help in formulating profitable policies for cancellations and refunds.

## Data Description

# Booking_ID: unique identifier of each booking
# no_of_adults: Number of adults
no_of_children: Number of Children
no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at hotel
no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at hotel
type_of_meal_plan: Type of meal plan booked by customer:
Not Selected – No meal plan selected
Meal Plan 1 – Breakfast
Meal Plan 2 – Half board (breakfast and one other meal)
Meal Plan 3 – Full board (breakfast, lunch, and dinner)
required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
room_type_reserved: Type of room reserved by customer. The values are ciphered (encoded) by INN Hotels.
lead_time: Number of days between the date of booking and the arrival date
arrival_year: Year of arrival date
arrival_month: Month of arrival date
arrival_date: Date of the month
market_segment_type: Market segment designation.
repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking
avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
booking_status: Flag indicating if the booking was canceled or not.
