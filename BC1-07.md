### Domain Modeling article
(https://github.com/codefellows/domain_modeling#domain-modeling)

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
1. Model its attributes with a constructor function that defines and initializes properties.
1. Model its behaviors with small methods that focus on doing one job well.
1. Create instances using the new keyword followed by a call to a constructor function.
1. Store the newly created object in a variable so you can access its properties and methods from outside.
1. Use the this variable within methods so you can access the object's properties and methods from inside.

### HTML Chapter 6, 126-145
Table Structure
`<table>`  
`<tr>` indicates new row  
`<td>` table data or cells
`<th>` table heading  
The colspan  and rowspan attributes can be used on headers or table data to make the cell span multiple columns or rows, respectively  

### JavaScript Chapter 3, 106-144
Object constructors can use a function as a template for creating objects.  
The name of the constructor function usually begins with a capital letter to remind developers to use the new keyword.  
```function Hotel(name, rooms, booked) {
    this.name = name;
    this.rooms = rooms;
    this.booked = booked;
    this.checkAvailability = function() {
        return this.rooms = this.booked;
    };
    }
}
```
This (it is a keyword)  
Arrays are objects, and the key for each value is its index number.  

In order to work with dates, you have to create an instance of the Date object.  
`var today = new Date();`
