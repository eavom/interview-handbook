### Given a user login information, find out the users who have logged in for 3 consicutive days. Also pulled out login and logout date.


==> users

| user_id   |       name       |       email                     |
|:---------:|:----------------:|:-------------------------------:|
|     1     | Aarti Sharma     | aarti.sharma@code.code          |
|     2     | Nilesh Chaudhari | nilesh.chaudhari@code.code      |
|     4     | Karan Verma      | karan.verma@code.code           |
|     5     | Ritu Deshmukh    | ritu.deshmukh@code.code         |


==> login_history

| user_id  | login_date  |
|:--------:|:----------: |
|     1    |  2025-08-10 |
|     1    |  2025-08-11 |
|     1    |  2025-08-12 |
|     1    |  2025-08-14 |
|     2    |  2025-08-09 |
|     2    |  2025-08-10 |
|     2    |  2025-08-11 |
|     2    |  2025-08-13 |
|     3    |  2025-08-08 |
|     3    |  2025-08-09 |
|     3    |  2025-08-10 |
|     3    |  2025-08-11 |
|     3    |  2025-08-15 |
|     3    |  2025-08-16 |
|     3    |  2025-08-17 |
|     4    |  2025-08-10 |
|     4    |  2025-08-12 |
|     5    |  2025-08-10 |
|     5    |  2025-08-11 |
|     5    |  2025-08-13 |


==> expected output

| user_id   | name             |         email              | login_date  | logout_date |
|:---------:|:----------------:|:--------------------------:|:-----------:|:-----------:|
|     1     | Aarti Sharma     | aarti.sharma@code.code     |  2025-08-10 |  2025-08-12 |
|     2     | Nilesh Chaudhari | nilesh.chaudhari@code.code |  2025-08-09 |  2025-08-11 |
|     3     | Meena Joshi      | meena.joshi@code.code      |  2025-08-08 |  2025-08-11 |
|     3     | Meena Joshi      | meena.joshi@code.code      |  2025-08-15 |  2025-08-17 |
