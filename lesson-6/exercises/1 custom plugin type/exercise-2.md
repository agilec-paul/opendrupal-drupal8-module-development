# Custom plugin type - Exercise 2
Estimated time: 45 minutes.

As a developer I want to structure my code to be loosly coupled and maintainable.

Create a service that loads the HTML.

- Use of descriptive names for the service and the method(s).
- Use the same code as in the PoC. Refactor when necessary.

Create a service that parses DOM data. 

- Start with the parsing code from the PoC.
- Use the simplehtmldom library to convert the HTML response to a DOM object. Add a composer.json to add this library.
- Use a dedicated method to return the h1 text from the DOM. 
- Separate concerns by using (at least) two different methods for the above.
