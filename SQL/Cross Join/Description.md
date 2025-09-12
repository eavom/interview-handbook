| main_dish_id  | dish_name        | is_veg         |
| -------------- | --------------- | -------------- |
| 1              | Grilled Chicken | false          |
| 2              | Veggie Burger   | true           |
| 3              | Pasta Alfredo   | true           |


| drink_id  | drink_name   |
| --------- | ------------ |
| 1         | Cola         |
| 2         | Orange Juice |


Expected Output =>

| main_course   | drink        |
| ------------- | ------------ |
| Veggie Burger | Cola         |
| Veggie Burger | Orange Juice |
| Pasta Alfredo | Cola         |
| Pasta Alfredo | Orange Juice |
