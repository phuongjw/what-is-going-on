# June 11, 2025.

## What is the Model-View-Controller (MVC) architecture?

A software architectural pattern that separates an application's logic into three interconnected components:
- The model
- The view
- The controller

This patter promotes a clean separation of concerns, making applications more modular, testable, and maintainable.

### Breakdown of each component:

**Model:**

Represents the application's data and logic. It handles data access, storage, and manipulation. For example, in a web application, the model might interact with a database to retrieve or store information.

**View:**

Represents the user interface. It displays the data from the model to the user and allows the user to interact with the application. The view might be a web page, a mobile screen, or any other presentation layer.

**Controller:**

Acts as an intermediary between the model and the view. It receives user input, processes it, updates the model, and then instructs the view to display the updated data. The controller manages the flow of control within the applicaiton.

## What is Knockout.js?

If you know React.js, Knockout.js is pretty similar as they both try to make it easier to build **dynamic**, **interactive user interfaces**. However, instead of a **Component-based architecture** like React, Knockout.js uses Model-View-ViewModel (MVVM) architecture.

### What is Model-View-ViewModel (MVVM)?

- **Model:** Data from the server or application logic
- **View:** The HTML UI
- **ViewModel:** The JavaScript code that connects the view and the model
