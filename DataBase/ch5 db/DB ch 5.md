# ch5 DB..The Relational Data Model And Relational DataBase Constrains

## Relational Data Model Concept:
- تصنف ضمن representaion data model.
- based on relations
- relation = tables...>>جدول
- The data elements in each row represents facts that correspond to real world entity
- t[Ai] == t.Ai  ⇒ component values of a tuple
- rows=tuples=records
- each column has column header that gives that dives an indication of the meaning of the data items in that colimns
- column header=attribute=field
- Each row has a unique attribute it called `key`
- In case no unique attribute I will create it and it called `Artificial Key or Surrogate Key`
  ___
  ### schema:
  
R(A1,A2,....,An) is the schema of the relation.

R is the name of the relation.

A1,A2,...,An are the Attributes of the relation.

Each attribute has domain (constraint): set of valid values.

a domain also has a data-type or a format defiened for it.
![5](../ch5%20db/pics/5.png)


  ### superkey and key:
  ![4](../ch5%20db/pics/4.png)


