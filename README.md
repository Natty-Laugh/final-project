# FinalProject

Temperature Sensor 

## Repository Structure



## Development server

Apache server will run once rasberry pie is turned on. 

## Connect the Raspberry Pi
Run:
```ssh pi@10.201.64.35```
Password: csci3308i

## Build

Code is in python.  Compile this code on bash via Rasberry Pie.

Databasev2.py builds the database script

Webgui2.py builds the web app and chart 

Make executable: chmod +x filename

Build code: ```python filename```

After these commands web app will be deployed 

## Running the Web App

Go to this link to build the web app once the server is running http://10.201.64.35/cgi-bin/webgui2.py

## Running unit tests
* Download the Selenium drivers for chrome and firefox, which can be found [here](https://selenium-python.readthedocs.io/installation.html.).
* Placed them in the same folder as our python scripts

Run: 
```python test_selenium.py```
```python test_chrome.py```

