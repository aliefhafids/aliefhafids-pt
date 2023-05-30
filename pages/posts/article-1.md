---
title: Be safe with the Komplek App Scanner
date: 2023/5/27
description: My project for mobile app.
tag: Mobile App, Flutter
author: Alief Hafids
---

# Be safe with the Komplek App Scanner

## Introduction

Advances in technology make it easier for anyone to carry out their activities, for example in making payment activities. Now payments can be made using the Qr code, all we have to do is scan the qr and the system will automatically process the payment. In semester 4  there was a mobile programming course using Flutter, the material provided started from how to layout mobile applications, and how to use API's in mobile applications. In order to pass this course, these students are required to make a car project application, by linking the ease of activity in payment using a QRcode, I decided to make an application used for guarding house.

So the concept of this application is that each security mobile phone will be installed with an application which will later be used to scan the QR code for each komplek. This application will later be useful for recording security working hours because from the QR code realtime data will be input into the database, and later the head of security can monitor the performance of the security.


<img src="/images/articles-1/mobile-login.png" data-align="center" alt="login" width="800px"/>

**Step 1** : User must log in first, to find out who the user will be doing the shift. Database checks user username and password.

**Step 2** : User will go to app home page. On that page there are 2 options buttons, a button to scan the QR and select the user's current location.

<img src="/images/articles-1/mobile-loc.png" data-align="center" alt="location" width="800px"/>

**Step 3** : If user want to know the current location, the user selects the location button and will display the address, latitude and longitude of that location.

<img src="/images/articles-1/mobile-scan.png" data-align="center" alt="scan" width="800px"/>

**Step 4** : To scan the qr the user selects the scan QR button and the first step is to scan the qr code first, if the QR data matches the data in the database it will be directed to the check in and check out page. If the qr code data is wrong then it cannot be entered on the next page.

....




