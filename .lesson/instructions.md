# Tables: Attributes and Style with CSS

## Task 1: Adding Borders

You can add borders to your tables using CSS. You can change the entire table, the table headings and table data in one ruleset like this:

```
  table, th, tr, td {
  
  }

```

Borders have many properties such as ```border-width```, ```border-color``` and ```border-style```.  When you use the ```border``` property, simply list the border-width and border-style like this:

```
  table, th, tr, td {
      border: 2px solid;
  }

```
```solid``` means that your table will have a solid border.  Other border styles include ```dashed``` and ```dotted```.

**Use CSS to add a border to the tables on the page.**

## Task 2: Adding a color to the border lines

To add color, simple add another property after the ```border-style``` like this (if you don't specify a color, the default will be black):

```
  table, th, tr, td {
      border: 2px solid gray;
  }

```

**Change the color of the tables on the page. You can choose your own color.**

## Task 3: Table Padding

You can add space around your content using the ```padding``` property.

**Add some space around the content of your tables like this:**

```
  table, th, tr, td {
      border: 2px solid gray;
      padding: 5px;
  }

```

## Task 4: Border Collapse

You will notice that the table, table heading and table data all have seperate borders.    You can change this so that they all share the same border by using the ```border-collapse``` property. 

**Make a ***new ruleset*** for the ***table only*** and collapse the border like this:**

```
table {
  border-collapse: collapse;
}

```

## Task 6

You can style the ```th```, ```td``` and the entire table seperately. 

**Add a different ```background-color``` and ```text color``` to the ```th``` table headings only like this:**

```
th {
  background-color: gray;
  color: white;
}

```
```color``` changes the text color. ```background-color``` changes the background.


## Task 7

**Challenge!** Change the **color** and background color of the ```<td>``` elements, make them different than the ```<th>``` elements.

## Task 8: Column Span

A ```<td>``` table data element can also be called a column.  You can expand one ```<td>``` element across multiple columns using the ```colspan``` attribute.

Go to ```index.html```. In the first row of Table One, find the ```<th>```  element.

**Add a ```colspan``` attribute  like this:**

```
<th colspan='4'>Highest Grossing Films Domestically (Adjusted for Inflation)</th>
```

```colspan='4'``` means the column in the first row will stretch across four columns.

## Task 9

In the second row of Table One, you will see a column containing the word "FILMS".  Make that column span across two columns underneath.

## Task 10

Go to table two. Make the column in the first row (the one that says Super Bowl Games 2016 - 2021) stretch across the entire table, like we did with the previous table.


Below is reference links for other ways to style tables using CSS:

[CSS Table Borders](https://www.w3schools.com/css/css_table.asp)

[CSS Table Size](https://www.w3schools.com/css/css_table_size.asp)

[CSS Table Align](https://www.w3schools.com/css/css_table_align.asp)

[CSS Table Style](https://www.w3schools.com/css/css_table_style.asp)


# Using Classes with Tables

When you have multiple tables on a page, you can use a class attribute to make them unique.

## Task 11

Find the opening tag for the second table.  Add a class attribute to the opening tag of the second table like this:

```
<table class="two">
```

To modify table two in CSS, the selector should look like this:

```
table.two {
    border: 3px solid blue;
  }
```

To modify the table headings and table data in CSS, create a new selector like this:

```.two th, .two td```


## Task 12

Add a class  attribute to the third table. Study the CSS Reference links and change the border style, color, fonts, and table background colors to make all three tables unique.  
