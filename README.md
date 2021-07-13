![Logo](wireframes/logo.JPG)

# T4Tri Triathlon Club



# Goal for this Project
Welcome to T4Tri Triathalon Club. This club provides an outlet for all age groups from 16 to 116 to get involved and give trathalons a go. 

This site gives some information about the club, basic information about triathlons and club events to capture the eye of a potential member. It also gives the ability to make contact with the club easily through social media or directly via the contact form.



![Responsive Displays](wireframes/different-displays.JPG)

# Table of Contents
* [UX](#ux "UX")
    * [User Goals](#user-goals "User Goals")
    * [User Stories](#user-stories "User Stories")
    * [Site Owners Goals](#site-owners-goals)
    * [User Requirements and Expectations](#user-requirements-and-expectations)
         * [Requirements](#requirements)
         * [Expectations](#expectations)
     * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Icons](#icons)
        * [Colours](#colours)
        * [Structure](#structure)
    * [Wireframes](#wireframes)
    * [Features](#features)
        * [Existing Features](#existing-features)
            * [Navigation Bar](#navigation-bar)
            * [Landing Page](#landing-page)
            * [About Section](#about-section)
            * [Events Section](#events-section)
            * [Contact Section](#contact-section)
            * [Footer](#footer)
        * [Features to be implemented](#features-to-be-implemented)
    * [Technologies used](#technologies-used)
        * [Languages](#languages)
        * [Tools and Libraries](#tools-and-libraries)
    * [Testing](#testing)
        * [Unfixed Bugs](#unfixed-bugs)
    * [Deployment](#deployment)
    * [Credits](#credits)
# UX

## User Goals
* Visually appealing, including images.
* Easily navigated around.
* Quality and valuable content.
* Easily found contact details.
* Form to directly contact the club.
## User Stories
* As a user, I want to know that the club is well established.
* As a user, I want the website to give me information about what is involved in trathalon.
* As a user, I want to be able to easily contact the club.
* As a user, I want to be able to make contact with the club via several different methods, i.e. social media.
* As a user, I want to be able to easily navigate through the website.
* As a user, I want to know where the club is based.
* As a user, I want to know what events are taking place.
## Site owners Goals
* Promote the club.
* Increase the number of members.
* Increase rankings on search engines.
### Requirements
* Easy to navigate on various screen sizes.
* Clear information on the services provided.
* Keep the user interested with small bits of information to make them want to engage with the club.
* Simple methods of contacting the club.
* Visually inviting so users do not leave.
### Expectations
* I expect to know if a form has been submitted properly and if items are not filled in, to be prompted.
* I expect all links to social media sites to be opened in a new tab.
* I expect all navigation links to work correctly.
* I expect screen size not to affect the quality of the website.
* I expect all information to be correct and accurate.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

## Design Choices

### Fonts
In order to move away from the basic fonts available, I have used 
[Google Fonts](https://fonts.google.com/ "Google Fonts") to find a text that best suits the feel of the website. For the main text I have chosen [Montserrat](https://fonts.google.com/specimen/Montserrat?query=mon "Montserrat font") as I feel it is has a sharp, simple and easy to read look. To make the headers and the navigation bar stand out form the text, I decided to use [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab?query=rob "Roboto Slab font"). This font is complimentary to Montserrat but gives clear definition between text and headers.

### Icons
I will used some icons for my website from the [Font Awesome library](https://fontawesome.com/ "Font Awesome"). These icons will only be used where there is no explination needed to their meaning, social media links, contact links and a hamburger for navigational links on smaller devices. All icons used will be styled and in keeping with the appearance of the website.

### Colours
I have used [Colourmind](https://colormind.io/ "colourmind") to help in the selection of my colour scheme. I selected the initial colour that I wanted the reast of my pallet to fit with and then used the generator to create the pallet, it can be seen [here](wireframes/colour_pallet.JPG "Generated Colour Pallet"). However when I tested the contrast of the colours in [WebAIM](https://webaim.org/resources/contrastchecker/ "WebAIM"), the contrast ratio from the text colour to the background colour was not good enough and failed tests, they can be seen [here](wireframes/contrast-checker.JPG "Failed tests"). After adjusting the colours manually, I gained a pallet that still gave great impact and had great contrast, these are the results for the contrast checker are [here](wireframes/contrast-checker-adjusted.JPG "Adjusted Colour Pallet").


I will explain the uses of the varius colours below, starting from top to bottom.


![Colour Pallet](wireframes/new-colour-pallet.JPG)


 
 * #8C00B3 - This colour will be used as a background colour for sections and as a text colour.
 * #FFFDDF - This colour will be used as a background colour for sections and as a text colour.
 * #8E689B - This colour will be used on the contact form for added styling.
 * #92579F - This colour will be used as a backgroung behind any images used.
 * #121A18 - This colour will be used as a text colour also the navigation and footer background colour.

### Structure
I will be building my website with a mobile first mindset using the iPhone 5/SE (320px) as the smallest screen size for styling to look good on. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap").

| Screen Size | Breakpoint |
| ----------- | ---------- |
| x-small     | <576px     |
| small       | => 576px   |
| medium      | => 768px   |
| large       | => 992px   |
| x-large     | => 1200px  |

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Wireframes
I have used [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") to develop my wireframes for my website. I initially created the mobile version and then the wireframes and then scalled it up for both tablet and desktop. Because a requirement is to give little but quality information to the user to make them want to engage with the club, a one-page website is used. This gets the user through the content and quickly to the contact form and details via scrolling or directly via the navigation bar.

The wireframes are below:


### [Desktop Wireframe](wireframes/T4Tri_desktop.png "Desktop wireframe")
### [Tablet Wireframe](wireframes/T4Tri_tablet.png "Tablet wireframe")
### [Phone Wireframe](wireframes/T4Tri_phone.png "Phone wireframe")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features

## Existing Features

### Navigation Bar

The navigation bar is fully responsive to allow for various screen sizes. It includes links to manover around the site easily and the club logo which doubles as a link back to the home screen.

+ Desktop (>=992px)
\
&nbsp;
    ![Navigation bar](wireframes/nav-bar-desktop.JPG)
    -   Spanning the full width of the device and with all links (Home, About, Events, Contact) to navigate visible, this gives ease and clear use to the end user.

    -   In order for the user to visably see which of the links they are hovering over there is a bar below the text.

    ![Navigation bar on hover](wireframes/nav-bar-hover.JPG)
    \
    &nbsp;
    -   For the user to know that a link has been clicked there is also a visual aid of the text changing colour.

    ![Navigation bar on focus](wireframes/nav-bar-focus.JPG)
    \
    &nbsp;


+ Small devices (<992px)
\
&nbsp;
    - As the navigation bar would be unuseable in the desktop version on smaller devices, it takes on a hamburger style.

    \
    &nbsp;
![Nav bar on small devices](wireframes/nav-bar-small.JPG)

    - When pressed, it opens up the main menu with all the links available then.

    \
    &nbsp;
![Nav bar on small devices expanded](wireframes/nav-bar-small-expanded.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;
### Landing Page

+ The landing page image
    - The image gives the user instant knowledge of what is involved in the club, and with added animation draws their eye to the site.
    - The text gives instant information to the user on what the club is. With the added animation of fading in slightly behind the image, it makes the user keep interest. 
    \
    &nbsp;

    ![Landing Page](wireframes/landing-page.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;


### Welcome Section

+ The welcome section gives a brief introduction to the user on what T4Tri is and who is welcome.
    \
    &nbsp;

    ![Welcome Section](wireframes/welcome.JPG)
    \
    &nbsp;

+ To speed up user interation, there is a *'Join Us'* button that directly links to the contact form. This button has a hover effect on it in the form of an animation to allow the user to know that it is something to be pressed.
    \
    &nbsp;

    ![Welcome Button](wireframes/welcome-button.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### About Section

+ The about section gives a brief, and attemped humerous, description of the diceplins of triathlon with the adition of a character showing the user what is involved, even if they do not want to read the descriptions. It is also responsive to suit the different screen sizes.
    \
    &nbsp;

    *Desktop*

    ![About Section on Desktop](wireframes/about.JPG)
    \
    &nbsp;


    *Laptop*
    
    ![About Section on Tablet](wireframes/about-laptop.JPG)
    \
    &nbsp;

    
    *Phone and Tablet*
    
    ![About Section on Phone](wireframes/about-phone.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Events Section

+ This is where the most upcoming club events are shown. It includes an icon to quickly show if it is a social or a race event to the user. Also, on the larger screen sizes it includes some images to break up the screen.
    \
    &nbsp;

    *Large device*

    ![Events Section on Large Display](wireframes/events-large-device.JPG)
    \
    &nbsp;

    *Small device*

    ![Events Section on Small Display](wireframes/events-small-device.JPG)

    \
    &nbsp;
+ The date and location are also shown with the added function of a link to the directions of the event via Google Maps. There is also a label added, and animation for extra information to the user that it is a link to follow.
    \
    &nbsp;

    ![Events Section Directions](wireframes/events-directions.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Contact Section

+ The contact section allows the user to quickly send a message to the T4Tri club. it also has a map of the location of the club base.
    \
    &nbsp;

    ![Contact Section](wireframes/contact.JPG)
    \
    &nbsp;

+ The text fields are all required fields and will not alow the user to submit until they are completed, this includes a validation on the email to ensure it is in a valid format. There is also a hover effect on the submit button to give the user feedback that it is and active button.
    \
    &nbsp;

    ![Contact Section](wireframes/contact-email.JPG)
    \
    &nbsp;

+ On submission of the form, the user is bought to a page showing that their details were received.
    \
    &nbsp;

    ![Contact Section](wireframes/contact-received.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Footer

+ The footer contains the social media links related to T4Tri and the copyright text. These social links all open in a new tab for ease of use to the user and also, so the user has an ability to easily come back to T4Tri's site.
    \
    &nbsp;

    ![Contact Section](wireframes/footer.JPG)
    \
    &nbsp;

+ There is also a hover effect over the links, again to improve user experiance.
    \
    &nbsp;

    ![Contact Section](wireframes/footer-hover.JPG)
    \
    &nbsp;

## Features to be Implemented

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Technologies used

## Languages
* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

## Libraries & Framework
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
## Tools
* [Gitpod](https://www.gitpod.io/ "Gitpod")
* [Balsamic](https://balsamiq.com/wireframes/ "Balsamic")
* [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML")
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS")
* [Bootstrap](https://getbootstrap.com "Bootstrap")
* [Colourmind](https://colormind.io/ "colourmind")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Unsplash](https://unsplash.com/ "Unsplash")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Testing

I feel that the site has hit the goals required by all parties. The site responds nicely to all different screen sizes, the images look clean and sharp on all device sizes with very little, large blank spaces. It allows the user to navigate around easily and aslo make contact via the contact form or social media simply. It The content is simple and to the point and the site is not overcrowded as to put the user off.
\
&nbsp;

I have encountered several issues during testing. 
 + I initially decided to create the site with a minimum width of 992px as my largest styling, however the site just did not look right so added an x-large screen size.

 + In my wireframes, I had designed to only have a 'Join Us' button on the larger screen sizes. While I was developing the site, this did not make sence. There was such a long scroll with it being a one-page site, I felt I needed to speed up the movement for someone who was instantly interested so included it on all screen sizes.

 + On actual smaller devices, instead of on Chrome Developer, the main navigation menu did not show the 'Contact' link. I simply changed the styling of the links and the changed the ul to flex-start and all is now clearly visable.

 + I was having issues with the navigation bar scrolling about 15px when I scrolled down on smaller devices whilst working on Chrome Developer. I lost a lot of time trying to figure out the issue, but when I tried the site on an acual device, the navigation bar stayed fixed as the code dictated. This was a bug in Chrome Developer and not with my site.

 + The main navigation on smaller devices was initially set to 90vh, however on testing on a physical device, the user could see the site scrolling at the bottom if they were to slide up or down. This looked very poor and clumsy on the eye, so I adjusted it to 100vh to cover it up.

 + I found that I was repeating alot of code in my style.css file in order to center items. I created a class to do this and then applied it whee needed.

 + All my buttons were styled completly differently. I added an animation to all buttons so there is a continuity between them all.

 + When I was validating HTML code, I had one error showing. This was in the contact form where I had a method of '#'. I was under the understanding that POST method should have been used, but when I did, it caused an error instead of going to my contact.html page. After a while I tried using GET and it worked solving my validation problem. The results of my validation for HTML and CSS are below.

    - HTML (index.html) validator [results](wireframes/html-validate.JPG "W3C HTML")
    - HTML (contact.html) validator [results](wireframes/html-contact-validate.JPG "W3C HTML")
    - CSS validator [results](wireframes/css-validate.JPG "W3C CSS")
\
&nbsp;

 + On testing on a physical mobile device, I thought that the google search bar looked odd, being white and my header a dark colour. For user experiance and to make it look cleaner and more fluid, I changed the colour to match using the following code.

 ```

 <meta name="theme-color" content="#121A18">


 ```

 + When going through my UX section, to ensure that all my goals were met for the project, I noticed that I had missed one, 'As a user, I want to know that the club is well established'. I adjusted the text in the welcome section to suit.
\
&nbsp;

## Unfixed Bugs

My learning has limited my use of the hamburger for smaller devices. It works nicely to open the menu up, but a tap of the hamburger again should close the menu down again. It does not do this, and the link has to be selected to enable the user to exit out of it. From my research it seems that all the streamline methods are using JavaScript and I am yet to learn this.


\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Deployment

Following writing the code then commiting and pushing to GitHub, this project was deployed using GitHub by the following steps.

+ Navigate to the repository on github and click 'Settings'.
+ Then select 'Pages' on the side navigation.
+ Select the 'None' dropdown, and then click 'master'.
+ Click on the 'Save' button.
+ Now the website is now live on https://sam-timmins.github.io/T4Tri-triathlon-club/
+ If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Credits

For code insperation, help and advice,
* [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin")
* [Mark Caron](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793 "Marc Caron")
\
&nbsp;

For content and style insperation,
* [3D Triathlon Club](https://www.3dtri.ie/ "3D Triathlon Club")
* [Limerick Triathlon Club](https://limericktriathlon.com/ "Limerick Triathlon Club")
* [Portmarnock Triathlon Club](https://www.portmarnocktriathlonclub.com/ "Portmarnock Triathlon Club")


\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;