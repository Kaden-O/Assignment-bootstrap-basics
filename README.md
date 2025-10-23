Bootstrap Basics Assignment 

1. First I started creating the form. I made a div with class="container" to put the form and table inside. I start with form and inside the form I make first the name inputs and labels. I make sure to give the first and last name div
   classe's a col of 6 so they can be side by side. After I make the email and password labels and inputs. I make sure to add the required element so that the user cannot submit the form without completing those sections. Then I make
   the checkbox button for agreeing to terms and then the submit button.

2. Next I made the table. I put the table in a div with class="table-responsive". I made <thead> for table head and <tbody> for table body. Everything in <thead> uses <th> and only the numbers in the <tbody> use <th> for the style
   of the numbers to be bold, everything else in <tbody> uses <td>. I made sure to add table-striped and table-hover as well.

3. Then I created a new div, this time it has a class="container-fluid". I made a responsive image using class="img-fluid" and I also made a circle image using class="rounded-circle". Then I made two buttons, the blue First Button is
   always visible where as the red Second Button will disappear on small screens. I used d-none and d-md-block to make the button disappear.
   
5. After, I made the navbar. I started off by creating this at the top of the html page. I made the <nav> tags and then the <div> tags containing class="container-fluid". Then I made the <a> tag to put the title of the page in the
   logo section of the navbar. Then I made the <div> tags with class="collapse navbar-collapse" and put the <ul> inside of those tags. In the <ul> I made the navbar links to Home, About, and Contact. After I made the navbar collapse
   into a hamburger icon when on small screens. I did this by creating the <button> tags under the <a> tags and above the <div> with class="collapse navbar-collapse". I connected the <button> tag to the same <div> that it is above by
   inserting into the <div> tags id="navbarSupportedContent". Inside the <button> tags I created <span> tags so the three lines icon appears.

6. Finally I went into the CSS and added media queries for the rounded-circle, form, table, and navbar.