# Lab-5 : IT314 (Static Analysis)
# Student Name: Aditya Jadeja
# Student ID: 202001432
Submission for Lab-5 of  course IT314 (Software Engineering) 


Selected Git-repository : https://github.com/Karan-0206/Python-_Graphs-DSA-algorithms.git

Static Analysis tool used : Pylint



## Errors Found using Pylint in different files:

## File-1:
![image](https://user-images.githubusercontent.com/100967786/227502518-6deaa02a-98e5-41b9-85da-79a3d0619b52.png)
## File-2:
![image](https://user-images.githubusercontent.com/100967786/227502583-8bc8bacd-43ba-48fa-8464-448ca628c73d.png)
## File-3:
![image](https://user-images.githubusercontent.com/100967786/227502664-48d36f3c-0904-4f67-97dc-12ef6739f194.png)
## File-4:
![image](https://user-images.githubusercontent.com/100967786/227502759-ed8da2d6-68ff-4958-9787-558e007ba65a.png)
## File-5:
![image](https://user-images.githubusercontent.com/100967786/227502863-64c36a0d-8fd2-4c64-a944-141df91f33c9.png)

## Understanding Most occured errors:

* C0114 and C0116 are related to missing module and function docstrings respectively. C0114 indicates that there is no module-level docstring, while C0116 indicates that there is no docstring for a function or method.

* C0103 indicates that there are invalid argument names which do not conform to the snake_case naming style.

* W0621 indicates that a name is redefined from the outer scope.

* W0622 indicates that a built-in function or module is being redefined.

* C0321 indicates that there are multiple statements on a single line, which can make the code harder to read and understand.

