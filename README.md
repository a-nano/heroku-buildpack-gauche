# Heroku buildpack: Gauche

This is a [Heroku buildpack][heroku-buildpack] for [Gauche][gauche] apps.

Usage
-----

Example usage:

    $ heroku create --buildpack https://github.com/naduma/heroku-buildpack-gauche.git

    $ git push heroku master

Notes
-----

All libraries are stored in /app/.gauche.d

[Gauche][gauche] 0.9.4, [SLIB][slib] 3b5, [Gauche-dbd-pg][gauche-dbd-pg] 0.2.1 and [Gauche-makiki][gauche-makiki].

[heroku-buildpack]: http://devcenter.heroku.com/articles/buildpacks
[gauche]: http://practical-scheme.net/gauche/
[slib]: http://people.csail.mit.edu/jaffer/SLIB.html
[gauche-dbd-pg]: https://github.com/kahua/Gauche-dbd-pg
[gauche-makiki]: https://github.com/shirok/Gauche-makiki
