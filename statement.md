# Problem Statement

Tracking student performance over time is an important task for teachers, parents, and students. In many cases, only final exam grades are considered, which hides whether a student is improving, remaining stable, or declining during the term. Manual tracking of marks across multiple tests and subjects can be time-consuming and prone to mistakes.

# Scope of the Project

This project implements a basic console-based Student Progress Tracker using Python. It focuses on a single student at a time and allows entry of marks across multiple tests (for example, Test 1, Test 2, Final) and a small set of subjects. The application calculates averages, assigns an overall grade, and analyzes whether the student’s performance in each subject is improving or declining.

The project is intentionally kept simple to align with an Introduction to Problem Solving & Programming course, using only fundamental programming constructs such as variables, lists, loops, conditionals, and functions. Data is handled in memory during a single run, without complex databases or external frameworks.

# Target Users

- Students who want to understand and monitor their progress across different tests.
- Teachers who need a quick tool to view trends in a student’s marks without manual calculations.
- Parents who wish to see whether their child’s performance is improving over time.
- Beginner programmers learning how to apply basic programming concepts to a real-world education-related problem.

# High-Level Features

- Input of basic student information (name, ID).
- Entry of marks for multiple tests in selected subjects (for example, Math, Science, English).
- Calculation of:
  - Average marks for each subject.
  - Overall average across all tests and subjects.
- Determination of performance trend per subject:
  - Improved, Declined, Same, or Mixed based on test-to-test comparison.
- Assignment of an overall grade using simple if/elif grading rules.
- Display of a clear progress report summarizing:
  - Marks in each test.
  - Per-subject averages.
  - Performance trend.
  - Overall average and grade.
