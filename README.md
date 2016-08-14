# HotelBookingPrediction
Expedia is one of the largest travel booking websites on the internet

1. The goal of this project is to predict the booking outcome (hotel reservation) for a user event, based on the attributes associated with that user
2. One can contextualize customer data and predict the likelihood, a user will book a hotel or not 
3. The data used in this project is a random selection from Expedia and is not representative of the overall statistics
4. Some initial conclusions can be made from Exploratory data analysis
5. Used Expedia dataset from www.kaggle.com repository - https://www.kaggle.com/c/expedia-hotel-recommendations
6. The dataset contains 24 attributes and we have chosen 18 of them - date_time,  posa_continent, user_location_country, user_location_region, user_location_city, orig_destination_distance, is_mobile, is_package, channel, srch_adults_cnt, srch_children_cnt, srch_rm_cnt, srch_destination_type_id, is_booking, hotel_continent, hotel_country,  hotel_market, hotel_cluster 
7. The 3 algorithms used are - KNN, CART, C5.0


Few Conclusions from the application of the above algorithms are listed below- 
1. The most significant attributes are is_mobile, hotel_cluster, date_time and origin_destination_distance 
2. Most of the bookings are done for 2 Star Hotels
3. Most of the users who booked the hotel have not done through mobile
4. Least number of bookings are done in Fall season



