# Automatic-Verification-of-Programming-Questions

Our primary objective of this project is: Given a set of solutions submitted by students (denote by S), identify the correct ones and grade the submissions appropriately. We can decompose our problem into the following subproblems:

Step 1: Given a set of submitted programs and a correct solution, identify the correct solutions from submitted answers (submissions i.e. S). Test cases that can discriminate wrong submissions from the correct ones
need to be generated. And then all submissions need to be testedagainst these test cases to find out which are the correct submissions(denote by S<sub>correct</sub> ) and the incorrect ones (denote by S<sub>incorrect</sub> ).

Step 2: As every student has her own programming style, S might contain different approaches to solve the same question. Given the correct solutions (S<sub>correct</sub>), find what are the unique approaches used by students to tackle the question correctly. We will call these unique approaches as GOLD STANDARDS (S<sub>gold−standard</sub> ).
Given S<sub>gold−standard</sub>, and a submission from S<sub>incorrect</sub> , find out which approach student was trying to follow. We require to find a tuple (P, G) where P ∈ S incorrect and G ∈ S<sub>gold−standard</sub> is the approach that
P is closest to.

Step 3: Given a pair of submitted solution and the corresponding gold standard (P, G), find the least number of steps to convert G to P using program repair techniques and assign appropriate scores.

We have worked on Step 2 and our proposed solution is based on identifying similar programs by comparing their Program Dependence Graphs (PDG). For more details regarding the approach please refer to [report.pdf](https://github.com/meghanakotagiri/Automatic-Verification-of-Programming-Questions/blob/master/report.pdf)

Contributors:
Meghana Kotagiri (meghanakotagiri)
G Neha (nehareddyg)
