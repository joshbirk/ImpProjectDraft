#Step 7: Monitor the data in Salesforce1

Now that you have connected your Imp to Salesforce, it might be handy to see that data on a mobile device.  Using Salesforce1, it is easy to keep track of your Smart Fridge on the go.


##Create a Custom Object 
First, let's give the custom object a tab so that Salesforce1 can add it to the left navigation.

1. Go to Setup
2. Under *Create*, click *Tabs*
3. Next to "Custom Object Tabs", click *New*
4. In the objects drop down, select "Frig_Reading"
5. Select an Icon
6. Click "Save"

##Open Salesforce1 in Chrome
You can access the Salesforce1 mobile app in three ways:

*As a downloadable mobile app (Salesforce1) that you install on your phone from the Apple AppStore or Google Play
*By navigating to login.salesforce.com using a mobile browser
*By using the Chrome Developer Tools

For this step, we'll use the last option.

Open a new tab in your Chrome browser and open the Developer Tools by clicking View | Developer | Developer Tools
Click the Toggle Device Mode button to simulate your browser as a mobile device.

1.To simulate the Salesforce1 app in your browser, copy and paste in the URL from the previous tab. Remove the part of the URL immediately after salesforce.com/. 

2. Append /one/one.app to the end of the URL after salesforce.com to start the Salesforce1 Application simulator. For example:
image

3. If the display is too small, change the size to 100%.

4. Click the three white bars in the upper left to open the left navigation

5. Under the "Recent" section, scroll down and click "More"

6. You will see "Frig_Reading" somewhere on the list.  Select it and you can now browse the readings as if it it were on a mobile device.