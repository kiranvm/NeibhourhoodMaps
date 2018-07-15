This is an Application using the Knockout framework, Google Street View APIs and Foursquare Places API to make a neighbourhood map which lists and marks out places using APIs asynchronously. Knockout is used to handle the list, filter, and any other information on the page that is subject to changing state. 

    Project:

    1. Implements a list view of the set of locations as defined in the helper file.

    2. Provide a filter option that uses an input field to filter both the list view and the map markers displayed by default on load. The list view and the markers update accordingly in real time. 

    3. Map marker assistance bubbles when list view entry is clicked (ex: Yelp reviews, Wikipedia, Flickr images, etc). Note that StreetView and Places don't count as an additional 3rd party API because they are libraries included in the Google Maps API. 

    4. Functionality to animate a map marker when either the list item associated with it or the map marker itself is selected.

    5. Functionality to open an infoWindow with the information described when either a location is selected from the list view or its map marker is selected directly.

  
Further Jquery references are here. http://api.jquery.com/val/

Google Street View API documentation here. https://developers.google.com/maps/documentation/streetview/intro

Foursquare Documentation here https://developer.foursquare.com/

Knockout Documentation here http://knockoutjs.com/documentation/introduction.html

Ignored js/secret_keys.js file format is as given below:

var keys = {
        foursquareClientId: 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX',
	foursquareClientSecret: 'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX'
};

How to Setup the Application

1. Git Clone the application or download the zip file to your PC 
2. Create your Google Maps API Key by refering to the below material
	- https://developers.google.com/maps/documentation/streetview/get-api-key
3. Create your Foursquare Application and generate Foursquare Client ID and Client Secret
4. Replace the Google Maps API Key in Line no: 67 Column No:90 of index.html file
5. Replace values of foursquareClientId and foursquareClientSecret in js/secret_keys.js in to the newly generated values.
6. Change the locations in js/locations.js file as per the locations you want to display in the map.
7. Launch the application by launching the index.html file
