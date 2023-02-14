The z-index
It defines the order of overlapping/stack order elements. Elements with a higher index will be placed on top of elements with a lower index. It only works on positioned elements or flex items ie: 
   elements with a position value eg. Position: absolute, position:relative
   Or
   Elements which have their display set to flex.


   //number2
Selectors in css
Selectors are the patterns used to select elements that are to be styled. Eg:
•	class selectors- by class name
•	id selectors- by id name
•	element selectors- by tag name
•	attribute selectors- select by attribute. selectors are surrounded by square brackets.
•	pseudo-class selectors- select by pseudo class. Commonly combined w element selectors
                          eg- :: after- adds content after element
                              :: checked- all elements that are checked
•	global selectors-uses an asterisk (*). selects all elements





    //number3
VH/VW in CSS
The viewport in css is the visible area on the browser page. Setting an element to 100vh means it will occupy the full height of the browser.
the value of 1vw is the same as 1% of the full view width









    //number4
Inline-block, inline, block
inline- elements dont start on new line and only occupies required width.you cant set width or height.
eg the <span>, <br>
inline- block-  allows us to set width and height.
diff w block is that it doesnt add a br after the element.
eg <button>, <input>
common use for this is to display list items horizontally eg navlinks.
Block- Elements begin on a new line . Takes up full width.
eg <div> <p>

    //number5
Pseudo-classes
Used to define a special state of an element
  eg for links.... 
     a:link - 
     a:visited
     a:hover
     a:active
They can be combined w html classes.
:first-child- matches a specified element in the 1st child of another
.lang- helps you define diff rules for diff languages

    //number6
Specifying units in css
The most commonly used unit is the pixels.
using pixels- they are 1/96th of an inch which makes it a dot in the comp.

Ems are a relative unit based on the calculated font size. It is like a ratio compared w other units* need  practical clarification on this

Rem unit (Rootem) it is works like em except it ignores any inherited font sizes(unlike ems)


    //number7
border box vs content box
content box- content inside of element will have the same as the element.Width and height can be calculated based on its content only. Any padding or border added to the element will increase the overall size of the element.

border box- the content dimension has to subtract the border and padding from the element's dimension.
Even when padding and margin is added, the width of the container remains the same
   * {
  box-sizing: border-box;
}
.my-element {
  box-sizing: content-box;
}



    //number8
Opacity
specifies transparency of an element
takes values btwn 0.0 and 1.0 where 1 is not transparent at all


    //number9
Centering a div inside another div
display flex for parent element
justify content and align items center


    //number10
Diff btwn relative and absolute in css
relative- positioning an element according to where it would usually be in the regular ui page.
absolute- takes the doc out of the doc flow. when position:absolute is used on an element, it is positioned absolutely w reference to the closest parent that has a position:relative value. 