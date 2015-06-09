#configuring your classroom

Gitlearn is configurable through the `config.sh` script.  
The following varriable names can be be changed if needed.
By default, the script is configured as followed:
```
#######################################
# configuration (can be modified)

# the github project name
classname="ucr-cs100"

# tmp folder for all student repos
tmpdir="$HOME/.gitlearn/$classname"

# branch of student git repository that stores the grades
gradesbranch="grades"

# folder containing instructor pgp keys
instructorinfo="people/instructors"

# folder containing student information
studentinfo="people/students"

#######################################
```

#variables  
**classname:**  
This varraible controls the name of the class. 
It is recommended to change it to the name of the repository.  
**tmpdir:**  
This varriable contains the file path that stores the student repositories on local machines and servers.  
**gradesbranch:** 
This varriable stores the name of where grades are stored
**instructorinfo:** 
This varriable stores the path for where the instructor keys are held.
**studentinfo:**  
This varriable stores the path for where student information are held.