# < Turing HTML Style Guide >

*A primarily decent approach to HTML*

## Style Guides

### other style guides

  - [CSS](https://github.com/turingschool-examples/css)
  - [JavaScript](https://github.com/turingschool-examples/javascript)

## Table of Contents

  - [Formatting](#formatting)
  - [Whitespace](#whitespace)
  - [Classes and Ids](#classes-and-ids)
  - [Keeping Elements on One Line](#keeping-elements-on-one-line)

### Formatting

* Use soft tabs (2 spaces) for indentation
* Each nested element should be indented once(including the head and body tags)

**Bad**

```html
<html>
<head>
head content goes here
</head>
<body>
body content goes here
<section>
    <h1>
    heading content goes here
    </h1>
</section>
</body>
</html>
```

**Good**

```html
<html>
  <head>
    head content goes here
  </head>
  <body>
    body content goes here
    <section>
      <h1>
        heading content goes here
      </h1>
    </section>
  </body>
</html>
```

**[back to top](#table-of-contents)**

### Whitespace

* There should be no empty lines in an html file

**Bad**

```html
<html>
  <head>


    head content goes here
  </head>


  <body>
    body content goes here

    <section>
      <h1>


        heading content goes here
      </h1>

    </section>
  </body>
</html>

```

**Good**

```html
<html>
  <head>
    head content goes here
  </head>
  <body>
    body content goes here
    <section>
      <h1>heading content goes here</h1>
    </section>    
  </body>
</html>
```

**[back to top](#table-of-contents)**

### Classes and Ids

* Class and Id names should be surrounded by double quotes

**Bad**

```html
<section   class=' section ' id=' section1'>
  section content here
</section>
```

**Good**

```html
<section class="section" id="section1">
  section content goes here
</section>    
```

**[back to top](#table-of-contents)**

### Keeping Elements on One Line

* Elements that are 80 characters or less including their content can be kept on one line.

```html
<section>
  This element is longer than 80 characters in length and should be broken
  onto multiple lines.
</section>
```

* **Pro Tip:** The 'Column' number in the bottom left corner of Sublime will tell you how many characters in the cursor is at any given time.

**[back to top](#table-of-contents)**

# </>
