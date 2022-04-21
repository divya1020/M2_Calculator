
# Calculator


## Introduction


The objective of this project is to build a calculator using microcontroller atmega382 to perform various tasks like multiplication, addition, subtraction and division. Calculator is considered an embedded system because in addition to calculating answers, it is also handling low level functions such as input from the keypad and output to the LCD screen.

## Features

- This allows students to solve complicated problems quickly and in an efficient manner
- It performs numerical operations like 
1. multiplication
2. addition
3. subtraction
4. division


## Software Used

- SimulIDE
- Visual Studio


## Components Used

- 4x4 Keypad
- ATmega328 microcontroller.
- 16x2 LCD

# Requirements

There are two types of requirements:

# High Level Requirements


| ID | Description | Status |
| -------- | -------- | ---------- |
| HLR_1 | Microcontroller | Implemented |
| HLR_2 | It should display the inputs enter by user | Implemented |
| HLR_3 | It should perform operations and display the result on LCD Screen | Implemented |
| HLR_4 | Software Design | Implemented |




# Low Level Requirements

| ID | Description | Status |
| -------- | -------- | ---------- |
| LLR_1 | Take input from user from the keypad input, 4x4 Keypad | Implemented |
| LLR_2 | ATmega328 | Implemented |
| LLR_3 | LCD | Implemented |
| LLR_4 | Visual Studio, Simulide | Implemented |





# Swot Analysis
 
## Strength
 
-   Small in size and portable
-   It allows students to solve complicated problems quickly and in an efficient manner
-   Low Cost
-   Easy to use


## Weakness

- Always power supply is needed for the calculator to perform an operation.
- Performing complex mathematical operations is difficult.

## Opportunities

- Complex operations can be done by modification
- We can reduce power consumption


## Threats

- Advanced calculators are already created
- Portable devices like mobile and laptops are widely used rather than electronic calculator
- No options to save previous calculations



![Swot Analysis](https://user-images.githubusercontent.com/88372627/164445831-ff1c23e7-cfa7-4b84-8806-74bead21f975.png)


# 4W's and 1 H's

## When 
- Anyone can use calculator from anywhere
- This calculator can be used in daily life to avoid mistakes.


## Why
- To get correct solution
- To reduce time and energy
 

## Who
- Can be used by anyone for numerical operation

## Where
- It can be used in various systems from anywhere.


## How
-  By giving different inputs one can find their desired output.


![4W's and 1 H's](https://user-images.githubusercontent.com/88372627/164444658-28639801-89fe-450d-9f35-edeb196adfd3.png)




# Design 










# Test Cases

## High Level

| ID | Description | I/P | Expected O/P | Actual O/P | Type Of Test |
| --- | ---------- | --- | ------------- | ---------- | ----------- |
| HL_1 | Input from the user | Input value | Should give output | Successful | Input based |
| HL_2 | Giving output from the input |  Input value from the user | Shows Output | Successful | Input based |






## Low Level 

| ID | Description | I/P | Expected O/P | Actual O/P | Type Of Test |
| --- | ---------- | --- | ------------- | ---------- | ----------- |
| LL_1 | Performing operation '+' |      |     |      |  Requirement based |
| LL_2 | Performing operation '-' |      |     |      |  Requirement based |
| LL_3 | Performing operation '*'|       |     |      |  Requirement based |
| LL_1 | Performing operation '/' |     |     |      |  Requirement based |
