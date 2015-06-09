#grading the class
The `gradeassignment-all.sh` script allows an instructor grade an assignment for the whole class.
Before execution, the script requires the parameter of which assignment to grade.
It will pull a local copy of each student's repository and check for the assignments.
It will open up a vim editor with a table setup as follow with each students name and id:
```
---------------------------------------------------------------------------------------------
 csaccount           | name           | grade/total | grader             | sig | notes (\\n for newline)
---------------------------------------------------------------------------------------------
 xxx001              |Edward Snowden  |             |                    | sig | notes (\\n for newline)
 xxx002              |Steve Jobs      |             |                    | sig | notes (\\n for newline)
 xxx003              |Bill Gates      |             |                    | sig | notes (\\n for newline)
 xxx004              |Linus Torvalds  |             |                    | sig | notes (\\n for newline)
 xxx005              |Ada Lovelave    |             |                    | sig | notes (\\n for newline)
 ...
```
At the end, it will automaically push all grades to each respected repository.

#grading individual assignments
The `gradeassignment-individual.sh` script allows an instructor grade an assignment for a specific student.
It will pull a local copy of the student's repository and check for the assignments.
This feature might be used more often as it would allow the grader to imput long feedback for the student.
It will open up a blank page in the vim editor for grading.
At the end, it will automaically push the grades to the respected repository.
