Challenge 3!

The objective of this challenge was to successfully create an employee payroll tracker. Given the starter code, the CSS and HTML were completed. It was my Job to build out the functions in JavaScript to complete the tracker. Bellow is the acceptence criteria along with the steps followed to complete it. 


``````
GIVEN an employee payroll tracker
WHEN I click the "Add employee" button
THEN I am presented with a series of prompts asking for first name, last name, and salary
WHEN I finish adding an employee
THEN I am prompted to continue or cancel
WHEN I choose to continue
THEN I am prompted to add a new employee
WHEN I choose to cancel
THEN my employee data is displayed on the page sorted alphabetically by last name, and the console shows computed and aggregated data
``````


1. The button already had an 'eventListener' attached to it looking for the click. Once clicked, the 'collectEmployees' function is started. To build this function I created an empty employeesArray along with a variable, 'continueAdding' and set it to true. 

2. I then used that variable to create a while loop allowing for mulitple employees to be added to the employeesArray using the .push method. When the user clicks cancel, the information in the employeesArray is printed onto the screen, sorted alphabetically by last name. The console displays the appropriate information associated with each employee. 

3. The final step was to select a random employee from the employeesArray and log them to the console. To do this we chose a random index using the length of the employeesArray to find a random number. From there, we pull the employee associated with that index and print them to the console. 

This challenge was fun an unique but definitly required some research on the best syntax and methods to use in order to find reach the desired outcome. The biggest challenge I encounted as ensuring that the information input to the salary field was a whole number. It took some research to figuire out the isNanN and parseFloat expressions but in the end I was able to ensure the salary field was filled out popperly.

