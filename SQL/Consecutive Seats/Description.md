#### We have one table as below that has list of Desk that are free. The table name is Desk.

### <u>desk_allocation</u>

| desk_id | row_number | is_free      |
|:-------:|:----------:|:------------:|
| SURF001 | 1          |              |
| SURF002 | 1          | X            |
| SURF003 | 1          | X            |
| SURF004 | 1          | X            |
| SURF005 | 2          | X            |
| SURF006 | 2          |              |
| SURF007 | 2          | X            |
| SURF008 | 2          | X            |
| SURF009 | 3          |              |
| SURF010 | 3          | X            |
| SURF011 | 3          | X            |
| SURF012 | 3          | X            |


### <u>Expected Output</u>
| desk_id |
|:-------:|
| SURF010 |
| SURF011 |
| SURF012 |
