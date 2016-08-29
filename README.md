#Project: Salesforce Smart Refrigerator

The following Trailhead project will use an Electric Imp to monitor a refrigerator and a Salesforce *Connected App* to track the current temperature and humidity in the fridge.  This example will also *open a case* in Salesforce if:  1) the refrigerator door is open for more than 30 seconds, or 2) the temperature remains over 11°C for more than 15 min, or 3) the relative humidity is over 70% for more than 15 min.  To track the current temperature and humidity we will create a Salesforce *custom object*, then update it with new readings every 15 sec.

## What you need

### General
 - Your WIFI *network name* and *password*
 - A smartphone (iOS or Android)
 - A computer with a web browser

### Accounts
  - An [Electric Imp developer account](https://ide.electricimp.com/login)
  - The Electric Imp BlinkUp app ([iOS](https://itunes.apple.com/us/app/electric-imp/id547133856) or [Android](https://play.google.com/store/apps/details?id=com.electricimp.electricimp))
  - A [Salesforce developer account](https://developer.salesforce.com/signup?d=70130000000td6N)

### Hardware
  - An Electric Imp developer kit - to purchase email saleforce.devkit@electricimp.com
  - [USB AC adapter](https://www.amazon.com/Omni-Universal-Adapter-Charger-Samsung/dp/B00YG0QALS/ref=sr_1_2?ie=UTF8&qid=1470954944&sr=8-2&keywords=usb+ac+adapter+5v)
  - [Electrical tape](https://www.amazon.com/Duck-299006-4-Inch-Utility-Electrical/dp/B001B19JLS/ref=sr_1_1?s=industrial&ie=UTF8&qid=1470867277&sr=1-1)