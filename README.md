# Mark Scheme for Year 9 Computer Science Summer 2024 AQA Yearly Assessment

### Q1. What is the output of the AND gate when both inputs are 1? [1 Mark]
- **Answer**: B. 1
- **Marking Criteria**: 1 mark for correct answer.

### Q2. What is the output of the OR gate when both inputs are 0? [1 Mark]
- **Answer**: A. 0
- **Marking Criteria**: 1 mark for correct answer.

### Q3. What is the output of the NOT gate when the input is 1? [1 Mark]
- **Answer**: A. 0
- **Marking Criteria**: 1 mark for correct answer.

### Q4. In the expression A AND B, what is the output if A=1 and B=0? [1 Mark]
- **Answer**: A. 0
- **Marking Criteria**: 1 mark for correct answer.

### Q5. In the expression A OR B, what is the output if A=0 and B=1? [1 Mark]
- **Answer**: B. 1
- **Marking Criteria**: 1 mark for correct answer.

### Q6. Complete the following Truth Table [8 Marks]
- **Answer**:
    ```
    A B C D | A OR B | C OR D | (A OR B) AND (C OR D)
    0 0 0 0 |   0    |   0    |         0
    0 0 0 1 |   0    |   1    |         0
    0 0 1 0 |   0    |   1    |         0
    0 0 1 1 |   0    |   1    |         0
    0 1 0 0 |   1    |   0    |         0
    0 1 0 1 |   1    |   1    |         1
    0 1 1 0 |   1    |   1    |         1
    0 1 1 1 |   1    |   1    |         1
    1 0 0 0 |   1    |   0    |         0
    1 0 0 1 |   1    |   1    |         1
    1 0 1 0 |   1    |   1    |         1
    1 0 1 1 |   1    |   1    |         1
    1 1 0 0 |   1    |   0    |         0
    1 1 0 1 |   1    |   1    |         1
    1 1 1 0 |   1    |   1    |         1
    1 1 1 1 |   1    |   1    |         1
    ```
- **Marking Criteria**: 1 mark for each correct row. Partial credit for partially correct rows.

### Q7. Binary Search [5 Marks]
- **Answer**:
    ```
    - Initial list: [Anthony, Booker, Curry, Durant, Embiid, George, Harden, Irving, James, Leonard, Mitchell, Paul, Thompson, Westbrook, Young]
    - Compare middle element "James" with "Irving".
    - "Irving" is greater than "James". Focus on the right sublist: [Leonard, Mitchell, Paul, Thompson, Westbrook, Young]
    - Compare middle element "Thompson" with "Irving".
    - "Irving" is less than "Thompson". Focus on the left sublist: [Leonard, Mitchell, Paul]
    - Compare middle element "Mitchell" with "Irving".
    - "Irving" is less than "Mitchell". Focus on the left sublist: [Leonard]
    - Compare "Leonard" with "Irving". "Irving" is found.
    ```
- **Marking Criteria**: 1 mark for each correct step, 1 mark for correct identification.

### Q8. Explanation of Algorithms [4 Marks]
- **Answer**:
    - **Primary purpose**:
        - Binary Search: To find the position of a target value within a sorted list.
        - Merge Sort: To sort an unordered list into ascending or descending order.
    - **Processing**:
        - Binary Search: Divides the search interval in half repeatedly.
        - Merge Sort: Divides the list into halves, sorts each half, and merges the sorted halves.
- **Marking Criteria**: 1 mark for each correct point (2 points for each algorithm).

### Q9. What is the output of the following code? [1 Mark]
- **Answer**: D. 3 and 1
- **Marking Criteria**: 1 mark for correct answer.

### Q10. Which of the following correctly identifies the data types stored in the variables? [1 Mark]
- **Answer**: A. int, float, string, bool
- **Marking Criteria**: 1 mark for correct answer.

### Q11. Which of the following is the correct order of operations to input a value and print it? [1 Mark]
- **Answer**: B. value = input() -> print(value)
- **Marking Criteria**: 1 mark for correct answer.

### Q12. Programming Task [5 Marks]
- **Answer**:
    ```python
    # Part 1
    age1 = int(input("Enter the age of the first family member: "))
    age2 = int(input("Enter the age of the second family member: "))
    age3 = int(input("Enter the age of the third family member: "))
    
    # Part 2
    total_age = age1 + age2 + age3
    
    # Part 3
    print(f"The total age of the three family members is {total_age}.")
    ```
- **Marking Criteria**:
    - 3 marks for correctly prompting and storing the ages.
    - 1 mark for correctly calculating the total age.
    - 1 mark for correctly printing the total age.

### Q13. What is a record in a database table typically referred to as? [1 Mark]
- **Answer**: C. A row
- **Marking Criteria**: 1 mark for correct answer.

### Q14. Which of the following is an advantage of using a flat file database? [1 Mark]
- **Answer**: A. Simplicity and ease of setup
- **Marking Criteria**: 1 mark for correct answer.

### Q15. What is a primary key in a database? [1 Mark]
- **Answer**: A. A unique identifier for each record
- **Marking Criteria**: 1 mark for correct answer.

### Q16. In the expression A AND B, what is the output if A=1 and B=0? [1 Mark]
- **Answer**: A. 0
- **Marking Criteria**: 1 mark for correct answer.

### Q17. In a relational database, what is the purpose of a foreign key? [1 Mark]
- **Answer**: C. To establish a link between data in two tables
- **Marking Criteria**: 1 mark for correct answer.

### Q18. Which of the following is a type of database that stores data in a plain text file? [1 Mark]
- **Answer**: B. Flat File Database
- **Marking Criteria**: 1 mark for correct answer.

### Q19. Which of the following relationships describes a situation where many classes may be taught by one teacher? [1 Mark]
- **Answer**: B. Many-to-One
- **Marking Criteria**: 1 mark for correct answer.

### Q20. Explain the difference between “record” and “field” in Database [2 Marks]
- **Answer**:
    - A **record** is a row in a table, representing a single, complete set of related data.
    - A **field** is a column in a table, representing a single piece of data within a record.
- **Marking Criteria**: 1 mark for each correct explanation.

### Q21. Explain the difference between “PRIMARY” and “FOREIGN” Keys in Database [2 Marks]
- **Answer**:
    - A **PRIMARY KEY** is a unique identifier for each record in a table.
    - A **FOREIGN KEY** is a field that creates a relationship between two tables.
- **Marking Criteria**: 1 mark for each correct explanation.

### Q22. Identify the primary and foreign keys: [3 Marks]
- **Answer**:
    - In the Players table, the primary key is **PlayerID**, and the foreign key is **TeamID**.
    - In the Teams table, the primary key is **TeamID**.
- **Marking Criteria**: 1 mark for each correct identification.

### Q23. Describe the relationship between the tables: [2 Marks]
- **Answer**: The relationship between the Players and Teams tables is a Many-to-One relationship, where each player belongs to one team.
- **Marking Criteria**: 2 marks for correct explanation.

### Q24. Determining Player-Team Relationships [1 Mark]
- **Answer**: PlayerID 5 belongs to the Los Angeles Clippers, and the coach of that team is Tyronn Lue.
- **Marking Criteria**: 1 mark for correct identification.

### Q25. Matching Players to Cities [1 Mark]
- **Answer**: Players coached by Erik Spoelstra are in the Miami Heat team, staying in Miami.
- **Marking Criteria**: 1 mark for correct identification.

### Q26. Identifying Coaches and Locations [2 Marks]
- **Answer**: Yes, players with PlayerID 1 (LeBron James) and PlayerID 11 (Anthony Davis) are taught by the same coach, Darvin Ham, and they are staying in Los Angeles.
- **Marking Criteria**: 2 marks for correct identification.
