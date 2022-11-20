# HTML REVISION
Here we will get everything about HTML

<h1>HTML</h1>
<h2>Introduction</h2>
<h3> HTML is a makup language commonly used to create Web pages.HTML is developed and maintained by <ins>World Wide Web consortium(W3C)</ins> .</h3>
<ul>
<h3><li> <ins>Markup Language :</ins> A markup language provides a way to describe the structure of text and graphics on a Web page. HTML is derived from a general markup language called Standard Generalized Markup Language (SGML) , which is an International Organization for Standardization(ISO) technology that defines markup languages.</li></h3>

<h3><li> <ins>Hyper Text :</ins> The term Hyper signifies the navigation from one location to another in a non-linear fashion.In other words , clicking a hypertext on a Web page takes us to the relevant page on the content,  i.e. the structure and the layout of a Web page with the hwlp of <ins>elements</ins> and <ins>attributes</ins>.</li></h3>

<ul>
<h3><li>HTML 1.0→ Released in 1992. Provides the idea of seperation between the logical structure and presentational elements in a Web Page. </li></h3> 
<h3><li>HTML 2.0→ Released in 1995. Updated version of HTML 1.0 . It introduced new features such as file uploading through a form, tables and client side image maps. </li></h3> 

<h3><li>HTML 3→ Introduced in 1996. It includes the addition of FIG,LISTS, LINK and NOTE elements. It provides the support   Updated version of HTML 1.0 . It introduced new features such as file uploading through a form, tables and client side image maps. </li></h3> 
<ul>
<h3><li>HTML 3.2 → It was introduced in early 1997 . It was released with the Character Data(CDATA) attributes and Document Type Declaration(DTD) to define the structure of an HTML Document. It has also omitted some features of HTML 3.1 , such as math formulas, and the BLINK and MARQUEE elements. 
</ul>
<h3><li>HTML 4→ Introduced in late 1997. It refers to a version that has introduced new elements for style sheets, scripts, frames, embedded objects, complex tables and forms. Apart from this it has provided improved accessibility features, such as accessing a form. </li></h3> 
<ul>
<h3><li>HTML 4.01 → It was introduced in late 1999 . This version has added the id attribute for all elements and has expanded the OBJECT element to include Java applets or any kind of external file in a Web page. It has also included the APPLET, EMBED, , and IMG elements and the feature of event capturing . </li></h3> 
</ul>
<h3><li>HTML 5→ Refers to the latest version of HTML , which was released in October 2009. HTML5 introduces a number of new elements and attributes such as AUDIO, VIDEO, and contentEditable , which allows us to create more interactive Web applications and websites.</li></h3>

</ul>
<h1>FUNDAMENTALS OF HTML</h1>
 
  <h3><li><ins>HTML TAGs</ins>: HTML is written in form of TAGs , which are pair of angle brackets(< and >) and some text placed between these angle brackets. The text present between a pair of angle brackets defines an HTML elements. </center></h3>
 
<h3><li><ins>HTML Elements</ins> : Elements are building blocks of an HTML document. The browser interprets an HTML document on the basis of the element types that are added in the document. As a result, an HTML document is displayed with all the properties specified by the elements embedded in it. </li></h3>
<h3> <center>The Structure of HTML ELEMENT : 1)An Opening/Starting TAG , 2) A Closing / Ending TAG, and 3) The content of the element enclosed between opening and closing TAG. Properties of Html Elements : 1)Attributes and 2) Content. </center></h3>
 
 ```Syntax
 
 <p> This is my first paragraph. </p>
 
 <p>→ It is the Opening TAG.
  
 </p>→It is the closing TAG.
 
 This is my first paragraph →The content of the element enclosed between opening and closing TAG.
 
 ```
 <h3><li><ins>ATTRIBUTES of ELEMENTS</ins>: The Attributes of an HTML element are placed within the opening tag(after the element's name)  . Most of the HTML attributes are name-value pairs, seperated by '=' sign. However , some attributes such as <i>ismap</i> attribute of the <i> img </i> element is written without specifying a value for it.Attribute values should be enclosed within either single or double quotes.</center></h3>
 
  ```Syntax
 Example :
 
 <p id = 'example' , lang="en"> This is an example of HTML </p>
 
 Here,
 
 Attributes: id , lang
 
 Value of Attributes : example , en
 
 ```
 
</ul>

<h1> Categories of HTML Elements </h1>
<ul>
<h3>HTML elements are predefined , which means we cannot create our own tags and must use these predefined tags only. HTML elements are categorized into the following types: </h3> 
 <ul>
 <h3><li>Root </li></h3> 
  <h3><li>Metadata </li></h3> 
  <h3><li>Section</li></h3> 
  <h3><li>Heading</li></h3> 
  <h3><li>Flow</li></h3> 
  <h3><li>Phrasing</li></h3> 
  <h3><li>Embedded</li></h3> 
  <h3><li>Interactive</li></h3>
 </ul>
</ul>

<h1>   Begining of HTML Document [Root Elements]</h1>

```Syntax

1. The <!DOCTYPE> ELEMENT 

```

<ul>
<h3> The !DOCTYPE element is the first element is the HTML document, which specifies the Document Type Definition (DTD) used by the document. A DTD is a seperate file containing formal definition of grammar, such as supported elements and attributes used in markup language. The browser checks the code of the document against the rules in the !DOCTYPE declaration. The !DOCTYPE doesnot have a closing tag. </h3>

```Syntax
 Example :
 
<!DOCTYPE html>
 
 ```

</ul> 
 
