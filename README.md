# netflix-imdb-userscript
A Greasemonkey/Tampermonkey script to show IMDb ratings on Netflix

How to install:
download the user.js file
get an API key for omdb.com and enter it where the APIkey variable is set
install it as a user script to Greasemonkey (Firefox) or Tampermonkey (Chrom)

I did not include my API key, as in the free version, the number of requests per day is limited.
This script will not work without your own key!

Behavior: when you look at the details of a movie, it will add the IMDb rating next to the basic movie information.
This will work for the sliders as well as the title page itself.

When movies do not have a year associated, it will not query the database.
