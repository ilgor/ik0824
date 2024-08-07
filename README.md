# Tool Rental System

This project was created using IntelliJ, JDK 22, Junit 5.8.2

## Unit tests

All the given unit tests are covered and added some more for edge cases.

## Printing the Rental Agreement

I have added Main class which can be run. It has the tool code, rental days, 
discount percent, checkout date are given and it will print out the Rental Agreement.
Those values can be changed to see other options. It will throw custom CheckoutException
if rental days are less than zero or discount percentage is not [0-100].