# Quotes Lab 08

## Feature Tasks
Feature Tasks
Use the file recentquotes.json to show random popular book quotes. Your program should use GSON to parse the .json file. The app
needs no functionality other than showing the quote and the author when it is run. The app should choose one quote each time it
is run.

This project is able to locate and parse a JSON file into a java object. It allows the user to generate a random author and quote from the JSON file.



## Tests

Grader can run code by running .gradlew test or by loading project into intelliJ and pressing the run button.

## Contributions
Worked with Sharmarke, Ryan, and Devon. Received some assistance from Raul and Rey.

Refactored random index function from stack overflow.

[//]: # (https://stackoverflow.com/questions/4023137/generating-a-random-index-for-an-array)

## Lab 09
## Feature Tasks
Feature Tasks
Start by refactoring anything that you don’t like about your solution from yesterday.
When running the application, don’t read in the quotes file. Instead, make a request to an API to get a random quote.
Rather than a Quote of the Day, please use an API that allows you to show a random quote.
We do still have this quotes file, though, and it might still be useful! Ensure that if your app has errors in connecting to the Internet, you instead display a random quote from your file.
When we grab a random quote from the Internet, we could add it to our file of quotes, for use if the app goes offline in the future. Add that functionality: when a quote comes back from a request, it’s also cached in the json file.


This project is able to send a request to an API and return the requested object. The object is able to be parsed and added to our local JSON file. It also allows you to locate and parse a JSON file into a java object. It allows the user to generate a random author and quote from the JSON file.



## Tests

Grader can run code by running .gradlew test or by loading project into intelliJ and pressing the run button.

## Contributions
Worked with Sharmarke and Ryan. Received some assistance from Rey, Raul, and Tammy.

Used stack overflow as a reference https://stackoverflow.com/questions/6467848/how-to-get-http-response-code-for-a-url-in-java