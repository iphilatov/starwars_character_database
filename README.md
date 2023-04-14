# Star Wars characters database

This repository contains a Jupyter notebook which works with MySQL database presenting data about characters of Star Wars canon media.

The information is scrapped from [the Star Wars Databank official website](https://www.starwars.com/databank) though the initial page was downloaded to a local machine to make its processing quicker.

The MySQL schema consists of 4 tables: 'characters', 'media', 'species', 'appearances'; it is maintaned through MySQL-connector driver for Python and works within a Docker container.

There is a small app that shows some types of manipulations with the database; it can show the information about certain characters as well as find and count characters, media, species of different characteristics.
