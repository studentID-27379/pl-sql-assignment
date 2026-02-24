Student Name: Obi Ekene
Student ID: 27379
Course: PL/SQL Programming
1. Approach Used
This assignment was completed using anonymous PL/SQL blocks in Oracle SQL Developer (XE). Each question was solved separately and tested to ensure it compiles and runs without errors.
Question 1 – Variables, %TYPE & DBMS_OUTPUT
Declared variables using appropriate data types (VARCHAR2, NUMBER, DATE, BOOLEAN).
Used %TYPE and %ROWTYPE to reference table columns and rows dynamically from the University schema.
Used SELECT INTO to retrieve specific records.
Printed formatted output using DBMS_OUTPUT.PUT_LINE.
Calculated years of service using MONTHS_BETWEEN(SYSDATE, hire_date) / 12.
Question 2 – IF / ELSIF / ELSE
Applied conditional statements to evaluate employee salary, commission, course availability, and student age eligibility.
Used logical operators (AND, OR) and NVL() to handle NULL values safely.
Used COUNT(*) queries to determine enrollment totals.
Ensured all outputs were clearly formatted and logically structured.
Question 3 – CASE Statements
Used searched CASE statements for score-to-grade conversion.
Used simple CASE statements for department building code assignment.
Compared computed grade results with stored grades to validate correctness.
Applied CASE logic to classify job titles into rank categories.
Question 4 – Loops
Used a basic LOOP with EXIT WHEN for tuition calculation.
Used a WHILE loop to process department salary data.
Used a FOR loop to generate student academic performance reports.
Applied aggregation logic inside loops (counting, summing, tracking maximum values).
Question 5 – Combined Challenge
Integrated %ROWTYPE, SELECT INTO, IF/ELSIF, CASE, and FOR loops into a single structured solution.
Generated a formatted employee profile report.
Performed salary analysis and service classification.
Calculated department statistics using looping logic.
2. Lessons Learned
Through this assignment, I gained a better understanding of:
The importance of %TYPE and %ROWTYPE for writing flexible code.
How to structure conditional logic effectively using IF and CASE.
When to use different types of loops (LOOP, WHILE, FOR).
How to combine multiple PL/SQL concepts in one solution.
The importance of testing each block individually before final submission.
3. Challenges Faced
Some challenges encountered during this assignment include:
Handling NULL values properly in conditions.
Ensuring SELECT INTO statements return exactly one row.
Designing logical salary and grade classification structures.
Formatting output clearly using DBMS_OUTPUT.
These issues were resolved through careful debugging and testing.
4. Conclusion
This assignment strengthened my practical understanding of PL/SQL programming. It improved my ability to work with database-driven logic, apply structured programming concepts, and develop organized, readable code.
All solutions compile and execute successfully in Oracle SQL Developer (XE).
