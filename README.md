# JSnake

## what is that?
It's a passion projet made in java, where I want to recreate the famous snake game by making my own "engine" in Java

> The project started on the 28th of march 2024 and was highly inspired by a video from Bro Code [here](https://www.youtube.com/watch?v=bI6e6qjJ8JQ). 

![](https://github.com/fixiple/JSnake/assets/59767843/1fcb315e-4e9a-400f-9130-704670120775)

## Getting Started

To launch the main program (file containing the main function), do the following (more info see [here](https://www.baeldung.com/javac-compile-classes-directory#using-file-names) and [here](https://stackoverflow.com/a/42819276)), like below:

```bash
javac -sourcepath ./src/ -d ./bin/ ./src/App.java  
java -cp bin App # bin = folder containing the .class files || App = filename/class
```

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

