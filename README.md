# John Gaynor Construction

This is a fully responsive website designed for a building construction business. The idea for the website is for a professional and operational look so users have confidence in the actual work of the company. 

Please click [here](https://john-gaynor-construction-cgaynor91.c9users.io/index.html) for a live demo of the website 

# UX

As I mentioned above, my objective for this website from the beginning was to have a professional and fully operational and responsive website. I wanted the user to be first greeted with some images of work that has already been completed by the company so the user knows immediately the high standard of work the company does and also the different variety of work. 

I decided to adapt the mobile first approach as in the current climate many people now book things or research things via their mobile device and/or tablet. When initially planning this website it occured to me that the client base was quite broad, ranging from customers who have no knowledge of the industry looking to hire a contractor to build a home or adapt their current home to large companies who want to hire a contractor for a big development. With this in mind I wanted to have the landing page demostrate that the company caters for both these customers.

I was also conscious of having too much information on the home page and wanted to divide up the different services and projects the company has to offer. Initially I wanted to have images of the previous projects all on my services page however I felt that was information overload for the consumer and decided it would be better to give each project it's own page and that way if the user wanted to see further work completed they could so at their discretion by clicking the links provided either on the home page or service page. 


## User Stories

- As a customer who has no knowledge of the building world I would like to see images of what kind of work this company has previously completed. I would like to see where their company is located and also how to get in contact with them. I would want to know what kind of work they specialise in and what are their qualifications. 
- As a large company looking to start a large project development I would like to see what previous large projects the company has worked on. It would be important to see images of large developments and also the scope of the developments. I would want to know who the company had previously worked with and where. 


**Wireframes**








## Features

The website itself has a responsive fixed top navbar displaying four visible links, the last link has a dropdown feature displaying a further five links ergo the website itself is a 9 page website. This navigation bar is displayed on all 9 pages. 

Across all pages (excluding home) I have implemented a breadcrumb that will enable the user to go back to the home page if needed. 


### Home Page

There is carousel displaying images of work completed by the company, this greets the user when they first visit the page.

There is a contact form provided for users to submit their email address to the company to enquire about the business. 

There are 6 card features displaying the variety of work the company does. These cards hold images and links allowing the user to click on the respective link they are interested in which will bring them to the relevant page. 

There is a further button at the end of the page that encourages the customer to get in contact with the company, this button brings the customer to the contact page. 

### Contact Page

The contact page has an embeded google map showing where the company is located

There is a bootstrap contact form enabling the customer to fill in their details and enquires and submit to the website. 

### Footer

The footer is fixed to the bottom of all pages and holds the scoial logo for linkedin and selecting same would bring you to the profile of the site manager of the company. 


## Technologies Used

- [Bootstrap](https://getbootstrap.com/) 
   - The Bootstrap framework was used to create a responsive design and plan the overall layout of the website. 
- [Fontawesome](https://fontawesome.com/start)
    - Used FontAwesome to style social link in footer and carousel indicators
- [JQuery](https://jquery.com/)
    - This was used to work with the document object model.

- [Embedded Google Map](https://www.google.com/maps/)
  - Using the embed option on the google maps website I embedded a link showing where the company is. 

- [Popper JS](https://popper.js.org/)
    - This was used to operate the dropwdown menu in the navbar and provide dynamic positioning and viewport detection. 

- [FavIcon](https://www.favicongenerator.com/)
  - I used the FavIcon generator to create the page icon and compress it to its required size.

- [Git](https://git-scm.com/)
  - Use of git to commit different stages of my project

- HTML
    
- CSS


## Testing 

 - Using [Browserling](https://www.browserling.com/) I tested the website across multiple browsers to ensure responsiveness and compatibility. 
 - Using Google Chrome developer tools I tested the websites responsiveness across various devices ie. iPhone, Android and Tablets. 
 - The enquiry form on the home page will not let you submit unless a valid e-mail address is entered and a note will be appear to advise the client of same
 - The contact form on the contact page also contains the required attribute for both email and phone number and this functions correctly
 - Manually tested all the hover styling on the navbar and also the links - all operating correctly.
 - Manually tested button on home page with internal link to contact page
 - Checked HTML and CSS oh respective validators
 - Manually checked fontawesome social link which brought me to the relevant page in a new browser window. 

### Addressing testing from User Stories 

*"As a customer who has no knowledge of the building world I would like to see images of what kind of work this company has previously completed. I would like to see where their company is located and also how to get in contact with them. I would want to know what kind of work they specialise in and what are their qualifications."*  

This customer's experience has been satisfied as the first thing as a visitor to the site that they will see is images of previous work completed. They have two options of getting in contact on the home page itself, by entering their e-mail in the enquiry box directly below the carousel or if they have scrolled to the bottom of the home page there is a further button encouraging them to get in touch with the company, this button subsequently will bring them to the contact page where they will find a google map showing the exact location of the company. On the home page they are also shown various pictures of previous work completed in different fields and also on every page above the footer is the company's qulaifications. 

*"As a large company looking to start a large project development I would like to see what previous large projects the company has worked on. It would be important to see images of large developments and also the scope of the developments. I would want to know who the company had previously worked with and where."*

Again this customer's experience has been met as there is images of previous work greeting them immediately on gaining access to the site. Also on the home page there is images with links and a brief description of previous commerical work completed. If they clicked on either the commercial or healthcare link they would be brought to the respective portfolio and given further detail of the projects completed ie. the cost, length of time the projects took to complete and who the company worked with on said projects. 


