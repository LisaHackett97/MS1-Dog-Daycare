# Freyas Dog Daycare
Code Institute User centric module milestone project MS1

Freyas Dog Daycare name is a fictional site for a dog cay care site, for anyone who wants to socialise their dog and provide company so dog is not alone. Focus is on small dogs and puppies.
Primary goal of the site for a user to find out details of the service offered, including opening hrs, prices and staff experience.
Primary goal of the site owner to encourage visitors to make contact and book services for their small dog or puppy.

# Table of Contents
- [UX](#ux)
    - [External User Goals](#external-user-goals)
    - [Site Owner Goals](#site-owner-goals)
    - [Strategy and Scope](#strategy-and-scope)
    - [Structure](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
        - [Colors](#colors)
        - [Typography](#typography)
        - [Images](#images)
- [Features](#features)
- [Technologies](#technologies-used)
- [Testing](#testing)    
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)    
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-during-development)
    - [Bugs](#bugs)
    - [Performance testing](#performance-testing)
    - [Code Validation](#code-validation)
- [Deployment](#deployment)
- [Credits](#credits)




---

# UX

## External User goals
### As a prospective user, I want to
- Be able to view the site on mobile/desktop/tablet.
- Be able to access all pages and navigate without confusion, without too many clicks.
- Be able to find information about services offered.
- Find out where the business is located.	
- How my dog is cared for.
- Opening hours and prices, so I can make informed decision. 
- Be able to enquire/book services online.
- Look at pictures of dogs in the day care.



## Site Owner goals
### As site owner I want: 
- Users to contact us: either online or telephone.
- Users to contact us to book 1 or more dogs into the day care.
- Users to be able to view recommendations. 
- To increase business/bookings.
- Showcase dogs having fun in a safe friendly environment.
- To show where business is located and show services offered.

## Strategy and scope.
Looking at both strategy and scope of the project, I referred back to the user stories, which helped in planning out the project. 
On the strategy plane, I did some research looking at similar business types, and identified what worked well and not so well on the sites from a UX perspective. 
One main difference between sites was how easy it was to find relevant information. For my site, I listed out the opportunities/problems and how each of these might be addressed. 
And for the scope plane, I planned out the content and functional requirements.

[strategy and scope tables](readme-assets/strategy%20and%20scope.pdf)


## Structure of the website
The structure of the site is designed to be easy to navigate, on all device sizes. The nav bar includes an icon identifying the business, which will bring user back to home page, and a menu to link to all pages.
As one of the main goals of the site owner is to encourage contact, to increase business, an easy to use contact form is included. Each page will include a CTA button, 
which will bring user to the contact form.
Address of the business to be included in the header/nav bar to highlight location and contact phone number, but some information to be hidden on small screen sizes.
Some information, such as maps to be hidden on smaller screen sizes so as not to present user with overload of info on the small screen.

## Wireframes
These were built using balsamiq.
[Wireframe Link](readme-assets/Wireframe%20Doggy%20day%20care.pdf)

## Surface

### Colors
The main colours I used are:
* Main text content  #373f47
* Other text #8B2760
* Background of pages  rgba(143, 160, 260, .1), rgba(74, 220, 226, 0.2)
* Other background #81b3d5
* Table background rgba(245, 230, 244, 0.8)
* Hover on menu items #81b3d5, with background #8B2760.


### Typography
I had planned to use Open Sans as a header and Lora for main text. I made a design decision during implementation and have decided to use the following fonts:
* Roboto Slab for main content.
* Lora for headers and nav bar text content.
* The font serif was used as a backup.

### Images
I used images from unsplash.com and pexels.com. Credited in the credits section.
One image was my own. 
The number of images and decision to hide or not on smaller screens changed during the development of the site. All images are visible on all screens.

# Features

The site consists of three pages accessible from a navigation menu. Home/Gallery/More Info (services)
#### Website has the following features:
##### Header which contains the following:
* Icon for business, which is a clickable link to bring user back to home page.
* Address and phone number for business, which is hidden on some screen sizes. Allows user to quickly view where business is located.
* Navigation menu. Allows user to navigate to all pages on the site.

##### Navigation menu: contains links to all three pages of site. collapses to a burger menu icon on smaller screens.
    *Home: allows user to click and go to the main home page.
    *Gallery:allows user to click and go to gallery page to view images.
    *More Info: This page was renamed more info on the nav menu, to be more intuive for users. 
        The html page which more info menu item is linked to is called services.

##### Footer: contains business phone number and links to social media sites. Link for youtube hidden on xs small screen sizes.
    *A short message is included on large screens.
    *Users can click on social media links for the business (generic websites used.). 
    *Links will open in seperate pages.

##### Title and short quote on each page. The quote transitions in when page is opened.

##### CTA button: "Contact us" button is contained on all three pages. 
    * allows user to click and go to the contact form, contained on the services page.
    * It is included at top of services/more info page, so that user does not have to scroll through all the content on the page, 
      if their goal is simply to contact the business.

#### Above features are consistent across all three pages.

#### Home page

##### Three images included, aligned to left. One imge for each section of content.
    
##### Three sections covering why, what business does and who the people are. 
    * allows the user to read more about the business and what it does.

##### The header for each section has an icon to draw the eye in and give a visual clue as what the content is about. 
     The why section has a home icon, the who we are section has a people icon and the what we do has a paw icon.

#### Gallery page
    * Allows users to view dog images with some recommendations throughout the page.

#### Services page.
    * This page is called More Info in the Navigation menu, as I felt it would be more intuitve for a user.The page gives additional information as well as list of prices/times.

##### Tables- allows user to view options for daycare and the relevant prices.
    * allows user to view drop off/pick up times.

##### CTA button included near top of page.
    * allows user to go to contact form.

##### Contact form
    *allows user to get contact, with options for why they are getting in contact. Submit button will bing user back to home page. Name/email/phone number are required.

##### Iframes: google map to business location. Map used is my local town/beach. It is only visible on large screens.

##### Links to animal charities included, with dog icon to left of text for visual appeal.It is only visible on large screens.Links will open in seperate pages.

# Future Features
Modal pop up when form submitted.
Gallery: Images are clickable and recommendation pop up when each clicked.

[Back to table of contents](#table-of-contents)

# Technologies Used

* HTML5 - Programming language for structuring the site.
* CSS3- Style sheet programming language
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) Use as a framework for layout and responsiveness.
* [Font Awesome](https://fontawesome.com/) -used to provide icons across the site.
* [Google fonts](https://fonts.google.com/) -used to select and provide typography.
* [Github](https://github.com/)-  software hosting platform to keep project in a remote location
* [Gitpod](https://gitpod.io/) - a development hosting platform
* Git - used for version-control.
* [Balsamiq](https://balsamiq.com/) - used to build wireframes. Downloaded software to use.
* Chrome Dev Tools - used to view responsiveness and layout as site was being developed. I found this very useful when developing the site, as it aided my learning throughout the project.
* [Image optimizer](http://www.imageoptimizer.net/Home.aspx) -used to optimize size of images used on the site
* [Tinypng](https://tinypng.com/) - used to optimize size of images used on the site

[Back to table of contents](#table-of-contents)
# Testing

## Functionality Testing

## Compatibility Testing
## User stories Testing


## Issues during development

## Bugs

## Performance Testing

## Code Validation


[Back to table of contents](#table-of-contents)

# Deployment

# Credits

### Media
##### icons
    * Puppy icon: credit [Creaticca-Flaticon.com](https://www.flaticon.com/authors/creaticca-creative-agency)
    * All other icons, including burgr menu icon,taken from fontawesome. 
##### Images
    [Pexels Images](https://pexels.com)

        Image Name | Photo credit
        ---------- | ------------
        dog in cup | Photo: Pixabay        
        gallery small dog playing | Pixabay
        two dogs  | Sebastian Coman Travel
        Gallery dog and paw | Karolina Grabowska
    
    [Unsplash Images](https://unsplash.com)
        Image Name|Photo credit
        ----------|------------
        g2-dog and woman|Photo by Tamas Pap
        g2-white-dog-running  | Joe Caione
        gallery-dog-on-grass  | anaminella
        gallery-dog-run | arjan_stalpers
        gallery-dogs-sleeping | BRUNO EMMANUELLE
        gallery-pug-yawning  | Charles Deluvio
        human and dog  | Anna Dudkova

    gallery Freya1 my own photo


#### content
##### Inspiration for content:
    * (https://blog.homesalive.ca/dog-blog/benefits-of-dog-daycare)
    * (https://pawcastle.com/benefits-of-doggy-day-care/)
    * (https://www.thebalancecareers.com/how-to-start-a-doggie-day-care-business-125525)
    * (https://www.pets4homes.co.uk/pet-advice/doggy-daycare-what-is-it-and-is-it-a-good-idea-for-your-own-dog.html)

##### Quotes
    * (https://sharpquotes.com/dog-quotes/)
    * (https://www.shutterfly.com/ideas/dog-quotes/)  


#### Code
* How to link to id on another page: Tutorial html links on [quackit.com](https://www.quackit.com/)
* Code for animations from article on [geeksforgeeks.org](https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css)

#### Map
Source code taken from settings on google maps.
* [Google Maps]("https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d13537.704603233597!2d-6.061830386757101!3d53.14339023410205!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sie!4v1616866569241!5m2!1sen!2sie")

#### Acknowledgements
    ##### Knowledge and help. 
        * Code Institute course material
        * [w3schools.com](https://www.w3schools.com)
        * [Bootstrap documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
        * [Inspiration and help for gallery layout](https://bootsnipp.com/search?q=gallery)
        * Slack Community - I searched for a topic and usually someone else had the same question. This has been a great help in developing my understanding.
        * StackoverFlow - I had an issue with a button not working with link, was ableto find where people had previously asked and answered this query.





