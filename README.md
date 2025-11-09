# Data-Visualization-Project

Before running the Streamlit app, please update the file paths for the following variables in the code:

# Line 25 - daily variable
daily = pd.read_csv("path/to/komuter_ridership_daily_v2.csv")

# Line 26 - hourly variable
hourly = pd.read_csv("path/to/komuter_hourly_schedule_combined_iqbal_v2.csv")

Replace the file paths with the correct directories to your local CSV files.
For example:

# Line 25
daily = pd.read_csv("C:/Users/Iqbal/Documents/komuter_ridership_daily_v2.csv")

# Line 26
hourly = pd.read_csv("C:/Users/Iqbal/Documents/komuter_hourly_schedule_combined_iqbal_v2.csv")


Make sure both variables — daily (line 25) and hourly (line 26) — point to the correct file locations before running the app.
