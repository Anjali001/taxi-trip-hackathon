# taxi-trip-hackathon
https://machinehack.com/hackathons/iiit_nr_taxi_trip_fare_prediction_challenge/overview

Train: 35000 rows x 20 columns 
Test: 15000 rows x 19 columns


Data description:
Trip_distance: The elapsed trip distance in miles reported by the taximeter.
Rate_code: The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride
Storeandfwd_flag: This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip
Payment_type: A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip
Fare_amount: The time-and-distance fare calculated by the meter
Extra: Miscellaneous extras and surcharges.
Mta_tax: $0.50 MTA tax that is automatically triggered based on the metered rate in use.
Tip_amount: Tip amount credited to the driver for credit card transactions.
Tolls_amount: Total amount of all tolls paid in the trip.
Imp_surcharge: $0.30 extra charges added automatically to all rides
Total_amount: The total amount charged to passengers. Does not include cash tips
Pickuplocationid: TLC Taxi Zone in which the taximeter was engaged
Dropofflocationid: TLC Taxi Zone in which the taximeter was disengaged
Year: The year in which the taxi trip was taken.
Month: The month on which the taxi trip was taken.
Day: The day on which the taxi trip was taken.
Day_of_week: The day of the week on which the taxi trip was taken
Hour_of_day: Used to determine the hour of the day in 24 hours format
Trip_duration: The total duration of the trip in seconds
calculated_total_amount: The total amount the customer has to pay for the taxi.
