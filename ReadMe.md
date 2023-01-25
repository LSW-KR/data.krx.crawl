
imports necessary libraries such as schedule, pandas, datetime, mariadb, telepot, selenium webdriver
sets Telegram bot chat ID and token number
defines a function called "crawl" which performs the following actions:
> formats the date for crawling
> opens a chrome browser using selenium and navigates to a specific url
> selects an option and clicks on a button on the webpage
> clicks on a specific date link and extracts information from the page
> saves the extracted information in a list
> inserts the data into a MariaDB database
>sends a message on Telegram using the telepot library with the extracted information.
    
Note: The script uses a class name and xpath to locate and extract the elements.
      This script also uses an external chrome driver and this script has some logic to handle specific situations like when a specific date is not available.
"""
