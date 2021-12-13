# pyscraper

## Summery

Able to scrape HTML page rendered with Javascript such as React.js and Vue.js.

Please check if you can use python3 and pip3.

```
$ python --version
Python 3.9.0
$ pip --version
pip 21.3.1 from ~/.anyenv/envs/pyenv/versions/3.9.0/lib/python3.9/site-packages/pip (python 3.9)
```

## Selenium & ChromeDriver 

Install selenium

```
$ pip install selenium
$ pip list
...
selenium  4.1.0
...
```

Install ChromeDriver

First, check the version of Chrome browser installed on your PC from "About Google chrome".

```
Example: 96.0.4664.93 
```

Check a near version of Chrome Driver.

https://sites.google.com/chromium.org/driver/downloads?authuser=0

Unzip the zip and you will see the `chromedriver` binary executable.

```
% pip install chromedriver-binary==96.0.4664.45
...
Successfully installed chromedriver-binary-96.0.4664.45.0
```

Complete !
Following is use version:
```
chromedriver-binary 96.0.4664.45.0
selenium 4.1.0
```

## Execute scraping_sample.py

```
$ python scraping_sample.py
```

get `Example Domain`.





