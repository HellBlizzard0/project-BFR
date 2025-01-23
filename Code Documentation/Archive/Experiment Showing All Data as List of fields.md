#Employee #SQL 

> [!note] Unused
> This idea is scrapped and will not be used
> 

I managed to call a variable column in an SQL block, as in the picture below:
![[Pasted image 20250122102936.png]]

The column name is fed as an input parameter to the SQL block. 
![[Pasted image 20250122103303.png]]
![[Pasted image 20250122110208.png]]
Expand Inline has to be set to true to bypass code sanitization before running the query.

> [!warning] Security
> Setting a query parameter's "Expanded Inline" to TRUE risks your code from SQL injection vulnerability.
> USE WITH CAUTION!


Column name is stored in a static entity of some sort


Static Entity

| Column  | Description                                                    |
| ------- | -------------------------------------------------------------- |
| ColName | The name of the data column that will be used in the SQL query |
| Label   | Label to be displayed of the text in the UI                    |
| Order   | The order of which the field is going to be displayed          |


