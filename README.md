# Code Institute - Milestone One

## User-Centric Frontend Development 

![Living Landscapes Logo](images/logo/footer_logo.png)

## Living Landscapes - [Live Site](https://emmahartedev.github.io/living-landscapes/)

Living Landscapes is a fictitious landscaping company based in Clonakilty, in Co. Cork.  
The company consists of 6 team members who provide 3 services, residential landscaping, commercial landscaping and garden maintenance. 

The company was founded in 2011 and has experienced significant growth in the last 5 years. 
With this is mind, the purpose of this website is to increase customer interaction, improve the customer experience and build brand awareness. 

Important information and features to the company include: 

* Utilising the brand colors, purple and green.
* Displaying the company's services.
* Conveying a strong message of excellent customer service.
* Listing information about the team and company.
* Offering an online method of contacting the team.
* Exhibiting past creations. 

----------------------------

## Contents
1. UX(link later)
    * Project Goals (em)
    * User Stories
    * Project Scope
    * Wireframes
    * Surface

2. Features 
    * Existing Features
    * Features Left to Implement

3. Technology Used

4. Testing
    * Browsers
    * Responsiveness
    * W3C Validation
    * User Story Testing

5. Deployment

6. Credits
    * Code
    * Contents
    * Media
    * Acknowledgements

----------------------------

## UX

### Project Goals
The goals of this website inlclude:
* Increase customer Interaction
* Showcase previous work 
* Build Brand awareness  
* Improve customer experience

The following table displays a breakdown of all opportunities/problems along with their importance and viability.

| Opportunity/Problem| Importance| Viability|
|-------------------------------|------------|-----|                                                            --|
| Increase customer interaction| 5| 5|
| Showcase previous work        | 4               | 4             |
| Build Brand awareness         | 5               | 4             |
| Become an industry leader     | 4               | 1             |
| Improve customer experience   | 4               | 5             |
|                               | 22              | 20            |


### User Stories

#### Client stories
* As a prospective client, I would like to find an 'about us' section on the website, so that I can learn about the company and it's staff so that I can understand what services are provided and if the staff are adequately qualified.

* As a prospective client, I would like to be able to send an online enquiry, so that I can receive additional information.

* As a prospective client who would prefer to speak over the phone rather than email, I would like to be able to request a call-back to an online enquiry and clearly be able to view a telephone number and call-times.

* As a prospective client, I would like to view a portfolio of past work, so that I can know what to expect.  

* As a prospective client who is knowledgeable in horticulture, I would like to see proof that the company are plant experts as this is important to me in garden design. 

* As a prospective client who is not knowledgeable in garden design, I would like to see what options are available to me so that I can descide if this compnay is right for me.  

* As an existing client and admirer of the company, I would like to be able to connect and follow the company through social media platforms, so that I build a connection with the brand.

#### Buisiness stories

* As a team member, I want to see my skills and strengths clearly defined in an 'About' section so that our clients will know I'm qualified.

* As a team member who deals with enquiries, I want to to know the user's name, phone number and email address so that I can get in contact with them.

* As a designer, I do not want prices to be posted online as quotes differ greatly dependending on the project and I really need to talk to the client first.

* As the CEO, I want all of our acheivements and past creations to be featured online. 

### Project Scope
Based on the above user stories, the following are features which will be inlcuded:

* links to company social platforms.
* A contact us form with an option to specify preferred method of contact.
* An 'About Us' section which will feature information about the team, company and services offered.
* A portfolio section which will contain examples of previous work.

The following is a list of features which will not be included: 

* Ecommerce functionality.
* Social media as an extention of the business.
* A blog.
* Back-end site development.
* extensive content/imagery on portfolio examples.

### Wireframes
All wireframes were created using the software [Balsamiq](www.balsamiq.com). 
Layouts were created following research on the five planes of UX and before coding. 
<strong>
Please note, the final website layout contains slight variations to the original wireframes.
</strong>

**Desktop** 
* [Home Page](assets/wireframes/desktop/dhome.png)
* [About Us](/assets/wireframes/desktop/dabout.png)
* [Portfolio](/assets/wireframes/desktop/dportfolio.png)
* [Contact Us](/assets/wireframes/desktop/dcontact.png)

**Tablet**
* [Home Page](assets/wireframes/tablet/thome.png)
* [About Us](assets/wireframes/tablet/tabout.png)
* [Contact Us](assets/wireframes/tablet/tcontact.png)

**Mobile**
* [Home Page](assets/wireframes/mobile/mhome.png)
* [About Us](assets/wireframes/mobile/mabout.png)
* [Contact Us](assets/wireframes/mobile/mcontact.png)


### Surface
A two color palette of green and purple was used, which took inspiration from the company logo. 
This was included in background colors, font & hover elements.

All fonts used are from Google fonts [Google Fonts ](https://fonts.google.com/). 

Fonts used include:
* B612 - used for all headings (h1 - h6)
* Roboto - used for other all body text


----------------------------

## Features

### Existing Features 
* **Navigation** 
    * The navigation contains the brand logo and four links which lead to 4 seperate pages. 
    * The brand logo is an anchor tag, which is linked to the homepage. 
    *  The pages are ordered to create a walk-through experience (Home > About > Portfolio > Contact Us)
    *  For mobile devices, the navbar is designed to collapse.
    *  This feature was created with the aid of Bootstrap 4 and styled in with custom CSS. 

* **Contact Us Form**
    * The contact form includes the necessary information required by the team. 
    *  Several of the fields are required and the user will be alerted by a message if a required field has not been filled in. 
    *  This feature was created using a Bootstrap 4 form and JavaScript.

* **Meet the Team**
    * All staff memebers are featured in the 'About' section. 
    * In addition to a text paragraph, Bootstrap 4 progress-bars are used to exhibit the employees key skills. 

* **About the Company**
    * The company's mission is found on the 'About' section, in a prime location just under the hero image. 
    * The services offered by the company are also included here. 
    * A Bootstrap 4 card is used to feature details on each service. 

* **Testimonials**
    * Testimonials are included on the 'Home' page.
    * Content includes the client's image, quotation and client details
    * A Bootstrap 4 card is used to hold the testimonial content. 
   

* **Portfolio**
    * Within the Portfolio page, award-winning garden designs are displayed seperately and include a gold-badge which shows the year in which the award was acheived. 
    * The company's recent creations are featured underneath, using an identical layout.

* **Footer**
    * The brand logo is features on the footer left.
    * Quick contact links are included in the footer center.
    * Social media links are visable on the footer right.

### Features Left to Implement
Due to project scope, the following features were note implemented in this release. 

These include:
* Back-end development - Server side development is required for functionality of the contact us form. 

* Maps Integration - I would like to Integrate maps into the website, for an added visual reference.  

* Image Carousel - I would like to include an image carousel feature for the indidual creation in the 'Portfolio' page. 

----------------------------

## Technology Used

* HTML5 - Used for structuring the site pages

* CSS - Used for styling the site pages

* Bootstrap 4 - Framework used for building the site pages

* Google Fonts - Used for typography

* Adobe Photoshop - Used to resize and edit images

* Font Awesome - Used for all Icons used

* Git - Used for version control

* Github - Used for respository hosting

* Github Pages - Used for site deployment

----------------------------
## Testing

### User Story Testing

#### Clients Stories

* As a prospective client, I would like to find an 'about us' section on the website, so that I can learn about the company and it's staff so that I can understand what services are provided and if the staff are adequately qualified.
    * A dedicated 'About' page has been created, which includes content on the company's mission,the services they provide and a detailed description on each team member and their skills.
    * The company's services are also viewable on the 'About' page. Within the footer, quick contact-us links have been provided to encourage the user to get in touch with any queries. 

* As a prospective client, I would like to be able to send an online enquiry, so that I can receive additional information.
    * An online enquiry form has been created within the 'Contact Us' section. This has been created to be very easy-to-use, with integrated invalid messages prompted to appear if the user  has missed a required field. 
     * Quick links to the 'Contact Us' page have also been  included in the footer and in the header (hero image banner CTA) of each page. 
     * By encouraging the user to contact the company in many ways, a strong approachable message is conveyed. 

* As a prospective client who would prefer to speak over the phone rather than email, I would like to be able to request a call-back to an online enquiry and clearly be able to view a telephone number and call-times.
    * A preferred method of contact can be specified on the online enquiry form. 
    * The company's contact telephone number is also visable on the footer of each page.
    * The compnay's contact telephone number with the message 'Want To Chat? So Do We!' is displayed on the 'Home' & 'Contact Us' page. 

* As a prospective client, I would like to view a portfolio of past work, so that I can know what to expect.  
    * A dedicated Portfolio' page has been created.
    * 'Award-Winning Gardens' are displayed first, showing the company's greatest acheivements.
    * 'Our Recent Creations' shows an additional six garden designs with a date and discription included. 
    * A variety of residential and commerical designs have been included to give a well-rounded representation of the company. 
    * A CTA on the hero image banner enourages the user to contact the compnay if they have any additional questions. 

* As a prospective client who is knowledgeable in horticulture, I would like to see proof that the company are plant experts as this is important to me in garden design. 
    * Portraying a strong message of plant knowledge was taken into consideration when creating every page. 
    * The company is branded as 'plant-first landscapers'; a message which is portrayed in the footer and the header blurb (under-neath the hero image banner) of pages. 
    * In the 'About' page, the user can learn about the employeees and their skills which are displayed using progress bars. 
    * In each creation listed on the 'Portfolio' page, all horticultural aspects of the projects are described. 

* As a prospective client who is not knowledgeable in garden design, I would like to see what options are available to me so that I can decide if this company is right for me.  
    * All services provided by the company are listed in the 'About Us' web page. 
    * All services provided and company description are included on the footer of each page. 
    * The company's past creations are viewable in the 'Portfolio' page. This gives an in-depth overview of the standard of work which can be expected. 
    * Testimonials are viewable on the 'Home' page, which give positive feedback on the company, showcasing how approachable the company is. 
    

* As an existing client and admirer of the company, I would like to be able to connect and follow the company through social media platforms, so that I build a connection with the brand.
    * Quick links to the compnay's social media platforms are viewable on the footer of each page. 


#### Buisiness Stories

* As a team member, I want to see my skills and strengths clearly defined in an 'About' section so that our clients will know I'm qualified.
    *
    *

* As a team member who deals with enquiries, I want to to know the user's name, phone number and email address so that I can get in contact with them.
    *
    *

* As a designer, I do not want prices to be posted online as quotes differ greatly dependending on the project and I really need to talk to the client first.
    *
    *

* As the CEO, I want all of our acheivements and past creations to be featured online. 
include testing grid for compatibility 
    *
### Browsers
    
The site's reponsiveness was continuously monitored during the development stage using Chromes Dev Tools. Further testing was done using Responsive Test Tool which allowed for testing on additional devices.
Responsiveness was also tested using the Lambdatest App.
### Responsiveness / Mobile Friendly

### W3C Validation
The validity of each page's HTML code was checked using [The W3C Markup Validation Service](https://validator.w3.org/).
The following code changes were made to satisy the validator:

* In index.html
    * Within the ul element, all h4 and a href elements were removed 
    * within the navbar-toggler class button element, the aria-controls attribute was corrected.

* contact.html
    * Within the contact form, the legend was replaced with a div.


The validity of the CSS code was checked using [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).
No errors were found.


----------------------------

## Deployment

The website was hosted on Github Pages. It was deployed by carrying out the following steps:

1. login into Github
2. Select the respository from profile
3. go to 'settings' in respo
4. In 'Github Pages' choose 'Master Branch' as Source and save.

The Live site deployed can be viewed on the following link: [Living Landscapes](https://emmahartedev.github.io/living-landscapes/)

### Local
To run locally, the following steps can be followed:

1. Visit the following Github repository [Github - Living Landscapes](https://github.com/emmahartedev/living-landscapes).
2. Clone or download the repository to an editor of your choice.
3. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

----------------------------

## Credits 

### Content
All content was written and developed by me.

### Code
The following websites were used for inspiration and assistance:

* [CSS Tricks](https://css-tricks.com/)
* [Awwwards](https://www.awwwards.com/)
* [Stack Overflow](https://stackoverflow.com/)

###  Media
The images used on this site are royalty free and were obtained from the following websites:

* [Unsplash](https://unsplash.com/)
* [Pexels](https://www.pexels.com/de-de/)
* [Pixabay](https://pixabay.com/de/)

### Acknowledgements
I would like to thank my Code Institute mentor, Mark Railton for his support and guidance throughout this project. 