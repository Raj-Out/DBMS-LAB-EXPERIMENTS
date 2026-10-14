# DBMS-LAB-EXPERIMENTS

Semester 3 DBMS lab experiments 1–6.

This repository contains the DBMS laboratory experiments in order. Experiments 1 and 2 preserve the supplied PDF files. Experiments 3–6 each have a separate MySQL source file and a detailed experiment README with the aim, explanation, run guidance, source code, and expected output.

## Experiments

| Experiment | Topic | Files |
|---|---|---|
| 1 | Indian e-commerce ER diagram | [Experiment 1 README](Experiment_1/README.md) · [Original PDF](Experiment_1/Experiment_1_ER_Diagram.pdf) |
| 2 | Relational schema and MySQL constraints | [Experiment 2 README](Experiment_2/README.md) · [Original PDF](Experiment_2/Experiment_2_Relational_Schema_MySQL.pdf) |
| 3 | Employee, department, and project queries | [Experiment 3 README](Experiment_3/README.md) · [SQL source](Experiment_3/experiment_3.sql) |
| 4 | Joins, subqueries, and query plans | [Experiment 4 README](Experiment_4/README.md) · [SQL source](Experiment_4/experiment_4.sql) |
| 5 | Views and recursive reporting chain | [Experiment 5 README](Experiment_5/README.md) · [SQL source](Experiment_5/experiment_5.sql) |
| 6 | Stored procedure, validation, and audit triggers | [Experiment 6 README](Experiment_6/README.md) · [SQL source](Experiment_6/experiment_6.sql) |

## Database setup

Experiments 3–6 use MySQL 8.0+. Each script creates or resets its own sample tables in the `DBMS_LAB` database. Run one experiment script at a time in a MySQL client. Experiment 6 uses stored procedures and triggers and therefore requires support for the `DELIMITER` client command. Each experiment README describes its expected result set and any statements that need to be run separately.

The source PDFs and the SQL scripts are organized separately by experiment. The experiment-specific READMEs embed the full code and document the expected outputs.
