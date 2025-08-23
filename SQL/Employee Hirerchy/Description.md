

##### employee

| emp_id   | emp_name   | reporting_to      | designation      |
|:--------:|:----------:|:-----------------:|:-----------------|
| 10       | Darpan     | null              | CTO              |
| 21       | Ramesh     | 10                | Manager          |
| 22       | Aarti      | 10                | Manager          |
| 31       | Shubham    | 21                | Tech Lead        |
| 32       | Ritesh     | 22                | Tech Lead        |
| 41       | Vaibhav    | 31                | Senior Engineer  |
| 42       | Ayesha     | 32                | Senior Engineer  |
| 43       | Nilesh     | 32                | Senior Engineer  |
| 51       | Heena      | 44                | Junior Engineer  |
| 52       | Kiran      | 43                | Junior Engineer  |

#### Given the table with the sample data, list out the employees who is directly or indirecty reporting to 'Aarti'

##### expected output

| emp_id   | emp_name   | direction  | hierarchy_tree                         |
|:--------:|:----------:|:----------:|:---------------------------------------:
| 32       | Ritesh     | direct     | Aarti ==> Ritesh                       |
| 42       | Ayesha     | indirect   | Aarti ==> Ritesh ==> Ayesha            |
| 43       | Nilesh     | indirect   | Aarti ==> Ritesh ==> Nilesh            |
| 52       | Kiran      | indirect   | Aarti ==> Ritesh ==> Nilesh ==> Kiran  |
