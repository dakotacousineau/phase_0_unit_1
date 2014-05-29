#### Include an inline screenshot of your codeschool's points from the profile page:

<!-- Modify the Markdown to include your answers. Don't delete the questions! -->

##QUIZ
* Explain which tabs support the following actions and how.
  * Realtime editing of HTML and CSS 
  Elements. It shows the HTML code on the left and the CSS code on the right allowing you to change and then reflects that change in the normal part of the browser. 
  * Javascript Debugging
  The sources tab allows for viewing of errors or see where a bottle neck happens. it shows all of the code and where it is going to. 
  * Performance Optimization 
  the network tab allows for performance optimization because it shows when things load and how long they took to load. it also shows the file size of the imbedded objects like images or videos. you can optimize by having the page load documents in the correct order that it is going to need them in. 

* What's the quick key for your OS to spawn the Dev Tools inspector?
Ctrl + Shift + I

* Go to http://www.postmachina.com/ and analyze and tweak this nicely designed page.
  * What is the current background color for the page?  (Surprisingly, it's not just black!)
  0b0f11
  * Tweak the background color to white.
  * Tweak the height of the side bar that contains the logo.  Shrink it down to 85px.
  * Roll over the navigation links.  When you hover over them, they dissapear.  Let's change the hover color to black instead.
  * Now take a screenshot of your new (and maybe not so improved) design.  It should match this screenshot: http://postimg.org/image/5ak1jkpl5/
  * Upload your own image to the imgs directory in the `1_Chrome_Dev_Tools` directory.  It should match the image above. The last nav link in the image above is black because the mouse was hovering there when the screenshot was taken. Do the same, and don't take a screenshot of your whole desktop, just the browser window. (This is part of the challenge.)

* For the postmachina website, why can't you tweak the color of the text "The most important things are not things"?  Please explain.
You can't edit that part because it is part of the image and not text. if you want to edit it you have to change the image file itself in photoshop or some similar program then reupload the image. 

* Go to www.ticketswizard.com and analyze the page.  
  * What is the largest image on the website? 

  * Explain how you would find out this information, and list the URL of offending image here and how big it is.
right click inspect element. click on the network tab then sort by size. look down the list for largest image under type. image is http://ds.serving-sys.com/BurstingRes//Site-2343/Type-0/03f345f1-f156-4242-84d3-216d409d976d.jpg

* Test the www.ticketswizard.com website with google's [PageSpeed Insights](http://www.ticketswizard.com/).  (You can also download the chrome plugin).  What is the easiest thing to change to optimize the website?  How many kilobytes of data can be eliminated? 
Minimize Request Size. There are multiple requests that could be optimized ranging from 1.5 KiB to 7.3 Kib