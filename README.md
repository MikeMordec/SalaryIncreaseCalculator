SalaryIncreaseCalculator
Description

This C++ program reads employee data from an input file, calculates updated salaries based on a specified pay increase percentage, and writes the results to an output file. The application is designed for processing and updating salary information efficiently.
Features

    Reads Data: Extracts employee details (first name, last name, current salary, and pay increase percentage) from an input file.
    Calculates Salaries: Computes updated salaries based on the provided pay increase percentage.
    Outputs Results: Writes the updated salary information to an output file.

Getting Started
Prerequisites

    A C++ compiler (e.g., g++, clang++)

Compilation

To compile the program, use the following command:

bash

g++ -o SalaryIncreaseCalculator Lab1_PE_3_5.cpp

Usage

    Prepare an input file with the following format:

    php

<LastName> <FirstName> <CurrentSalary> <PayIncreasePercentage>

Example:

Doe John 50000 5
Smith Jane 60000 3

Run the compiled program:

bash

    ./SalaryIncreaseCalculator

    Enter the name of the input file when prompted. The program will generate an output file named Ch3_Ex5Output.dat with the updated salary information.

Example

If the input file contains:

Doe John 50000 5
Smith Jane 60000 3

The output file Ch3_Ex5Output.dat will contain:

John Doe 52500.00
Jane Smith 61800.00
