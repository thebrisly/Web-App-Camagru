# Web-App-Camagru

<h1> MVC Model </h1>

<img width="695" alt="Capture d’écran 2024-07-30 à 21 07 10" src="https://github.com/user-attachments/assets/af0151cb-1b22-412e-9c1b-dff46fbb7ee9">

The Model View Controller architectural pattern separates concerns into one of 3 buckets:

Model: stores & manages data.
Often a database, in our quick example we’ll use local web storage on a browser to illustrate the concept.

View: Graphical User Interface
The view is a visual representation of the data- like a chart, diagram, table, form.

The view contains all functionality that directly interacts with the user - like clicking a button, or an enter event.

Controller: Brains of the application.
The controller connects the model and view. The controller converts inputs from the view to demands to retrieve/update data in the model.

The controller receives input from view, uses logic to translate the input to a demand for the model, the model grabs the data, the controller passes data from the model back to the view for the user to see in a nice display.

Source : https://www.educative.io/blog/mvc-tutorial
