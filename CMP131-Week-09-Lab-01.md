# CMP 131 – Python Programming

> **Required file location:** Keep every Python file directly in the repository root. Do not create a `src` folder.

## Week 9 – Lab 1: Functions and Return Values

**Total Points: 100**

- Program 1: Kinetic Energy — 30 points
- Program 2: Celsius Temperature Table — 30 points
- Program 3: Future Value — 40 points

## Learning Objectives

After completing this lab, students should be able to:

- Define and call Python functions.
- Pass arguments to functions.
- Use parameters to receive information.
- Perform calculations inside functions.
- Return calculated values to the calling statement.
- Store and display returned values.
- Use a loop to call a function repeatedly.
- Convert numeric user input.
- Format numeric and monetary output.
- Organize programs using a `main()` function.
- Test functions using different input values.

## Assignment Overview

Create three separate Python programs that demonstrate functions, parameters, arguments, and return values:

1. `kinetic_energy.py`
2. `celsius_temperature_table.py`
3. `future_value.py`

Each program must include at least one function that performs the required calculation and returns the result.

The instructor is not providing completed Python code or an exact output design. Students must design, write, and test their own programs.

# Program 1: Kinetic Energy

**Points: 30**

An object's kinetic energy is calculated using:

**KE = 1/2 × m × v²**

where:

- `m` is mass in kilograms.
- `v` is velocity in meters per second.

Create `kinetic_energy.py`.

Your program must:

- Display a descriptive title.
- Ask the user for mass and velocity.
- Convert both values to appropriate numeric types.
- Pass the mass and velocity to a function.
- Have the function calculate kinetic energy.
- Return the kinetic energy to the calling statement.
- Display the result clearly.
- Organize the program using a `main()` function.

Test several different mass and velocity values and confirm the returned result is correct.

# Program 2: Celsius Temperature Table

**Points: 30**

Create `celsius_temperature_table.py`.

Use the conversion formula:

**Celsius = 5/9 × (Fahrenheit - 32)**

Your program must:

- Include a function that accepts a Fahrenheit temperature.
- Convert the Fahrenheit value to Celsius inside the function.
- Return the Celsius result.
- Use a loop to process Fahrenheit temperatures from 0 through 20.
- Call the conversion function during each loop repetition.
- Display a clearly labeled Fahrenheit-to-Celsius table.
- Organize the program using a `main()` function.

Do not manually write 21 separate conversions.

# Program 3: Future Value

**Points: 40**

Create `future_value.py`.

The future value of an account is based on:

- Present value or starting balance.
- Monthly interest rate.
- Number of months the money remains in the account.

Use the standard future-value relationship:

**Future Value = Present Value × (1 + Monthly Interest Rate) ^ Number of Months**

Your program must:

- Display a descriptive title.
- Ask the user for the present value.
- Ask for the monthly interest rate.
- Ask for the number of months.
- Convert the values to appropriate numeric types.
- Pass the required values to a function.
- Have the function calculate and return the future value.
- Display the future value as a monetary amount with two decimal places.
- Organize the program using a `main()` function.
- Validate values when appropriate so negative or invalid financial inputs are not accepted.

Test the program with multiple input combinations and verify the returned value.

# Function Requirements

Across the three programs:

- Use meaningful function names.
- Use parameters to receive data.
- Use arguments when calling functions.
- Return calculated values rather than relying only on output inside the calculation function.
- Keep user interaction and calculation responsibilities organized clearly.
- Use a `main()` function where required.

# Code Comments

Each Python file must include a comment header containing:

- Student name
- Course number
- Week number
- Lab number
- Assignment title
- Date

Use comments to explain major sections such as input, function definitions, calculations, loops, returned values, and final output.

# General Requirements

- Keep all Python files directly in the repository root.
- Make sure all three programs run without errors.
- Test every function with more than one value.
- Use clear labels and readable formatting.
- Follow `AI-Use-Policy.md`.
- Complete `AI-Use-Report.md` honestly.

# Submission Requirements

Your repository must include:

- `CMP131-Week-09-Lab-01.md`
- `kinetic_energy.py`
- `celsius_temperature_table.py`
- `future_value.py`
- `AI-Use-Policy.md`
- `AI-Use-Report.md`

Before submitting:

1. Run and test all three programs.
2. Confirm filenames are correct.
3. Confirm all Python files are in the repository root.
4. Complete the AI-use report.
5. Commit and push your latest work.
6. Verify the newest files on GitHub.
7. Submit through Blackboard Ultra as directed.

**Do not push your work to the instructor's starter repository.**
