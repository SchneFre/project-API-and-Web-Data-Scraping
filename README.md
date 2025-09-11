First I used BeautifulSoup to scrape a list of Country Names from Wikipedia.
The data also included UN-Member Status and sovereignity Disputes.
After scraping the table from wikipedia I created a Dataframe and saved this dataframe as a csv file in the outputs folder (as requested).

For the second part of the project i used the list of countries and iterated over this list.
For each Country I called the spotify API using spotipy.
For every country I tried to get a Top-Hits playlist and saved the top hits with the artist names in a dataframe aswell.

Presentation:
https://docs.google.com/presentation/d/1TYGErFBmd53WK7bPh3acFoN2G2kktEXyzGHnM2wf32E/edit?usp=sharing

Business Questions:
- Display distribution of song-length over all countries
- What are the Top 10 Countries with longest songs?
- Which Artist appear most often? 
- Which song appears in most countries?
- Which Album appears in most countries?

Key Findings:
- Vatican City has by far the longest songs in the datasample
- Average songlength over the entire dataset is 212 Seconds (=3:32 Min)
- Fadel Chaker and Ed Sheeran are most popular artists
- kPop Demon Hunters is the most popular Album
- Alex Warrens son “Ordinary" is most popular in the given Data Sample
- the Playlists are more random than anticipated. I was excpecting the common superstars to be most common but I don't even know most artists in the dataset
