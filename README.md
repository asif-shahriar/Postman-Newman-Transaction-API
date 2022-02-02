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
npx newman run .\Collections\Transaction.json -e .\Collections\TransactionENV.json -n 1
```
```
npm i newman-reporter-htmlextra
```
```
node .\report.js 
```

This is the screenshot of **index.html** file

![Screenshot_1](https://user-images.githubusercontent.com/71173675/152147707-fb673ef7-23d7-4b1d-b32e-09f0f38e5b52.png)

