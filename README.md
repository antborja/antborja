<h1>
  <img src = "https://github.com/antborja/antborja/assets/112919376/4ff65cb8-ad76-4317-b0d5-d9dc2fc326bd" width = "40"> ᜃᜓᜋᜓᜐ᜔ᜆ (Hello), my name is Anthony Borja! <img src="https://github.com/antborja/antborja/assets/112919376/3ed4508b-cd26-4aac-92a3-5781814edc86" width="40">
</h1>

<em> Electrical Engineering student at <strong>Pasadena City College</strong> </em> 

<h2> About Me </h2>

```javascript
const anthony = {
    pronouns: "He" | "Him",
    code: [CPP, LATEX, Java, MATLAB],
    projects: {
        cpp: ["SQL Database System", "SFML Graphing Calculator"]
    },
    goalOfTheWeek: "Finish SQL Project README.md",

    hobbies: ["jazz trumpet", "jazz guitar", "film photography", "reading", "saving gotham"]
};
```

<h1>Project Showcase</h1>

<p>Below are quick demos of different projects I have made previously. These projects
may have public repositories that will be linked within the project description.</p>

Contents
===========

* [SQL Database Project (C++)](https://github.com/antborja#sql-database-project)
* [SFML Graphing Calculator Project (C++)](https://github.com/antborja#sfml-graphing-calculator)

<!---
SQL PROJECT
-->
<h2>SQL Database Project</h2>
<em>Written in C++ by Anthony Borja</em>
<br>

### About
---
The SQL Data base project handles tables of information that can be accessed and stored through the application.
All files and information are stored using binary files and text files and can later be accessed anytime.

### Usage
---
### Entering a Command
<img src="https://github.com/antborja/antborja/assets/112919376/8d648222-3a42-43bb-9afc-6df46a7b539d" width="400">

Commands are entered through the terminal, following the `>` character.
When the program starts, the user can view the tables currently stored in the database (explained later).

### Making a Table
To create a table, use the `make` command by typing

```terminal
make table [table name] fields [field names separated by commas]
```

Here's an example in which I make a table called "students" with the field columns lname (last name), fname (first name), age and major:
![make_students](https://github.com/antborja/antborja/assets/112919376/5db93128-34f4-4a42-a7d1-8e9dcc0efea6)

To create multiple tables, simply run the `make` command again with a different table name.

Another example in which I create a table called "employees":
![make_table](https://github.com/antborja/antborja/assets/112919376/500538af-5c09-4a9d-bb14-b31f66d9a90c)


### Saving a Table
Each table is saved automatically after creation. When the program is opened, the tables that are stored will be displayed at the top, followed by the name of their
respective binary file:

![saving_files](https://github.com/antborja/antborja/assets/112919376/e2848b79-66ef-4941-9575-ed0c67dd4bf1)

### Inserting Into a Table
To create a table, use the `insert into` command by typing

```terminal
insert into [table name] values [values to insert]
```
The values inserted, *must* be entered in the same order as the field columns of the table. 
For example, if a table has the fields `lname`, `fname`. and `age`, inserting must go as follows:

```terminal
insert into [table name] values [lname], [fname], [age]
```

Here is an example in which I insert a record into `students.bin`:

![insert_peter](https://github.com/antborja/antborja/assets/112919376/3deb4772-21b1-43e6-b9f4-128ec3cdbd76)

#### Inserting Values with Spaces
To insert a single value made of multiple words, use quotations to enclose the value:

```terminal
insert into [table name] values "Value 1", "Value 2", "Value 3"
```

Here is an example in which I insert into `employees.bin` with "J. Jonah" as a single value:

![insert_quotes](https://github.com/antborja/antborja/assets/112919376/f44d49ed-bc2a-4018-9565-7260dbe58e0e)

### Selecting Values from a Table
To initiate a select, use the `select` command followed by the fields you wish to select. If you wish to 
select all fields, use the `*` operator.

```terminal
select [field name] from [table name]
select * from [table name]
```

![select fields](https://github.com/antborja/antborja/assets/112919376/d9b1bb6e-69cb-4cdf-90ad-87e43e0734bc)
![select all](https://github.com/antborja/antborja/assets/112919376/e6a56f37-ba0d-46c5-a394-f2cdebdbdfc7)

To apply a condition, begin your condition using the `where` command. Conditions follow 
the general form `field name` `operator` `filter` in which field name is the field name of a table,
operator is a relational or logical operator (explained in [Operators](https://github.com/antborja/antborja/blob/main/README.md#operators)).

```terminal
select * from [table name] where [condition]
```

![select with conditions](https://github.com/antborja/antborja/assets/112919376/62ce5c3d-264a-4952-b784-92efc63af701)

#### Operators
Conditions filter through records using the following operators:
```terminal
=        Must equal right hand side
<        Must be less than right hand side
>        Must be greater than right hand side
<=       Must be less than or equal to right hand side
>=       Must be greater than or equal to right hand side
and      Must follow both left hand and right hand conditions
or       Follows either left hand or right hand conditions
(        Encloses a condition
)        Encloses a condition
```




<h2>SFML Graphing Calculator</h2>
<em>Written in C++ by Anthony Borja</em>
<br>
<img src="https://github.com/antborja/antborja/assets/112919376/04dbc9a0-c8f9-412f-9af7-df2067f8fca0" width="700">

<h3>Features</h3>

<p>User input is displayed in real time as the user types in an equation.</p>
<img src="https://github.com/antborja/antborja/assets/112919376/f3af5dbc-4fa9-4eba-b7ce-caf50cc3c702" width="300">

<p>To graph an equation, user must press TAB to enter the text bar, type a valid equation, then press enter:</p>
<img src="https://github.com/antborja/antborja/assets/112919376/00da0934-c2eb-4a65-918e-ee1b5d6d84f2" width="700">
<em>Some basic algebra</em>

<p>Vertical and horizontal panning:</p>
<img src="https://github.com/antborja/antborja/assets/112919376/d13ff310-9cc2-4ba0-8a62-9b72b3fd9694" width="700">
<img src="https://github.com/antborja/antborja/assets/112919376/f6ee66f7-1b3c-4000-b042-5ea272d88e72" width="700">

<p>Zooming in and out</p>
<img src="https://github.com/antborja/antborja/assets/112919376/1f36db36-be82-41f4-a918-b8528d72b3a5" width="700">

<h3>Some cool graphs...</h3>
<p>Trigonometric Hyperspace Travel!</p>

<img src="https://github.com/antborja/antborja/assets/112919376/5bf036dd-e040-47f0-b5ac-24f571503e28" width="700"> <img src="https://github.com/antborja/antborja/assets/112919376/bab53ad2-af42-4f23-8bd7-8f71257f113d" width="700">

<p>Fourier-type function</p>

<img src="https://github.com/antborja/antborja/assets/112919376/e526187d-04c2-4097-aafa-eed29ae03a04" width="700">



