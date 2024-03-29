# Exercise 02 tables


Well in this repo I would like to show a few things related to tables, wich are still in use in Mark up languages.

We should use `<table>` label to start table. Inside, each`<tr>` label will instantiate a row, and inside each row we add cells through `<td>` label.

Before that, we can use `<caption>` to add a tittle to our table. Also, instead of `<td>` we can use `<th>` in first cells to add a
header or main cell.

Cells (`<td>`) has attributes, wich are `colspan="number"` to merge cells and `rowspan="number"` to merge rows.

Other interesting attributes are `abbr="value"` for header `<th>` label (accessibility issues for screen readers), and `sumary="text"` to `<table>` label, also for screen readers info.

## Example

Let's see how will look like an html table wich has two colspanned cells as main or header `<th>` **NAME** info, followed by other `<th>`cell for **AGE** info. If table has two rows, we should be in front a three columns table with two colspanned cells in first row for the header **NAME**:

```
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
<table>
```

<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
<table>


In this repo's exercises we have done two Acid smiling faces and a simple calendar with a few css style attributes, wich are those from this two demos:

![](media/calendari.png)                  ![](media/acid-tabla.png)

And this is what I did:

![](media/calendar.png)

![](media/face.png)                       

![](media/face2.png)    
