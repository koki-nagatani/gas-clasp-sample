# gas-sample
This is a sample program for Google Apps Script development using clasp

## Environment
* Node.js: 21.7.3

## Getting Started
This is an example of how to create new GAS application.

### Prerequisites
* Enable Google Apps Script API
Access https://script.google.com/home/usersettings and turn on Google Apps Script API

* clasp
```
npm install -g @google/clasp
```

### Installation
1. Clone this repo
```
git clone https://github.com/koki-nagatani/gas-sample.git
```
2. Install npm packages
```
npm install
```
# Usage
1. clasp login
Execute below command and then URL for Authorization is shown. Copy and paste the URL on your browser, and allow the request.
```
clasp login
```
2. Create GAS
Execute below command and select `standalone` to create new script.  
If completed, a GAS is created in your Google Drive.
```
clasp create
```
3. Push the script
By executing below command, the script in `main.ts` is converted and deployed to the GAS in your Google Drive.
```
clasp push
```
4. Open the script on web editor
```
clasp open
```