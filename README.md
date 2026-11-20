# AI-Assisted Student Record and Result Management System

## Student Details
- **Name:** Anirudh Chaudhary
- **SAP ID:** 590033702
- **Batch:** 20
- **Course:** Programming in C (PRC1001)
- **Program:** B.Tech CSE, Semester I

## Project Overview
This project is a console-based, menu-driven **Student Record and Result Management System** developed in C. It stores student academic and personal information, calculates CGPA, sorts and searches student records, and provides simple CGPA-based academic advice.

The program stores its records in `Students.dat`, so student data can be loaded again when the program is restarted.

## Features
- Add student records
- Display all student records
- Search a student using SAP ID
- Delete an individual student record
- Calculate CGPA from available semester SGPA values
- Calculate average CGPA of students year-wise
- Display records in increasing order of SAP ID
- Display records in increasing order of student name
- Save and load records using file handling
- AI-Assisted Academic Advisor based on CGPA

## Student Information Stored
Each student record contains:
- SAP ID
- Roll Number
- Name
- Phone Number
- Email ID
- Year
- Current Semester
- SGPA for available semesters
- CGPA

## AI-Assisted Academic Advisor
The project includes a simple academic advisor designed with assistance from ChatGPT. The final recommendation is generated locally by the C program using `if-else` conditions.

| CGPA | Category | Recommendation |
|---|---|---|
| 8.5 and above | Excellent Performance | Maintain the current study pattern and explore advanced learning opportunities. |
| 7.0 to below 8.5 | Good Performance | Keep up the good work and focus on improving weaker subjects. |
| 5.0 to below 7.0 | Needs Improvement | Focus more on subjects with lower SGPA and follow a regular study schedule. |
| Below 5.0 | Requires Immediate Attention | Give immediate attention to weak subjects and seek guidance from faculty. |

No external AI API is connected to the C program. AI was used only as a learning and development assistant.

## Files in the Repository
```text
student-record-ai-c/
├── 590033702.c
├── Students.dat
├── README.md
├── AI_USAGE_LOG.md
└── tests/
    ├── sample_input.txt
    └── sample_output.txt
```

## How to Compile and Run

### Using GCC
```bash
gcc 590033702.c -o student_record
./student_record
```

### On Windows
```bash
gcc 590033702.c -o student_record.exe
student_record.exe
```

## Program Menu
```text
1. Add Student
2. Display all Student
3. Display in Increasing order of SAP Id
4. Display in Increasing order of Name
5. Search and Display record of Student
6. Delete a student Record
7. Calculation of CGPA of student till his current Semester
8. Calculation of Average CGPA of all year student
9. AI-Assisted Academic Advisor
10. Exit
```

## Concepts Used
- Structures
- Functions
- Arrays
- Pointers
- Dynamic memory allocation (`malloc` and `realloc`)
- File handling
- Loops and conditional statements
- String handling
- Searching
- Sorting
- Menu-driven programming

## AI Usage
ChatGPT was used as a learning assistant for designing the academic-advisor categories, understanding how the advice could be converted into `if-else` logic, reviewing project requirements, and improving project documentation.

The AI suggestions were checked against the assignment requirements and the final implementation was reviewed before being included in the project. See `AI_USAGE_LOG.md` for details.

## GitHub Development
The project should be developed using meaningful commits instead of uploading everything in one commit. Example commit history:

1. `Initial C program and student structure`
2. `Add student record search and file handling`
3. `Add CGPA calculation and sorting functions`
4. `Add AI academic advisor and documentation`

A GitHub Issue can also be created for a task such as **Implement and test CGPA calculation**, then closed after completion.

## Author
**Anirudh Chaudhary**  
SAP ID: **590033702**
