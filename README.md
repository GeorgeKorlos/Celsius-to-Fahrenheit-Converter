# Celsius to Fahrenheit Converter: A Python Dictionary Comprehension Example

This repository contains a Python script that converts a dictionary of daily temperatures from Celsius to Fahrenheit using dictionary comprehension. This script is a great example for those learning about dictionary operations, comprehensions, and temperature conversion in Python.

## Description

The script performs the following steps:

1. **Takes user input:**
    - The user inputs a dictionary where the keys represent days, and the values represent temperatures in Celsius.

2. **Processes the input:**
    - A dictionary comprehension is used to convert each temperature from Celsius to Fahrenheit.

3. **Outputs the result:**
    - The script prints the resulting dictionary, showing each day and its corresponding temperature in Fahrenheit.

### How It Works

1. **User Input:**
    - The user is prompted to enter a dictionary of temperatures in Celsius (e.g., `{'Monday': 12, 'Tuesday': 14, 'Wednesday': 15}`).

2. **Temperature Conversion:**
    - The script converts each temperature from Celsius to Fahrenheit using the formula:
      \[
      \text{{Fahrenheit}} = \text{{Celsius}} \times \frac{9}{5} + 32
      \]
    - This conversion is applied to all key-value pairs in the input dictionary.

3. **Output:**
    - The script prints a new dictionary where the keys are the same days, but the values are the corresponding temperatures in Fahrenheit.

### Example

**Input:**

```bash
{'Monday': 12, 'Tuesday': 14, 'Wednesday': 15}
