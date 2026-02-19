What I Learned
Understanding the Navigation System

How the Navigator manages a stack of routes (push and pop behavior)

The difference between direct navigation using MaterialPageRoute and named routes

How pushNamed and onGenerateRoute create a scalable routing system

How Flutter builds screens through Route objects, not widgets directly

Working With Routes

Setting up a clean onGenerateRoute structure inside MaterialApp

Creating routes that can receive dynamic data

Avoiding common mistakes like:

navigating inside build()

forgetting to pass arguments

type-casting errors with settings.arguments

Passing Data Between Screens

Sending data using route arguments (arguments: {...})

Receiving data inside onGenerateRoute

Extracting values safely using Map<String, dynamic>

Passing data into screen constructors cleanly and predictably

Screen Architecture & Folder Structure

Separating UI into a screens/ folder

Keeping each screen in its own file for clarity

Maintaining a clean and scalable project structure

Widget Usage & State Management

Using TextEditingController to read and manage user input

Storing and cleaning up controllers inside a StatefulWidget

Keeping the second screen Stateless because it only displays data
