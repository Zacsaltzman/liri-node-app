LIRI stands for Language Interpretation and Recognition Interface.  LIRI is a command line app that has the ability to find song information, find movies, read tweets, and do actions from a text file.  Zachary Saltzman was responsible for all aspects of this application.

The spotify-this-song command takes advantage of the spotify NPM package to find song information.  The command line takes two arguments.  The first is the action that needs to be taken (spotify-this-song) and the second is the song to be queried.  If no song is presented, the default search is "The Sign" by Ace of Base.

The movie-this command takes advantage of the OMDB NPM package to find movie information.  The command line takes two arguments.  The first is the action that needs to be taken (movie-this) and the second is the movie to be queried.  If no movie is presented, the default search is "Mr. Nobody".

The my-tweets command takes advantage of the twitter NPM package to find recent tweets.  The command line takes one argument.  The argument is the action that needs to be taken (my-tweets).  The command presents the recent tweets of the user that is defined within the javascript file.

The do-what-it-says command has the ability to run any of the commands previously defined on this page.  However, instead of accepting arguments, the do-what-it-says command reads what to do from a text file located within the repository.  The text file can be altered to perform different tasks.  The default task is "spotify-this-song" "I Want It That Way" by the Backstreet Boys.

Technologies Used: Node, Javascript, Spotify NPM Package, Twitter NPM Package, and OMDB NPM Package
