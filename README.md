# Hotel Bookings Analysis
# A Capstone Project on Exploratory Data Analysis (EDA) using Python
## Project description:
Hotel Bookings Analysis project consists with the real - world data record of hotel bookings of a city hotel and a resort hotel for the period 2015 - 2017 respectively. The project data record consists of information such as type of hotel booked, average daily rate, booking details, arrival date, length of the stay, the number of adults, children, and / or babies booked, customer country, meal preferences, type of the customer, parking space details, reservation status, channels used for booking, booking cancellation details, booking lead time details, among other details. Data analysis and data visualization will be performed using Python libraries.

I started the Hotel Bookings Analysis project to analyse the data and explore the key factors that govern the hotel bookings. In this project, I have downloaded the given dataset of hotel bookings (CSV file) to use it as a pandas dataframe using pandas library. I have came to know more details about the datset by using df.info() method. I have checked the number of data types in the dataset using value_counts() method. If any column of the dataset has highest missing values, the respective coulmn should be removed using drop() method. I have performed data wrangling using value_counts() method and sort_values() method to sort the accordingly. Fianlly, the Vizualization is done in a structured way while following the "UBM" U - Univariate Analysis, B - Bivariate Analysis (Numerical - Categorical, Numerical - Numerical, Categorical - Categorical), and M - Multivariate Analysis visualize using matplotlib and seaborn libraries respectively.
## Objectives:
Out main objective is perform Exploratory Data Analysis (EDA) on the given dataset and draw useful insights and conclusions about trends in hotel bookings and the factors governing hotel bookings.
## Project Files:
Executable File: All theexecutions and data analysis is performed in Python using Google's cloud platform Colaboratory, https://colab.research.google.com/drive/1F8GWIS7zeIVJRtTK2j2tCbVsphjlW5w0?usp=sharing this file contains data analysis, exploration, visualisations and conclusion.

Data File: The repository contains the CSV file, which has hotel bookings data.
## Approach:
1. Understanding the business case.
2. Importing relevant Python libraries and dataset.
3. Data inspection and cleaning.
4. Performing Exploratory Data Analysis to identify factors govern hotel bookings.
5. Document insights and conclusions drawn deom data analysis.
## Data Analysis:
Data Analysis of hotel bookings is done in order to answer the business objectives. The analysis is carried our in 3 steps:
## Univariate Analysis:
In this analysis, we use the data of one variable to analyze the pattern in it.In this project, we have done analysis on:
1. Most preferred meal type by the customers.
2. Bookings percentage of each hotel.
3. Most preferred distribution channel for hotel bookings.
4. Bookings cancellation percentage of each hotel.
5. Most bookings from customer origin country.
## Bivariate Analysis:
In this analysis,we use the data of two variables to analyze the relationship between them. In this project,we have done analysis on:
1. To identify which hotel generates more revenue.
2. To find most preferred length of stay in each hotel.
3. To identify which room type is in most demand and which room type generate the highest adr.
## Correlation Analysis:
In this analysis, we have performed correlation heatmap to understand correlation on variables. Correlation analysis computes the level of change in one variable due to the change in the other. In this dataset, we have performed correlation analysis using a correlation heatmap with the variables, 'lead_time', 'adr', 'total_guests', 'total_stays_in_nights', 'previous_cancellations', 'booking_changes', 'days_in_waiting_list', 'required_car_parking_spaces', 'total_of_special_requests' and 'previous_bookings_not_canceled'.
## Conclusion:
The conclusions from the data analysis are:
1. Bread & Beakfast (BB) is the most preferred meal type by the customers.
2. As the City Hotel has more bookings, it generates more revenue and it has more cancellations as well.
3. Most number of bookings are made in the month of August.
4. Type A room is the most preferred room by the customers.
5. People from Portugal has made most number of hotel bookings.
6. Most preferref customer stay is 1-3 days in the hotels.
7. Most preferred distribution channel by customers is Travel Agent / Tour Oprator (TA/TO) to make hotel bookings.
8. Most of the customers prefer City Hotel for shorter stay and Resort Hotel for longer stays.
