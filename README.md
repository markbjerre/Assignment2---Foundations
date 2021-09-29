"#Assignment 2_try 2" 

DiplomaProgramme class:
ATTRIBUTES

METHODS
Get_students
Get_Program_Courses
Add_Course(course name)
Remove_Course(course name)


Course class:

ATTRIBUTES
name = str
students = list
id = str
program = DiplomaProgramme class

METHODS 
Get_Students()
Add_Student(student)
Add_All_Students()
Remove_Student(student)
Remove_All_Students()
Pass_Assignment(assignment, student)
Pass_All(student)
Fail_Assignment(assignment,student)
Fail_All(student)

Student: 
ATTRIBUTES
fname = str
lnmae = str
name = str, fname + lname
programe = DiplomaProgramme class object
id = str, student + counter
assignments = dict, key = Course object, /
val = list of assignments (True/False/NaN)

METHODS
Set_ID() - called on instance creation
Set_Assignments(course) - called on student assignment to course, course method Add_Student
Remove_Assignments(course) - called when course is errased, Programme method Remove_Course(course)
Get_Courses()
Get_Grades()
Show_Grades()

something new
"# Assignment 2---Foundations" 
