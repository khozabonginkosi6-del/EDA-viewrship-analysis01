📊 Viewership Analysis Project
📌 Overview
This project analyzes video viewership data from an Excel file. The workflow includes:

Importing essential Python libraries

Installing dependencies for consistent execution

Loading data from Excel into a Pandas DataFrame

Displaying and exploring the dataset for further analysis

🛠️ Requirements
The following libraries are required:

python
import pandas as pd
import numpy as np
Additional dependency:

bash
%pip install openpyxl
pandas → For data manipulation and analysis

numpy → For numerical operations

openpyxl → Required for reading Excel files (.xlsx)

✅ Note: If you install new packages, restart the kernel using %restart_python or dbutils.library.restartPython() to ensure updates are applied.

📂 Data Source
The dataset is stored in an Excel file:

Code
/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx
This file contains viewership logs with the following columns:

Column	Description
DateID	Date of the event (YYYYMMDD format)
CustomerID	Unique identifier for the customer
TotalTimeWatched	Total viewing time in seconds
Platform	Platform used (e.g., Leanback, Mobile)
PlayEventType	Type of event (e.g., LiveTV, VOD)
VideoTitle	Title of the video watched
📥 Loading the Data
python
# Location of the Excel file
data_path = "/Workspace/Users/khozabonginkosi6@gmail.com/Viewership Analysis .xlsx"

# Read the Excel file into a DataFrame
df = pd.read_excel(data_path)

# Display the data
display(df)
📊 Sample Output
Example of the dataset:

DateID	CustomerID	TotalTimeWatched	Platform	PlayEventType	VideoTitle
20201101	EW1DENH0EC1J3M9WAOZF9LSV004O	300	Leanback	LiveTV	F1 '20: Emilia Romagna GP
20201101	EW1DENH0EC1J3M9WAOZF9LSV004O	300	Leanback	LiveTV	F1 '20: Emilia Romagna GP
🚀 Next Steps
Perform exploratory data analysis (EDA)

Aggregate viewership by platform, event type, or video title

Build dashboards for executive reporting

Identify trends and insights in customer behavior

📌 Notes
Ensure the Excel file path is correct and accessible in your environment.

Keep dependencies pinned to avoid issues with library updates.

Restart the Python kernel after installing new packages.
