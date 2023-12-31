# Meet App

A serverless, React progressive web app that uses a test-driven development technique. The application uses the Google Calendar API to fetch upcoming events.

## Key Features

-Filter Events by City.
-Show/Hide Event Details.
-Specify Number of Events.
-Use the App When Offline.
-Add an App Shortcut to the Home Screen.
-Display Charts Visualizing Event Details.

## User Stories & Scenarios

Scenario: Filter events by city
Given: a function was written to filter events by cities
When: the user selects a city within the filter
Then: the function will return the events in the selected city

Scenario: Show/hide event details
Given: the list of events was loaded
When: the user clicks on “Show details” for an event
Then: the event element will be expanded to show the event details including
    Name of Event
    Time and Date of event
    Locatin of Event
    About the Event
    Button to view in google calendar
    hide/show details button

Scenario: Specify number of events
Given: the list of events was loaded
When: the user selects a number of events
Then: the number of events displayed will update based on the user input

Scenario: Use the app when offline
Given: the app was created to be functional offline
When: the user uses the app offline
Then: the functionalities will still be functional

Scenario: Add an app shortcut to the Home Screen
Given: the app shortcut was added to the Home Screen
When: the user selects the shortcut
Then: the app will open from the home screen

Scenario: Display charts visualizing event details
Given: the event details were loaded into a chart
When: the user selects the given event 
Then: the appropriate chart will be displayed for that event

## Serverless Function Usage
In this app, serverless functions will be used for authentication by requesting and retrieving access tokens.



