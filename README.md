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
## Dependencies:
Python 3.12
## Getting Started:
1. Clone the repository to your local machine:
```python
git clone https://github.com/straznikit/ISS-over-head
```
2. Configure the script with your email credentials and location preferences.
3. Run the script and monitor the output for real-time updates on the ISS location and email notifications.
## Contributing:

Contributions are welcome! If you have any suggestions, improvements, or feature requests, please feel free to submit a pull request or open an issue in the repository.

## Acknowledgments:

Special thanks to the developers of the APIs used for ISS tracking and geolocation services. Additionally, gratitude to the Python community and contributors for their valuable insights and support in developing this ISS tracking script.
