# Running a Class within Another Class

This repository contains a simple Java project that demonstrates how to run a class within another class.

## Getting Started

To run the project on your local machine, follow these steps:

### Prerequisites

- Java Development Kit (JDK) installed on your machine.

### Clone the Repository

1. Open a terminal or command prompt.
2. Change the current working directory to the location where you want to clone the repository.
3. Run the following command to clone the repository:

   ```
   git clone https://github.com/lelokarma/Multiple-Classes-in-Java.git
   ```

### Running the Application

1. Navigate to the project directory:

   ```
   cd Multiple-Classes-in-Java.git
   ```

2. Compile the Java source files:

   ```
   javac javafxGui/RunnableClass.java
   ```

3. Once the compilation is successful, run the application:

   ```
   java javafxGui.RunnableClass
   ```

4. The application should now execute, and you will see the output in the console.

## Project Structure

The project has the following structure:

```
.
└── javafxGui
    ├── RunnableClass.java
    └── Aopples.java
```

- `RunnableClass.java`: The main class that runs the application and calls the `Aopples` class.
- `Aopples.java`: A custom class that contains the implementation of the `simpleMethod()`.

Feel free to explore the code and make any modifications as needed.

## Contributing

If you'd like to contribute to this project, you can fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
