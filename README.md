# liri-bot

project name: liri-bot

command line interface app that takes in several different functions leveraging OMDB, Spotify and BandsInTown

<h3>instructions</h3>

_______________________________________

after running npm install, the command line app will take in the following four commands and respond in the following manner.

<b>node liri.js spotify-this-song ''</b>

this function calls the Spotify API and displays the following fields.

artist
song name
a Spotify preview link
album
by default, the app will show 'The Sign' by Ace of Base.

<b>node liri.js movie-this ''.</b>

this function calls the OMDB API and displays the following fields.

movie title
year of release
IMDB rating
rotten tomatoes rating
country of production
language
plot summary
actors

<b>node liri.js do-what-it-says</b>

the liri retrieves the text from random.txt and then calls one of the app's commands. on default, it should run spotify-this-song for 'I want it that way' by Backstreet Boys per the homework requirements.

<b>node liri.js concert-this</b>

this will display concerts using the BandsInTown API.

here is a screen-grab of the application at work using the aforementioned commands.

![alt text](https://raw.githubusercontent.com/cluskinator/liri-bot/master/outputscreenshot.png)


