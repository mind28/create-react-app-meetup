# WuzUp

WuzUp is a web app that will allow users to browse events in their city.

## Technology

WazUp will be using react for the client side and AWS for the server side.

## User Stories

1.  As a user,

I should be able to show and hide event details.

So that the user can view the list of events clearly.

2.  As a user,

I should be able to specify the number of events viewed in the events list.

So that the app can accommodate all screen sizes and internet connection speeds.

3.  As a user,

I should be able to use the app while offline.

So that the user can view their upcoming events without internet connection.

4.  As a user,

I should be able to view a chart of all events in a city.

So that the user can have a quick overview of events in their city.

## scenarios

### Filter Cities

1.  Given the user has navigated to the home page.

When the user does not search for a city

Then the user will see a list of all upcoming events

2.  Given the user has navigated to the home page.

When the user starts typing their city in the textbox.

Then they will see a list of suggested cities. 3)
Given the user has typed a city in the textbox.

When the user selects a city from the suggested city.

Then they will navigate to the city page where they will view a list of events for their city.

### Show/Hide event details

1.  Given the user has NOT selected an event from the event list.

When the user selects an event from the event list.

Then the user will see the full details of the selected event.

2.  Given the user has not closed the full details component.

When the user closes the full details component.

Then the user will see the list of events again.

### Users to specify the number of events to view

1.  Given the user has navigated to the event list page.

When the user does NOT specify the number results they want to view.

Then the user will see 32 events as a default.

### Offline Usage

1.  Given the user does not have internet connection.

When the user attempts to view cached data.

Then the user will be able to view previously viewed cached data

2.  Given the user does not have internet connection.

When the user tries to view new data that has not been cached.

Then the user will see an error message.

### Data Visualization

1.  Given the user has navigated to the city’s events list page.

When the user views the page.

Then the user will see a chart with the total events in the city.
