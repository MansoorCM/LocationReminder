# LocationReminder

# Note
This app is built as part of the Udacity Android Kotlin Developer Nanodegree program

## The app requires google maps Api key and needs to be registered with firebase(firebase authentication).

To run the app obtain google maps API key from the APIs & Services section at the Google console.
Register the app in firebase and copy the googleservices.json file provided by firebase to the app folder.

# App description

Location Reminder is a TODO list app with location reminders that remind the user to do something when the user is at 
a specific location. It uses firebase authentication(with gmail and email/password combination) for login. Users can set reminders with 
title, description, and map POI(which is selected in the google maps view). The app creates a 
geofence at the location selected for the reminder and triggers a notification as a  reminder when the user enters the geofence.
