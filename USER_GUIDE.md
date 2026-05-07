1. This program is a grading calculator for an Intro to Programming in C++ class. It helps users calculate their overall grade by entering scores from different assignments, quizzes, and tests. The calculator makes it easier to keep track of grades without having to do all the math manually. It is simple to use, accurate, and designed for people of all ages and experience levels, making grade calculation faster and less stressful.
2. To get started, compile the program using the build command provided in the README file with a C++17 compatible compiler such as g++. After compiling, run the generated executable file (./GradeCalculator for macOS/Linux or GradeCalculator.exe for Windows) to launch the grading calculator.
3.
[Welcome Message]
   - The program displays a greeting and explains that the grading calculator will help calculate the user’s final grade.
   - Data Type / Format Expected: No input required.
   - Acceptable Input Range / Constraints: None.
   
[Enter Assignment Score]
   - The program asks the user to enter a score for an assignment, quiz, or test.
   - Data Type / Format Expected: A whole number or decimal number such as 95 or 87.5.
   - Acceptable Input Range / Constraints: The score must be between 0 and 100.
     
[Continue Entering Scores or Stop]
   - The program asks the user if they want to continue entering scores or stop the program.
   - Data Type / Format Expected: A sentinel value such as -1 or a character response such as Y/N.
   - Acceptable Input Range / Constraints: Enter -1 only when all grades have been entered.
     
[Enter Additional Scores]
   - The program continues asking for more assignment scores until the user enters the stop value.
   - Data Type / Format Expected: Whole numbers or decimal numbers.
   - Acceptable Input Range / Constraints: Scores must remain between 0 and 100.
     
[View Sorted Scores]
   - The program displays all entered grades sorted from highest to lowest.
   - Data Type / Format Expected: No input required.
   - Acceptable Input Range / Constraints: None.
     
[Final Grade Calculation]
   - The program calculates the overall average percentage and determines the final letter grade.
   - Data Type / Format Expected: No input required.
   - Acceptable Input Range / Constraints: None.
     
[Final Results Display]
   - The program displays the final percentage grade and corresponding letter grade for the course.
   - Data Type / Format Expected: No input required.
   - Acceptable Input Range / Constraints: None.
     
4. The program uses something called a sentinel value to let the calculator know when the user is finished entering assignment scores. Instead of asking the user ahead of time how many grades they want to enter, the program keeps accepting scores until a negative number is typed in. Since assignment grades cannot normally be negative, the program recognizes this value as a signal to stop collecting input. Once the negative number is entered, the calculator automatically ends the input process, sorts the grades, calculates the average percentage, and displays the final letter grade. This makes the program easier and more flexible to use because the user can enter as many grades as needed without restarting the program or entering a fixed amount beforehand.

5.
Welcome to the C++ Grading Calculator!
This program will help you calculate your final grade.

Enter an assignment score (enter a negative number to finish): 92
Enter an assignment score (enter a negative number to finish): 85.5
Enter an assignment score (enter a negative number to finish): 78
Enter an assignment score (enter a negative number to finish): 96
Enter an assignment score (enter a negative number to finish): 88
Enter an assignment score (enter a negative number to finish): -1

Grades entered (highest to lowest):
96
92
88
85.5
78

Final Average: 87.9%
Letter Grade: B

Thank you for using the Grading Calculator!
6. Sample Session — paste a complete example run (input + output) so the user can see what success looks like.
7. Understanding Your Results — explain what each line of the final output means (Total Points Earned, Total Percentage, Final Letter Grade).
8. Troubleshooting — at least 2 common mistakes (e.g., entering letters where a number is expected, forgetting that the sentinel is negative).
