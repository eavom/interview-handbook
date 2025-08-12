#### Below table having desk allocation detail. If desk is allocated then is_free indicator would be blank/false. Let's suppose we want to allocate available desks to 3 member working in the same time. Find out the best fit in the same row.

### <u>desk_allocation</u>

| desk_id | row_number | is_free      |
|:-------:|:----------:|:------------:|
| SURF001 | 1          |              |
| SURF002 | 1          | X            |
| SURF003 | 1          | X            |
| SURF004 | 1          | X            |
| SURF005 | 1          | X            |
| SURF006 | 2          |              |
| SURF007 | 2          | X            |
| SURF008 | 2          |              |
| SURF009 | 2          | X            |
| SURF010 | 2          | X            |
| SURF011 | 3          | X            |
| SURF012 | 3          |              |
| SURF013 | 3          | X            |
| SURF014 | 3          | X            |
| SURF015 | 3          | X            |


### <u>Expected Output</u>
| desk_id |
|:-------:|
| SURF013 |
| SURF014 |
| SURF015 |
