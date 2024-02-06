# HTML 

#### Question 1: Are the HTML tags and elements the same thing?

  * Html tags & elements are not same.
  
#### Question 2: What are tags and attributes in HTML?
  
* Tag is define root of elements
* Example : `<p>, <div>, <h1> to <h6>`
* Attribute is define tag of element... Attributes are used to provide information to the tag 
* Example : `<class>, <id>, <name>`

#### Question 3: What are void elements in HTML? With Example.

* Void element used blank space or not show but perform 
* tags are not closed in void element
* Example : `<img>, <br>, <hr>` 

#### Question 4 : What are HTML Entities? With Example.

* Html Entities are some type of string (code) & then show output in symbols
``` 
<p> This is Copyright &#169; </p> 
<p> This is Empty Set &#8709; </p> 
```

#### Question 5: What are different types of lists in HTML? With Example.

1. Order List `<ol>`
2. Unorder List `<ul>`
3. Description List `<dl>, <dt>, <dd>`
   
```
    Gujrati Items
    <ul>
        <li> Gathiya </li>
        <li> Thepla </li>
        <li> Gujrati Thali </li>
    </ul>   
    Panjabi Items
    <ol type="A">
        <li> Butter Roti </li>
        <li> Panner Tikka </li>
        <li> Dal Fry </li>
    </ol> 
```   

#### Question 6: What is the ‘class’ attribute in HTML? With Example.

* 'Class' attributes specifies one or more class names for an element
* 'Class' attribute used in ' .classname ' in style tag
```
<style>
    .box{
        width: 200px;
        height: 200px;
        background-color: red;
    }
</style>

<div class="box">
    <p> This is Some P Tag </p>
</div>
```
* this example class name is 'box'.

#### Question 7: What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements? With Example.

* 'Id' attribute is more specifies for an element.
* 'Id' name used in one time... This is more than specifies of 'class' attribute.
* but 'class' attribute used in one or more names for an element. 

```
<head>
    <style>
        p.box{
        padding: 20px;
        font-size: 20px;
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bold;
        }

        .box1{
            width:100px;
            height:100px;
            background-color: rgb(118, 118, 0);
        }

        .box2{
            width:80px;
            height:80px;
            background-color: blue;
        }

        #box3{
            width: 200px;
            height: 20px;
            color: black;
            font-size: 16px;
            background-color: yellow;
        }
    </style>
</head>

<body>
    <div class="container">
        <p class="box box1"> This is some p tag </p>
        <p class="box box2"> This is some p tag </p>
        <p id="box3"> This is some p tag </p>
    </div>
</body>

```

#### Question 8: What are the various formatting tags in HTML?

* different types of formatting tags are used.
* Underline, italic, bold, sub text, sup text...etc
* Example : `<u>, <i>, <b>, <sub>, <sub>, <em>`

#### Question 9: How is Cell Padding different from Cell Spacing? With Example.

* Cell Padding is space inside cell.
* Cell Spacing is space outside cell & some border outside space in cell spacing..
* Cell Spacing is same as margin.

```
<body>
<table cellspacing="8" cellpadding="4" border="1">
        <tr>
            <td> Hyy </td>
            <td> Hello </td>
        </tr>
        <tr>
            <td> Hyy </td>
            <td> Hello </td>
        </tr>
    </table>
</body>
```

#### Question 10: How can we club two or more rows or columns into a single row or column in an HTML table? With Example. 

* Using "rowspan" & "colspan"
* Two or more row merge then using colspan
* Two or more col merge then using rowspan

```
<body>
    <table>
        <tr>
            <td colspan="2"> Hyy </td>
            <td> Hello </td>
        </tr>
        <tr>
            <td rowspan="2"> Hyy </td>
            <td> Hello </td>
            <td> Hiii </td>
        </tr>
        <tr>
            <td> Hyy </td>
            <td> Hello </td>
        </tr>
    </table>
</body>
```

#### Question 11: What is the difference between a block-level element and an inline element?

* Elements occupying as much space as required are called inline elements.
* Elements that occupy the entire space except where required are called Block elements.


#### Question 12: How to create a Hyperlink in HTML? With Example.

* Hyperlink used anchor tag `<a>`
* Hyperlink used different target
  * target = "_blank"
  * target = "_self"
  * target = "_parent"
  * target = "_top"

```
    <a href="https://www.amazon.in/" target="_blank"> Amazon Website </a>
```

#### Question 13: What is the use of an iframe tag? With Example.

* iframe is used to load another website in a frame of same page.

```
    <iframe src="https://www.amazon.in/" height="100" width="500px"> </iframe>
```

#### Question 14: What is the use of a span tag? Explain with example?

* `<span>` tag is a inline tag
* This tag is used in some styling in tag.

```
<p> This is some <span style="font-weight: bold; color: red;"> p </span> tag </p>
```

#### Question 15: How to insert a picture into a background image of a web page? With Example.

```
<div style="background-image: url(../images/image.jpg); height: 200px; width: 200px;"> </div>
```

#### Question 16: How are active links different from normal links?

```
<a href="https://www.amazon.in/" target="_blank"> Amazon Website </a>
```

* Normal Link : normal link color is blue & show underline.
* Active Link : active link is hover mouse on link then show website name n then click to load website & show website is same page or another new page.


#### Question 17: What are the different tags to separate sections of text?

*Example: `<div>`, `<section>`, `<br>`

* This tags are different b/w one department to another department.
  

#### Question 18: What is SVG?

* SVG means Scalable Vector Graphics.
* Svg file zoom in & zoom out is more cleared... image pixels are not cracked.



#### Question 19: What is difference between HTML and XHTML?

* HTML rules & syntax are flexible.
* XHTML rules are strict & syntax properly follow. XML rules apply.



#### Question 20: What are logical and physical tags in HTML?

* Physical Tags are understand mostly user.
* Logical Tags are understand mostly user & computer (program) both.

* Physical Tags: `<b>`, `<i>`, `<u>`
* Logical Tags: `<strong`, `<em>`, `<strike>`