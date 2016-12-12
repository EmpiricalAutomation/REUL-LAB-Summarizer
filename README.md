# Based on ExplainToMe

[![travis](https://travis-ci.org/jjangsangy/ExplainToMe.svg?branch=master)](https://travis-ci.org/jjangsangy/ExplainToMe)
[![licence](https://img.shields.io/pypi/l/coverage.svg)](https://github.com/jjangsangy/ExplainToMe/blob/master/LICENSE)
[![Quay](https://quay.io/repository/jjangsangy/explaintome/status)](https://quay.io/repository/jjangsangy/explaintome)

## Automatic Web Article Summarizer for the REUL LAB

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# What is it?

The `REUL LAB Summarizer` is based on `ExplainToMe` is a automatic text summarizer, that utilizes
[TextRank](http://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf),
a graph based algorithm to scans through the contents of a website to
extract a concise machine generated summary. The methodology is similar
to the way search engines return the most relevant web pages from a
users search query.

# Support

Here’s a list of Python platforms that are officially supported. You will have to install one of the Python versions below using https://www.python.org/downloads/.

* Python 2.7
* Python 3.4
* Python 3.5
* pypy 2.5.0 -> 2.7.9

# Quickstart

# Install

## Clone Repository

```bash
$ git clone https://github.com/jjangsangy/ExplainToMe.git
```

## Create a virtualenv

```bash
$ virtualenv -p python venv
```

## Source Virtualenv

```bash
$ source venv/bin/activate
```

## Install Python Dependencies

```bash
$ pip install --upgrade pip setuptools wheel
$ pip install -r requirements.txt
```

## Run Server

```bash
$ python manage.py runserver
Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

Now go to your browser and point it towards `http://127.0.0.1:5000`

