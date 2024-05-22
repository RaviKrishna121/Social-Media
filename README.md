# Objective
The aim is to develop and provide a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a SQL database, and enables users to search for channel details and join tables to view data in the Streamlit app.


# Youtube Social-Media data Analysis
Youtube channel data analysis
In this I have used  Google API to fetch Channel details based on Youtube Channel ID.
# Software/tools used :  Python + SQL, and Streamlit.
further Power BI, graphical representation are used to showdata visiually

# **Overview**


User need to input a YouTube channel ID  - to retrieve all the relevant data (like Channel name, subscribers, total video count, playlist ID, video ID, likes,dislikes, comments of each video) 

Date featched through Python code is stored in SQL and in  MongoDB database as a data lake.

Option available to select a channel name and migrate its data from the data lake to a SQL database as tables.

Able to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.

# **Tools and libraries used for this project :**

    1) Python	Scripting, to make requests to the API for retrieve datas.
                        Following Python Libraries are used
                        googleapiclient
                        mysql.connector
                        pandas
                        streamlit
                        PIL (Python Imaging Library)
                        datetime, time, dateutil
      
    2) MySQL	Migrate to a SQL data warehouse for converting as structured/tabular format.
    
    3) Streamlit	Using Streamlit to create a simple UI.
    
    4) Pandas	For EDA processes.
    
    5) Power BI for data visulation and graphs.

$ **APPROACH :**
