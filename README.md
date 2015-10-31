# blackBox
back box exercise xercise to Perform Black Box Testing on the Grades Program:

Inputs: For each student, exam scores are expressed as
percentages (i.e., integers between 0 and 100 inclusive), and
practical scores are expressed as percentages.


Outputs: Course grades, computed as follows: A combined score percentage is computed as:
combined = (0.6 * exam) + (0.4 * practical)

1. For combined scores less than 50, the grade is ”Fail”.
2. For exam scores less than 40, the grade is ”Component Fail” (no matter what the practical score is)
3. For practical scores less than 40, the grade is ”Component Fail” (no matter what the exam score is)
4. For combined scores between 50 and 80 inclusive, the grade is ”Pass”.
5. For combined scores between 80 and 100 inclusive, the grade is ”Pass with distinction”.
6. For all other inputs, the program should report ”Invalid input”.


TO DO:

Check out  the source files from Martin's Github project using the git clone command:

https://github.com/moconnoritt/black-box-testing.git

- Change directory into the new directory

- You should see a Grades.class file

The grades program expects 2 parameters - based on the grades logic above.

1. Run the file by issuing the java command followed by the name of the java program with no parameters

2. What do you see?

Define and test 6 "good quality" test cases.

3. Using a text editor, record each test case, and show the expected output and observed output.
