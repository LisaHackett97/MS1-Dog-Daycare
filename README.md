# [Freyas Dog Daycare](https://lisahackett97.github.io/MS1-Dog-Daycare/?target="_blank">)


![Site-Mockup](readme-assets/mock-up.png)

Freyas Dog Daycare name is a fictional site for a dog cay care site, for anyone who wants to socialise their dog and provide company so dog is not alone. Focus is on small dogs and puppies.
Primary goal of the site for a user to find out details of the service offered, including opening hrs, prices and staff experience.
Primary goal of the site owner to encourage visitors to make contact and book services for their small dog or puppy.

**To open any links in a new tab, please press Ctrl + click**


## Table of Contents

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
  - [Performance and Accessibility testing](#performance-and-accessibility-testing)
  - [Code Validation](#code-validation)
- [Deployment](#deployment)
- [Credits](#credits)

---

## UX

### External User goals

#### As a prospective user, I want to

- Be able to view the site on mobile/desktop/tablet.
- Be able to access all pages and navigate without confusion, without too many clicks.
- Be able to find information about services offered.
- Find out where the business is located.
- How my dog is cared for.
- Opening hours and prices, so I can make informed decision.
- Be able to enquire/book services online.
- Look at pictures of dogs in the day care.

### Site Owner goals

#### As site owner I want

- Users to contact us: either online or telephone.
- Users to contact us to book 1 or more dogs into the day care.
- Users to be able to view recommendations.
- To increase business/bookings.
- Showcase dogs having fun in a safe friendly environment.
- To show where business is located and show services offered.

### Strategy and scope

Looking at both strategy and scope of the project, I referred back to the user stories, which helped in planning out the project.
On the strategy plane, I did some research looking at similar business types, and identified what worked well and not so well on the sites from a UX perspective.
One main difference between sites was how easy it was to find relevant information. For my site, I listed out the opportunities/problems and how each of these might be addressed.
And for the scope plane, I planned out the content and functional requirements.

[strategy and scope tables](readme-assets/strategy%20and%20scope.pdf)

### Structure of the website

The structure of the site is designed to be easy to navigate, on all device sizes. The nav bar includes an icon identifying the business, which will bring user back to home page, and a menu to link to all pages.
As one of the main goals of the site owner is to encourage contact, to increase business, an easy to use contact form is included. Each page will include a CTA button,
which will bring user to the contact form.
Address of the business to be included in the header/nav bar to highlight location and contact phone number, but some information to be hidden on small screen sizes.
Some information, such as maps to be hidden on smaller screen sizes so as not to present user with overload of info on the small screen.

### Wireframes

These were built using balsamiq.
[Wireframe Link](readme-assets/Wireframe%20Doggy%20day%20care.pdf)

### Surface

#### Colors

The main colours I used are:

- Main text content #373f47
- Other text, including header and footer content #771851.
- Background of pages rgba(221, 229, 240, 0.6)
- Other background #c4d7ed
- Table background rgba(245, 230, 244, 0.8)
- Hover on menu items #c4d7ed, with background #771851.
- Header and footer background #c4d7ed

#### Typography

I had planned to use Open Sans as a header and Lora for main text. I made a design decision during implementation and have decided to use the following fonts:

- Roboto Slab for main content.
- Lora for headers and nav bar text content.
- The font serif was used as a backup.

#### Images

I used images from unsplash.com and pexels.com. Credited in the credits section.
One image was my own.
The number of images and decision to hide or not on smaller screens changed during the development of the site. All images are visible on all screens.

[Back to table of contents](#table-of-contents)

## Features

The site consists of three pages accessible from a navigation menu. Home/Gallery/More Info (services)

**_Website has the following features_**

### Header

contains the following:

- Business icon and name: a clickable link to bring user back to home page.
- Menu bar: Allows user to navigate to gallery and services pages, and to the contact form.

### Navigation menu

- Contains links to all gallery and services pages of site. collapses to a burger menu icon on smaller screens.(Home page is accessed by clicking icon on left side)
- Gallery: allows user to click and go to gallery page to view images.
- More Info: This page was renamed more info on the nav menu, to be more intuive for users.
- The html page which the more info menu item is linked to, is called services.
- Contact option on the menu will bring user to to the contact form on the services page.

### Footer

- Contains business phone number and links to social media sites.
- Contains business name and address.
- Users can click on social media links for the business (generic websites used.).
- Links will open in seperate pages.

### Title

- The page title and short quote on each page. The quote transitions in when page is opened.

### CTA button

- **"Contact us"** button is contained on all three pages

  - Allows user to click and go to the contact form, contained on the services page.
  - It is included at top of services/more info page, so that user does not have to scroll through all the content on the page,
    if their goal is simply to contact the business.
  - The CTA button is included at the bottom of the home and gallery pages.

**_Above features are consistent across all three pages_**

### Home page

- Three images included

These are aligned to left. One image for each section of content.

- Three content sections

These cover why choose this type of business, what business does and who the people are.

Allow the user to read more about the business and what it does.

- Icons

  - The header for each section has an icon to draw the eye in and give a visual clue as what the content is about.
  - The why section has a home icon, the who we are section has a people icon and the what we do has a paw icon.

### Gallery page

- Allows users to view dog images with some recommendations throughout the page.
- CTA button included

### Services page

This page is called More Info in the Navigation menu, as I felt it would be more intuitve for a user.The page gives additional information as well as list of prices/times.

#### Tables

- Allows user to view options for daycare and the relevant prices.
- Allows user to view drop off/pick up times.

#### CTA button is included near top of page

#### Contact form

- Allows user to get contact, with options for why they are getting in contact. Submit button will bring user back to home page. Name/email/phone number are required. Booking option is prechecked.

#### Iframes

- google map to business location. Map used is my local town/beach. It is only visible on large screens.
- a link is included below the iframe so that if browser doesn't support the iframe, data can still be retrieved by user.
- Link to google maps is included in small and medium sized screens.

#### External Links

- Links to animal charities included, with dog icon to left of text for visual appeal. It is only visible on large screens. Links will open in seperate pages.

### Future Features

- Modal pop up when form submitted.
- Gallery: Images are clickable and recommendation pop up when each clicked.
- Pop up modal when phone number in header and footer selected.

[Back to table of contents](#table-of-contents)

## Technologies Used

- HTML5 - Programming language for structuring the site.
- CSS3- Style sheet programming language
- [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) Use as a framework for layout and responsiveness.
- [Font Awesome](https://fontawesome.com/) -used to provide icons across the site.
- [Google fonts](https://fonts.google.com/) -used to select and provide typography.
- [Github](https://github.com/)- software hosting platform to keep project in a remote location
- [Gitpod](https://gitpod.io/) - a development hosting platform
- Git - used for version-control.
- [Balsamiq](https://balsamiq.com/) - used to build wireframes. Downloaded software to use.
- Chrome Dev Tools - used to view responsiveness and layout as site was being developed. I found this very useful when developing the site, as it aided my learning throughout the project.
- [Image optimizer](http://www.imageoptimizer.net/Home.aspx) -used to optimize size of images used on the site
- [Tinypng](https://tinypng.com/) - used to optimize size of images used on the site
- Scripts included to enable menu on small screens to work as expected.
  - <http://code.jquery.com/>
  - [bootstrap cdn js](https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js)
- Unicorn revealer extension was helpful when developing the site
- WAVE extension for reviewing accessibility and colour contrasts in testing.

[Back to table of contents](#table-of-contents)

## Testing

### Functionality Testing

Site was viewed in xs, small, medium, large and extra large sizes on Chrome and Edge browsers, using dev tools.

- One image not displaying. Issue resolved by correcting file path.

  - Site now rendering as expected.
  - Testing made 1 bug clear: active menu item is not showing as expected. Documented in Bugs section. Not a browser issue.

- Site then viewed in landscape mode on xs, small, medium, large and extra large sizes on chrome and edge.

  - One issue: fieldset was showing too narrow in landscape, with elements overflowing.
  - Resolved by changing the bootstrap class on fieldset to col-sm-8 and removing the max-width css property.

- Menu/Nav bar items manually tested on all pages

  - Paw/business icon on left: click and will brings user back to home page
  - Gallery menu item: click and will brings user to gallery page
  - More Info menu item: click and will brings user services/more info page.
  - Contact menu items: click and will bring user to the contact form.

- Footer social media links tested on all pages.

  - Click and each opens to the correct web page, and opens in a new tab.

- Contact Us button on all pages.

  - Click and brings user to the contact form on the services page.

- Four links to external animal charities on services page, only on larger sized screens

  - Click and each opens to the correct web page, and in a new tab.

- Form on services page.

  - Negative testing by clicking Send Form button without fields being updated.
  - Form will not "send" unless Name, Email and Phone Number are updated. Phone number must also be numeric
  - Once these are updated, by clicking send form, user will be brought back to the home page.
  - Reason for contact is a prechecked field.

- Link under Iframes map: this is an alternative for user where the map does not load.
  - Link was opening in same page as site. target="\_blank" added to link. Issue resolved.

### Compatibility Testing

- Site was manually tested on google chrome, microsoft edge and IE on windows 10. No issues.
- Site was also checked on other browsers using the following site [lambatest](https://www.lambdatest.com/) Browsers checked included firefox, opera, firefox and safari.
  - Site displaying as expected.

[Back to table of contents](#table-of-contents)

### User stories Testing

#### As a prospective user, I want to

- Be able to view the site on mobile/desktop/tablet.
  - User can view the site on mobile/tablet/laptop/desktop screensizes without issues.
  - I have added some line breaks within the paragraphs of content. This enables user to more easily view content, especially on smaller mobile devices.

- Be able to access all pages and navigate without confusion, without too many clicks.

  - User can click on menu, which is fixed to top of all pages, to access the pages of the site.
  - Business icon can be clicked to bring user back to home page.
  - One to click to access any of the pages on the site
  - One click to go to contact form

- Be able to find information about services offered.
  
  - Services page is labelled "more info" in the menu bar, which user can navigate to for further information which is not provided on the home page.
  - A Contact form is provided, if a user has questions which are not answered on the site. Link to this is included in the menu bar.

- Find out where the business is located.

  - Address and phone number are provided in the footer on all three pages. Decision to include in footer so that it did not have to be hidden on smaller screen sizes.
  - On large screen sizes, a map showing the business location is provided on the "more info" page.
  - On medium and smaller sized screens, a link to the map is provided below the contact form.

  
- Find out how my dog is cared for.
  - Home page gives on overview of what happens in dog daycare and the staff involved
  - The more info page provides the following sections
    - Your dogs day: which gives details on the days structure
    - About Us: gives further details on the staff training.

- Find out what are the opening hours and prices, so I can make informed decision.
  - At the top of the More Info page, two tables are provided, giving prices and also times for drop-offs and pickups.

- Be able to enquire/book services online.
  - A contact form is provided on the services/more info page, which can be access through menu bar and cta buttons provided on all pages, for quick and easy access. This form requires users to give a reason for contact: booking a service/asking a question/other. Space is provided for user to give more details on the query.
  - Social media links are also provided in the footer, which would enable user to contact business through these sites. 

- Look at pictures of dogs in the day care.
  - Three images are provided on the home pages, aligned with each section of content.
  - Gallery page is provided for users to eacily access with one click. This page shows images of dogs, along with three recommendations.

#### As site owner I want

- Users to contact us: either online or telephone.
  - User can access the contact form on the More info page, either by selecting the Contact menu item, the contact Us button provided on each page, or by scrolling down on the more info page.
  - Phone number is provided in the footer on all three pages.

- Users to contact us to book 1 or more dogs into the day care.
  - Users can contact the business by phoning or using the contact form. Contact form has a booking option provided.
  - Table containing prices at top of more info/services page, provides details of cost for a 2nd dog.

- Users to be able to view recommendations.
  - Recommendations can be viewed on the gallery page, between each section of images.

- To increase business/bookings.
  - Site provides a "why dog daycare" section on the home page. This section is intended to give users more information around dog daycare, with the aim of increasing business for users who mya not have been aware of the advantages of the business.

- Showcase dogs having fun in a safe friendly environment.
  - Images are provided on home and gallery pages showing happy, playful small dogs.

- To show where business is located and show services offered.
  - Address provided in footer on all three pages.
  - Location map is provided on large screen size, on the more info/services page.
  - Link to location map is provided on medium and smaller sized screens, below the contact form.
  - Table are provided at top of the more info page giving details of service and prices.
  - Contact form will also enable a user to get in touch if they have further questions on services.

[Back to table of contents](#table-of-contents)

### Issues during development

At the beginning of the project I had issues using bootstrap to make the pages responsive on different screens. I needed to look again at bootstrap videos to aid my understanding.
As development on the site progresses, issues decreased as my knowledge and understanding increased.

Burger menu was not appearing after I had added a background color to the nav bar. An icon was needed, which I took from fontawesome.
Buger menu was not opening and showing menu links as expected. Scripts for jsquery/popper needed to be added to end of HTML page.
Both these issues were resolved after searching slack and stackoverflow, where other users previously had same issues.

Layout of gallery page was an issue. I had tried to layout the page as per the wireframe.
However, the icons and images did not look well on different screens.
While a second layout looked better and was more responsive, after advice from my mentor I looked at snippets for inspiration.
Decided to use a simpler, more structured layout.Removed icons which I orignally had included on the page.

Footer contents on small screens were wrapping and not staying inline.
After inspecting it with chrome dev tools, I realised the screen size I was looking at was under the px size for the breakpoint for sm screens.
Needed to take into account XS size screens, for older phones and display the contact number as block, and only display the text on larger screens.

Use dev tools to check placement of items in Header and footer
Decided to use obligue on brand name text,and not on main business name. Decided to keep brand name on smaller sizes, to keep the business name on screen for user.
I orignally wanted to use a warm yellow colour for the header/footers. However this colour did not view well on a higher resolution screens.
Could not find an appropriate shade with contrasting colour for text that worked well on all screens. Therefore decided to change the yellow for a blue shade.

Following advice from my mentor, I moved the contact form and iframe maps to the more info page, and re-arranged layout of elements on home page.
Home page looks visually better, and structure makes more sense.

[Back to table of contents](#table-of-contents)

### Bugs

- I did a manual review of css code. The hover of the brand icon was not sorking as expected. background colour was not changing. I has a linear gradient defined inthe rule. Once this was removed, and background colour set to the #8B2760, icon displays as expected on hover.

- After adding a 4th social media icon to the footer, there was overlap of elements on xs screen sizes. Spacing between social media icons needed to be reduced.
- Contact number was wrapping on screens under 329px. Corrected this by removing font size rule from footer element.
- There was a gap showing at right side of footer on some screens. Changed footer container to container-fluid.

[Screenshots](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/bugs-screenshots.pdf/) for above Bugs.

- Inspection of site of diff browser sizes showed that the bottom border on active menu bar was not responsive, when menu collapsed.
  It was appearing too large in comparison to the menu text on some medium screens, and too small on smaller screen sizes.

  - resolved by changing div containing menu anchor elements from col-3 col-md-4 to col-3 col-md-2 col-lg-4
    col-3 col-md-4

- Links in footer were showing as accessibility errors with WAVE. Added sr class with details to resolve. Footer appearing as expected.

- Placeholder text was not appearing. Resolved by putting the closing textarea tag on same line.

#### HTML Code Validation Bugs

- Review of image attributes:
  Updated the alt attributes to be more descriptive

- Image names: I had spaces in names of images. These showed as errors on the W3 validator check.

  - Removed spaces from image names and updated file path in the index.html page.
  - Reviewed names of images on gallery page before running validator. Two of these images had spaces. Replaced space with hyphen and updated file paths on the gallery.html page.
  - Checked all images to ensure they were still displaying correctly.

- Element smaller was used on text in the heading and caused a validation error.

  - The element was not changing anything on the text and as text looked ok, I removed the **_smaller_** tag.

- Stray script error on index.html: Was caused by my two scripts being outside body of html. Once I moved these inside the closing body tag, it corrected the validation error.

  - Moved scripts on gallery.html and services.html. Tested burger menu, and it is still working as expected.

- Iframes validation error showing if there is text between the iframe tags. I had included text to cover if map did not load.

  - to correct validation error: removed text from iframe tag. Added a link below map for users to click on

- Error on contact form button: Input not allowed as a descendant.
  - Removed input element and added class and type to the button.
  - Had to add id to the element in order for it to style as required

[Validation of HTML](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/Html-validation-checks.pdf/)

#### Bugs when viewing in Chrome and Edge Browsers

- One image not displaying on live site in Edge. checked and was the same issue in Chrome.

  - Resolved as file path was not correct.

- Fieldset too narrow in landscape mode, elements were overflowing.
  - Resolved by setting bootstrap columns to 8 on small screen sizes and removing max-width property from css rule.

- Lighthouse report on services page showing an issue where the tap target is not appropriately sized for mobiles. This is the radio list on the contact form. 
- Prechecked button on form is showing as default colour.
  - Both these issues were resolved by changing css styles on the input[type="radio"]:checked:after. Solution was found on stackoverflow.

[Back to table of contents](#table-of-contents)

#### Bugs not Fixed

- When viewing pages for different devices using chrome dev tools, sometimes the menu bar is showing as overflowing the screen. Last test this happened only on ipad pro device. Screen view for this device was then checked on lambdatest, and was displaying correctly. A smiliar issue had occurred for me previously, but had corrected itself next time I logged on.



[Back to table of contents](#table-of-contents)

### Performance and accessibility Testing

#### Lighthouse testing

- First report run showed issued with images on home page. These were re-optimized and uploaded
- rel attribute added to footer links and meta description added to all 3 pages
- Unresolved Issues affecting Best Practice score
  - unload listener/runtime error when testing/issues with cookies: I do not currently have the knowledge to fix these issues. Score for page is 80. However when report is re-run at a later time, issue is resolved and score is higher.

Attached are the audit reports [lighthouse-reports](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/lighthouse-reports.pdf)

- Reports re-run after user stories were tested.
  - sr class added to links to services page in menu bar. This is because  the .html file is called services, while it is called More info on the screen, to a more intuitive experience for the end user.

-Below are final lighthouse scores on mobile

   ![Lighthouse final mobile reports](readme-assets/final-lighthouse-reports.png)

#### Accessibility

Scores reviewed in lighthouse.

- WAVE extension for further accessibility testing.

  - aria labels added to textarea of form and to the alternative link provided for google maps loction.
  - heading levels used on services page restrucutred.
  - As I heading levels were restructured, it made more sense for the reader to be shown charity links under h5 heading, and more info for dog body signals under h6, as this is providing more information if a user is interested. It might be more important to a user to see charity links first.
  - The two alerts on the services/more info page, are coming from the google maps links. There are two links set up, depending on screensize and if iframe is visible or not. The alert on home page is due to the fact that the last link in menu bar is to contact form, and next link further down on the page, is also to the contact form. 
  - No other WAVE errors or alerts

 ![WAVE reports](readme-assets/WAVE-results.png)

  [Back to table of contents](#table-of-contents)

### Code Validation

I used the following to validate code by direct input:

- html <https://validator.w3.org/>

  - index.html validation. Errors/bugs found and corrected. documented in bugs section. Errors also applied to gallery and services pages.
  - gallery.html valiation. No errors.
  - services.html validation. Errors on iframe and button. Corrected.

Ran the three html pages through the validator again and no issues.

- css <http://jigsaw.w3.org/css-validator/>

  - three errors: font-style rule and overflow rule removed. Not required. Font-family error needed a comma after first font-family was declared
  - Two warnings:
    - First warning was related to imported style sheets not being checked. no action to be taken.
    - Second warning was related to the rgba colour selected for background. Decided to change to simple one colour background.

Re-run file through validator: no errors.

- Contrast Checker <https://webaim.org/resources/contrastchecker/>

  - Contrast between content text and background: no issue.
  - Contrast between headings colours and background: no issue.
  - Contrast between navbar elements and navbar background: Some fails on contrastchecker. (same applied to footers)
  - Contrast colours on charity links buttons had some fails on contrastchecker.

- For the fails, I used lightness adjuster on the contrast checker to select colors that contrasted better and updated CSS code.
- I installed the WAVE extension and rechecked contrast on all three pages. No issues

- [Screenshots for CSS and Color contrast checks](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/CSS-validation-and-contrast-Checks.pdf/)

- Below are the final validation reports
 ![Final validation reports](readme-assets/html-css-validation-final.png)

[Back to table of contents](#table-of-contents)

## Deployment

The project was deployed to GitHub pages using the following steps:

1. Log into GitHub and select the repo.
2. Go to settings
3. Select Pages from vertical menu on left
4. On Source, select Master Branch and click save.
5. Website is now live and the URL will be displayed. [Link to live site](https://lisahackett97.github.io/MS1-Dog-Daycare/)
6. When updates are commited and pushed to GitHub, live site will be updated.

![Deployment of live site screenshot](readme-assets/Deployment.png)

To download and run locally, follow the below steps:

1. Log into GitHub and select the repository, MS1-Dog-Daycare
2. Select Code
3. Click Download Zip
4. Once files have downloaded, you can extract and useclone-project.png locally.

Select this file for screenshot [Run Locally](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/run-project-locally.png)

To Clone, follow the below steps:

1. Log into GitHub and select the repository, MS1-Dog-Daycare
2. Select Code
3. Click https and copy the link
4. Open git bash
5. Change the working directory to where you want the cloned directory
6. Use command git clone and the copied URL
7. Press ente

Select this file for screenshot [Clone repo](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/clone-project.png/)

Forking the repository:

1. Log into GitHub and select the repository, MS1-Dog-Daycare
2. Select Fork on top right hand corner.
3. A copy should be created in your github profile and pull requests submitted.

GitHub docs link [Forking a repository](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop#forking-a-repository/)

[Back to table of contents](#table-of-contents)

## Credits

### Media

#### Icons used

- Puppy icon: credit [Creaticca-Flaticon.com](https://www.flaticon.com/authors/creaticca-creative-agency")
- All other icons, including burger menu icon,taken from fontawesome.

#### Images used

[Pexels Images](https://pexels.com/)

| Image Name                | Photo credit           |
| ------------------------- | ---------------------- |
| dog in cup                | Photo: Pixabay         |
| gallery small dog playing | Pixabay                |
| two dogs                  | Sebastian Coman Travel |
| Gallery dog and paw       | Karolina Grabowska     |

[Unsplash Images](https://unsplash.com)

| Image Name            | Photo credit       |
| --------------------- | ------------------ |
| g2-dog and woman      | Photo by Tamas Pap |
| g2-white-dog-running  | Joe Caione         |
| gallery-dog-on-grass  | ana minella        |
| gallery-dog-run       | arjan_stalpers     |
| gallery-dogs-sleeping | Bruno Emmanuelle   |
| gallery-pug-yawning   | Charles Deluvio    |
| human and dog         | Anna Dudkova       |

Image called "gallery Freya1" my own photo.

### Content

#### Inspiration for content

- <https://blog.homesalive.ca/dog-blog/benefits-of-dog-daycare>
- <https://pawcastle.com/benefits-of-doggy-day-care>
- <https://www.thebalancecareers.com/how-to-start-a-doggie-day-care-business-125525>
- <https://www.pets4homes.co.uk/pet-advice/doggy-daycare-what-is-it-and-is-it-a-good-idea-for-your-own-dog.html>

#### Quotes

- <https://sharpquotes.com/dog-quotes/>
- <https://www.shutterfly.com/ideas/dog-quotes/>

### Colours

coolors.co was originally used to pick colours.
Color picker then used and adjust and pick colours which I felt worked with the site.

### Code

- How to link to id on another page: Tutorial html links on [quackit.com](https://www.quackit.com/)
- Code for animations from article on [geeksforgeeks.org](https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css)
- Code for nav bar and burger menu taken from bootstrap documentation and customized for the site.
- CSS code solution to change colour of radio buttons found on a thread on stackoverflow. (https://stackoverflow.com/questions/4253920/how-do-i-change-the-color-of-radio-buttons)

### Map

Source code taken from settings on google maps.

- [Google Maps]("https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d13537.704603233597!2d-6.061830386757101!3d53.14339023410205!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sie!4v1616866569241!5m2!1sen!2sie")

### Acknowledgements

I referred to the following to add to my knowledge and for help.

- [Bootstrap documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- Code Institute course material
- [w3schools.com](https://www.w3schools.com)
- [Inspiration and help for gallery layout](https://bootsnipp.com/search?q=gallery)
- Slack Community - I searched for a topic and usually someone else had the same question. This has been a great help in developing my understanding.
- Stackoverflow.com - I had an issue with a button not working with link, was ableto find where people had previously asked and answered this query.

- Thank you to my mentor Adegbenga Adeye

[Back to table of contents](#table-of-contents)

This site was developed for Educational purposes.
