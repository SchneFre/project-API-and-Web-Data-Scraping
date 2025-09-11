First I used BeautifulSoup to scrape a list of Country Names from Wikipedia.
The data also included UN-Member Status and sovereignity Disputes.
After scraping the table from wikipedia I created a Dataframe and saved this dataframe as a csv file in the outputs folder (as requested).

For the second part of the project i used the list of countries and iterated over this list.
For each Country I called the spotify API using spotipy.
For every country I tried to get a Top-Hits playlist and saved the top hits with the artist names in a dataframe aswell.

Presentation:
https://docs.google.com/presentation/d/1TYGErFBmd53WK7bPh3acFoN2G2kktEXyzGHnM2wf32E/edit?usp=sharing
