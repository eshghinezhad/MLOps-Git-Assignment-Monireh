#  Assignment1_Report

## 1. GitHub Network Graph
![Network Graph](screenshots/network-graph.png)

## 2. Branch Protection Rules


## 3.  git log --oneline --graph


## 4. Reflection — Merge Conflict Challenges
The most challenging part for me was understanding WHEN 
a conflict actually happens.

In my first attempt, I added my student name and ID in one 
location of README.md, and the course code and date in a 
different location. I expected a conflict, but GitHub 
automatically merged both changes with no conflict at all.

This confused me at first. I learned that Git is smart enough 
to merge changes that are in different locations of the same 
file — it only creates a conflict when two branches edit the 
EXACT SAME LINE.

In my second attempt, I edited Line 1 (the title) on both 
branches with different text. This time GitHub showed:
"Can't automatically merge."

The conflict markers looked like this:
<<<feature/update-readme
 MLOps-Git-Assignment-Monireh | Monireh Eshghinezhad | ID: 150705234
=======
 MLOps-Git-Assignment-Monireh | MAI201 | 2026-06-04
>>>develop

I resolved it by keeping BOTH changes combined into one line,
then removing the conflict markers.