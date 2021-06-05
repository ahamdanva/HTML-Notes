# tables in html

The ```<table>``` tag defines an HTML table.
```
Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.

By default, the text in <th> elements are bold and centered.

By default, the text in <td> elements are regular and left-aligned

```

# list in html 

basically there are two type of list in html.

1.ordered list :-
```
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.It start with counting
---------------------
 <ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol> 
```

2. unordered list:-
```
An unordered list starts with the <ul> tag. Each list item starts with the <li>

 <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul> 
```

### ```<li> is used for listing items```


# Images in html
```
<img> tag is used to embed an image in a web page.

   *src - Specifies the path to the image
   *alt - Specifies an alternate text for the image


    <img src="url" alt="alternatetext"> 
```
**in src you have to link or put the proper path of image.(image extention is very important)**



# div/span tag (important)

```The <div> element is often used as a container for other HTML elements.```
```
<div style="background-color:black">
  <h2>London</h2>
</div>
```

```The <span> element is an inline container used to mark up a part of a text, or a part of a document.```

```
<p>
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Enim obcaecati dicta ipsa? Eum velit blanditiis
    
     ***<span style="font-weight: 600;">incidunt</span> ***
    
    reiciendis, corporis mollitia molestias culpa?
</p>
```


# Forms in HTML

### steps to create basic html form.

* form tag.
* label tag.
* input tag and input tag
* button

## There are two type of methods to send data using Html form.

1. Get Method.
    * Appends the form data to the URL, in name/value pairs.
    * NEVER use GET to send sensitive data!
2. Post Method.
    * Appends the form data inside the body of the HTTP request .
    * OST has no size limitations, and can be used to send large amounts of data.
    * Form submissions with POST cannot be bookmarked.