# Listing Youtube search results for user-chosen querys, then emailing a list of the most recent videos relevant to the query. 

# Forked from the below
# [youtube-search-python](https://github.com/alexmercerind/youtube-search-python)

# This uses the above to perform Youtube searches based on query strings, ordered by most recent, filtering out those with less than 1000 views. It then takes those items and sends one email per query term with a list of the items it found, with some basic HTML to stop it looking too awful. Clickable thumbnails and some borders to make it look somewhat orderly. I made this before I had a clue how HTML worked.

# I use this to stay up to date on the latest fragrance releases and discontinuations, as this is important for my side business.

# Running daily with cron 

#

# To use, navigate to privates.txt and follow the instructions within, and change the query strings in query_strings to your needs. Remember you will get 1 email per item in this list.
