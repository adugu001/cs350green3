# cs350green3
Repo for cs350 green3 to establish working development process

# Dependencies
1. Gradle 4.4.1
2. Java 21

# How To Run
1. Build from the right directory:
    
    For Gradle to properly build the software it has to be executed from the proper directory
    ``` bash
    cd ./generic-path/cs350green3
    ```
2. Do a clean build of the jar file:
    
    
    This allows cleaning of any platform specific build files generated previously, ensuring the build suite can properly compile on your machine.

    The executable will be placed in ```/CS350green3/build/lib```
    

    ``` bash
    ./gradlew clean build
    ```
3. Run the executable jar:
    ``` bash
    java -jar build/libs/cs350green3.jar <path> [options]
    ```

# How To Test

# Project Structure