# Student Gradebook Management System (C Program)

This C program implements a simple **student gradebook management system**, which allows users to:

- Add students and courses  
- Record grades for assignments and exams  
- Display lists of students, courses, and grades  
- Calculate and display the GPA for a student  

---

## Key Features

### Data Structures
- **Student**: Stores a student's name and ID.  
- **Course**: Stores a course name and code.  
- **Grade**: Stores a student's assignment and exam grades for a specific course.  

### Storage
- Uses arrays to store up to:
  - 100 students  
  - 100 courses  
  - 100 grade entries  

### Functionality
- **Add Student**: Prompts user for name and ID, and stores the student.  
- **Add Course**: Prompts for course name and code.  
- **Add Grades**: 
  - Links grades to a student ID and course code after verifying their existence.  
  - Allows entering multiple assignment and exam grades.  
- **Display Functions**: Lists all students, courses, and detailed grade entries.  
- **GPA Calculation**: 
  - Calculates GPA based on weighted averages:
    - 40% assignment grades  
    - 60% exam grades  
  - Assumes all courses have 3 credit hours.  

### User Interface
- Text-based menu system with numbered options for easy navigation.  
- Loops until the user chooses to exit.  
