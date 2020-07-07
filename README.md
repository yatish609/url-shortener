# URL-Shortener

This project is a Python-based URL-Shortener. 

_old = Shortens the URL, stores it in database, allows you to manually set URL. However, it doesn't redirect the URL.

default = Shortens the URL, stores it in database, doesn't allow you to manually set URL. However, it redirects the URL.

To run this project on a windows system:
1. Download dist/gui.exe and run

To manually compile and run this project:
1. Install the dependencies mentioned below.
2. Run using 'python3 gui.py'

Libraries used:
>PyQt5

>Pymongo

>Dns

>Requests

Based on Python 3.8.2 and compiled using python's own virtualenv.

To install dependencies:

~~~
pip install pyqt5-tools pymongo dns requests
~~~