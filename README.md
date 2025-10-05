## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

## Compile and Run:

# Compile all Java files
javac -d bin src/com/mile1/bean/Student.java src/com/mile1/exception/*.java src/com/mile1/service/*.java src/com/mile1/main/StudentMain.java

# Run the program
java -cp bin com.mile1.main.StudentMain
