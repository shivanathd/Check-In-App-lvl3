Level 3: Check-In App
=================

This app for Salesforce1 Developer Week is a check-in application that demonstrates both getting directions to a given account record and then the ability to check-in to that location based off of the geolocation from which you are accessing the app.

Code exported from the demo org with [the Force.com CLI](https://github.com/heroku/force). Import the metadata with `force import`:

    $ force import
    Imported from /Users/sready/src/Check-In-App-lvl3/metadata
    
Setup Instructions
=================
1. Modify the *Account Page Layout* and drag the **DirectionsPage** into the Mobile Cards section of the layout.
2. Add the included Quick Action to the publisher. To do so go to **Setup > Build >  Customize > Chatter > Publisher Layouts** and then edit the **Global Layout**. Drag the **Check In** action into the list of publisher actions (tip:  put it next to **Post** so it is on the initial publisher screen)
3. NOTE : you need to create a GeoLocation Field on Account called : Location
For the demo flow, [watch this tutorial](https://www.youtube.com/watch?v=VdGHX8MUv84)
