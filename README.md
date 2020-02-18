HART HEALTH AND FITNESS

This project is to build a HTML/CSS website for HART Health and Fitness solely for advertisement. Owner of HART (Joe Morgan) has recently moved to Copenhagan, Denmark and is trying to establish his brand overseas. 
In his time in Denmark he has managed to form a good client base through word of mouth.
The website is designed to increase knowledge of the brand and services on offer, and hopefully generate this into further clients and business.
The website provides a short background of the brand, the services offered, reviews from current clients, common questions and finally a contact form to register interest of services.


UX

The website has been created for Joe Morgan, Owner of HART Health and Fitness. The website is designed to provide advertising and generate further business and spread knowledge of the brand.
The website concisely provides all relevant information on the brand, services offered, positive reviews of Joe's services and a contact form. 

User Story:

User - Potential Customers/Clients

I want to be able to find out the following:

Services available;
How good the service is? (Reviews);
How to get in touch?;

User - Business Owner:

I want to be able to provide the following:

Be able to give potential customers a basic overview of what services are provided.
Answer as many questions as possible.
Provide feedback from current clients to encourage contact.
Make contacting as simple as possible (Contact forma and alternate methods of contact)



Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - Nav Bar
Nav Bar allows simple and efficient navigation to desired area of the web page.

Feature 2 - Contact form
Contact Form allows quick and easy contact to HART Health and Fitness with minimal information required.

Feature 3 - Footer
This provides further contact details enabling users multiple ways to access services.
Social media link, provides further show case of classes, client workouts and client progress.


Features Left to Implement
JavaScript incorporation on the contact form to link to business email address.

Future Possibilites

Members login area (This would include)

Calender: To book/cancel/rearrange PT sessions
Payment section: To pay for classes
Access to Training plans
Access to nutrional plans
Access to progress/goals



Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

HTML
CSS
Fontawesome: https://fontawesome.com/
Use of basic icons in the services section and faq section.
google fonts: https://fonts.google.com/
To enable the import and use of different font types.
Bootstrap: https://getbootstrap.com/docs/4.4/getting-started/introduction/
Used to implement grid layout for simple web page layout and design. Further features taken from site to incorporate into website.

JavaScript
JQuery
Used to enable features e.g contact form errors/missing information and action movement on the accordion features within the FAQ section.

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

