The data on ridesharing in the year 2022 in the city of Chicago, which can be found here:
https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips/m6dm-c72p/data

The dataset consists of the following columns:
1. Trip ID: A unique identifier for the trip.
2. Trip Start Timestamp: When the trip started, rounded to the nearest 15 minutes.
3. Trip End Timestamp: When the trip ended, rounded to the nearest 15 minutes.
4. Trip Seconds: Time of the trip in seconds.
5. Trip Miles: Distance of the trip in miles.
6. Pickup Census Tract: The Census Tract where the trip began. This column often will be blank for locations outside Chicago.
7. Dropoff Census Tract: The Census Tract where the trip ended. This column often will be blank for locations outside Chicago.
8. Pickup Community Area: The Community Area where the trip began. This column will be blank for locations outside Chicago.
9. Dropoff Community Area: The Community Area where the trip ended. This column will be blank for locations outside Chicago.
10. Fare: The fare for the trip, rounded to the nearest $2.50.
11. Tip: The tip for the trip, rounded to the nearest $1.00. Cash tips will not be recorded.
12. Additional Charges: The taxes, fees, and any other charges for the trip.
13. Trip Total: Total cost of the trip. This is calculated as the total of the previous columns, including rounding.
14. Shared Trip Authorized: Whether the customer agreed to a shared trip with another customer, regardless of whether the customer was actually matched for a shared trip.
15. Trips Pooled: If customers were matched for a shared trip, how many trips, including this one, were pooled. All customer trips from the time the vehicle was empty until it was empty again contribute to this count, even if some customers were never present in the vehicle at the same time. Each trip making up the overall shared trip will have a separate record in this dataset, with the same value in this column.
16. Pickup Centroid Latitude: The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
17. Pickup Centroid Longitude: The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
18. Pickup Centroid Location: The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
19. Dropoff Centroid Latitude: The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
20. Dropoff Centroid Longitude: The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
21. Dropoff Centroid Location: The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
