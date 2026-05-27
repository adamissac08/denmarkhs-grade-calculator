# Forsyth Grade Calculator
1st Coding Project

A Python-based grade calculator created for students in Forsyth County Schools and Denmark High School. This program calculates weighted class averages using formative and summative grades while also predicting the final letter grade.

## Features

* Calculates weighted averages using summative and formative categories
* Validates user input to prevent invalid grades or percentages
* Displays:

  * Lowest grade
  * Highest grade
  * Average summative score
  * Average formative score
  * Final numerical grade
  * Final letter grade
* Supports customizable grading weights for different classes

## How It Works

The program asks the user for:

1. Class name
2. Summative weight percentage
3. Formative weight percentage
4. Number of summative grades
5. Number of formative grades
6. Individual grades for each category

The calculator then:

* Computes averages
* Applies weighted grading percentages
* Outputs the final course grade and letter grade

## Technologies Used

* Python
* Lists
* Functions
* Loops
* Input validation
* Basic data processing

## Example Output

```bash
What is the name of the class you want your grade calculated for? Biology

How much percent do Summatives contribute to your overall grade?: 70
How much percent do Formatives contribute to your overall grade?: 30

How many summative grades have you taken?: 3
Enter summative grades: 90
Enter summative grades: 85
Enter summative grades: 95

How many formative grades have you taken?: 2
Enter formative grades: 100
Enter formative grades: 92

Your final grade calculation for Biology is: 91.4
Your final letter grade is an A
```

## Purpose

This project was created as a collaborative school programming assignment to help students better understand how weighted grading systems work in high school classes.

## File Structure

```bash
grade_calculator.py
README.md
```

## Author

Created by Adam Issac and a project partner.
