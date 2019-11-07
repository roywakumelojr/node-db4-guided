# Data Modeling Notes

## Requirements

A client has hired you to build an API for managing `zoos` and the `animals` kept at each `zoo`. The API will be use for `zoos` in the _United States of America_, no need to worry about addresses in other countries.

For the `zoos` the client wants to record:

- name.
- address.

For the `animals` the client wants to record:

- name.
- species.
- list of all the zoos where they have resided.

Determine the database tables necessary to track this information.
Label any relationships between table.


*** NOTES ***

### A Good Data Model ###
- Captures All / ONLY the information the system needs. 
- It should reflect reality from the system's point of view.
- It should be flexible and can evolve with the system.
- It should guarantee `data integrity`, without sacrificing too much system performance .
- The model should be driven by the way the data is going to be used.

** The components of a data model. **
- Resources also known as entitles which map to tables
- Properties also known as column or fields
- Relationships which are expressed through the use of foreign keys

** Work Flow. **
- Identify entities
- identify the properties
- identify the relationships 

** Relationship Types **
- One to one
- One to many: This is the most common
- many to many: 

** Model Design Mantras. **
- Every table mush has a **primary key**
- Work on **two to three** entities at a time 
- One to many relationships are modeled using a foreign key
- The foreign key always goes on the many table
- The foreign key column mush be the same type as the primary key  is reference.
- many to many relationships are modeled using a third table
- The third table could include other column


Links:
https://www.postgresql.org/docs/12/datatype.html