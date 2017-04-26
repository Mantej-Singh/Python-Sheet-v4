# Python Sheets: 
[![Pampa ds160.png](https://s19.postimg.org/x69rfot6b/Pampa_ds160.png)](https://postimg.org/image/uc6m28qzz/)
## [pygsheets](https://github.com/nithinmurali/pygsheets)- Google Spreadsheets Python API v4
### Insert, Update, and Delete from a Google Spreadsheet with Google Sheets Python API v4

## Requirements
`Python 2.6+ or 3+`

## Installation
### From PyPi
`pip install pygsheets`

### From GitHub (Recommended)
`pip install https://github.com/nithinmurali/pygsheets/archive/master.zip`

## Calling API:
### To programmatically access your spreadsheet, you’ll need to create a service account and OAuth2 credentials from the Google API Console.
1. Go to the [Google APIs Console](https://console.developers.google.com/) and create a new project (or select the one you have.).
2. You will be redirected to the API Manager, there Under “Library”, Google APIs click on “Sheets API”.
3. Click Enable API. Search for “Drive API” and enable the Google Drive API.
4. Create credentials for a Web Server to access Application Data.
5. Go to “Credentials” Tab and choose “Create Credentials > OAuth Client ID”.
6. Download the JSON file.
6. Copy the JSON file to your code directory and rename it to
`gc = pygsheets.authorize(outh_file='client_secretxxx.json')`

[![google-developer-console.gif](https://s19.postimg.org/6djlnmfub/google-developer-console.gif)](https://postimg.org/image/9ke5790a7/)


## My Google SpreadSheet:
[![Pampa ds160.png](https://s19.postimg.org/myr83a6yb/Pampa_ds160.png)](https://postimg.org/image/de7lgehm7/)

## Panda Output:
[![Pampa ds160.png](https://s19.postimg.org/d5em47u7n/Pampa_ds160.png)](https://postimg.org/image/4zwk625yn/)
