## File Structure

```
Training Day 2
    - Main.java
    - Supply.java
```

## Overview

### Training Day 2

#### Supply
The `Supply` class manages food information by providing methods to input and display details about the food item. It includes:
- `GetType()`: Determines the type of food based on the sticker color.
- `FoodIn()`: Prompts the user to input food details and sets the member variables.
- `FoodOut()`: Displays the food details.

#### Main
The `Main` class serves as the entry point for the program. It creates an instance of the `Supply` class, calls the `FoodIn()` method to input food details, and then calls the `FoodOut()` method to display them.


## Getting Started

To run these programs, ensure you have Java installed on your machine. Compile and run the programs using the following commands:

```sh
javac Supply.java
javac Main.java

java Main
```
