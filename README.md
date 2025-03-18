Programming in Java Coursework (Part 1)

What I Did
For this project, I built a Java program to manage student societies in the Computer Science Department, focusing on equality, diversity, and inclusivity (EDI). The goal was to track society members and ensure that each group had at least three key roles: President, Secretary, and Treasurer.

How I Did It

SocMember Class
   -I created a SocMember class with fields for name and student number, making sure they were properly encapsulated with getters and setters.
   -Added a static integer field student_counter to keep track of the number of members created.

SocTeam Class
   -Designed a SocTeam class to represent a society.
   -Included fields for President, Secretary, and Treasurer, all of which were SocMember objects.
   -Implemented a constructor to assign the first three members to these roles.
   -Used proper access modifiers to keep things secure and provided getter methods for retrieving member names.

Main Class
   -Created an array allStudentNames with at least six student names.
   -Made another array, allStudentNumbers, for their student numbers.
   -Randomly picked between 4 and 6 students to form the members array.
   -Set up two societies:
      -women_soc: Assigned the first three members as President, Secretary, and Treasurer.
      -bame_soc: Assigned the last three members the same roles.
   -Printed out the names of each society’s President, Secretary, and Treasurer.
   -Checked if student_counter matched the number of members and printed "SUCCESS" if everything was correct.

Final Thoughts:
   -This project was a great way to practice OOP principles, including encapsulation, constructors, static fields, and working with arrays. It also helped me get ready for the viva assessment, making sure I fully understood my own code!
