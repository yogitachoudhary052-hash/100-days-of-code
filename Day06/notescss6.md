# CSS Notes

# Types
- Inline: <h1 style="color:red">This is inline css</h1>

- Internal: This is written in the head section inside <style></style> and it is written as :-
h1{
    color:red;
}

- External: This has a seperate css file named as style.css and it is connected to a html file through link as :- 
<link rel="stylesheet" href="style.css">

# color
- Used to set color of foreground (text)

# background-color
- Used to set color of background.

# rgb
- color: rgb(255,0,0);
- color: rgb(0,255,0);

# Hex(Hexadecimal)
- color: #ff0000;
- color: #00ff00;

# Selectors

# Universal selector
- *{} - set to whole html document.

# Element selector
- h1{

} Used for multiple h1 in document.

# ID selector
- #myld{

} Used for unique id, name.

# Class selector
- .myclass{}
- Used for the class whole class in which we want same style

# text align
- left/right/center

# text decoration
- underline/overline/line-through

# font wieght
- normal/bold/bolder/lighter
- 100-900

# font-family
- It changes the style of fonts

# Units in CSS
- pixels(px)
- 96px=1inch
- font-size: 2px

# line-hieght
- the gap between the texts of two lines there we use line hieght

# text-transform
- uppercase/lowercase/capitalize/none

# box model in CSS
- height
- width
- margin
- padding

# border
- border-width
- border-style: solid/dotted/dashed
- border-color:black;
- border: 2px solid black;
the above is border width, style and color
- border-radius:20px
used to round the border

# padding
- the space between content and border
 
# margin 
- the space betwwen one box and another box

# display property
- display: inline/block/inline-block/none

# visibilty
- hidden
- but it has its space reserved

# alpha channel 
- RGBA
- deciddes opacity (0 to 1)
- if it is zero then the colour is not visible
- if it is set to one then the colour is visible as darker as possible
- rgba{255, 2, 0, 0.75}

# Units in CSS
- Relative
- % 
- em
- rem

# position
- position: static/relative/absolute/fixed

# background image
- background-image: url("path of the folder");

# background-size
- background-size: cover/contain/auto

# flexbox
- flexible box layout
- it is a one dimensional layout method for arranging items in a row or columns.

# flexbox direction
- it sets how flex items are placed in the flex container, along which axis and direction.
- flex-direction: row/row-reverse/column/column-reserve

# Flex properties

- justify-content:space- around/space-between/space-evenly/start/center/end;

- flex-wrap: nowrap/wrap/wrap-reverse

- align-items: alignment alog the cross axis

- align- content: alignment of space between & around the content along cross- axis

- align-self: alignment  of individual along the cross axis

- flex-grow: how much a flex item will grow relative to the rest of the flex items if space is available

- flex-shrink: how much a flex will shrnk relative to the rest of the space is available.

 
