## Popular Movies

Popular movies provides you an accessible API that grabs a list of the popular movies and their IMDB id's. This should help you get a list of movies that were possibly only in theaters and separate it from the less mainstream movies.

### Install

* Get an API key from [TMDb](https://www.themoviedb.org/account/sluzorz/api-details).
    
    * Rename the file [application/config/tmdb.php.sample](application/config/tmdb.php).

            mv application/config/tmdb.php.sample application/config/tmdb.php

    * Place the key into that file.

* Get an API key from [Rotten Tomatoes](http://developer.rottentomatoes.com/apps/register).

    * Rename the file [application/config/rt.php.sample](application/config/rt.php).

            mv application/config/rt.php.sample application/config/rt.php

    * Place the key into that file.

* Fill in your database information.

    * Rename the file [application/config/database.php.sample](application/config/database.php).

            mv application/config/database.php.sample application/config/database.php

    * Create a database table.

    * Edit the file with your information.

### License

MIT.