# div element

1. If you just write an empty div, you won't see anything on the page, because it has no height.
   
   By empty I mean having no child elements.
   
   There are two ways to give a div a height: \n
   a) By giving it height directly using CSS.
   b) By giving it at least one child element that should have a height.
   
   Note: If the child element also doesn't have any height, the parent div will still be invisible.
   Note: In mode a, the height of the div cannot be changed by other elements. Here you can only change it by directly giving it CSS height.
         In mode b, the height of the div element will change according the child element's height.
