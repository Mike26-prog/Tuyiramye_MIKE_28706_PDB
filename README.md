Oracle PDB Assignment II – 28706
Student Name: Tuyiramye Mike
Student ID: 28706
Repository: oracle_pdb_ass_II_28706_MIKE
Visibility: Public

Overview of Tasks

This repository contains the documentation and evidence for the following Oracle Pluggable Database (PDB) practical tasks:

Task 1: Create a Pluggable Database (PDB) and a user
Task 2: Create and delete a temporary PDB
Task 3: Oracle Enterprise Manager (OEM) access
Task 4: Presentation available in this repository

Repository Link:
https://github.com/Mike26-prog/oracle_pdb_ass_II_-28706-_-Mike-/tree/main

Oracle Environment Used

Oracle Version: Oracle 19c
Operating System: Windows
Oracle Tools: SQL*Plus
Non-Oracle Tools: Command Prompt

Task 1 – Create a PDB and User

Details
PDB Name: MI_PDB_28706
Username: MI_PLSQLAUCA_28706
Password: auca

Description
A new Pluggable Database was created using the required naming standards.
A user was successfully created inside the PDB and verified.

The Container Database (CDB) name is visible in the screenshots.

Evidence
Screenshots located in Task 1 folder.

The screenshots show:
PDB creation command
PDB open state
User creation
Container (CDB) name

Task 2 – Temporary PDB Creation and Deletion

Details
Temporary PDB Name: MI_pdb_to_delete_28706

Description
A temporary PDB was created and verified using actual SQL commands.
After verification, the PDB was closed and deleted completely.

Command used:
ALTER PLUGGABLE DATABASE MI_to_delete_pdb_28706 CLOSE IMMEDIATE;

The deletion was confirmed by checking that it no longer appears in v$pdbs.

Evidence
Screenshots located in Task 2 folder.

Shows:
PDB creation
PDB open
PDB close
PDB deletion
Verification from v$pdbs

Task 3 – Oracle Enterprise Manager (OEM)

Status: Not Completed

This task was started but could not be fully completed due to time limitations.
However, screenshots show that the listener was successfully opened.

Evidence
Screenshots located in Task 3 folder.

Challenges Faced

Limited time to complete all tasks
System instability and computer crashes
OEM setup required more configuration time

Integrity Statement

I declare that this assignment is entirely my own work.
All tasks were performed by me, and the evidence provided is genuine and valid.

Submission Information

Repository Link:
https://github.com/Mike26-prog/oracle_pdb_ass_II_-28706-_-Mike-/tree/main

PDB Created: MI_PDB_28706

Issues Encountered:
System crashes and insufficient time for OEM completion

Author
Tuyiramye Mike
Student ID: 28706