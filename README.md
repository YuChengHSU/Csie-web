# Csie-web
## Pre-requiste software
* python 3.6 or above

or alternatively (though not recommended)
* python 2.6 (It is installed by default in most of Apple products)
## 1. Set up your computer as localhost
Open commandline (or terminal in Apple products) 
### a. change the directory
Change the directory to the directory of the folder "CSIE". For example if your file structure is something like

> [blah]/[blah blah]/Csie-web/CSIE/..

So you need to first type in commandline/terminal
```
 cd [blah]/[blah blah]/Csie-web 
```
### b. executing python local http server
Type in 
```
[python.exe source path]/python -m http.server 8000  ----for python3.X version
```

or
```
[python.exe source path]/python -m SimpleHTTPServer 8000 ----for python2.X version
```
## 2. You are good now, let's go to the website
Type the url below in your browser (google chrome is recommended as I test the web on this browser)

[127.0.0.1:8000/CSIE/fitbit.html](127.0.0.1:8000/CSIE/fitbit.html "Go to there by clicking the link!")

## 3. Ok let's collect data!
It can be separate into 3 main steps
### i. Login into Fitbit
a. First you need to login into Fitbit by pressing Login to Fitbit, and you will be redirect to fitbitLogin.html

b. Selecting the account you wan to log in 

c. Entering account and password

d. Authuorizing the web to collect it, and you will be redirect to the original page

You do not need to do it that often as the web stores the cookie in your browser and it sill last for 1 hours. i.e you do not need to do in again as long as you have logged into this account within 1 hour
### ii.Select the time period you want to collect
a. pressing the blank with underline at "Start date" column, a dateTime picker will appear, and choose the date and time of the starting time you want to collect

b. pressing the blank with underline at "End date" column, a dateTime picker will appear, and choose the date and time of the end time you want to collect

c. pressing collect to collect the data

... it will take few seconds to collect the data ...
### iii. Output to csv
WARNING: Please check the data is complete before doing so

a. press "Export XXX to csv" to output the data to csv file.
