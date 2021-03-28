# The URL Shortening App

It's only for eduaction purposes. Don't use it in production

## Install

Create a project folder and a venv folder within:

$ mkdir myproject
$ cd myproject
$ python3 -m venv venv

Activate the environment

Before you work on your project, activate the corresponding environment:

$ . venv/bin/activate

Install Flask

Within the activated environment, use the following command to install Flask:

$ pip install Flask

Run 

$ python linkshorter.py

## How to use

$ curl localhost:5000/shorten -H "content-type: application/json" --data '{"url":"https://linkedin.com"}'
Shortened: r/a62a4

[School of SRE](https://linkedin.github.io/school-of-sre/python_web/url-shorten-app/)

