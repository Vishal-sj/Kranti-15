# Kranti-15
Official Android application for the Kranti symposium, 2015

---The Kranti'15 Android app---

This app was designed to make it easier for participants to know more about the symposium.

All features of the app can be accessed via the home screen through the buttons.

At the start of the app, a 2d Kranti animation is displayed along with buttons for navigation. The 2d Kranti animation was made using blender and can be replayed using the 2d animation button on the home screen

There are two video elements in the app,the teaser and trailer of the symposium.

The trailer uses the Youtube Data API to fetch video content from the official Kranti Youtube channel. The Youtube Data API provides several options such as play-functions,full screen mode,quality and captions support as well as maintaining sessions all of which have been integrated into the app. The trailer is for online viewing only as the app was designed to be minimal on storage and the trailer can take up 50-60mb if stored within the app.

Although the trailer is for online viewing, the teaser exists within the app and can be watched offline. The online trailer and offline teaser parts of the app were designed such that even, in the absence of internet connectivity, the offline teaser video is available for the user to view while not compromising on app size.

The maps activity uses the Google Maps Android API to make the full use of features of Google Maps. When the Maps Activity is initiated,the Marker is positioned at the coordinates of Meenakshi Sundararajan Engineering College, with the optimum zoom level set for smart phones.

The gallery activity makes use of GridViewAdapter ,displaying images of the event,logo,merchandise and so on.

Finally, the kranti15.tk button redirects the user to the official Kranti website for viewing the web based interface.

Upcoming Performance Improvements:

Navigation Menu Independent Splash Screen Coordinators Contacts Integration

Hopefully this app is useful for participants as a dedicated stand alone app for Kranti and also for developers for future Android projects.

Vishal
