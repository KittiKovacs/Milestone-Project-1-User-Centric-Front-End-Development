# Milestone-Project-1-User-Centric-Front-End-Development

The project is a website for a real-life small car and motorbike repairs and motor trader business. The purpose of this project is to introduce the garage and its services, to serve as a platform for advertising the items on sale and to generate more business. It contains 3 pages: the homepage povides and overview of the garage's services, the second page features the vehicles that are available for purchase and the contact page provides contact information and a contact form.

## UX
The target audience is private individuals looking for a reliable local garage for repairs, advice or used cars and motorbikes. This website is easy to navigate, provides all essential information for the visitor to be able to decide whether they want to take the next step and contact the business. The website invites visitors to get in touch and offers them multiple options, including links to other sites like Facebook or Ebay. 

The layout and colour scheme are similar on all 3 pages. It features the same background image  with a white header on top and black footer on the bottom.

The website is responsive, on medium and small viewports the telephone number is hidden from the header and on small wiewports the menu items are stacked below the company logo. The content also shrinks to fit the current viewport width.

[Wireframe](https://github.com/KittiKovacs/Milestone-Project-1-User-Centric-Front-End-Development/blob/master/GL%20Motors%20wireframes.pdf)

### User stories

* User 1 is looking for a new mechanic to carry out the annual MOT service. They would like to get a first impression of the garage and its services. They can read about the services available, items for sale, opening times and location on Google Maps.

* User 2 is looking for used cars or motorbike from a trustworthy local source, and comes across this website where he can find photos and basic information about the available models. They can and send a query through the website by filling in the contact form.

* User 3 is in an emergency and needs their car fixed by Monday to be able to go to work. He is looking for a mechanic who’s working flexible hours, even weekends. Looking at the contact page he can check the opening hours, find the exact location on the map provided, and quickly contact the business by calling the telephone number in the header.


## Features

### Existing Features
* **Header**-contains company name and logo, navigation links and basic contact details. The navigation links get an underline animation on mouse hover. By clicking on the company logo the user is able to return to the main page from any page.
 
* **Footer**- Contains links to **social media** pages. This is currently the company's Facebook page only. The Facebook logo changes colour on mouse hover to indicate that there is an action available.

* **Home page** – contains a short introduction and a list of **services** provided by the garage. The list style icons are replaced by a wrench icon to match the company's profile. 
This page also contains a callout to users who are interested in buying car parts and a link to the owner's Ebay page. 

* **Cars&Bikes page**- Contains a short description of cars and motorbikes currently for sale and a **photo gallery** below each description. On hovering over the thumbnail images with the mouse they enlarge by 25%. Each image opens in a separate browser tab when a user clicks on them. 

* **Contact page**-informs the user about the **address** of the business and **opening times**; features a **Google maps** snippet which leads to the Google Maps website when clicked on. The page also features a **contact form** that is  going to enable users in the future to send a message to the business directly when they click on the Send button. Currently it leads to a subpage with a message informing the user that this feature is not available yet. The button changes colour and the cursor changes to a pointer on mouse hover.

### Features Left to Implement

* Webshop
* More complex contact form with subject options (Request a part, general
enquiry, I have something for sale, etc.) 
* Animated image gallery with professional photos of the cars for sale
* Language choice options
* News section
* Blog
* Client testimonials

## Technologies Used

* HTML to create the code for the website's content
* CSS to add styling to HTML
* Bootstrap v 4.5.0 (https://getbootstrap.com/) for advaced styling and positioning. This includes the grid structure and parts of the navigation.
* Font Awesome (https://fontawesome.com/) for the icons
* Google Fonts(https://fonts.google.com/) for the fonts used on the site
* Google Maps (https://www.google.com/maps) for the map snippet featured on the Contact page.

## Testing

User story 1:
1. Types of services available on the homepage for user to view.
2. Scroll down for a link to Ebay where some spare sparts are sold.
3. Contact details are accessible by clicking on "Contact" in the navigation bar.
4. Click on "view larger map" to view garage location on Google maps or zoom out on this site.
5. Return to homepage by clicking on company logo in the top left corner or the "Home" navigation item.
6. View what used vehicles are for sale by choosing "Cars and Bikes for sale" in the navigation bar.

User story 2:
1. Click on "Cars and Bikes for sale" in the navigation bar.
2. Scroll down for images and more information.
3. Click on individual images to open them in a separate window.
4. Access contact form by clicking on "Contact" in the navigation bar and scrolling down.
5. Fill in form with name, email address and message.
6. Click on "send" button to send message. 

User story 3:
1. Contact details accessable by clicking on "Contact"in the navigation bar.
2. Read about opening times on the same page.
3. Click on map to access a larger version. 
4. Call contact number.

**Testing features:**

*Link to Ebay*
 1. Scroll down the homepage to find Ebay image.
 2. Click on image to activate link.The link is for the seller's page on Ebay.

*Link to Facebook* 
 1. Find Facebook icon in the footer on any page.
 2. Click on icon to activate link that leads to the relevant Facebok profile.

*Gallery*
1. Choose "Cars and Bikes for sale in the navigation bar
2. Hover over the images to enlarge them.
3. Click on individual images to open them in a new tab

*Form*
1. Go to Contact page
2. Scroll down to find contact form.
3. Try to submit form without valid email address.
4. Add valid email address an submit form. This action leads to a new page informing the user that this feature is not available.
5. Click on the arrow to return to Contact page.

All HTML code passed the W3C's [markup validation](https://validator.w3.org/).
The CSS code passed the W3C's [CSS validation](https://jigsaw.w3.org/css-validator/).

## Deployment

The project was created in GitPod and deployed on GitHub. I also used Repl.it for testing new ideas or small changes as I find Gitpod is not really suitable for this purpose.

I deployed the project to GitHub in small increments starting with the header and footer which I copied from index.html to the other 2 pages. Originally I created a separate page for the car parts but I couldn't fill it with enough information so I removed it and placed the Ebay link on the homepage. I did a lot of research on positioning to make the website responsive which took up most of my time during development process. I used Chrome developer tools extensively to help me throughout the process.

I added an additional page containing a short error message as an afterthought, which is not accessible via the navigation links. I realized that the contact form I created doesn't actually perform an action which would be confusing to users. Now clicking on the Send button takes the user to this page informing them that this feature is temporarily unavailable and gives options as to what to do next.

## Credits

### Content
All content was provided by GL Motors.

### Media
* Image sources: https://www.pexels.com/ 
* the garage's owner's own photos of vehicles for sale.

### Acknowledgements
My inspiration for the project was my partner who owns this business and he helped me by providing photos and all the information I needed to make the website suitable for a real business as well as his insight as a client.
My Tutor Guido Cecilio Garcia Bernal had great suggestions about the form and header parts of the page.


