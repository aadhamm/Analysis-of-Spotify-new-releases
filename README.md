# Spotify New Releases Data Gathering
This project utilizes the Spotify Web API to gather data on new releases and converts the output of the HTTP response into a CSV file for further analysis in Excel. It also uses the Openpyxl library to extract images from the Excel sheet and perform analysis on them in Python.


![s drawio](https://user-images.githubusercontent.com/86083079/231360707-d96f7b81-4f0a-491b-aff6-db65a50daef8.png)


## Setup
1- First, you will need to create a Spotify Developer account and create a new app to obtain a client ID and client secret key. You can do so by going to the https://developer.spotify.com/dashboard and creating a new app.

2- Once you have your client ID and client secret, add them to the Code,
CLIENT_ID = "your_client_id"
CLIENT_SECRET = "your_client_secret"

3- Install the necessary Python packages by running the following command in your terminal:
pip install -r requirements.txt

4- The output will be saved as a CSV file named new_releases.csv in the output folder.


## Analysis in Excel

1- Open the new_releases.csv file in Excel.

2- Use the data tools in Excel to analyze the data. For example, you can use the "Filter" feature to filter the data by specific artists or release dates.

3- You can also create charts and graphs to visualize the data. To do so, select the data you want to visualize and click on "Insert" -> "Chart" in the Excel ribbon.

## Conclusion

This project provides a simple way to gather and analyze new release data from Spotify using Python, Openpyxl, and Excel. Feel free to modify the code to fit your specific needs or to add additional features.





