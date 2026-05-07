1. This program is a grading calculator for an Intro to Programming in C++ class. It helps users calculate their overall grade by entering scores from different assignments, quizzes, and tests. The calculator makes it easier to keep track of grades without having to do all the math manually. It is simple to use, accurate, and designed for people of all ages and experience levels, making grade calculation faster and less stressful.
2. To get started, compile the program using the build command provided in the README file with a C++17 compatible compiler such as g++. After compiling, run the generated executable file (./GradeCalculator for macOS/Linux or GradeCalculator.exe for Windows) to launch the grading calculator.

 <img width="238" height="236" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/3964f1e0-4208-4276-a125-40a29b2444e9" />

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
 [Welcome to the C++ Grading Calculator!]

 
 This program will help you calculate your final grade.

-Enter an assignment score (enter a negative number to finish): 92

-Enter an assignment score (enter a negative number to finish): 85.5

-Enter an assignment score (enter a negative number to finish): 78

-Enter an assignment score (enter a negative number to finish): 96

-Enter an assignment score (enter a negative number to finish): 88

-Enter an assignment score (enter a negative number to finish): -1

Grades entered (highest to lowest):
96
92
88
85.5
78

Final Average: 87.9%
Letter Grade: B

Thank you for using the Grading Calculator!
<img width="559" height="524" alt="Screenshot (423)" src="https://github.com/user-attachments/assets/dcd67b8e-15b0-4391-a682-6b212834e452" />


6. [Understanding Your Results]

• Total Points Earned  
This shows the sum or overall amount of points the user has received based on all the assignment scores entered. It represents the combined performance before converting it into a percentage.

• Total Percentage  
This is the calculated average of all the entered scores shown as a percentage. It gives a clear view of how well the student performed overall in the course out of 100 percent.

• Final Letter Grade  
This is the letter equivalent of the total percentage. The program converts the numeric percentage into a standard letter grade (such as A, B, C, D, or F) to make it easier to understand overall performance at a glance.

<img width="543" height="518" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/3529dfd7-a2d0-4c1f-a977-454ac6891851" />


7. [Troubleshooting]

• Entering letters instead of numbers  
If the user types letters or symbols when the program is expecting a numeric grade, the program may give an error or ignore the input. To fix this, make sure to only enter whole numbers or decimal values such as 85 or 92.5 when entering scores.

• Forgetting the sentinel value is negative  
Some users may keep entering grades and forget how to stop the program. The program only ends input when a negative number is entered. Make sure to enter a negative number (such as -1) when you are finished adding all assignment scores.

• Entering scores outside the valid range  
If a user enters a number lower than 0 or higher than 100, the result may not be accurate. Always make sure grades are between 0 and 100.

• Not entering all grades before stopping  
If the sentinel value is entered too early by mistake, the program will stop collecting input and calculate the final grade using incomplete data. In this case, the program may need to be run again to re-enter all scores.

<img width="536" height="472" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/68018505-d0af-46ac-8a90-551877688a19" />

