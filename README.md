# project0
For project0, I chose to create a website for my pets. I briefly described three of my pets, each with their own .html page. 

The index.html file serves as the homepage. As seen in index.scss, I made use of SCSS variables such as $basic: black as this color was routinely used throughout my code. I also exhibited use of SCSS inheritance with %equal-heights that included flexbox, using this on every page of the website by using @extend. Next is a table that displays use of SCSS nesting, CSS selectors, and CSS properties. To set up the layout of the page, I included an #id selector known as #homepage. This also displays use of SCSS nesting, forms, and numerous CSS selectors and properties. 

champ.html is the second page for my dog, Champ. Here I made use of the class "message" rather than the id selector #homepage to extend %equal-heights and set up the layout of my page. I made use of the bootstrap component "col-3" in the class "row" to lay out my images nicely. I also display an unordered list on this page. 

eevee.html is the third page for my cat, Eevee. This is similar to champ.html, but I made use of the grid model to lay out the images rather than the "row" class. With grid, I can specify my own properties more specifically. Most notably, the grid-template-columns command lets me size the images however I would like. I additionally use an ordered list for this page.

Lastly, skip.html is for my past dog, Skip. It shares similar properties to eevee.html aside from having an unordered list, different images, and different colors. I also made use of the mobile-responsive @media query, showing some style changes with the buttons as the screen size shrinks below 700px. 