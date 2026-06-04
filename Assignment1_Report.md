##  Assignment1_Report - Git Branching & Collaboration

### Name: Monireh Eshghinezhad
### Student ID: 150705234
### Course: MAI201 - MLOps
### Date: 2026-06-04
---
## 1. GitHub Network Graph
<img width="1109" height="616" alt="image" src="https://github.com/user-attachments/assets/d9149806-44c7-453a-8953-4956d0a2caf6" />

## 2. Branch Protection Rules
<img width="1084" height="1243" alt="image" src="https://github.com/user-attachments/assets/4e2d595a-8e49-42c7-ba27-edfe23f5a7fb" />
<img width="1173" height="1057" alt="image" src="https://github.com/user-attachments/assets/21a61698-7b4c-4e5a-83eb-1e7053af4b17" />

## 3.  git log --oneline --graph
<img width="1571" height="835" alt="image" src="https://github.com/user-attachments/assets/8032e851-45e5-40e6-95e8-81c5be01f325" />

## 4. Reflection - Merge Conflict Challenges
The most challenging part for me was understanding WHEN 
a conflict actually happens.

In my first attempt, I added my student name and ID in one 
location of README.md, and the course code and date in a 
different location. I expected a conflict, but GitHub 
automatically merged both changes with no conflict at all.

This confused me at first. I learned that Git is smart enough 
to merge changes that are in different locations of the same 
file, it only creates a conflict when two branches edit the 
EXACT SAME LINE.

In my second attempt, I edited Line 1 (the title) on both 
branches with different text. This time GitHub showed:
"Can't automatically merge."
 
The conflict markers looked like this:
<img width="962" height="167" alt="image" src="https://github.com/user-attachments/assets/31aaeb19-7929-42ee-b18a-37784465012e" />


I resolved it by keeping BOTH changes combined into one line,
then removing the conflict markers.
