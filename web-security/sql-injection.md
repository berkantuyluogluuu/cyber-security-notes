# sql injection basics

## what is sql injection

sql injection allows attackers to manipulate database queries

## example payload

```sql
' OR '1'='1
```

## risks

- authentication bypass
- data leak
- database manipulation

## prevention

- prepared statements
- parameterized queries
- input validation
