#Setup gitlearn for your class

This is a general overview on tools that an instructors would use for class.

This tutorial will cover the basics of instructor tool scripts, but more specifically, how to setup your class with **gitlearn**.

<a name="top"/>
##Table of Contents
[1. Setup](#setup)
[2. Adding Instructors](#addkey)
[3. Grading](#grading)
[4. View Grades](#view)
[5. Additional tools/resources](#resources)

<a name="setup"/>
###Setup

[Back to table of contents](#top)

<a name="addkey"/>
###Adding Instructor

After setting up gitlearn onto your local repository along with your class files,
it is recommended to add the instructor keys so that student grades can be verified for validity.
On the home directory of the class repository, run:
```
$ instructortools-addgrader.sh
```

![addgrader.png](img/addgrader.png)

**NOTE:**
It will take time for your system to generate a strong RSA key that will be automatically push to the github repository.
Expect somewhere around 15~ minutes (depending on your current hardware).

**NOTE:**
The key will automatically push itself onto the main repository.
Make sure you have your instructors setup on the contributor setting for the repository.

**IMPORTANT:**
Make sure you generate the key on the computer that you will grade on.

[Back to table of contents](#top)

<a name="grading"/>
###Grade Assignments

[Back to table of contents](#top)

<a name="view"/>
###View Grades

[Back to table of contents](#top)

<a name="resource"/>
###Additional tools/resources

[Back to table of contents](#top)
