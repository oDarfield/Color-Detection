# Color-Detection

I have created a Python program that detects the color of where the cursor is on any image you upload. Please let it be known that this idea was not mine; I was just testing it out for the first time - I learned how to make this from https://data-flair.training/blogs/project-in-python-colour-detection/

For this program to work, the numpy, pandas, and opencv pip-installable libraries are requied. It is also important to import argparse

The program will work for any image file you give, provided you give the correct directory. When you open the image and double-click anywhere on it, the program will identify the exact color using a csv sheet downloaded for reference. An image file is also downloaded as an example. The program will give the RGB values of the exact color along with the name of that color.

This can be done any number of times until you hit the escape key, exiting the program.
