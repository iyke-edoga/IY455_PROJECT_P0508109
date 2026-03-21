<style>
</style>

| Module Code        | IY455                                   |
| ------------------ | --------------------------------------- |
| Group              | B                                       |
| Module Title       | Information Systems Analysis and Design |
| Assessment Type    | Coursework Stage 1                      |
| Module Tutor Name  | Mustafa Gashim                          |
| Student ID Number  | P508109                                 |
| Date of Submission | 11/03/2026                              |

☐ *I confirm that this assignment is my own work. Where I have referred to academic
sources, I have provided in-text citations and included the sources in the
final reference list.*

 ☐ *Where I have used AI, I have cited and
referenced appropriately.*

<style>
</style>

<style>
</style>

Task 1 –
Data Base Normalisation – Upload to github (2 COMMITS)

**1.1 What
is normalisation? – use the libraries to get more info and reference**

Normalisation is a systematic Process of organising a regional database’s
attributes and tables in order to reduce data redundancy and improve
data integrity. Normalisation involves decomposing a table into smaller less redundant tables without losing information and defining between those tables.

The process proceeds through a series of progressive stages
called normal forms. Each normal form addresses a specific type of anomaly or
redundancy. The three most applied normal forms in practice are First form,
Second Normal form and Third Normal form.

**1.2 Advantages
of Normalisation – use libraries to get more information**

·      Eliminates data redundancy: Each piece of
information is stored only once, reducing storage requirements and improving
inconsistencies.

·      Prevents update anomalies: Changing a value in one place is
sufficient. There is no risk of the same fact being updated in one location but
not another.

·      Prevents insertion anomalies: New records can be added without
requiring unrelated data
to exist first.

·      Prevents deletion anomalies:
Deleting a record does not actually destroy information about unrelated
entities.

·      Improves data integrity and consistency: Through
primary and foreign assortations.

·      Simplifies logic: Well structured tables are
easier to edit and manage or maintain.

**1.3
Disadvantages of Normalisation – use libraries to get more information**

·       Increased
number of tables: A full
normalised schema may require JOIN operations to retrieve data, which can
impact query performance.

·       Query
complexity: Queries become
more complex as data is spread across multiple related tables.

·       Potential performance overhead: In high-volume reporting
environments, denormalization is sometimes preferred for read performance.

·       Overhead in design: Identifying all functional dependencies requires
careful analysis and domain knowledge.

**1.4
Un-Normalised Form**

Here is the un-normalised form of the DVD Loan Management
System sample form.

**1.5  First Normalised Form (1NF)**

**To achieve
this, all repeated rows are removed and each row is identified/identifiable.**.
