# Real-Time International Space Station Tracker

This Python script provides real-time tracking of the International Space Station (ISS) and notifies the user via email when the ISS is in close proximity to their location.

## Features:

Live Tracking: Utilizes real-time data to track the current location of the International Space Station.

Location Awareness: Determines the user's current location and compares it with the ISS position to identify proximity.

Email Notification: Sends an email notification to the user's specified email address when the ISS is sufficiently close to their location.

## How it Works:

1. The script retrieves live data on the current position of the ISS using external APIs.

2. The user enters his location.

3. The script calculates the distance between the user's location and the ISS.

4. If the ISS is within a predetermined proximity threshold, an email notification is sent to the user's specified email address.
