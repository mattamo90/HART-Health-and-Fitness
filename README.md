HART HEALTH AND FITNESS

This project is to build a HTML/CSS website for HART Health and Fitness solely for advertisement. Owner of HART (Joe Morgan) has recently moved to Copenhagan, Denmark and is trying to establish his brand overseas. 
In his time in Denmark he has managed to form a good client base through word of mouth.
The website is designed to increase knowledge of the brand and services on offer, and hopefully generate this into further clients and business.
The website provides a short background of the brand, the services offered, reviews from current clients, common questions and finally a contact form to register interest of services.


UX

The website has been created for Joe Morgan, Owner of HART Health and Fitness. The website is designed to provide advertising and generate further business and spread knowledge of the brand.
The website concisely provides all relevant information on the brand, services offered, positive reviews of Joe's services and a contact form. 



In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

JQuery
The project uses JQuery to simplify DOM manipulation.

Testing



Nav Bar:
Tested Nav Bar on Desktop and Mobile devices. (Via Chrome Developer tools and Iphone XR device)
Tested on desktop by using each individual link heading and ensuring this scrolls to the correct section.
On mobile, tested that the NAV Menu icon/dropdown worked and then again tested each individual nav heading scrolled to the correct section.

Whilst testing the NAV elements, i discovered that the HREF link i had initially configured were causing an issue. Due to building a one page website,
instead of using the # element alone, e.g #about (to navigate to the about section) i had stated index.html#about. This caused the entire page to reload everytime a nav heading was selected. This reloading issue further highlighted a problem with the size of the background image.
Due to background image size it was taking too long for the site to load, impacting on user experience.  All issue resolved.

Contact form:
Go to the "Contact" Section,
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.

Website:
Tested Website on Desktop and Mobile devices, (Via Chrome Developer tools and Iphone XR device).

On testing across multiple devices and screen sizes I discovered issue with padding impacting readability on smaller screen sizes. 
I have incorporated @media styling for smaller screen sizes to improve user design.

Main issue i discovered was the horizontal overflow of the site. This meant that on larger screens there was a horizontal scroll bar present that revealed large amounts of white space to the right of the page.
On smaller screen sizes this issue manifested itself in a permanent white line down the right side of the page.

Using chrome developer tools, I tried to determine whether there was a particular element or section that was overflowing and causing this issue. However, there was no obvious cause.
In the end I applied overflow-x: hidden within CSS in both the standard CSS and within the media query for smaller devices.



If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
Project published to GitHub Pages via the GitHub website.

This was done by navigating to the Repository.
Settings
Scrolling to GitHub Pages Section
Publish.

Credits
Content
The code for the FAQ section was copied from https://mdbootstrap.com/docs/jquery/javascript/accordion/
The code for the Contact form was taken from https://getbootstrap.com/docs/4.4/components/forms/
Other parts of the code were tailored from examples found at:

https://getbootstrap.com/docs/4.4/
https://www.w3schools.com 

Media
Photos sourced from:
Joe Morgan;
unsplash.com

