#Step 3: Created a Salesforce Connected App

Step by step instructions to create a Connected App:

  1. Log into Salesforce and click on the **Setup** tab in the top right navigation menu
  ![Salesforce Navbar](http://i.imgur.com/mhYIfBx.png)
  2. In the sidebar under **Build** unfold the **Create** menu and select **Apps**
  3. At the bottom of the page under **Connected apps** click the **New** button
  ![Salesforce Apps](http://i.imgur.com/40aXTlL.png)
  4. In the **New Connected App** form fill in:
    - Basic Information
      - Connected App Name
      - API Name
      - Contact Email
    - API (Enable OAuth Settings)
      - Check the *Enable OAuth Settings* Box
      - Callback URL - this should be your agent url
      - Selected OAuth Scopes
        - Select *Access and manage your data (api)*
        - then click *Add*
    - When above info is filled out click **Save**
  5. You will be redirected to the *Connected App Name - your app name* page
    - Make a note of your Consumer Key (you will need to enter this into your agent code)
    - Click on Consumer Secret *Click to reveal*
    - Make note of your Consumer Secret (you will need to enter this into your agent code)
  ![Salesforce Keys](http://i.imgur.com/uussyzV.png)

Open the Electric Imp IDE & select your device.  Find the *SALESFORCE CONSTANTS* section at the bottom of the Agent code and enter your **Consumer Key** and **Consumer Secret**.

![IDE with code](http://i.imgur.com/hvligYx.png)
