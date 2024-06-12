# 1. Scope the Project
________________________________________
Our plan is to use a supervised learning technique to predict which customers are most likely to cancel their subscription using the past three months of customer data which includes subscription and listening history.
________________________________________
keyboard_arrow_down
# 2. Gather Data
________________________________________
Read the following files into Python:
●	Customer data: maven_music_customers.csv
●	Listing history: maven_music_listening_history.xlsx

# 3. Clean Data
________________________________________

# 4. EDA
________________________________________
Try to better understand the customers who cancelled:
●	How long were they members before they cancelled?
●	What percentage of customers who cancelled had a discount vs customers who didn't cancel?

________________________________________
Better understand the customers' listening histories:
●	Join together the listening history and audio tables
●	How many listening sessions did each customer have in the past 3 months?
●	What were the most popular genres that customers listened to?

# 5. Prep for Modeling
________________________________________
Create a DataFrame that is ready for modeling with each row representing a customer and the following numeric, non-null columns:
●	Customer ID
●	Whether a customer cancelled or not
●	Whether a customer received a discount or not
●	The number of listening sessions
●	Percent of listening history consisting of Pop
●	Percent of listening history consisting of Podcasts

________________________________________
Visualize the relationships in the modeling DataFrame using a pair plot:
●	What are some of your observations?
●	What variables might do a good job predicting customer cancellation?
