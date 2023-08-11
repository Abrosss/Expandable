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

# Data Binding
Data binding is a programming concept that enables synchronization and communication between different parts of a software application, often between user interface elements and the underlying data or business logic. It allows changes in one element to automatically reflect in another element without requiring explicit updates.Data Binding allows us to communicate between a component class and its corresponding view template

## One way Data Binding
Data only flows in one direction, either:
- When we can access the COmponent's properties in its corresponding View Template
- We can also access a value in the View Template in the Component Class
</br>
However, changes in the UI don't affect the data source. This is often used to display data to the user.

## Two way Data Binding
Data flows both ways. Two-way data binding not only updates the UI when the data source changes, but it also updates the data source when the user interacts with the UI. This enables a seamless synchronization between the UI and the data.

# Concurrency design patterns
concurrency patterns are those types of design patterns that deal with the multi-threaded programming paradigm. </br>
Concurrency design patterns are a set of reusable solutions and best practices used in software development to manage and address challenges related to concurrent and parallel programming. Concurrency involves the execution of multiple tasks or processes simultaneously, while parallelism involves the actual execution of those tasks on multiple processors or cores. </br>
