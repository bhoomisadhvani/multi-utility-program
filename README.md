C Programs Collection

This repository contains three simple C programs written using the stdio.h library. Each program demonstrates basic input, calculation, and output concepts in C.

1. Celsius to Fahrenheit Converter
Description

This program converts a temperature from Celsius to Fahrenheit using a mathematical formula.

Formula Used
Fahrenheit = (0.9 / 0.5) × Celsius + 32

How It Works

Takes Celsius temperature as input from the user

Converts it into Fahrenheit

Displays the result up to two decimal places

Sample Output
enter celsius value: 25
77.00

2. Gross Salary Calculator
Description

This program calculates the gross salary based on base salary and allowance percentages.

Inputs Required

Base Salary

HRA (House Rent Allowance) percentage

DA (Dearness Allowance) percentage

TA (Travel Allowance) percentage

Formula Used
Gross Salary = Base Salary × (1 + (HRA + DA + TA) / 100)

Sample Output
enter your base salary: 20000
enter your hra: 10
enter your da: 5
enter your ta: 2
23400.00

3. Third Angle of a Triangle
Description

This program calculates the third angle of a triangle when the first two angles are given.

Formula Used
Third Angle = 180 − (First Angle + Second Angle)

How It Works

Takes two angles as input

Calculates the third angle

Displays the result

Sample Output
enter first angle: 60
enter second angle: 50
third angle is 70

Requirements

C Compiler (GCC recommended)

Basic knowledge of C programming

How to Compile and Run
gcc filename.c
./a.out
