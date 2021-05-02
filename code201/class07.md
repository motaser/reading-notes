# Tables 
When representing information in a table, you need to think
in terms of a grid made up of rows and columns (a bit like a
spreadsheet). In this chapter you will learn how to:

* Use the four key elements for creating tables.
* Represent complex data using tables.
* Add captions to tables.

A table represents information in a grid format.
Examples of tables include financial reports, TV schedules, and sports results.

**<table>**:The <table> element is usedto create a table. The contents of the table are written out row by row.

**<tr>**:You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.)
It is followed by one or more <td> elements (one for each cell in that row). At the end of the row you use a closing </tr> tag.

**<td>**:Each cell of a table is represented using a <td>
element. (The td stands for table data.)

**<th>**:The <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)

1. The <table> element is used to add tables to a web
page.
2. A table is drawn out row by row. Each row is created
with the <tr> element.
3. Inside each row there are a number of cells
represented by the <td> element (or <th> if it is a
header).
4. You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
5. For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>.

# Functions, Methods, and Objects

![imges](https://miro.medium.com/max/12000/0*YRHDXex7hlzpKw60)

* Functions allow you to group a set of related
statements together that represent a single task.
* Functions can take parameters (informatiorJ required
to do their job) and may return a value.
* An object is a series of variables and functions that
represent something from the world around you.
* In an object, variables are known as properties of the
object; functions are known as methods of the object.
* Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
* JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
* Arrays and objects can be used to create complex data
sets (and both can contain the other).