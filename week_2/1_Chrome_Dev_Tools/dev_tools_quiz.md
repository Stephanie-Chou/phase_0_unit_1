#### Include an inline screenshot of your codeschool's points from the profile page:

<!-- Modify the Markdown to include your answers. Don't delete the questions! -->

##QUIZ
* Explain which tabs support the following actions and how.
  * Realtime editing of HTML and CSS 
  Elements: shows you the HTML and CSS and allows you to edit the attributes by double clicking and typing.


  * Javascript Debugging
  Sources: This is a similar editor interface as Elements except this is specific to Javascript

  * Performance Optimization 
  Network: tells you what is loading and for how long. Allows you to sort by loadtime and therefore what to modify. For example, if an image is taking too long to load then you can compress it or change its file type.

* What's the quick key for your OS to spawn the Dev Tools inspector?
cmd+opt+I

* Go to http://www.postmachina.com/ and analyze and tweak this nicely designed page.
  * What is the current background color for the page?  (Surprisingly, it's not just black!)
  #0b0f11
  * Tweak the background color to white.
  * Tweak the height of the side bar that contains the logo.  Shrink it down to 85px.
  * Roll over the navigation links.  When you hover over them, they dissapear.  Let's change the hover color to black instead.
  * Now take a screenshot of your new (and maybe not so improved) design.  It should match this screenshot: http://postimg.org/image/5ak1jkpl5/
  * Upload your own image to the imgs directory in the `1_Chrome_Dev_Tools` directory.  It should match the image above. The last nav link in the image above is black because the mouse was hovering there when the screenshot was taken. Do the same, and don't take a screenshot of your whole desktop, just the browser window. (This is part of the challenge.)

* For the postmachina website, why can't you tweak the color of the text "The most important things are not things"?  Please explain.

* Go to www.ticketswizard.com and analyze the page.  
  * What is the largest image on the website? 
  * Explain how you would find out this information, and list the URL of offending image here and how big it is.
  Inspect the page element and click on 'Network'. Next, filter the results using the filter button. The Look at the column 'Time'. This column will tell you which image took the longest to load.
  http://www.ticketswizard.com/Images/Catalog/ad724279-bc48-4560-8b68-af9e87202afa_Large.png
  291KB

* Test the www.ticketswizard.com website with google's [PageSpeed Insights](http://www.ticketswizard.com/).  (You can also download the chrome plugin).  What is the easiest thing to change to optimize the website?  How many kilobytes of data can be eliminated?


The Easiest thing to edit would be the images. They can be optimized by compression and could save 885.9 KiB