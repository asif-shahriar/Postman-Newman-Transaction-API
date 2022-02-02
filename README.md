# Postman-Newman-Transaction-API
## Prerequisites:
* Install Postman 9.4.1
* Install Nodejs 16.13.1
## How to run this file:
* Clone the repo
* Open terminal in root folder
* Give following commands:
```
npm i newman
```
```
npx newman run .\collection\customers_collection.json -e .\collection\customerEnv.json -n 1
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js 
```

This is the screenshot of **index.html**

