A trivial tool for finding what "colour" your Postgres instance is in
Heroku.

It's an error for there to be no Postgres instance, or for there to be
more than one.

Usage:

 $ PG_INSTANCE=$(which-heroku-pg)
 $ heroku pg:promote $PG_INSTANCE

