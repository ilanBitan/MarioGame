# SuperClaw
![image](https://user-images.githubusercontent.com/62257681/139892750-1cc92012-6f68-4812-868d-65b1d8614140.png)

**This is my first 2D game based on Mario nostalgic game.**

## To Run

1. You must have Gradle 6.3+ and Java 1.8+ installed. If you do not have these installed, you should install them and add them to your environment variables.
    * Once you have them installed you should be able to run:

        > ```gradle --version```

        and

        > ```java -version```

        And get no errors.
2. Open a Command Prompt in the projects root directory.
    * If you run ```ls``` (Mac, Linux) or ```dir``` (Windows) you should see ```libs```, ```src```, and ```assets``` listed as *part* of the output.
3. Run:
    >```gradle fatJar```
    * This will create a fat JAR containing all the dependencies for the game.
4. Run
    >```java -jar build/libs/mario-1.0-SNAPSHOT-all.jar```
    * This should open a new Window with the Mario game running.
    
![image](https://user-images.githubusercontent.com/62257681/139877858-eb643d39-2a27-435c-9032-cb0008f09f34.png)
