#### We have one table as below that has list of Desk that are free. The table name is Desk.

### <u>flights</u>

| flight     | source     | destination |
|:----------:|:----------:|:-----------:|
| AIR 0087   | Pune       | Rajasthan   | 
| AIR 0187   | Delhi      | Ahmedabad   | 
| AIR 0767   | Rajasthan  | Delhi       |
| AIR 1678   | Kolkata    | Ahmedabad   |
| AIR 0369   | Bangalore  | Pune        |
| AIR 0029   | Rajasthan  | Ahmedabad   |
| AIR 8878   | Delhi      | Hyderabad   |


Travel - Banglore ==> Ahmedabad
### <u>Expected Output</u>
| flight   |
|:--------:|
| AIR 0369 |
| AIR 0087 |
| AIR 0029 |



|pid|  date|price|
|:---:|:------:|:-----:|
|  1|26-May|  100|
|  1|27-May|  200|
|  1|28-May|  300|
|  2|29-May|  400|
|  3|30-May|  500|
|  3|31-May|  600|



|pid|  date|price|new_price|
|---|------|-----|---------|
|  1|26-May|  100|      100|
|  1|27-May|  200|      300|
|  1|28-May|  300|      600|
|  2|29-May|  400|      400|
|  3|30-May|  500|      500|
|  3|31-May|  600|     1100|