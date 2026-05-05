# Grade Calculator

A C++ console application that calculates a student's final letter grade
from a user-defined grading scheme and a set of assignment scores.

## Author
Arman Tanvir - COSC 1436, Spring 2026

## Description
I built a grading calculator in C++ as part of my introduction to programming, using foundational concepts like variables, conditional logic, loops, and functions to process and organize user input. The program calculates weighted averages, handles multiple assignments dynamically, and ensures accuracy through structured logic, reinforcing both problem-solving and a clear, step-by-step approach to thinking through tasks. Designed for students and educators, it offers a practical, efficient tool for tracking academic performance while demonstrating how core programming principles translate into meaningful, real-world applications.

## Features
- Time-of-day greeting
- User-defined grading scheme (Total Points + A/B/C/D cutoffs)
- Unlimited assignment entry with sentinel-controlled input
- Automatic sort of assignments highest to lowest
- Final letter grade and rounded percentage

## Files
| File          | Purpose                       |
|---------------|-------------------------------|
| main.cpp      | Driver program                |
| Greeting.h    | Greeting function declaration |
| Greeting.cpp  | Greeting function definition  |
| USER_GUIDE.md | End-user instructions         |

## How to Build
Using g++ (Linux / macOS / WSL / MinGW):

    g++ -std=c++17 main.cpp Greeting.cpp -o GradeCalculator

## How to Run
    ./GradeCalculator        # macOS / Linux
    GradeCalculator.exe      # Windows

## Requirements
- C++17 or newer compiler (g++, clang, or MSVC)

## Course Concepts Demonstrated
Chapters 1-12 of Fundamentals of C++ Programming.
