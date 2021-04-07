# City Filter for Contacts | Vanilla JavaScript DOM Manipulation

[Live Site](https://brianhook1183.github.io/JSDOM_final-assignment/)

This is an assignment for Thinkful's Software Engineering bootcamp ([starter project](https://github.com/Thinkful-Ed/jsdom-assignment-solution)).

## What it Does
+ `Filter By City` list is dynamically generated from the given `contacts` list
+ Selecting `" -- Select a city --"` will render all contact cards to the DOM
+ Selecting any other city will filter the contact cards
+ Deleting a contact card will delete that contact from `contacts` and remove the card from the DOM (you can reset by reloading the page).


## Additional Features
I added the following features and improvements after the assignment was submitted and accepted (`test/solution.test.js` may no longer show all passing tests because of these updates).
+ handled edge case of capitalization errors in a contact's listed city
   + (`"South Vale"` and `"South vale"` assumed to be same city - now merged in `Filter By City` dropdown)
+ filtered view now persists after a contact is deleted instead of refreshing to all contacts.
+ `"0 results"` feedback when the last contact of a selected city is deleted
+ Cities that have zero contacts to display can still be selected, `"0 results"` will display. 
+ Added a custom favicon

## Skills Used

The focus of the assignment was DOM manipulation done purely through vanilla js - no jquery or other additional libraries.
+ selecting elements
+ updating the DOM
+ event listeners
+ form submissions
+ render pattern