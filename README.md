# Student Progress Tracker

## Project Title
Student Progress Tracker

## Overview of the Project
Student Progress Tracker is a simple Python console application that helps track a student's marks across multiple tests and subjects. It focuses not only on calculating averages and grades but also on checking whether the student’s performance is improving, declining, or staying the same over time. This makes it more insightful than a single-exam grade calculator and connects directly with real-world academic progress tracking.

## Features
- Accepts basic student details (name, ID).
- Records marks for multiple tests in multiple subjects.
- Calculates per-subject averages and overall average.
- Determines performance trend for each subject (Improved / Declined / Same / Mixed).
- Assigns an overall grade based on the final average.
- Displays a neat text-based progress report for the student.

## Technologies / Tools Used
- Programming Language: Python 3.x
- Environment: Any Python-capable IDE or terminal (VS Code, PyCharm, IDLE, or command-line)
- Standard input/output for user interaction

## Steps to Install & Run the Project

1. Install Python 3 (if not already installed)  
   - Download from the official Python website and follow the installer steps.

2. Download or clone the project repository:
   https://github.com/Sanjay2528/Student_progress_tracker.git
3. Run the Python program:
   or, depending on your system:

4. Follow the on-screen menu or prompts to enter student details and marks.

## Instructions for Testing

When testing the application, try the following scenarios:

# Case 1: Clear Improvement  
- Enter lower marks in Test 1 and higher marks in Test 2 (and/or later tests) for each subject.  
- Expected: Progress status should show “Improved” for those subjects.

# Case 2: Decline in Performance  
- Enter higher marks in Test 1 and lower marks in Test 2.  
- Expected: Progress status should show “Declined” for those subjects.

# Case 3: Same Performance  
- Enter equal marks across tests.  
- Expected: Progress status should show “Same”.

# Case 4: Mixed Performance  
- Enter marks that go up in one test and down in another.  
- Expected: Progress status should show “Mixed” or your chosen label.

# Case 5: Boundary Values  
- Use 0, 100, and mid-range values to ensure average and grade calculations are correct.
- Check if your grade logic behaves correctly around boundary values (for example, 39/40, 59/60, etc.).



