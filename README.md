# Todo App

This is a simple Todo App built with Flutter, based on the tutorial from FreeCodeCamp: [Learn State Management in Flutter](https://www.freecodecamp.org/news/learn-state-management-in-flutter/).

## Overview

The Todo App allows users to create, manage, and track their todo items. It demonstrates the implementation of state management using the `StatefulWidget` and `setState` approach in Flutter.

## Features

- Add new todo items
- Mark todo items as completed or incomplete
- Delete todo items
- Display a list of all todo items with their completion status

## Getting Started

To run the Todo App on your local machine, follow these steps:

1. Make sure you have Flutter installed on your system. If not, you can follow the official [Flutter installation guide](https://flutter.dev/docs/get-started/install).

2. Clone this repository or download the source code.

3. Open the project in your preferred IDE or code editor.

4. Run the app using the following command:

```
flutter run
```

This will launch the app on your connected device or emulator.

## Project Structure

The entire project is contained within the `main.dart` file.

```
main.dart
```

- `main.dart`: This file contains the entry point of the application, the root widget (`TodoApp`), the stateful widget (`TodoList`), the data model class (`Todo`), and the stateless widget (`TodoItem`).

## Dependencies

This project has no external dependencies beyond the core Flutter framework.