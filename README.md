# PA1-Programming-Assignment

Author: Noah Oliver H. Nazal  
Date: 09/16/2025  
Course: ECE2112 – Programming Assignment  

# Software(s) Used:
- Anaconda Navigator  
- Jupyter Notebook  

# Repoistory Information
About: Contains solutions for PA 1 (3 Problems)  

# Languages Used
- Pyhton (100%)

# Version History
V1.0 ([09-14-2025]) – Initial Coding for PA1  

V1.1 ([09-15-2025]) - Creation of Repository Along with Read Me file  

V1.2 ([09-16-2025]) – Finalization of Coding PA1 and Edited Documentation, Code Formatting, and Design in the README File  

# Problem 1: Alphabet Soup Problem
Takes input of string from user and returns them in alphabetical order  

Example:  

Input: "noah"  

Output: "ahno"  

# Problem 1: ALPHABET SOUP PROBLEM
    # Input of word
    x = input("Enter a string:")

    # Sorting word alphabetically
    x_sorted = sorted(x)

    # Output of sorted word
    alpha_sorted = "".join(x_sorted)
    print(alpha_sorted)
