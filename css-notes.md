# Day 5 - Designing webpages with CSS

### What is CSS?
CSS allows you to create rules that specify how the content of an element (from the HTML) should **appear**.

### How CSS works?
Thinking ***INSIDE*** the box. The key to understand how CSS work is to imagine that there is an invisible box around every HTML element. Each box are those commands that we covered in HTML5 (ie ```body``` or ```header```).

These boxes you canthen apply different style elements such as:
- typeface
- size
- color
- italics, bold, upper/lowercase



### Some how-to's with CSS

```
p {
    font-family: Arial;}
```


The syntax in CSS is a bit different, because it needs to connect to the HTML code, using a *selector* and a *declaration*.
- selector - indicates which HTML element to apply the rules to. In this example the selector is: ```p``` 
    - each selector needs to then start with a curly bracket : {}
- declaration - indciates how the elements should be styled, which then have a property and a value. In this example the declaration is: ```font-family: Arial```. 
    - each declaration needs to end with a semicolon
- Properties - font-family is the property (which style element you want)
- values - arial is the option amongst the property that you are selection
- the ***FURTHEST*** command will take precedence. ie if you have a list of CSS and two select the same HTML element, the one deeper on the page will override the one at the top

### Some other commands:
- in the ```<head>``` you link to the CSS file. an example would be:
```
<head>
    <title> using external CSS</title>
    <link href="css/styles.css" type="text/css" rel="stylesheet" />
</head>
```

    - href - this is how you link to the right CSS file
    - type specifies the type of document being linked to
    - rel specifies the relationship between the HTML page and the file it is being linked to
    - you can also internally do the CSS code within the ```<head>```

### Color
- see page 247
- color helps bring your site to life and also helps convey the mood and evokes reactions
- there are three ways to specify colors in CSS: RGB, hex codes, and color names. 
- color pickers can help you choose a good color