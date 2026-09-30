# AI-Assisted Code Review, Refactoring and Testing

## Aim

To perform AI-assisted code review, refactoring, and testing of a
Python project and document where AI assistance succeeded and where
manual intervention was required.

## Project: Student Grade Calculator

This Python program accepts marks for three subjects, calculates the
total and average, and assigns a grade.

## Technologies Used

- Python
- GitHub Copilot / Cursor / Claude Code
- Pytest
- Git

## 1. Original Program

```python
marks = []

for i in range(3):
    marks.append(float(input("Enter mark: ")))

total = 0

for mark in marks:
    total = total + mark

avg = total / 3

if avg >= 90:
    grade = "A"
elif avg >= 80:
    grade = "B"
elif avg >= 70:
    grade = "C"
elif avg >= 60:
    grade = "D"
else:
    grade = "F"

print("Total:", total)
print("Average:", avg)
print("Grade:", grade)
