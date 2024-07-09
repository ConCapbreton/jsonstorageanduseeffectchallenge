Dave Gray youtube tutorial (link below) for React JS creating a Json storage display App
Project completed 09/07/2024 
Button click sets the reqType state to the text of the button.
Uses useEffect to fetch data whenever reqType is changed (whenever a button is clicked).
Button color / text is controlled using a ternary operator to determine className dependent on reqType ! If className is "selected" (because buttonText === reqType) then CSS "selected" class selector is used to change that button's styles. 
reqType is also used to modify the API href to get the correct data from https://jsonplaceholder.typicode.com/ and "setItems" accordingly.
Then the data (in the items array) is simply mapped. 

In the second part of the project Dave Gray shows how to format the data from a simple list to a table using table, tb, tr and td HTML elements accompanied with some CSS styling. No new states are created in order to achieve this.

link: https://www.youtube.com/watch?v=RVFAyFWO4go