# Genshtab maps georeferencing tool

Sample README.md file preparing for DEVOPS cource, homework GIT 04.
Application described below is not exist at the moment of file creation.

This tool allows to create, modify, compare and share georeference 
data for Soviet era topographic maps also known as "Genshtab maps"

## Features

 * Supports data on a local file system or in a cloud object store
 * Add new raster map image to global map catalog
 * Generate  raster imaage description based on image properties
 * Search/Compare input raster image within the  maps catalog
 * Initialize and update georeference for added or existing images
 * Sharing the geospatial data for public access
 * Reprojection maps to different formats
 
## Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Running the application](#running-the-application)
- [Running the tests](#running-the-tests)
- [Development and contributing](#development-and-contributing)
- [External libraries using in this project ](#external-libraries-using-in-this-project)
- [Authors](#authors)
- [License](#license)
- [Acknowledgments](#acknowledgments) 

## Prerequisites

What things you need to install the software and how to install them

* Python - See https://www.python.org/
* Pip - See https://pypi.python.org/pypi/pip
* Virtualenv - See https://virtualenv.pypa.io/en/stable/
* PostgreSQL - See https://www.postgresql.org/
* [Optional] Docker - See https://www.docker.com/products/overview


## Running the application

To run the application directly:

```
$ cd genshtab_grtool/
$ ./manage.py runserver
```

To run using Docker:

`$ docker-compose up`


## Running the tests

To run tests, just run ./runTests.py This will run random tests for each 
of samples maps, and also some specific unit tests.

### Test data

In test_data/ directory there are different map samples you can use 
to try main program features, so they can be useful for testing 
and measuring speed in different scenarios.

## Development and contributing

Feel free to send pull requests and raise issues.

When developing, please include clear changes description and test 
examples. Any issues should include test input samples.
Thank ou for cooperation!

## External libraries using in this project 

* [PROJ](https://proj.org/) - PROJ is a generic coordinate transformation software
* [ImageMagick](https://imagemagick.org/) - Convert, Edit, or Compose Digital Images tool

## Authors

 * **Evgeny Mukhanov** - *Initial work*

## License

This project is licensed under the MIT License

## Acknowledgments

* [REBRAIN] (https://rebrainme.com/) team. Thanks so much for cool DEVOPS lessons!
