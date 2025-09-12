| employee_id  | name        | hourly_rate  |
| ------------ | ----------- | ------------ |
| 1            | Alice Smith | 25           |
| 2            | Bob Johnson | 30           |
| 3            | Carol Davis | 28           |
| 4            | Dave Thomas | 32           |


| log_id  | employee_id  | work_date  | hours_worked  |
| ------- | ------------ | ---------- | ------------- |
| 101     | 1            | 2025-09-01 | 8             |
| 102     | 1            | 2025-09-02 | 6             |
| 103     | 2            | 2025-09-01 | 7             |
| 104     | 2            | 2025-09-03 | 8             |
| 105     | 3            | 2025-08-30 | 8             |
| 106     | 3            | 2025-09-02 | 8             |

Expected Output

| employee_id  | name        | month      | total_hours  | total_pay  |
| ------------ | ----------- | ---------- | ------------ | ---------- |
| 1            | Alice Smith | 2025-09-01 | 14           | 350        |
| 2            | Bob Johnson | 2025-09-01 | 15           | 450        |
| 3            | Carol Davis | 2025-09-01 | 8            | 224        |
| 4            | Dave Thomas | 2025-09-01 | 0            | 0          |
