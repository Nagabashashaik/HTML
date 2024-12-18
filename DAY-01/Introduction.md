<h1>What is HTML ?</h1>
<ul>
<li>HTML stands for <b>"Hyper Text Markup Language"</b></li>
<li>HTML is the standard markup language for creating Web pages</li>
<li>Here markup language means,The language which uses the normal text as tags and elements to define the structure and format of the particular document</li>
<li>HTML describes the structure of a Web page</li>
<li>Webpage is a single docuement, that contains information and content and it is a part of a website.
<li>HTML consists of a series of elements</li>
<li>HTML elements tells the browser how to display the content</li>
<li>HTML is a not a case-sensitive</li>
</ul>

<h1>HISTORY OF HTML</h1>
<ul>
<li>1989	Tim Berners-Lee invented www</li>
<li>1991	Tim Berners-Lee invented HTML</li>
<li>1993	Dave Raggett drafted HTML+ </li>
<li>1995	HTML Working Group defined HTML 2.0
<li>1997	W3C Recommendation: HTML 3.2</li>
<li>1999	W3C Recommendation: HTML 4.01</li>
<li>2000	W3C Recommendation: XHTML 1.0</li>
<li>2008	WHATWG HTML5 First Public Draft</li>
<li>2012	WHATWG HTML5 Living Standard</li>
<li>2014	W3C Recommendation: HTML5</li>
<li>2016	W3C Candidate Recommendation: HTML 5.1</li>
<li>2017	W3C Recommendation: HTML5.1 2nd Edition</li>
<li>2017	W3C Recommendation: HTML5.2</li>
</ul>

<h1>STRUCTURE OF A HTML DOCUMENT</h1>
<pre>
 &LT!DOCTYPE html>
 &LThtml>
    &LThead>
       &LTtitle>my website &LT/title>
    &LT/head>
    &LTbody>
    &LTh1> This is a Heading &LT/h1>
    &LTp> This is a paragraph &LT/p>
    &LT/body>
  &LT/html>
</pre>

<ul>
<li>The <code>&LT!DOCTYPE html></code> declaration defines that this document is an HTML5 document</li>
<li>The <code>&LThtml></code> element is the root element of an HTML page</li>
<li>The<code>&LThead></code> element contains meta information about the HTML page</li>
<li>The <code>&LTtitle></code> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)</li>
<li>The<code>&LTbody></code> element defines the document's body, and is a container for all the visible contents, such as headings,paragraphs, images, hyperlinks, tables, lists, etc.</li>
<li>The <code>&LTh1></code> element defines a large heading</li>
<li>The <code>&LTp></code> element defines a paragraph</li>
</ul>


<h1>WHAT IS AN ELEMENT</h1>
<ul>
 <li>An Element is a combination of start_tag, end_tag along with some content between them is called an <b>"ELEMENT"</b></li>
 <li><code>syntax:- &LTstart_tag>--content--&LTend_tag></code></li></li>
 <li>HTML elements tells the browser how to display the content</li>
 <li>we can add the colors to the headings by using the CSS or <code>style</code> attribute, This can be discussed later</li>
 <li>There are some elements are there which doesn't have end_tag and content,Then that type of elements is called as 
 <b>"EMPTY ELEMENTS"</b></li>
 <li>EX:-  <code>&LTimg></code>, <code>&LThr></code>, <code>&LTbr></code>, <code>&LTbase></code>......</li>
</ul>

<h1>HEADINGS IN HTML</h1>
<ul>
	<li>Generally, Every webpage will contain headings,So to write headings in a document HTML provides a six-levels of headings</li>
	<li>Each level is specified with different sizes</li>
	<li>Here are the syntaxes of the following headings in a HTML</li>
	<li><code>&LTh1>--heading_name--&LT/h1></code></li>
    <li><code>&LTh2>--heading_name--&LT/h2></code></li>
	<li><code>&LTh3>--heading_name--&LT/h3></code></li>
    <li><code>&LTh4>--heading_name--&LT/h4></code></li>
	<li><code>&LTh5>--heading_name--&LT/h5></code></li>
	<li><code>&LTh6>--heading_name--&LT/h6></code></li>
</ul>
<pre>
 &LT!DOCTYPE html>
 &LThtml>
    &LThead>
       &LTtitle>my website &LT/title
    &LT/head>
    &LTbody>
    	&LTh1> This is a Heading-1 &LT/h1>
	&LTh2> This is a Heading-2 &LT/h2>
    	&LTh3> This is a Heading-3 &LT/h3>
	&LTh4> This is a Heading-4 &LT/h4>
    	&LTh5> This is a Heading-5 &LT/h5>
    	&LTh6> This is a Heading-6 &LT/h6>
    &LT/body>
 &LT/html>
</pre>
<h4>output:</h4>
<pre>
	<h1>This is a Heading-1</h1>
	<h2>This is a Heading-2</h2>
	<h3>This is a Heading-3</h3>
	<h4>This is a Heading-4</h4>
	<h5>This is a Heading-5</h5>
	<h6>This is a Heading-6</h6>
</pre>

<h1>PARAGRAPHS IN HTML</h1>
<ul>
	<li>HTML have the feature to write the paragraph in a webpage</li>
	<li>This can be done by the following syntax:</li>
 	<li><code>&ltp>------paragraph-------&LT/p></code></li>
	<li>we can also add the color to the paragraph by using the css or <code>style</code> attribute.</li>
	<li>we can write the no.of paragraphs in a webpage by using the above syntax</li>
</ul>
<h4>example:</h4>
<pre>
 &LT!DOCTYPE html>
 &LThtml>
    &LThead>
       &LTtitle>my website &LT/title
    &LT/head>
    &LTbody>
    &LTh1>This is a Heading</h1>
	&LTp>This is a paragraph</p>
    &LT/body>
 &LT/html>
</pre>

<h4>output:</h4>
<pre>
	<h1>THis is a Heading </h1>
	<p>This is a paragraph</p>
</pre>







 
