# README #
  ____                                  _                 _          ____
 / / / __   _______   _____  __ _      | |__   ___   ___ | | _____   \ \ \
/ / /  \ \ / / _ \ \ / / __|/ _` |_____| '_ \ / _ \ / _ \| |/ / __|   \ \ \
\ \ \   \ V /  __/\ V /\__ \ (_| |_____| |_) | (_) | (_) |   <\__ \   / / /
 \_\_\   \_/ \___| \_/ |___/\__,_|     |_.__/ \___/ \___/|_|\_\___/  /_/_/
 
Vevsa is an online medium for Students to get books. It is a place where customer can easily ask & get which book He/She wants. Vevsa is an E-Reqtal (Request+Portal). 

Features
1) Vevsa Money wallet
2) Second Hand books Listing
3) Request 5 books simultaneously and get instant rates from the vendor.
4) vevsa vendor app
5) vevsa customer app
6) vevsa backend panel


This is the back-end https server for vevsa-books application. 

### What is this repository for? ###

//Hello tutorial
* vevsa-books android application 
* 0.0.1
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Clone the repository
* make sure you have node installed on your machine
* run 
```
#!bash

npm install
```
* to install dependencies

```
#!bash

NODE_ENV=development node app.js
```

When running in cluster mode, you have to gracefully reload the server(addressing all clusters with the common alias).


```
#!python

pm2 gracefulReload vevsa:7001
```
