# div element

1. If you just write an empty div, you won't see anything on the page, because it has no height.
   
   By empty I mean having no child elements.
   
   There are two ways to give div a height: <br>
   a) By giving it height directly using CSS. <br>
   b) By giving it at least one child element that should have a height.
   
   Note: If the child element also doesn't have any height, the parent div will still be invisible.<br>
   Note: In mode a, the height of the div cannot be changed by other elements. Here you can only change it by directly giving it CSS height.
         In mode b, the height of the div element will change according the child element's height. <br>
   Note: At least one inner element should have a height so that the parent element be visible.
   
2. The parent div and the child div has a height (none of the elements have margin or padding). Here 3 modes may happen: <br>
   a) The parent div's height is more than the child's height.<br>
   b) The parent div's height is equal to the child's height.<br>
   c) The parent div's height is less than the child's height.
   
