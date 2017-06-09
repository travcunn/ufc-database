# ufc-database
UFC database

## Queries

##### List all fighters defeated by (fighter name)
```sql
select person2.name from fight join person as person1 on fight.fighterA = person1.id join person as person2 on fight.fighterB = person2.id where person1.name = "Conor McGregor";
```
