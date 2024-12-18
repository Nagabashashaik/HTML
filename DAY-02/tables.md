<h1>TABLES IN HTML</h1>
<ul>
  <li>Tables in a webpage plays a major role,tables are useful to arrange the particular data linearly</li>
  <li>Tables in html are created by using the <code>&LTtable></code> element</li>
  <li><code>syntax:- &LTtable>---table---&LT/table></code></li>
  <li>There are 5 major things are there in HTML tables</li>
  <ol type="1">
    <li>CRAETING A TABLE ROWS AND CELLS</li>
    <li>CREATING TABLE HEADERS (VERTICAL & HORIZONTAL)</li>
    <li>MERGING ROWS AND COLS</li>
    <li>TABLE PADDING AND SPACING</li>
    <li>TABLE STYLING</li>
  </ol>
  <li></li>
</ul>


<h1>1.CREATING A TABLE ROWS AND CELLS</h1>
<ul>
  <li>To create a table row we can use the <code>&LTtr></code> tag</li>
  <li>Inside the table row we can create the table cells, that can be done by using the <code>&LTtd></code> tag</li>
  <li>By using the above two tags we can create the entire table in HTML</li>
</ul>
<h4>example:</h4>
<pre>
  &LT!DOCTYPE html>
  &LThtml>
    &LThead>
      &LTtitle>my website&LT/title>
    &LT/head>
    &LTbody>
    &LTtable border="1"><code>---------------------------------------------------------------->table_starting</code>
      &LTtr><code>----------------------------------------->row1_starting</code>
        &LTtd>NAME&LT/td><code>-------------->indicates row1 col1 cell</code>
        &LTtd>BRANCH&LT/td><code>------------>indicates row1 col2 cell</code>
        &LTtd>ID NO&LT/td><code>------------->indicates row1 col3 cell</code>
      &LT/tr><code>---------------------------------------->row1_ending</code>
      &LTtr>
       &LTtd>HRITIK&LT/td>
       &LTtd>CSE&LT/td>
       &LTtd>O220518&LT/td>
      &LT/tr>
      &LTtr>
       &LTtd>NITESH&LT/td>
       &LTtd>ESE&LT/td>
       &LTtd>O220224&LT/td>
      &LT/tr>
      &LTtr>
       &LTtd>KOUSHIK&LT/td>
       &LTtd>EEE&LT/td>
       &LTtd>O220897&LT/td>
      &LT/tr>
    &LT/table><code>---------------------------------------------------------------------------->table_ending</code>
     &LT/body>
  &LT/html>
</pre>

<h4>output:</h4>
  <!DOCTYPE html>
  <html>
    <body>
    <table border="1">
      <tr>
        <td>NAME</td>
        <td>BRANCH</td>
        <td>ID NO</td>
      </tr>
      <tr>
       <td>HRITIK</td>
       <td>CSE</td>
       <td>O220518</td>
      </tr>
      <tr>
       <td>NITESH</td>
       <td>ESE</td>
       <td>O220224</td>
      </tr>
      <tr>
       <td>KOUSHIK</td>
       <td>EEE</td>
       <td>O220897</td>
      </tr>
     </body>
  </html>

<ul>
  <li>In the above example, we have used <code>border</code> . This is a attribute used in table start_tag.</li>
  <li><code>border</code> attribute is used to apply the borders(outlines) for the entire table.</li>
  <li><code>syntax:- &LTtable border="value" >; value= either 0 or 1 (by default it will be 0)</code></li>
</ul>
