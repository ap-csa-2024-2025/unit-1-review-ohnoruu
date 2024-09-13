[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15931009)
# unit-1-review

For this assignment, you will write a program to calculate a student's final course grade based on the student's homework, quiz, and final exam scores.

You will create the following variables:
* Name of the course (as a string)
* Average amount of time the student spent on the course per week in minutes (as an int)
* 4 integers representing the student's homework scores
* 2 decimals representing the student's quiz scores
* decimal representing the student's final exam score

The program should then output the course name and the average time spent for the course in a week in hours and minutes. This should be followed by the average homework grade, the average quiz grade, and the final exam grade (as doubles), and an overall grade (as an int).

The overall grade should be computed as a weighted average. The formula for the grade calculation is given by

$$ \text{Final Grade} = (\text{Average homework grade} \cdot \text{Homework weight}) + (\text{Average quiz grade} \cdot \text{Quiz weight}) + (\text{Final Exam grade} \cdot \text{Final exam weight}) $$

The weights are as follows:

* Average homework grade - 35%
* Average quiz grade - 15%
* Final exam grade - 50%

The overall grade should be rounded to the nearest integer (NOT just truncated to the integer below).

When you write the code to produce your program's final output, take extra care to ensure all the labels used are exactly as shown in the sample run, including the colon after each label. The program which grades your solution will look for the values after these labels, so if they don't match exactly your solution may not be graded correctly.

Sample Run:
```
course name: AP Computer Science A
average time spent in a week for this course in minutes: 135
homework grades for this course:
75
99
80
100
quiz grades for this course:
89.2
98.1
final exam grade for this course:
87.58
Weekly time spent: 2h15
Average homework grade: 88.5
Average quiz grade: 93.65
Final exam grade: 87.58
Overall grade: 89
```
