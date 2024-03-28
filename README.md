<div align="justify"> 
  
# Ebay listings scrapping

This notebook contains a python code which performs web scraping on eBay listings for phones. The main objective is to extract specific information from listings based on user preferences and save the data to a MongoDB database for further analysis.

**Steps :**
- Import necessary libraries -  pandas, requests, BeautifulSoup, time, and selenium for web automation.
- Load the eBay URL by passing it as an argument to the driver.get() function to open the webpage.
- Gather user preferences for phone models and automate the application of these filters using Selenium's find_element() and click() functions.
- Implement a 3-second time delay between requests, this will ensure the script to adhere to eBay's API policies.
- Save the eBay search page's HTML file locally to parse the data later.
- Read the saved HTML file and parse it using BeautifulSoup, extracting the required details of phone listings.
- Set up a connection to a MongoDB database and create a table for storing the phone listing information.
- Save the extracted data to the MongoDB table for further analysis and manipulation.

</div>
