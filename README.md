R code to download motions from the current Dutch Parliament (2012-2015) and build their cosponsorship networks.

This is a __very early draft__ that only produces [static plots](http://f.briatte.org/parlviz/motie/plots.html) for now.

# SOURCES

* [Motions from the House of Representatives](http://www.tweedekamer.nl/kamerstukken/moties)
* [Motions from the Senate](https://www.eerstekamer.nl/moties_3)

# HOWTO

Run `make.r` after checking the dependencies at the top of the script. The data collection process is slow and error-prone (there are many, many motions), so I recommend running the `data-*` scripts a few times independently.

The code in `functions.r` was written for the [`parlnet`](https://github.com/briatte/parlnet) project.
