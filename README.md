# Anime_scrapper 

Allows you to download all episodes of a series from animeheaven.eu . 

First install the required modules 

    pip install -r requirements.txt   
    


Run the script with the link of the series as a command line argument . 

You may give a second command line argument specifying the location where to download the files.

        python <script> <url> [location]
        


To get all episodes download links as textfile 

        python get_epi_filelist.py <url>

url is link of anime series  having all episodes 

       python get_epi_filelist.py "http://animeheaven.eu/i.php?a=Hunter%20x%20Hunter%202011%20Dubbed"

To prevent scrapy log output in terminal 

       python get_epi_filelist.py "http://animeheaven.eu/i.php?a=Hunter%20x%20Hunter%202011%20Dubbed"  2> /dev/null

 


# DISCLAIMER:

 Downloading copyrighted media without the  owner’s permission is illegal is some countries. 
 Under no circumstances is this script intended to encourage illegal activity, 
 and there are no guarantees that this information will    protect you from any legal action.   
 
 
