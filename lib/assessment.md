This file is a **markdown** file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

In responding to some of these questions, you may be asked to write HTML or CSS code. Please do so using the following Markdown formatting.

**index.html**
```HTML
<html>
...
</html>
```

**style.css**
```CSS
ul {
  ...
}
```

Using this format will make it easier for us to grade you, so that we can get everyone their feedback faster. Thanks for your help!

## Question 1
When we say that the web is a service, what does that mean? Explain the interaction in terms of clients and servers.
<!-- your answer starts here -->
It means that the experience of using the web is made possible by the interaction of two parties, a 'client', which makes a requst, and a 'server', which responds to the request. In particular, a client makes an 'HTTP request' (which we will cover soon), and a server responds by sending back some kind of response (usually either HTML/CSS/JS or JSON).
<!-- your answer ends here -->

## Question 2
As mentioned in the lesson, there are two general categories of elements, 'block' elements and 'inline' elements. Please give three examples of each type of element, and explain the difference between the two categories.
<!-- your answer starts here -->
Block elements (nearly) always cause there to be a new line, while inline elements do not.

Block:
* `div`
* `img`
* `p`

Inline:
* `span`
* `a`
* `input`

<!-- your answer ends here -->

## Question 3
Below, write some HTML to create a basic web page. It should have a title in the head and an unordered list (with three items) inside the body.
<!-- your answer starts here -->
**index.html**
```HTML
<!DOCTYPE html>
<html>
<head>
  <title> My Web Page </title>
</head>
<body>
  <ul>
    <li> Item One </li>
    <li> Item Two </li>
    <li> Item Three </li>
  </ul>
</body>
</html>
```
<!-- your answer ends here -->

## Question 4
What are the three ways we can add CSS to an HTML document? Which will we use most often?
<!-- your answer starts here -->
Inline styling (via the `style` attribute), `<style>` tags, and external stylesheets. External stylesheets will be what we use most often.
<!-- your answer ends here -->

## Question 5
What selectors could we write to select each of the following categories of elements?
* All elements that belong to the class `big`
* The element matching ID `contentPane`
* Any elements that belong both to the `important` and `red` classes
* Any `p` elements whose parent elements are `div`s

<!-- your answer starts here -->
Selectors that would work are (respectively)
* `.big`
* `#contentPane`
* `.important.red`
* `div > p`  
<!-- your answer ends here -->

## Question 6
Consider the following HTML and CSS code. What color and font-family values will the div 'specialDiv' have?
**index.html**
```HTML
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="assets/css/main.css">
</head>
  <div class="things">
    <div id="specialDiv" style="font-family: cursive">
      Blah blah blah.
    </div>
  </div>
</html>
```

**main.css**
```CSS
* {
  color: black;
}
div {
  color: blue;
}
#specialDiv {
  color: yellow;
  font-family: sans-serif;  
}
.things {
  font-family: arial;
}
.things div {
  color: red;
  font-size: 16px;
}
```

<!-- your answer starts here -->
Font Family will be `cursive`
Color will be `yellow`
<!-- your answer ends here -->
