# Reading notes 07

Object-oriented programing is effective for adhering to DRY principles. Both objects and tables are useful for modeling data.

## Domain Modeling

1. Domain modeling can be used to reuse code from a single source. Useful for reducing memory requirements.

## HTML Table Basics

1. Screen-readers will attempt to describe a table, so using one for the layout can make it difficult for a user to understand.
2. <tr> table row element used to describe each row, <td> table data element used to surround the data, and <th> table head used for headers

## Constructors

1. A constructor is a function that takes in some data and returns an object. When using a constructor you can add rules to prevent objects that could break code elsewhere from being created.
2. In a constructor this effects only the item being instantiated.

## Object Prototypes Using A Constructor

1. I had a job as an inventory specialist, basically I counted things. The assignments were based on the speed they expected from you so at the top you might be assigned anywhere, at the next level down you might be anywhere except the very highest count areas, and so on. Each level would inherit the permissions of those below it and unlock one further on their level.
