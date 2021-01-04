# Smart-Health-Informatics-with-Gurobi-Optimizer
There are 6 new patients at an Emergency Room (ER) at a busy hospital. Each patient needs to be addressed by any one of its six available doctors. Because of the differences in symptoms of the patients as well as the expertise and experience of the doctors, the doctors require spending varying amounts of time on attending each patient. The senior doctor of the ER has estimated the time requirements as shown in Table 1.
Table 1: Time requirements (in minutes) for doctors to attend patients at ER at the hospital.
Patient 1
Patient 2
Patient 3
Patient 4
Patient 5
Patient 6
Doctor 1
Doctor 2
Doctor 3
Doctor 4
130
95
Doctor 5
118
83
Doctor 6
1. Formulate an optimal assignment of Patient 1 and Patient 2 to Doctor 4 and Doctor 5 in such a way that each doctor receives a different patient and the total hours spent by the doctors is minimized. Show how to use a visualization method (e.g., by hand) to find the optimal time. Provide explanation what happened and what was expected.
2. Fill the empty cells in Table 1 with random integer values with your assumptions (e.g., between 50 and 150). Formulate an optimal assignment of patients to doctors in the entire Table 1 such that each doctor receives a different patient and the total time expended by the ER is minimized.
3. Write a Gurobi script to model the problem in part 1. Verify your solution with the visualization method in part 1.
Now, extend the Gurobi script to model the problem in part 2.
Provide the Gurobi script (Student-ID.py) and solution screenshot (Student-ID.jpg).
