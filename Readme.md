# Plants Vs Zombies
**Created by:
[Himanshu Raj](https://www.github.com/himanshuraj18) and [Pankil Kalra](https://www.github.com/pankilkalra)**

A clone of Plants vs Zombies made from scratch using JavaFX. Applied OOPs concept and suitable Design Patterns.
Made as a part of project in Advanced Programming course at IIIT-Delhi.

### Features-
1. 5 levels with increasing difficulty.
2. 4 different types of Plants to protect your arena.
3. Restart, Load and Save game feature.
4. Multiple User Support.

### Tools and Technologies Used-
1. JavaFX: Animations in the game were implemented using Controllers and AnimationTimer available in the JavaFX platform.
2. FXML Scene Builder
3. Intellij IDE
4. Lucidchart for UML Diagram

### Design Patterns Used-
1. Model View Controller
   - Model : All classes and implementation of different functionality.
   - View  : FXML (for GUI) files
   - Controller : It uses model to make changes in view (or GUI).
2. Iterator to ensure that Plant, Zombie and Lawnmower lists are accessed in a synchronized way.
3. Facade for menu based implementation.
4. Singleton for the database and for progress bar feature, as we need only one reference through out the game.

### Screenshots of Game
![alt_text](https://github.com/himanshuraj18/PlantsVsZombies/blob/master/Screenshots/final-1.png)


![alt_text](https://github.com/himanshuraj18/PlantsVsZombies/blob/master/Screenshots/final-2.png)


![alt_text](https://github.com/himanshuraj18/PlantsVsZombies/blob/master/Screenshots/final-3.png)


![alt_text](https://github.com/himanshuraj18/PlantsVsZombies/blob/master/Screenshots/final-4.png)


### How to run this Game?
- For running it in Eclipse or IntelliJ IDE
   1. Clone this repository.
   2. Open the folder PlantsVsZombies.
   3. Open PVZ folder as IntelliJ or Eclipse project.
   4. Build and Run.
- For running it from terminal or command prompt
   1. Clone this repository.
   2. Go to PlantsVsZombies/PVZ/src folder from terminal.
   3. Compile the sample package using following command.
        - ```javac ./sample/Login.java```
   4. Run the game using following command.
        - ```java sample.Login```

Enjoy the Game!!
