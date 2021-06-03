# DBSCAN on Golem
## Current state
This project was meant to be done during the 0xHack hackathon. but unfortunately, I didn't have the time to finish it up yet, but I'm pretty sure that this idea will work! I put some effort into my work to make a simple library so that the algorithm could be used by someone else.
Currently this project is a PoC project for running Map Reduce programming model on top of Golem.network. this project is based on my [WIP] [golem-mapreduce](https://github.com/hhio618/golem-maprerduce) library.
## Overview
This is an implementation of the [DBSCAN clustering algorithm](http://en.wikipedia.org/wiki/DBSCAN) 
on top of [Golem.network](http://Golem.network/). It is based on my original work on top of the Apache PySpark, see [here](https://github.com/hhio618/dbscan-pysprak).
### Golem map reduce
This uses the [golem map reduce](https://github.com/hhio618/golem-maprerduce) project to run map reduce programming model on top of the Golem.network.

## License

This project is available under the Apache 2.0 license. 
See the [LICENSE](LICENSE) file for details.

