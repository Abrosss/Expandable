# MVC
Developers use different patterns to layout applications. One of them is MVC. Model - View - Controller </br>
The goal of this pattern is to split a large application into specific sections that have their own purpose.
- Model handles data logic and interacts with database
- Controller handles user requests, errors
- View handles data/error presentation and rendering
</br>
Model and View never interact with each other, they only interact through the Controller
</br>
The MVC pattern promotes separation of concerns, making the codebase more organized, modular, and maintainable.

# MVVM
MVVM stands for Model - View - ViewModel. It is an architectural pattern that helps to separate the user interface (UI) from the business logic and data of an application.
- Model handles data/databases/API and business logic
- ViewModel. This is the part that acts as a bridge between the view and the model. 
- View doesn't contain any business logic, it only contains logic to directly manipulate views.
</br>
MVVM is a powerful pattern to make an application scalable, easily testable and understandable
