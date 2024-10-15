# ORIGINAL NAME: Luna vs Pickles

Developed a 2D game using C# and the Unity engine. The game implements user settings and data
management features to operate the game. The game challenges players to navigate a character through obstacles, with game-over conditions based on collision detection and added background particles.

## How to run:

It is best to use UNITY. Install these files, then transport them to Unity. 
I had the help of [GMTK](https://www.youtube.com/@GMTK) on youtube, to build this game. 

## How to play:

When you click the start button, it should automatically throw the cat into the air. You must click the space button to keep it in the air. Try to navigate through the pickles. DO NOT let the cat get in contact with the pickles. If you do, game over. 
The system automatically counts how many you've done so as you navigate the pickles.

## Installation

-- install the Unity Hub application
    [Unity Website](https://unity.com/download)

1. git clone the repository to the local machine

```git clone <repository-url>```

2. Open the Unity Hub application and, in the application, click on the "Add" button and navigate it to the directory (where you cloned the repository). Then, select the folder to add the project to the Unity application.

3. After opening the project, click on it in Unity Hub to open it in the Unity Editor.

4. If there are missing packages or dependencies, Unity prompts you to install them-- follow the instructions/prompts to resolve the issue.

5. open the main scene from the /Users/beatriztorres/spaceGame/Assets/Scenes directory in the Unity Editor. Then click the "Play" button to run the game.

Double-check: Make sure you have the correct version of Unity installed that matches the project's requirements.

## Testing the Compilation of the Project

1. After launching and running the project, double-check for errors. In case of errors, Unity will automatically compile the scripts when saved or when the project is opened.
        - look at the console window Unity
            ```Window > General > Console```
        - If there are any compilation errors, they will be displayed here.

2. Run the game 

4. Build the Project:
    - go to File > Build Settings.
    - select your target platform.
    - click the "Build" button and choose a location to save the build.
    - Unity will compile the project and create an executable.

5. Test the Build
    - Navigate to the location where you saved the build.
    - Run the executable to ensure the game works outside Unity Editor.

If any other issues present, refer to the Console window for error messages and debug accordingly.

## Running Unit tests in Visual Studio Code

- Install the Unity test frame
    - Ensuring that the Unity project has the Unity test Framework installed- you can add it via the Unity Package Manager.
    - install .NET SDK; Ensure you have the .NET SDK installed on your machine.
                you can download it from [microsoft](https://dotnet.microsoft.com/en-us/download)

- Install the C# Extension

- Open the project in VS Code

- Create a test Script and place it in the ```Assets/Tests``` directory. Unity typically uses the NUnit framework for testing.

An example of a test script:
~~~cpp
Using NUnit.Framework;

public class ExampleTest
{
    [Test]
    public void TestMethod()
    {
        Assert.AreEqual(1, 1);
    }
}
~~~

- run the test: ```Window > General > Test Runner```
- run the test from the command line:
    unity -runTests -projectPath <path-to-your-project> -testResults <path-to-results-file>

This setup will allow you to write and run unit tests for the project within VS Code.

## Images

![alt text](<ImagesforReadMe/Screenshot 2024-09-10 at 5.37.40 PM.png>)

![alt text](<ImagesforReadMe/Screenshot 2024-09-10 at 5.37.31 PM.png>)