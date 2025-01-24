**Tetris Bot Project**
======================

Welcome to the Tetris Bot Project! This repository contains the implementation of various phases of a Tetris game, including AI bots, game logic, and user interfaces. The project demonstrates how different algorithms and strategies can be applied to solve problems in a Tetris-like environment.

**Table of Contents**
---------------------

*   [About the Project](#about-the-project)
    
*   [Features](#features)
    
*   [Directory Structure](#directory-structure)
    
*   [Getting Started](#getting-started)
    
*   [Usage](#usage)
    
*   [Contributing](#contributing)
    
*   [License](#license)
    

**About the Project**
---------------------

This project is an exploration of artificial intelligence and algorithms applied to the game of Tetris. It consists of:

*   AI bots that analyze and determine optimal moves.
    
*   A graphical user interface (GUI) for interacting with the game.
    
*   Different algorithms, including brute force and greedy strategies, implemented for solving problems within the game.
    

**Features**
------------

*   **AI Bots**:
    
    *   Several bots with varying strategies to optimize gameplay.
        
*   **Pentomino Handling**:
    
    *   Efficient handling of pentomino shapes using a database.
        
*   **User Interface**:
    
    *   A GUI for interacting with the game and observing bot behavior (powered by JavaFX).
        
*   **Algorithms**:
    
    *   Implementation of brute force and greedy approaches.
        

**Directory Structure**
-----------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   cssCopyEditproject-1-1-main/  ├── Phase 2/  │   ├── TetrisBot/  │   ├── TetrisGame/  │   ├── pentominos/  │   ├── tetris/  ├── Phase 3/  │   ├── src/  │   ├── QuestionC/  │   ├── Database/  ├── README.md   `

*   **Phase 2**: Contains bot and game logic.
    
*   **Phase 3**: Advanced implementations, including dancing links and other algorithms.
    
*   **pentominos.csv**: Stores data about pentomino shapes.
    

**Getting Started**
-------------------

### Prerequisites

*   **Java Development Kit (JDK)**: Ensure JDK 8 or later is installed.
    
*   **JavaFX SDK**: Required for running the GUI. Download the appropriate version from the [JavaFX website](https://openjfx.io/).
    
*   **IDE**: Use any Java IDE, such as IntelliJ IDEA, Eclipse, or VSCode.
    

### Installation

1.  bashCopyEditgit clone https://github.com/your-username/tetris-bot.gitcd tetris-bot
    
2.  Download and set up the **JavaFX SDK**:
    
    *   Add the lib directory of the JavaFX SDK to your project dependencies.
        
    *   bashCopyEdit--module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
        
3.  Open the project in your preferred IDE.
    
4.  Configure the project to include the JavaFX library in the build path.
    
5.  bashCopyEditjavac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -d bin src/\*.java
    

**Usage**
---------

1.  bashCopyEditjava --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -cp bin TetrisGUI
    
2.  Experiment with different bots by modifying their configurations in the source files.
    
3.  Use the provided pentomino data in pentominos.csv for customization.
    

**Contributing**
----------------

We welcome contributions to this project! To contribute:

1.  Fork the repository.
    
2.  bashCopyEditgit checkout -b feature/your-feature
    
3.  bashCopyEditgit commit -m "Add your feature"
    
4.  bashCopyEditgit push origin feature/your-feature
    
5.  Open a pull request.