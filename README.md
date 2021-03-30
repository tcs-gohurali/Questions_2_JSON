# Convert Questions to JSON

The following program is a helper for Phase II end project, Online Exam

### How to use

Questions are written to the `questions.txt` file line by line.   
```
What state is Mt. Rainier located in?
The is the name of the largest building in the US?
```

Choices are written to `choices.txt` line by line. It's recommended you use a numeric or alphabetical character to represent the choice.
```
a. Pennsylvania
b. Washington
c. Alaska
d. California
---
a. Space Needle
b. Willis Tower
c. Empire State Building
d. One World Trade Center
---
```
Notice that choices are seperated by `---` (three dash characters) which shows the end of the choices for the respective question

Solutions are written to `solutions.txt` line by line
```
b
d
```

### How to Run

Please ensure that you have Python installed. Then run the following in terminal:
```
$ python generate_data.py
```
