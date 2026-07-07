# BMI Calculator (Java)

## Overview

This is a simple Java console application that calculates a user's **Body Mass Index (BMI)** based on their weight and height. The program accepts the user's weight in **pounds (lbs)**, converts it to **kilograms (kg)**, calculates the BMI using the standard formula, and displays the corresponding BMI category.

## Features

* Accepts user input for:

  * Weight in pounds (lbs)
  * Height in meters (m)
* Converts weight from pounds to kilograms
* Calculates BMI using the standard formula
* Displays the calculated BMI
* Classifies BMI into one of the following categories:

  * Underweight
  * Healthy weight
  * Overweight
  * Obese

## BMI Formula

[
\text{BMI} = \frac{\text{Weight (kg)}}{\text{Height (m)}^2}
]

Weight conversion:

```
1 pound = 0.453592 kg
```

## BMI Categories

| BMI Range      | Category       |
| -------------- | -------------- |
| Below 18.5     | Underweight    |
| 18.5 – 24.9    | Healthy weight |
| 25.0 – 29.9    | Overweight     |
| 30.0 and above | Obese          |

## Requirements

* Java Development Kit (JDK) 8 or later
* Any Java IDE (Eclipse, IntelliJ IDEA, VS Code) or command line

## How to Run

1. Compile the program:

```bash
javac BMICalculator.java
```

2. Run the program:

```bash
java BMICalculator
```

3. Enter your:

   * Weight in pounds
   * Height in meters

4. The program will display:

   * Your BMI
   * Your BMI category

## Example

**Input**

```
Enter your weight in Pounds:
150

Enter your height in meters:
1.75
```

**Output**

```
Your BMI is: 22.22
You are Healthy weight
```

## Project Structure

```
day4/
└── BMICalculator.java
```

## Author

Created as a beginner Java project to practice:

* User input with `Scanner`
* Arithmetic calculations
* Unit conversion
* Conditional statements (`if-else`)
* Basic console output

