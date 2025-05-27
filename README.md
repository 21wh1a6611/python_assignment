# python_assignment
question 1 : department question
create a class having a variable dept id ,dept name , dept location dept lead through the constructor department attributes
create a method to display the department information 
display the total departments in your organsiation  instead of hard code take the input from user and 
print get the input from user like no of departments to store that much no of departments in list or dict 
use for loop to get department information search department ,department id if  it is there it will display info  search department by department _name 
if it is there it will display department_info.

question 2: inventory question
inventory = [
    # name,       category,   unit_price, units_sold, units_left
    ["Strawberry", "Fruit",      3.50,        40,          10],
    ["Broccoli",   "Vegetable",  2.20,        25,           8],
    ["Cheddar",    "Dairy",      5.00,        18,           4],
    ["Baguette",   "Bakery",     2.80,        35,           2],
    ["Blueberry",  "Fruit",      4.00,        22,           6],
    ["Spinach",    "Vegetable",  1.80,        30,          12],
    ["Yogurt",     "Dairy",      1.20,        50,          15],
    ["Croissant",  "Bakery",     3.00,        28,           3],
]
calculate the TotalRevenue
List Low stock item if stock is less than 5
calculte the categorywise Revenue

question 3:maange student data
You're building a system to manage student data for a university. Each student is identified by a unique student ID and has the following details:
- Name
- Major
- Enrolled Courses (each course has a course name and a dictionary of assessment scores like midterm, final, and project)
 Sample Data (Nested Dictionary):
university_data = {
"S101": {
        "name": "Alice Johnson",
        "major": "Computer Science",
        "courses": {
            "Python101": {"midterm": 88, "final": 92, "project": 94},
            "Math201": {"midterm": 78, "final": 85, "project": 80}
        }
    
    },
    "S102": {
        "name": "Bob Smith",
        "major": "Mathematics",
        "courses": {
            "Math201": {"midterm": 90, "final": 93, "project": 88},
            "Stats101": {"midterm": 84, "final": 80, "project": 85}
        }
    },
    "S103": {
        "name": "Clara Lopez",
        "major": "Physics",
        "courses": {
            "Physics101": {"midterm": 75, "final": 82, "project": 78},
            "Math201": {"midterm": 70, "final": 72, "project": 68}
        }
    }
}
Q1: Print all student names and their majors
Q2: Average score per course per student 
Q3: Find students who scored >90 in final of Python101 
Q4: Add new course AI101 for student S101
Q5: Print average for each course


question 4: student grading management system
Build a student grade management system using the following Python concepts:
- List of dictionaries
- Function with required arguments, *args, **kwargs
- Function decorator
- Loops and control statements

Requirements
1. Use a **decorator** to log function activity.
2. Use a function to **add student data** using `*args` and `**kwargs`.
3. Store student records in a **list of dictionaries**.
4. Use **loops and conditionals** to calculate and display results.




