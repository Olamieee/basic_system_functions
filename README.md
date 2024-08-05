# basic_system_functions
# Overview
This project provides functionalities for image processing and unit conversion. The implementation is done in Python using libraries like PIL for image processing and Streamlit for the web interface.

# Table of Contents
• Installation
• Usage
• Project Structure
• Features
• Contributing
• License

# Installation
To set up the project, follow these steps:
1. Clone the repository:
git clone https://github.com/Olamieee/basic_system_functions
2. Install the required packages:
pip install -r requirements.tx

# Usage
To run the project, use the following command:
streamlit run webFunc.py
This will start a local server where you can interact with the image processing and unit conversion features.

# Project Structure
• functions.py: Contains utility functions for mathematical operations, image processing, and unit conversion.
• webFunc.py: Contains the Streamlit web interface that uses the functions from functions.py.

# functions.py Overview
• Mathematical Operations:
  • add(num1, num2): Returns the sum of two numbers.
  • subtract(num1, num2): Returns the difference of two numbers.
  • multiply(num1, num2): Returns the product of two numbers.
  • divide(num1, num2): Returns the quotient of two numbers.
  • power(num1, num2): Returns the power of one number to another.
  • perform_calculation(num1, num2, operation): Performs a selected calculation operation.
• Image Processing:
  • resize_image(image, width, height): Resizes the image.
  • crop_image(image, left, upper, right, lower): Crops the image.
  • apply_filter(image, filter_type): Applies a selected filter to the image.
  • flip_image(image): Flips the image horizontally.
• Unit Conversion:
  • convert_length(value, from_unit, to_unit): Converts length units.
  • convert_weight(value, from_unit, to_unit): Converts weight units.
  • convert_temperature(value, from_unit, to_unit): Converts temperature units.

# webFunc.py Overview
This file sets up a Streamlit web interface with the following features:
• Image Processing:
  • Upload an image and apply operations like resizing, cropping, and filtering.
  • Flip the image horizontally.
• Unit Conversion:
  • Convert values between various units of length, weight, and temperature.

# Features
• Perform basic mathematical operations.
• Process images by resizing, cropping, applying filters, and flipping.
• Convert between different units of length, weight, and temperature.
• Interactive web interface built with Streamlit.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

# License
This project is licensed under the Apache License. See the LICENSE file for more details.

Feel free to customize this README further based on your specific project details and preferences.
