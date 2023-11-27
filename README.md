# College-Admission
As the governing body of college admissions, we want a system that can match students to colleges based on their marks.

Assume we are given this list of colleges, their capacities, and minimum cut off marks respectively.

|Name | Maximum capacity | Cut off marks
| ------------- | ------------- |
|IIT            |2              |180
|NIT            |1              |150

Fetch the list of students, marks and college preference (only one college) as dynamic input from the user.

Assign students to colleges based on their total marks, i.e.: a student with higher total marks should get more preference in college selection compared to another student with lesser marks. Also, a student can be assigned to a college only if their total marks is equal to or greater than the college's defined cut off marks.

NOTE: The input (college details) can be hard coded, and need not be read from the console. However, there should be a clear separation between such hard coding and actual application logic so that the hard coding can be easily replaced by dynamic user/file/database input without requiring any change in the core application logic.

Output:
Enter student name: Ram
Enter marks: 165
Enter student college preference: IIT
Enter student name: Rani
Enter marks: 195
Enter student college preference: IIT
Enter student name: Prem
Enter marks: 199
Enter student college preference: IIT
Enter student name: Rohit
Enter marks: 149
Enter student college preference: NIT
Enter student name: Surya
Enter marks: 130
Enter student college preference: IIT

Ajay: NIT
Rakesh: -
Praveen: IIT
Ram: -
Rani: IIT
Prem: -
Rohit: -
Surya: -
