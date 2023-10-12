# Project Phase 3
## Semester 1 2023/2024

- [P2 Guidlines](https://github.com/IzyanIzzatiK/SECD2523-Database/blob/main/phase2.md#p2-guidelines)
- [P2 Database Conceptual Design](https://github.com/IzyanIzzatiK/SECD2523-Database/blob/main/phase2.md#p2-database-conceptual-design)
- [P2 Rubrics](https://github.com/IzyanIzzatiK/SECD2523-Database/blob/main/phase2.md#p2-rubric)
  - [1. Reporting](https://github.com/IzyanIzzatiK/SECD2523-Database/blob/main/phase2.md#1-reporting-2)
  - [2. ERD Design Process ](https://github.com/IzyanIzzatiK/SECD2523-Database/blob/main/phase2.md#2erd-design-process-3)

<table>
  <tr>
    <td>Subject</td>
    <td>Subject	:	Database (SECD2523)</td>
  </tr><tr>
    <td>Section</td>
    <td></td>
  </tr><tr>
    <td>Task</td>
    <td>Phase 3 (P3) – Database Logical Design & SQL (20%)/td>
  </tr><tr>
    <td>Due</td>
    <td>WEEK 14 (07 Jan – 13 Jan 24)</td>
  </tr>
</table>

---

## P3 Guidelines

<table>
  <tr>
    <th>No</th>
    <th>Task</th>
    <th>Deliverables (Items in Database)</th>
  </tr>
  <tr>
    <td>1.</td>
    <td>
      <ul>
        <li>- Transform the conceptual ERD in P2 into logical ERD. (e.g.: by removing non-relational features e.g.: *:* relationships, complex relationships, etc.)</li>
        <li>- Derive relations schema from the logical ERD produced above.</li>
        <li>- Perform normalization up till BCNF (if-any) to these relations.</li>
        <li>- Draw the final logical ERD.</li>
        <li>- Update the data dictionary based on the normalized relations produced from above.</li>
        <li>- Validate logical ERD with the system’s transaction requirements using interface design.</li>
    </td>
    <td>
      A report containing the following:
      <ul>
        <li>Logical ERD (global data model)</li>
        <li>Relational database schemas (normalized table)</li>
        <li>Data dictionary for the normalized logical design</li>
        <li>Interface design (mapped to the proposed SQL statement)</li>
        <li>Proposed SQL statement (refer to rubric)</li>
      </ul>
        Demonstration:
          <ul>
            <li>Individual demonstration for SQL statement.</li>
          </ul>
    </td>
  </tr>
</table>



 ---

## P3 Database Logical Design
Prepare a Database conceptual design as below:

- 1.0	Introduction
- 2.0	Overview of project
- 3.0	Database conceptual design
  - 3.1	Updated business rule
  - 3.2	Conceptual ERD
- 4.0	DB logical design
  - 4.1	Logical ERD
  - 4.2	Updated Data Dictionary
  - 4.3	Normalization 
- 5.0	Relational DB Schemas (after normalization)
- 6.0	SQL Statements (DDL & DML)
- 7.0	Summary

---

## P3 Rubrics
### 1. Reporting
#### A. Overal (2%)
<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Document the whole process of designing the ERD</td>
    <td>Documented ALL reports on the construction of the database design. Shows FULL understanding of the requirements based on the case study.</td>
    <td>Documented MAJOR reports on the construction of the database design. Shows a GOOD understanding of the requirements based on the case study.</td>
    <td>Documented MINIMAL reports on the construction of the database design. Shows MINIMAL understanding of the requirements based on the case study.</td>
    <td>LITTLE evidence that the documents are based on the given case study.</td>
  </tr>
  <tr>
    <td>SQL documentation</td>
    <td>The student provides THOROUGH documentation for their SQL code, including comments explaining the purpose of the code, any complex logic, and the structure of the database.</td>
    <td>The student provides ADEQUATE documentation for their SQL code, but it may lack some details or clarity in explaining complex logic</td>
    <td>The student provides MINIMAL documentation for their SQL code, making it challenging to understand the purpose and logic</td>
    <td>The student provides NO documentation for their SQL code, making it nearly impossible to understand the purpose and logic</td>
  </tr>
</table>

#### B.	Database Logical Design – ERD & Normalization (6%)
<table>
  <tr>
    <th>Criteria</th>
    <th>High (4)</th>
    <th>Average (3)</th>
    <th>Low (2)</th>
    <th>Unsatisfied (1)</th>
  </tr>
  <tr>
    <td>Follow the instructions to draw the logical ERD and derive the relations</td>
    <td>COMPLETE understanding of how to draw ERD and derive relations</td>
    <td>Exhibits a GOOD understanding of how to draw ERD and derive relations</td>
    <td>Exhibits MINIMAL understanding of how to draw ERD and derive relations.</td>
    <td>UNABLE to follow the instructions on how to draw ERD and fails to derive relations.</td>
  </tr>
  <tr>
    <td>Identifies all the basic concepts in normalization (relational schema)</td>
    <td>COMPLETE understanding of the basic concepts in ERD</td>
    <td>Exhibit a GOOD understanding of the basic concepts in ERD.</td>
    <td>Exhibit a MINIMAL understanding of the basic concepts in ERD.</td>
    <td>UNABLE to show understanding of the basic concepts of ERD.</td>
  </tr>
  <tr>
    <td>Represents the dependency diagram (and relational schema) based on the given case study</td>
    <td>COMPLETELY and ACCURATELY use of names, definitions in entities, and attributes - table name is appropriately used in regard to its data elements</td>
    <td>Some MINOR inaccurate use of names, definition in entities and attributes - FEW table name is not clear in regard to its data elements</td>
    <td>INACCURATE the use of names, definitions in entities, and attributes - table name DID NOT correlate with its data elements</td>
    <td>WRONG the use of names, definitions in entities and attributes. Shows NO understanding in identifying the tables based on the case study.</td>
  </tr>
  <tr>
    <td>Differentiates the keys in the dependency diagram</td>
    <td>COMPLETE understanding of the dependencies and normal-form levels</td>
    <td>Exhibit a GOOD understanding of the dependencies and normal-form levels</td>
    <td>Exhibit a MINIMAL understanding of the dependencies and normal-form levels</td>
    <td>UNABLE to differentiate the dependencies and normal-form levels</td>
  </tr>
  <tr>
    <td>Label the necessary transitive and partial dependencies</td>
    <td>Correctly choose ALL of the PKs and FKs, with regard to the naming convention</td>
    <td>Correctly choose MOST of the PKs and FKs, in regard to the naming convention.</td>
    <td>INCORRECTLY choose the PKs and FKs.</td>
    <td>WRONGLY choose the PKs and FKs.</td>
  </tr>
  <tr>
    <td>Illustrates the normalization steps - from 1NF --> 2 NF --> 3NF -->BCNF (if applicable)</td>
    <td>A COMPLETE populated the tables with CORRECT data elements as outlined in the ERD design.</td>
    <td>Populated the tables with ALL data elements as outlined in the ERD design - with MINIMAL errors.</td>
    <td>Populated the tables with MINIMAL data elements as outlined in the ERD design - with MINIMAL errors.</td>
    <td>Populated the tables with MINIMAL data elements as outlined in the ERD design - with NUMEROUS errors.</td>
  </tr>
</table>
