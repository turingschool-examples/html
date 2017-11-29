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
      <h1>
        heading content goes here
      </h1>
    </section>    
  </body>
</html>
```

**[back to top](#table-of-contents)**

### Classes and Ids

* Class and Id names should be surrounded by double quotes

**Bad**

```html
<html>
  <head>
    head content goes here
  </head>
  <body>
    <section   class=' section ' id=' section1'>
      section content here
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
    <section class="section" id="section1">
      section content goes here
    </section>    
  </body>
</html>
```

**[back to top](#table-of-contents)**

# </>

