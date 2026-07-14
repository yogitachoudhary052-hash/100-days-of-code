# 100-days-of-code
My 100-day journey to becoming a Full Stack Developer.
# DAY 02

# What is HTML?
- Hyper text markup language 
- It is used to structure the content of a webpage.
- HTML is structure of house like a box walls, doors, windows.
- CSS is paint, interior, decoration of house 
- JavaScript is electricity, fans, automatic doors opening.

# What is <!DOCTYPE html>?
- It is the edition in which the code is bieng written and this document uses HTML5.

# HTML
- Container for whole website. All the code is written here.

# <head>
- It includes:
Page title,
Character encoding,
Links to CSS files,
Meta information,
Favicon

# <body>
Everything which is visible to  a user is inside the body.

# HTML document structure

<!DOCTYPE html>
<html>
<head>
<title>

</title>
</head>
<body>
HERE THE CODE IS WRITTEN.
THIS IS VISIBLE TO THE USER. 
</body>
</html>

# Headings
<h1> Highest </h1>
<h2>  </h2>
<h3>  </h3>
<h4>  </h4>
<h5>  </h5>
<h6> Lowest </h6>

# Paragraph
- used for normal text. 
- <p> Hello world! </p>

# Break
-<p> Hello <br> world! </p>
- used to break and move the next word to next line 

# Horizontal
- This creates a horizontal line across the page.
- <hr>

# Comments
- It is for developers whatever is written in comments is not visible on the website.
- <!-- This is a comment -->

# Lists
- Unordered List
- <ul>
<li> HTML </li>
<li> CSS </li>
<li> JavaScript </li>
</ul>

- Ordered List
<ol>
<li> HTML </li>
<li> CSS </li>
<li> JavaScript </li>
</ol>

# Links
<a href=" ">
Google
</a>

<a>= Anchor tag
href= The destination URL

# Images
- <img src=" " alt=" ">
- src tells browser where the image is.
- alt provides alternative text if the image can't be displayed.


# Attributes
- src
- alt


# DAY 03

# What is a form?
- A form collects info from the user.
- Examples:

- Login Page
- Registration Page
- Contact Form
- Booking Form
- Feedback Form

# <label>
- Name _________
- The text name is label.

# <input>

- This is the most important form element.

- input types:

text
email
password
number
date
tel
file
radio
checkbox

# <textarea>
- used when users need to type multiple lines.

- Eg:
- feedback, address, Description

# <select>

- Used for dropdown menus.
- Choose City

Vadodara

Ahmedabad

Surat

# <option>
- each item inside a dropdown is an option. 

# <button>
- it is clickable

# placeholder

- Example:

Enter your name

- It disappears when the user starts typing.

# required
- HTML can stop form submission if required field is empty.

# name
- attribute

# value
- use to provide a default value or the value sent for certain inputs like radio buttons and checkboxes.

# Day 04

# Table
- Used to display data in rows and columns
- <table></table>

# tr table row
- Every horizontal line in a table is a row.

# th table heading 
- It is used for column names.
- <th> </th>
- The headings are bold and centered by default.

# td table data
- It stores actual information.

# rowspan
| Teacher | Student |
| ------- | ------- |
| Meena   | Rahul   |
|         | Priya   |
- <td rowspan="2">Meena</td>
- Vertical merge


# colspan
| Student Details |     |
| --------------- | --- |
| Name            | Age |
- <th colspan="2">Student Details</th>
- Horizontal merge

# semantic HTML

## Header
- Top part of website
- Usually contains

Logo

Title

Navigation

## Navigation menu

Home

About

Contact

Services

## <main>

-Contains

Main content

There should usually be only one <main> element per page.

## <section>
- Used to divide the page into meaningful sections.

Example

About Me

Projects

Skills

Contact

Each can be its own <section>.

## <article>

Independent content.

Examples

News article
Blog post
Product review

It should make sense on its own.

## <aside>

<aside>

Extra information.

Example

Latest Posts

Advertisements

Related Articles

Usually shown beside the main content.

## footer
<footer>

Bottom of website.

Contains

Copyright

Contact

Social Links

Example: 

© 2026 Yogita
GitHub
LinkedIn