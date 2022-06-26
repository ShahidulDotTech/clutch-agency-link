Here is the code for scraping the website clutch.co

The spider is called agency

The main spider is in the this directory:
healthgrades/healthgrades/spiders/agency.py

To run the spider you have to write the below code in a linux shell

    source venv/bin/activate
then
    
    cd healtgrades
then

    scrapy crawl doctor -O output.csv

`-O output.csv` - This part will save the data in a csv file named output.csv

