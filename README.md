# Phone Search App

This is a simple web application that allows users to search for phones using a search term. 
The application fetches phone data from an API and displays it on the page. Users can click on a phone to
view more details.

## Hosted Link -
https://sanketmahadik191.github.io/JS_WeekslyTest_5/

## JavaScript Functionality

Here's a brief overview of how the JavaScript functionality was used to build this application:

### Search Handler: 
The searchHandler function is responsible for handling search queries. 
When the user inputs a search term and clicks the "Search" button, this function is called. 
It sends a request to the API with the search term, retrieves phone data, and displays it on the page.

### Loading Spinner: 

The loading function is used to show/hide a loading spinner. 
It's called to indicate that the application is loading data.

### Load Phone Data: 
The loadPhone function sends a request to the API using the search term and retrieves phone data. 
It also handles the option to show all phones.

### Display Phones: 
The displayPhones function displays the retrieved phone data on the webpage. 
It creates HTML elements for each phone and appends them to the container. 
There's also a "Show All" button to view all phones.

### Show Details: 
When a user clicks on the "Show Details" button for a specific phone, the showDetailsHandler function is called.
It fetches additional details about the phone and displays them in a modal.

### Show Phone Details: 
The showPhoneDetails function displays detailed information about a phone in a modal. 
It includes the phone name, brand, specifications, and release date.

### Show All Button: 
The "Show All" button allows users to view all phones in the list.

## How to Use
Enter a search term in the search field.
Click the "Search" button to retrieve phone data.
Click on a phone to view more details.
Use the "Show All" button to view all phones.
 
