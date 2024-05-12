# YouTube-Data-Harvesting-and-Warehousing

YouTube Data Harvesting and Warehousing is a project that intends to provide users with the ability to access and analyse data from numerous YouTube channels. SQL and Streamlit are used in the project to develop a user-friendly application that allows users to retrieve, save, and query YouTube channel and video data.

### Technologies used:
Python :  Core programming language for the application.
Streamlit : Framework for building the web application's interactive user interface.
Mysql : MySQL is an open-source relational database management system that uses SQL to manage and manipulate data stored in a database.
YouTube Data API : Utilized to fetch data from YouTube channels and videos.

### Overview:
This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app.

### Libraries:
* googleapiclient.discovery
* Pandas
* MySql
* Streamlit

### Workflow:

Step 1:Set up a Streamlit app: Streamlit is a great choice for building data visualization and analysis tools quickly and easily. You can use Streamlit to create a simple Ul where users can enter a YouTube channel ID, view the channel details, and select channels to migrate to the data warehouse.

Step 2:Connect to the YouTube API: You'll need to use the YouTube API to retrieve channel and video data. You can use the Google API client library for Python to make requests to the API.

Step 3:Store and Clean data: Once you retrieve the data from the YouTube API, store it in a suitable format for temporary storage before migrating to the data warehouse. You can use pandas DataFrames or other in-memory data structures.

Step 4:Migrate data to a SQL data warehouse: After you've collected data for multiple channels, you can migrate it to a SQL data warehouse. You can use a SQL database such as MySQL for this.

Step 5:Query the SQL data warehouse: You can use SQL queries to join the tables in the SQL data warehouse and retrieve data for specific channels based on user input. You can use a Python SQL library such as SQLAlchemy to interact with the SQL database.

Step 6: Display data in the Streamlit app: Finally, you can display the retrieved data in the Streamlit app. You can use Streamlit's data visualization features to create charts and graphs to help users analyze the data.

## Contacts:

Email: praveen2726r@gmail.com     

LinkedIn: https://www.linkedin.com/in/praveenr27/
