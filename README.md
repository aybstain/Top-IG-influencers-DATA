The project consists of writing a Python script that allows scraping information from Instagram profiles. The script uses the requests library to send HTTP requests to Instagram profile URLs and retrieve the HTML content of the page. It also uses the BeautifulSoup library to parse the HTML content and extract the desired information using CSS selectors.

The script reads the Instagram profile URLs from a text file and uses the getinfo method to extract the information from each profile. It stores the information in a list of tuples, then creates a Pandas DataFrame from the list and saves the DataFrame to a CSV file.

The script allows extracting the name, username, number of followers, number of following accounts, and number of posts from each Instagram profile. If the profile has been deleted or blocked, the script returns empty strings for all extracted information.

To use this script, you will need to have Python installed on your computer, as well as the requests and bs4 libraries. You will also need a text file called ig_users.txt that contains a list of Instagram profile URLs, one URL per line.

To run the script, open a terminal or command prompt, navigate to the directory where the script is located, and type python InstagramScrapper.py. This will launch the script and create a CSV file called ig_users_data.csv in the same directory, containing the extracted information from the Instagram profiles.




