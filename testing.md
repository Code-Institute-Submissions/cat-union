# Testing

 * return to [readme](README.md)

 ---

### Validator testing


* W3C Jigsaw CSS Test:

    - Copied and pasted all code from style.css 
    - Made changes to an error.
    - Pasted edited code to verify that that part of the CSS had passed this time.
    - Repeated steps 1-3 until all the errors in my code had passed. 


* Visited W3C HTML Validator:

    - Copied and pasted all code from index.html 
    - Made changes to an error.
    - Pasted edited code to verify that that part of the HTML had passed this time.
    - Repeated steps 1-3 until all the errors in my code had passed. 


* Visited W3C HTML Validator:

    - Copied and pasted all code from what-we-do.html 
    - Made changes to an error.
    - Pasted edited code to verify that that part of the HTML had passed this time.
    - Repeated steps 1-3 until all the errors in my code had passed. 

* Visited W3C HTML Validator:

    - Copied and pasted all code from support-us.html 
    - Made changes to an error.
    - Pasted edited code to verify that that part of the HTML had passed this time.
    - Repeated steps 1-3 until all the errors in my code had passed. 

* Visited W3C HTML Validator:

    - Copied and pasted all code from pet-advice.html 
    - Made changes to an error.
    - Pasted edited code to verify that that part of the HTML had passed this time.
    - Repeated steps 1-3 until all the errors in my code had passed. 

### Mobile friendly

* Visited mobile friendly test on google [search] (https://search.google.com/test/mobile-friendly)

    - Pasted the github URL for Cat Union-support-us.
    - Tested the website.
    - Test came back saying Page is mobile friendly.
    - Repeated 1-3 for all website pages.
    - Confirmed mobile friendly for three other pages.
    - Test passed

* Smallest mobile view test:
    - Asked a friend with an iphone 5s to test website on mobile browser.
    - Received feedback that there was padding on the right of the support-us-page.
    - Solved by adding 100% to the width of the coverletter element on the form. 
    - I asked friend to retest the website.
    - Confirmed the padding issue was, ‘resolved’.
    - Test passed

* What we do page not working as intended on mobile horizontal view.

    - Edited media queries to include vertical phone screen sizes
    - Changed the position of the upper/middle/lower statements
    - Tested on all screen sizes in vertical and horizontal view
    - Working as intended
    - Test

### Navigation

* Navbar
    - Visited the navigation bar on the first page 
    - Ensured that each link led to the correct location on every page
    - Repeated steps 1 and 2 on mobile and tablet.

* Volunteer
    - Information covered the Navbar
    - Had a z-index set to 1 so removed it
    - Fixed

### Contact Form:

* Volunteer Form
    - Visited the volunteer application section of the website.
    - Filled in the full name section but left the Email blank
    - Attempted to submit the contact form.
    - Unable to submit without an email address.
    - Filled in the Email but left the full name blank. 
    - Unable to submit without a full name.
    - Left file input without file but filled two sections
    - Unable to submit without a file
    - Filled in both sections and added file
    - Form submitted 
    - Repeated steps 1-10 on mobile and tablet.
    - Test passed

### Buttons

* Donate button and modal test:

    - Visited the website on multiple devices to verify that the donate button leads to a working modal.
    - Clicked on the donate button 
    - Clicked on checkout
    - Paypal verification comes up then price demo
    - Clicked continue shopping button which closes modal.
    - Modal working as intended. 
    - Test passed

* Sponsor buttons and modal test:

    - Visited the website on multiple devices to verify that the sponsor buttons lead to a working modal for each individual cat.
    - Clicked on the sponsor button under Jess-cat information
    - Clicked on checkout
    - Paypal verification comes up then price demo
    - Clicked continue shopping button which closes modal.
    - Repeated for the other three cats available to sponsor
    - Modal working as intended. 
    - Test passed

### Footer

* Visited footer on multiple devices:

    - Clicked on adopt to check it goes to the adopt part of the index page
    - Tested on every page to make sure it worked
    - Repeated steps 2-3 with donate and sponsor
    - All buttons passed test 

* Location link:

    - Tested modal on map button.
    - Modal pops up with a map and contact details. 
    - Close button works to close modal. 
    - Repeat on all four pages.
    - Test passed 

* Visited social media icons on the website.

    - Clicked each icon to verify that links direct users to intended website main pages in a new tab. 
    - (Only links to each websites home page as the company is fictional)
    - Test passed


### Button colours

* !Important
Bootstrap button colour options not fitting in with scheme of website.
Some developers suggest it is valid on occasion as said [here](https://css-tricks.com/when-using-important-is-the-right-choice/). This [website] states that it should only be used when necessary and other options are gone. 
In order to change the bootstrap-secondary element, the background-color and color were changed and !important added at the end. 
Colors changed to <img src="assets/images/readme-color-yellow.png"/> background with black words.  