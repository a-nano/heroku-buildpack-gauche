# Heroku buildpack: Gauche

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [Gauche][gauche] apps.

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack http://github.com/naduma/heroku-buildpack-gauche.git

    $ git push heroku master

Notes
-----

All libraries are stored in /app/.gauche.d

[Gauche][gauche] 0.9.3.3 and [SLIB][slib] 3b3.

[gauche]: http://practical-scheme.net/gauche/
[slib]: http://people.csail.mit.edu/jaffer/SLIB.html
