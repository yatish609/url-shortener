# URL-Shortener

This project is a Python-based URL-Shortener. 

_old = Shortens the URL, stores it in database, allows you to manually set URL. However, it doesn't redirect the URL.

default = Shortens the URL, stores it in database, doesn't allow you to manually set URL. However, it redirects the URL.

Input URL Format: https://www.example.com

# Installation

* To run this project on a windows system:
    1. Download the [executable](https://github.com/yatish609/URL-Shortener/releases).

* To manually compile and run this project:
    1. Install the dependencies:
        ~~~
        For _old files:
        pip install pyqt5-tools pymongo dns requests

        For default files:
        pip install pyqt5-tools requests validators
        ~~~
    2. Run using 'python3 gui.py'

Based on Python 3.8.2 and compiled using python's own virtualenv.

