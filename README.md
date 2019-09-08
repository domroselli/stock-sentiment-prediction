# stock sentiment prediction

![License](http://img.shields.io/:license-mit-blue.svg)

A fork of [Alec Armbruster's](https://github.com/alectrocute) [flaskSaaS](https://github.com/alectrocute/flaskSaaS). Uses Twitter API to do sentiment analysis on tweets for a given stock ticker symbol.

This is an assignement from Siraj's Machine Learning Course (https://www.machinelearningcourse.io).

## Setup

### Vanilla

- Install the requirements and setup the development environment.

	`make install && make dev`

- Create the database.

	`python manage.py initdb`

- Run the application.

	`python manage.py runserver`

- Navigate to `localhost:5000`.

## Configuration

TBD

## License

The MIT License (MIT). Please see the [license file](LICENSE) for more information.
