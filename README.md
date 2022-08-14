# Elite Python

    Life is short，you need Python
                                   -- Bruce Eckel


Python makes your life easy, but these Python frameworks, libraries, software and resources make it even easier.

If you want a more comprehensive list, go to [Awesome Python](https://github.com/vinta/awesome-python)

- [Elite Python](#elite-python)
  - [Admin Panels](#admin-panels)
  - [Code Analysis](#code-analysis)
  - [Command-line Interface Development](#command-line-interface-development)
  - [Command-line Tools](#command-line-tools)
  - [Cryptography](#cryptography)
  - [Data Analysis](#data-analysis)
  - [Data Visualization](#data-visualization)
  - [Database](#database)
  - [Date and Time](#date-and-time)
  - [DevOps Tools](#devops-tools)
  - [Downloader](#downloader)
  - [Editor Plugins and IDEs](#editor-plugins-and-ides)
  - [Environment Management](#environment-management)
  - [Logging](#logging)
  - [Package Management](#package-management)
  - [Package Repositories](#package-repositories)
  - [Penetration Testing](#penetration-testing)
  - [Processes](#processes)
  - [Refactoring](#refactoring)
  - [RESTful API](#restful-api)
  - [Search](#search)
  - [Shell](#shell)
  - [Specific Formats Processing](#specific-formats-processing)
  - [Static Site Generator](#static-site-generator)
  - [Tagging](#tagging)
  - [Template Engine](#template-engine)
  - [web content extracting](#web-content-extracting)
  - [web crawling](#web-crawling)
  - [web frameworks](#web-frameworks)
  - [websocket](#websocket)
  - [wsgi servers](#wsgi-servers)

---

## Admin Panels

*Libraries for administrative interfaces.*

* [ajenti](https://github.com/ajenti/ajenti) - The admin panel your servers deserve.
* [django-grappelli](https://grappelliproject.com/) - A jazzy skin for the Django Admin-Interface.
* [jet-bridge](https://github.com/jet-admin/jet-bridge) - Admin panel framework for any application with nice UI (ex Jet Django).

## Code Analysis

* Code Analysis
    * [vulture](https://github.com/jendrikseipp/vulture) - A tool for finding and analysing dead Python code.
* Code Linters
    * [flake8](https://pypi.org/project/flake8/) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
        * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions)
* Code Formatters
    * [black](https://github.com/python/black) - The uncompromising Python code formatter.
* Static Type Checkers, also see [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing)
    * [mypy](http://mypy-lang.org/) - Check variable types during compile time.

## Command-line Interface Development

*Libraries for building command-line applications.*

* Command-line Application Development
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [typer](https://github.com/tiangolo/typer) - Based on Python type hints.
    * [python-fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A library for building powerful interactive command lines.
* Terminal Rendering
    * [alive-progress](https://github.com/rsalmei/alive-progress) - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - A package to create full-screen text UIs (from interactive forms to ASCII animations).
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal.
    * [colorama](https://github.com/tartley/colorama) - Cross-platform colored terminal text.
    * [rich](https://github.com/willmcgugan/rich) - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
    * [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI.

## Command-line Tools

*Useful CLI-based tools for productivity.*

* [httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement.

## Cryptography

* [cryptography](https://github.com/pyca/cryptography) - A package designed to expose cryptographic primitives and recipes to Python developers.
* [paramiko](https://github.com/paramiko/paramiko) - The leading native Python SSHv2 protocol library.

## Data Analysis

*Libraries for data analyzing.*

* [Numpy](https://github.com/numpy/numpy) - A fundamental package for scientific computing with Python.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [mplfinance](https://github.com/matplotlib/mplfinance) - matplotlib utilities for the visualization, and visual analysis, of financial data.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [Dash](https://plot.ly/products/dash/) - Built on top of Flask, React and Plotly aimed at analytical web applications.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash)

## Database

*Databases implemented in Python.*

* [pickleDB](https://github.com/patx/pickledb) - A simple and lightweight key-value store for Python.
* [TinyDB](https://github.com/msiemens/tinydb) - A tiny, document-oriented database.
* [ZODB](https://github.com/zopefoundation/ZODB) - A native object database for Python. A key-value and object graph database.

## Date and Time

*Libraries for working with dates and times.*

* [Arrow](https://arrow.readthedocs.io/en/latest/) - A Python library that offers a sensible and human-friendly approach to creating, manipulating, formatting and converting dates, times and timestamps.
* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [delorean](https://github.com/myusuf3/delorean/) - A library for clearing up the inconvenient truths that arise dealing with datetimes.
* [Pendulum](https://github.com/sdispater/pendulum) - Python datetimes made easy.
* [pytz](https://github.com/stub42/pytz) - Brings the IANA tz database into Python.

## DevOps Tools

*Software and libraries for DevOps.*

* Configuration Management
    * [ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform.
* SSH-style Deployment
    * [fabric](https://github.com/fabric/fabric) - A simple, Pythonic tool for remote execution and deployment.
* Process Management
    * [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.
* Monitoring
    * [psutil](https://github.com/giampaolo/psutil) - A cross-platform process and system utilities module.
* Backup
    * [BorgBackup](https://www.borgbackup.org/) - A deduplicating archiver with compression and encryption.
* Container
    * [Docker](https://www.docker.com/) - Docker helps developers bring their ideas to life by conquering the complexity of app development.
    * [docker-compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).

## Downloader

*Libraries for downloading.*

* [akshare](https://github.com/jindaxiang/akshare) - A financial data interface library, built for human beings!
* [you-get](https://you-get.org/) - A YouTube/Youku/Niconico video downloader written in Python 3.
* [youtube-dl](https://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.

## Editor Plugins and IDEs

* Emacs
    * [elpy](https://github.com/jorgenschaefer/elpy) - Emacs Python Development Environment.
* Vim
    * [jedi-vim](https://github.com/davidhalter/jedi-vim) - Vim bindings for the Jedi auto-completion library for Python.
    * [python-mode](https://github.com/python-mode/python-mode) - An all in one plugin for turning Vim into a Python IDE.
    * [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) - Includes [Jedi](https://github.com/davidhalter/jedi)-based completion engine for Python.
* Visual Studio Code
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - The official VSCode extension with rich support for Python.
* IDE
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.
    * [spyder](https://github.com/spyder-ide/spyder) - Open Source Python IDE.
    * [Thonny](https://thonny.org/) - Python IDE for beginners.

## Environment Management

*Libraries for Python version and virtual environment management.*

* [venv](https://docs.python.org/3/library/venv.html) - A Standard Python virtual environment module.
* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management.
* [virtualenv](https://github.com/pypa/virtualenv) - A tool to create isolated Python environments.

## Logging

*Libraries for generating and working with logs.*

* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.
* [loguru](https://github.com/Delgan/loguru) - Library which aims to bring enjoyable logging in Python.
* [sentry-python](https://github.com/getsentry/sentry-python) - Sentry SDK for Python.
* [structlog](https://www.structlog.org/en/stable/) - Structured logging made easy.

## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The package installer for Python.
    * [pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh.
    * [PyPI](https://pypi.org/)
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.
* [poetry](https://github.com/sdispater/poetry) - Python dependency management and packaging made easy.

## Package Repositories

*Local PyPI repository server and proxies.*

* [bandersnatch](https://github.com/pypa/bandersnatch/) - PyPI mirroring tool provided by Python Packaging Authority (PyPA).
* [devpi](https://github.com/devpi/devpi) - PyPI server and packaging/testing/release tool.
* [localshop](https://github.com/jazzband/localshop) - Local PyPI server (custom packages and auto-mirroring of pypi).
* [warehouse](https://github.com/pypa/warehouse) - Next generation Python Package Repository (PyPI).

## Penetration Testing

*Frameworks and tools for penetration testing.*

* [fsociety](https://github.com/fsociety-team/fsociety) - A Penetration testing framework.
* [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) - A toolkit for social engineering.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) - Automatic SQL injection and database takeover tool.

## Processes

*Libraries for starting and communicating with OS processes.*

* [sarge](https://sarge.readthedocs.io/en/latest/) - Yet another wrapper for subprocess.
* [sh](https://github.com/amoffat/sh) - A full-fledged subprocess replacement for Python.

## Refactoring

*Refactoring tools and libraries for Python*

 * [Bowler](https://pybowler.io/) - Safe code refactoring for modern Python.
 * [Rope](https://github.com/python-rope/rope) -  Rope is a python refactoring library.

## RESTful API

*Libraries for building RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions.
    * [flask-api](https://github.com/flask-api/flask-api) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
* Pyramid
    * [cornice](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid.
* Framework agnostic
    * [falcon](https://github.com/falconry/falcon) - A high-performance framework for building cloud APIs and web app backends.
    * [fastapi](https://github.com/tiangolo/fastapi) - A modern, fast, web framework for building APIs w(ith Python 3.6+ based on standard Python type hints.
    * [Starlette](https://github.com/encode/starlette) - Starlette is a lightweight ASGI framework/toolkit, which is ideal for building async web services in Python.
    * [sanic](https://github.com/huge-success/sanic) - A Python 3.6+ web server and web framework that's written to go fast.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django.
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [whoosh](https://github.com/mchaput/whoosh) - A fast, pure Python search engine library.

## Shell

*Shells based on Python.*

* [xonsh](https://github.com/xonsh/xonsh/) - A Python-powered, cross-platform, Unix-gazing shell language and command prompt.

## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
    * [tablib](https://github.com/jazzband/tablib) - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
* Office
    * [docxtpl](https://github.com/elapouya/python-docx-template) - Editing a docx document by jinja2 template
    * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
    * [pyexcel](https://github.com/pyexcel/pyexcel) - Providing one API for reading, manipulating and writing csv, ods, xls, xlsx and xlsm files.
    * [python-docx](https://github.com/python-openxml/python-docx) - Reads, queries and modifies Microsoft Word 2007/2008 docx files.
    * [python-pptx](https://github.com/scanny/python-pptx) - Python library for creating and updating PowerPoint (.pptx) files.
    * [unoconv](https://github.com/unoconv/unoconv) - Convert between any document format supported by LibreOffice/OpenOffice.
    * [XlsxWriter](https://github.com/jmcnamara/XlsxWriter) - A Python module for creating Excel .xlsx files.
    * [xlwings](https://github.com/ZoomerAnalytics/xlwings) - A BSD-licensed library that makes it easy to call Python from Excel and vice versa.
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files.
* PDF
    * [pdfminer.six](https://github.com/pdfminer/pdfminer.six) - A tool for extracting information from PDF documents.
    * [PyPDF2](https://github.com/mstamy2/PyPDF2) - A library capable of splitting, merging and transforming PDF pages.
    * [ReportLab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
    * [Mistune](https://github.com/lepture/mistune) - Fastest and full featured pure Python parsers of Markdown.
    * [Python-Markdown](https://github.com/waylan/Python-Markdown) - A Python implementation of John Gruber’s Markdown.
    * [Python-Markdown2](https://github.com/trentm/python-markdown2) - A fast and complete Python implementation of Markdown.
* YAML
    * [PyYAML](https://github.com/yaml/pyyaml/) - YAML implementations for Python.
* CSV
    * [csvkit](https://github.com/wireservice/csvkit) - Utilities for converting to and working with CSV.
* Archive
    * [unp](https://github.com/mitsuhiko/unp) - A command line tool that can unpack archives easily.

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [lektor](https://github.com/lektor/lektor) - An easy to use static CMS and blog engine.
* [mkdocs](https://github.com/mkdocs/mkdocs/) - Markdown friendly documentation generator.
* [nikola](https://github.com/getnikola/nikola) - A static website and blog generator.
* [pelican](https://github.com/getpelican/pelican) - Static site generator that supports Markdown and reST syntax.
* [makesite](https://github.com/sunainapai/makesite) - Simple, lightweight, and magic-free static site/blog generator (< 130 lines).

## Tagging

*Libraries for tagging items.*

* [django-taggit](https://github.com/jazzband/django-taggit) - Simple tagging for Django.

## Template Engine

*Libraries and tools for templating and lexing.*

* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language.

## web content extracting

*libraries for extracting web contents.*

* [python-readability](https://github.com/buriy/python-readability) - Fast python port of arc90's readability tool.
* [sumy](https://github.com/miso-belica/sumy) - A module for automatic summarization of text documents and html pages.

## web crawling

*libraries to automate web scraping.*

* [scrapy](https://github.com/scrapy/scrapy) - A fast high-level screen scraping and web crawling framework.

## web frameworks

*traditional full stack web frameworks. also see [restful api](https://github.com/vinta/awesome-python#restful-api).*

* [django](https://www.djangoproject.com/) - The most popular web framework in python.
    * [awesome-django](https://github.com/shahraizali/awesome-django)
    * [awesome-django](https://github.com/wsvincent/awesome-django)
* [flask](http://flask.pocoo.org/) - A microframework for python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
* [pyramid](https://pylonsproject.org/) - A small, fast, down-to-earth, open source python web framework.
    * [awesome-pyramid](https://github.com/uralbash/awesome-pyramid)
* [Bottle](https://github.com/bottlepy/bottle) - Bottle is a fast, simple and lightweight WSGI micro web-framework for Python.

## websocket

*libraries for working with websocket.*

* [channels](https://github.com/django/channels) - Developer-friendly asynchrony for django.
* [websockets](https://github.com/aaugustin/websockets) - A library for building websocket servers and clients with a focus on correctness and simplicity.

## wsgi servers

*wsgi-compatible web servers.*

* [gunicorn](https://github.com/benoitc/gunicorn) - Pre-forked, ported from ruby's unicorn project.
* [uwsgi](https://uwsgi-docs.readthedocs.io/en/latest/) - A project aims at developing a full stack for building hosting services, written in c.
* [waitress](https://github.com/pylons/waitress) - Multi-threaded, powers pyramid.
* [werkzeug](https://github.com/pallets/werkzeug) - A wsgi utility library for python that powers flask and can easily be embedded into your own projects.
* [uvicorn](https://github.com/encode/uvicorn) - An ASGI web server implementation for Python.
