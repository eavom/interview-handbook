

##### employee

| emp_id   | emp_name   | reporting_manager | designation      |
|:--------:|:----------:|:-----------------:|:-----------------|
| 10       | James      | null              | CTO              |
| 21       | Ramesh     | 10                | Manager          |
| 22       | Aarti      | 10                | Manager          |
| 31       | Shubham    | 21                | Tech Lead        |
| 32       | Ritesh     | 22                | Tech Lead        |
| 41       | Vaibhav    | 31                | Senior Engineer  |
| 42       | Ayesha     | 32                | Senior Engineer  |
| 43       | Nilesh     | 32                | Senior Engineer  |
| 51       | Heena      | 44                | Junior Engineer  |
| 52       | Kiran      | 44                | Junior Engineer  |

#### Given the table with the sample data, list out the employees who is directly or indirecty reporting to 'Aarti'

##### expected output

| emp_id   | emp_name   | direction  |
|:--------:|:----------:|:----------:|
| 32       | Ritesh     | direct     |
| 42       | Ayesha     | indirect   |
| 43       | Nilesh     | indirect   |


#### Given the table with the sample data, generate the employee hierarchy as give below who is directly or indirectly reporting to 'Ramesh'

#### expected output

| emp_id   | emp_name   | hierarchy_tree                          |
|:--------:|:----------:|:---------------------------------------:|
| 33       | Ritesh     | Aarti ==> Ritesh                        |
| 34       | Shubham    | Aarti ==> Shubham                       |
| 41       | Vaibhav    | Aarti ==> Ritesh ==> Vaibhav            |
| 42       | Ayesha     | Aarti ==> Ritesh ==> Ayesha             |
| 43       | Nilesh     | Aarti ==> Ritesh ==> Nilesh             |
| 51       | Heena      | Aarti ==> Ritesh ==> Nilesh ==> Heena   |
| 52       | Kiran      | Aarti ==> Ritesh ==> Nilesh ==> Kiran   |