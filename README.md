# John Gaynor Construction

This is a fully responsive website designed for a building construction business. The idea for the website is for a professional and operational look so users have confidence in the actual work of the company. 

Please click [here](https://cgaynor91.github.io/John-Gaynor-Construction/) for a live demo of the website 

# UX

As I mentioned above, my objective for this website from the beginning was to have a professional and fully operational and responsive website. I wanted the user to be first greeted with some images of work that has already been completed by the company so the user knows immediately the high standard of work the company does and also the different variety of work. 

I decided to adapt the mobile first approach as in the current climate many people now book things or research things via their mobile device and/or tablet. When initially planning this website it occured to me that the client base was quite broad, ranging from customers who have no knowledge of the industry looking to hire a contractor to build a home or adapt their current home to large companies who want to hire a contractor for a big development. With this in mind I wanted to have the landing page demostrate that the company caters for both these customers.

I was also conscious of having too much information on the home page and wanted to divide up the different services and projects the company has to offer. Initially I wanted to have images of the previous projects all on my services page however I felt that was information overload for the consumer and decided it would be better to give each project it's own page and that way if the user wanted to see further work completed they could so at their discretion by clicking the links provided either on the home page or service page. 


## User Stories

- As a customer who has no knowledge of the building world I would like to see images of what kind of work this company has previously completed. I would like to see where their company is located and also how to get in contact with them. I would want to know what kind of work they specialise in and what are their qualifications. 
- As a large company looking to start a large project development I would like to see what previous large projects the company has worked on. It would be important to see images of large developments and also the scope of the developments. I would want to know who the company had previously worked with and where. 


**Wireframes**

[Mock Ups](assets/Wireframe/Wireframes.pdf) with basic mock-up of what I originally wanted the landing page to look like across different devices.

Also a basic idea of what I wanted the [about](assets/Wireframe/mockupabout.pdf) page to look like. 

I also had an idea of what I wanted my [contact page](assets/Wireframe/mockupcontact.pdf) to lay out like 




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
 - Checked HTML and CSS on respective validators
 - Manually checked fontawesome social link which brought me to the relevant page in a new browser window. 

### Issues when Testing

- I found when testing the website on smaller screen sizes such as iphone or android devices there appeared to be a small white margin to the right of the screen, sometimes creating a horizontal scroll-bar, I fixed this issue by adding `overflow-x: hidden` in my CSS. 
- I had issues with the google maps image not resizing on smaller screens when I was checking the responsiveness and added CSS style code found on [Emded Google Maps](https://www.embedgooglemap.net/). I then had to customise this CSS to suit my own website.
- I linked my website to family and friends to see if there was any issues and get general feedback about UX. I received 99% positive feedback, the only issue that was reported was my mother couldn't understand why the word "in" was at the bottom of every page :) 

### Addressing testing from User Stories 

*"As a customer who has no knowledge of the building world I would like to see images of what kind of work this company has previously completed. I would like to see where their company is located and also how to get in contact with them. I would want to know what kind of work they specialise in and what are their qualifications."*  

This customer's experience has been satisfied as the first thing as a visitor to the site that they will see is images of previous work completed. They have two options of getting in contact on the home page itself, by entering their e-mail in the enquiry box directly below the carousel or if they have scrolled to the bottom of the home page there is a further button encouraging them to get in touch with the company, this button subsequently will bring them to the contact page where they will find a google map showing the exact location of the company and a fully functional form where they can liaise with the company and give a description of their project/idea/query. There is also contact details on the home page and the contact page so the customer can see their operating hours and contact details. On the home page they are also shown various pictures of previous work completed in different fields and also on every page above the footer is the company's qulaifications. 

*"As a large company looking to start a large project development I would like to see what previous large projects the company has worked on. It would be important to see images of large developments and also the scope of the developments. I would want to know who the company had previously worked with and where."*

Again this customer's experience has been met as there is images of previous work greeting them immediately on gaining access to the site. Also on the home page there is images with links and a brief description of previous commerical work completed. If they clicked on either the commercial or healthcare link they would be brought to the respective portfolio and given further detail of the projects completed ie. the cost, length of time the projects took to complete and who the company worked with on said projects. 


## Deployment

This website is hosted using GitHub pages which were deployed directly from the master branch. The webiste will automatically update when updated commits are made to the master branch. 
The webiste was developed using Cloud9 IDE, it was then committed to git and pushed to GitHub using the terminal in Cloud9.

To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

- Log into GitHub.
- Select the repository **cgaynor91/John-Gaynor-Construction**.
- At the top of the page, under the "watch" icon select *settings*.
- Scroll down to the GitHub Pages section.
- Under Source, click on the dropdown menu and select **Master Branch**
- The selection refreshes the page and in turn the website is deployed
- The live link for the webiste will now appear beneath the **GitHub Pages** header. 


### How to run this project locally
If you wish to clone this project from GitHub:

- Click on this [link](https://github.com/cgaynor91/John-Gaynor-Construction) to the GitHub repository.
- There is a green button saying "Clone or download" - click on this.
- Copy the clone URL for the repository.
- Open Git Bash in your local IDE.
- Change the current working directory to the location where you want the cloned directory to be created.
- Type git clone, and then paste the URL copied in Step 3.
- git clone https://github.com/USERNAME/REPOSITORY
- Press Enter to create your local clone.

## Credits
   
### Content

- Text was taken from [Conack Construction](https://www.conack.ie/) and [MFC](https://www.mfc.ie/)
   
### Media
   
- Images were taken from [Conack Construction](https://www.conack.ie/) and [MFC](https://www.mfc.ie/)
- Construction images taken from Google Image Search
- Health and Safety Logos downloaded from respective safety websites. 
- The navbar styling using the social media link was taken from Code Insititutes mini project "Rosie CV" - customised and adapted to suit the page
- CSS Styling for google maps was taken from [Emded Google Maps](https://www.embedgooglemap.net/) and customised for the website. 
- FavIcon was generated using [FavIcon Generator](https://www.favicongenerator.com/)

## Acknowledgements

I got a lot of my inspiration for my website from [Conack Construction](https://www.conack.ie/) and [MFC](https://www.mfc.ie/). 

I used [this](https://www.w3schools.com/bootstrap/bootstrap_carousel.asp) tutorial to create the home page website's carousel 





