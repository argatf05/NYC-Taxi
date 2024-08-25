# NYC-Taxi
# **Background (Latar Belakang)**
Congestion surcharges for taxis in the Manhattan borough were implemented back in 2019 (https://www.cbsnews.com/newyork/news/for-hire-congestion-pricing/). This has sparked debate among the government and taxi users.

Effective congestion pricing is crucial for the long-term sustainability of urban transportation systems. The congestion surcharges aim to reduce carbon emissions, traffic, and encourage the use of public transportation.

However, the New York Taxi Workers Alliance claims that the surcharges will severely impact drivers and medallion owners. On the other hand, ride-share apps such as Uber and Lyft claim to support the initiative. They said it enables fairer practices since taxi users also contribute to the congestion occurring in Manhattan. This initiative has also received some support from taxi passengers, who have alternative transportation modes such as the subway.

Therefore, is the implementation of the congestion surcharge already fair and beneficial?

---
# **Problem Statement (Rumusan Masalah)**
1. How has the congestion surcharge been applied throughout Manhattan? (Bagaimana pemerataan implementasi *congestion surcharge* di Manhattan?)
2.  How do customers behave towards the implementation of the congestion surcharge? (Bagaimana *customer behavior* terhadap penerapan congestion surcharge?)
3. What are the potential impacts of a fairer congestion surcharge implementation? (Apa potensi dampak dari penerapan *congestion surcharge* yang lebih merata?)

# **Section**
This project consists of Data Understanding, Data Cleaning, and Exploratory Data Analysis

# **Data Dictionary**
|Feature | Description |
|---- | ---- |
| VendorID | A code that differentiates the provider of the Livery Payment and Enabling Platform (LPEP), with code "1" for Creative Mobile Technologies, LLC and code "2" for VeriFone Inc.|
| lpep_pickup_datetime | Contains the date and time when the trip begins|
| lpep_dropoff_datetime | Contains the date and time when the trip ends|
| Store_and_fwd_flag | Indicates whether the trip data is first stored locally on the vehicle's memory before being sent to the vendor (Y = Store and Forward trip) or not (N = Not a store and forward trip)|
| RateCodeID | Contains a code that identifies the type of fare for each trip, determined at the end of each trip: 1 = Standard rate, 2 = JFK (fare to or from John F. Kennedy International Airport), 3 = Newark (fare to or from Newark Liberty International Airport), 4 = Nassau or Westchester (fare to Nassau County or Westchester County), 5 = Negotiated fare, 6 = Group ride |
| PULocationID | Contains a code that identifies the location (TLC Taxi Zone code) where the trip starts |
| DOLocationID | Contains a code that identifies the location (TLC Taxi Zone code) where the trip ends |
| passenger_count | Number of passengers input by the driver |
| trip_distance | Distance in miles as measured by the taximeter |
| fare_amount | Fare based on time and distance as measured by the meter |
| extra | Additional charges: $0.50 for peak hours and $1.00 for overnight|
| mta_tax | Additional Metro Transit Authority (MTA) tax of $0.50 based on distance|
| tip_amount | Amount of tip given by the customer (paid via credit card and does not include cash tips)|
| tolls_amount | Amount of tolls incurred during the trip|
| improvement_surcharge | Additional improvement fee|
| total_amount | Total amount paid by the passenger, excluding cash tips|
| payment_type | Category code that classifies the payment method: 1 = Credit Card, 2 = Cash, 3 = No charge, 4 = Dispute, 5 = Unknown, 6 = Void|
| trip_type | Code that categorizes the type of trip booking, which determines the metered rate and can also be adjusted by the driver: 1 = Street-hail (direct booking), 2 = Dispatch (indirect booking)|
| congestion_surcharge | Charge applied due to traffic congestion |

