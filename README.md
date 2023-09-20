
# BeatTheQueue

This repository contains the code for BeatTheQueue, a web-based service designed to help you beat the queues at theme parks. 
The service allows users to select a theme park, preferred rides, and maximum wait time.
It then provides real-time alerts based on queue times for the selected rides.

## How to Use

1. Open the `theme_park_trip_planner_complete_with_api_calls.html` file in a web browser.
2. Select your preferences and click the "Generate Alerts" button.
3. Receive real-time alerts based on your selected preferences and real-time queue data.

## Acknowledgment

Powered by [Queue-Times.com](https://queue-times.com/)

## Outline for BeatTheQueue

### Core Features

1. **Data Collection**
    - Fetch data from the queue-times API.
    - Parse the JSON data to get ride details like name, wait time, and status (open/closed).

2. **User Preferences**
    - Ask the user for their preferences, such as favorite rides, tolerance for wait times, etc.

3. **Trip Planning Algorithm**
    - Use the user's preferences and the API data to generate an optimized trip plan.

4. **Notifications**
    - Implement a system to send push notifications for ride wait times and status changes.

### Future Features

5. **Flight Deals**
    - Integrate with Skyscanner or Google Flights API to notify users of flight deals to the theme parks they are interested in.

6. **Best Times to Visit**
    - Analyze historical data to suggest the best times to visit.

7. **iOS App**
    - Wrap all these features into an iOS app.

