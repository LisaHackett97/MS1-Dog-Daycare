# Freyas Dog Daycare

Code Institute User centric module milestone project MS1

Freyas Dog Daycare name is a fictional site for a dog cay care site, for anyone who wants to socialise their dog and provide company so dog is not alone. Focus is on small dogs and puppies.
Primary goal of the site for a user to find out details of the service offered, including opening hrs, prices and staff experience.
Primary goal of the site owner to encourage visitors to make contact and book services for their small dog or puppy.

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
        - [Performance testing](#performance-testing)
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

## Strategy and scope

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

- Main text content  #373f47
- Other text was #771851.
- Background of pages  rgba(221, 229, 240, 0.6)
- Other background #C4D7ED
- Table background rgba(245, 230, 244, 0.8)
- Hover on menu items #C4D7ED, with background #771851.

### Typography

I had planned to use Open Sans as a header and Lora for main text. I made a design decision during implementation and have decided to use the following fonts:

- Roboto Slab for main content.
- Lora for headers and nav bar text content.
- The font serif was used as a backup.

### Images

I used images from unsplash.com and pexels.com. Credited in the credits section.
One image was my own.
The number of images and decision to hide or not on smaller screens changed during the development of the site. All images are visible on all screens.

[Back to table of contents](#table-of-contents)

## Features

The site consists of three pages accessible from a navigation menu. Home/Gallery/More Info (services)
***Website has the following features***

### Header

contains the following:

- Icon for business, which is a clickable link to bring user back to home page.
- Address and phone number for business, which is hidden on some screen sizes. Allows user to quickly view where business is located.
- Navigation menu. Allows user to navigate to all pages on the site.

### Navigation menu

- Contains links to all three pages of site. collapses to a burger menu icon on smaller screens.
- Home: allows user to click and go to the main home page.
- Gallery:allows user to click and go to gallery page to view images.
- More Info: This page was renamed more info on the nav menu, to be more intuive for users.
        The html page which more info menu item is linked to is called services.

### Footer

- Contains business phone number and links to social media sites. Link for youtube hidden on xs small screen sizes.
- A short message is included on large screens.
- Users can click on social media links for the business (generic websites used.).
- Links will open in seperate pages.

### Title

- The page title and short quote on each page. The quote transitions in when page is opened.

### CTA button

#### "Contact us" button is contained on all three pages

- Allows user to click and go to the contact form, contained on the services page.
- It is included at top of services/more info page, so that user does not have to scroll through all the content on the page,
      if their goal is simply to contact the business.

***Above features are consistent across all three pages***

### ***Home page***

#### Three images included

These are aligned to left. One image for each section of content.

#### Three content sections

These cover why choose this type of business, what business does and who the people are.

- Allows the user to read more about the business and what it does.

#### Icons

- The header for each section has an icon to draw the eye in and give a visual clue as what the content is about.
- The why section has a home icon, the who we are section has a people icon and the what we do has a paw icon.

## Gallery page

- Allows users to view dog images with some recommendations throughout the page.

## Services page

 This page is called More Info in the Navigation menu, as I felt it would be more intuitve for a user.The page gives additional information as well as list of prices/times.

### Tables

- Allows user to view options for daycare and the relevant prices.
- Allows user to view drop off/pick up times.

#### CTA button included near top of page

- Allows user to go to contact form.

#### Contact form

- Allows user to get contact, with options for why they are getting in contact. Submit button will bring user back to home page. Name/email/phone number are required.

#### Iframes

- google map to business location. Map used is my local town/beach. It is only visible on large screens.

#### External Links

- Links to animal charities included, with dog icon to left of text for visual appeal. It is only visible on large screens.Links will open in seperate pages.

## Future Features

- Modal pop up when form submitted.
- Gallery: Images are clickable and recommendation pop up when each clicked.
- Contact Form: Make reason for booking (radio items) required so that user must select one option.
- Pop up modal when phone number in header and footer selected.

[Back to table of contents](#table-of-contents)

## Technologies Used

- HTML5 - Programming language for structuring the site.
- CSS3- Style sheet programming language
- [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) Use as a framework for layout and responsiveness.
- [Font Awesome](https://fontawesome.com/) -used to provide icons across the site.
- [Google fonts](https://fonts.google.com/) -used to select and provide typography.
- [Github](https://github.com/)-  software hosting platform to keep project in a remote location
- [Gitpod](https://gitpod.io/) - a development hosting platform
- Git - used for version-control.
- [Balsamiq](https://balsamiq.com/) - used to build wireframes. Downloaded software to use.
- Chrome Dev Tools - used to view responsiveness and layout as site was being developed. I found this very useful when developing the site, as it aided my learning throughout the project.
 [Image optimizer](http://www.imageoptimizer.net/Home.aspx) -used to optimize size of images used on the site
- [Tinypng](https://tinypng.com/) - used to optimize size of images used on the site
- Scripts included to enable menu on small screens to work as expected.

        - (http://code.jquery.com/)
        - [bootstrap cdn js](https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js)
- Unicorn revealer extension was helpful when developing the site
- WAVE extension for reviewing accessibility and colour contrasts in testing.

[Back to table of contents](#table-of-contents)

## Testing

### Functionality Testing

- Site was viewed in xs, small, medium, large and extra large sizes on Chrome and Edge browsers, using dev tools.
        - One image not displaying. Issue resolved by correcting file path.
        - Site now rendering as expected.
        - Testing made 1 bug clear: active menu item is not showing as expected. Document in Bugs section. Not a browser issue.

- Site then viewed in landscape mode on xs, small, medium, large and extra large sizes on chrome and edge.
        - One issue: fieldset was showing too  narrow in landscape, with elements overflowing.
        - Resolved by changing the bootstrap class on fieldset to col-sm-8 and removing the max-width css property.

- Menu/Nav bar items manually tested on all pages
    Paw/business icon on left: click and will brings user back to home page
    Home menu item: click and will brings user back to home page
    Gallery menu item: click and will brings user to gallery page
    More Info menu item: click and will brings user services/more info page.

- Footer social media links tested on all pages.
    Click and each opens to the correct web page, and opens in a new tab.

- Contact Us button on all pages.
    Click and brings user to the contact form on the services page.

- Four links to external animal charities on services page, only on larger sized screens
    Click and each opens to the correct web page, and in a new tab.

- Form on services page.
    Negative testing by clicking Send Form button without fields being updated.
    Form will not "send" unless Name, Email and Phone Number are updated.
    Once these are updated, by clicking send form, user will be brought back to the home page.
    "reason for contact" is not yet a required field.

- Link under Iframes map: this is an alternative for user where the map does not load.
    Link was opening in same page as site. target="_blank" added to link. Issue resolved.

## Compatibility Testing

Site was manually tested on google chrome, microsoft edge and IW on windows 10. No issues.
Site was also checked on other browsers using [lambatest](https://www.lambdatest.com/) Browsers checked included firefox, opera, firefox and safari. Site displaying as expected.

## User stories Testing

## Issues during development

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

## Bugs

- I did a manual review of css code. The hover of the brand icon was not sorking as expected. background colour was not changing. I has a linear gradient defined inthe rule. Once this was removed, and background colour set to the #8B2760, icon displays as expected on hover.

- After adding a 4th social media icon to the footer, there was overlap of elements on xs screen sizes. I have hidden the youtube icon link on these screen sizes.
- Contact number was wrapping on screens under 329px. Corrected this by removing font size rule from footer element.
- There was a gap showing at right side of footer on some screens. Changed footer container to container-fluid.

Bugs [Screenshots](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/bugs-screenshots.pdf)

- Inspection of site of diff browser sizes showed that the bottom border on active menu bar was not responsive, when menu collapsed.
It was appearing too large in comparison to the menu text on some medium screens, and too small on smaller screen sizes.
        - resolved by changing div containing menu anchor elements from col-3 col-md-4 to col-3 col-md-2 col-lg-4
    col-3 col-md-4

- Links in footer were showing as accessibility errors with WAVE. Added sr class with details to resolve. Footer appearing as expected.

### HTML Code Validation

- Review of image attributes:
    Updated the alt attributes to be more descriptive

- Image names: I had spaces in names of images. These showed as errors on the W3 validator check.
    Removed spaces from image names and updated file path in the index.html page.
    Reviewed names of images on gallery page before running validator. Two of these images had spaces. Replaced space with hyphen and updated file paths on the gallery.html page.
    Checked all images to ensure they were still displaying correctly.

- Element smaller was used on text in the heading and caused a validation error.
    The element was not changing anything on the text and as text looked ok, I removed the ***smaller*** tag.

- Stray script error on index.html: Was caused by my two scripts being outside body of html. Once I moved these inside the closing body tag, it corrected the validation error.
        - Moved scripts on gallery.html and services.html. Tested burger menu, and it is still working as expected.

- Iframes validation error showing if there is text between the iframe tags. I had included text to cover if map did not load.
        - to correct validation error: removed text from iframe tag. Added a link below map for users to click on

- Error on contact form button: Input not allowed as a descendant.
        - Removed input element and added class and type to the button.
        - Had to add id to the element in order for it to style as required

[Validation of HTML](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/Html-validation-checks.pdf)

#### Bugs when viewing in Chrome and Edge Browsers

- One image not displaying on live site in Edge. checked and was the same issue in Chrome
        - Resolved as file path was not correct.

- Fieldset too narrow in landscape mode, elements were overflowing.
        - Resolved by setting bootstrap columns to 8 on small screen sizes and removing max-width property from css rule.

#### Bugs not Fixed

## Performance and accessibility Testing

Lighthouse testing

- First report run showed issued with images on home page. These were re-optimized and uploaded
- rel attribute added to footer links and meta description added to all 3 pages
- Unresolved Issues affecting Best Practice score
    unload listener/runtime error when testing/issues with cookies: I do not currently have the knowledge to fix these issues. Score for page is 80. However when report is re-run at a later time, issue is resolved and score is higher.
Attached are the audit reports "https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/lighthouse-reports.pdf"

Accessibility
Scores reviewed in lighthouse.
WAVE extension for further accessibility testing.
    - aria labels added to textare of form and to the alternative link provided for google maps loction.
    - heading levels used on services page restrucutred.
    - As I heading levels were restructures, it made more sense for the reader to be shown charity links under h5 heading, and more info for dog body signals under h6, as this is providing more information if a user is interested. It might be more important to a user to see charity links first.
    - There is an alert across the three pages. This in relation to adjacent links going to same url. These are the two links in the nav bar, which user can click to go to home page. Icon set to go to home page, and Home item in menu bar.
    - No other WAVE errors or alerts

## Code Validation

I used the following to validate code by direct input:

- html <https://validator.w3.org/>
        - index.html validation. Errors/bugs found and corrected. documented in bugs section. Errors also applied to gallery and services pages.
        - gallery.html valiation. No errors.
        - services.html validation. Errors on iframe and button. Corrected.

- Ran the three html pages through the validator again and no issues.

- css <http://jigsaw.w3.org/css-validator>
        - three errors: font-style rule and overflow rule removed. Not required. Font-family error needed a comma after first font-family was declared
        - Two warnings:
            - one was related to imported style sheets not being checked. no action to be taken.
            - Second warning was related to the rgba colour selected for background. Decided to change to simple one colour background.
    Re-run file through validator: no errors.

- Contrast Checker  <https://webaim.org/resources/contrastchecker/>
        - Contrast between content text and background: no issue.
        - Contrast between headings colours and background: no issue.
        - Contrast between navbar elements and navbar background: Some fails on contrastchecker. (same applied to footers)
        - Contrast colours on charity links buttons had some fails on contrastchecker.
        For the fails, I used lightness adjusteer o the contrast checker to select colors that contrasted better and updated CSS code.
        I installed the WAVE extension and rechecked contrast on all three pages. No issues

- [Screenshots for CSS and Color contrast checks](https://github.com/LisaHackett97/MS1-Dog-Daycare/blob/master/readme-assets/CSS-validation-and-contrast-Checks.pdf)

[Back to table of contents](#table-of-contents)

## Deployment

## Credits

## Media

### Icons used

- Puppy icon: credit [Creaticca-Flaticon.com](https://www.flaticon.com/authors/creaticca-creative-agency)
- All other icons, including burgr menu icon,taken from fontawesome.

### Images used

[Pexels Images](https://pexels.com)

Image Name | Photo credit
---------- | ------------
dog in cup | Photo: Pixabay
gallery small dog playing | Pixabay
two dogs  | Sebastian Coman Travel
Gallery dog and paw | Karolina Grabowska

[Unsplash Images](https://unsplash.com)

Image Name | Photo credit
----------|------------
g2-dog and woman|Photo by Tamas Pap
g2-white-dog-running  | Joe Caione
gallery-dog-on-grass  | ana minella
gallery-dog-run | arjan_stalpers
gallery-dogs-sleeping | Bruno Emmanuelle
gallery-pug-yawning  | Charles Deluvio
human and dog  | Anna Dudkova

Image called "gallery Freya1" my own photo.

## Content

### Inspiration for content

- <https://blog.homesalive.ca/dog-blog/benefits-of-dog-daycare>
- <https://pawcastle.com/benefits-of-doggy-day-care>
- <https://www.thebalancecareers.com/how-to-start-a-doggie-day-care-business-125525>
- <https://www.pets4homes.co.uk/pet-advice/doggy-daycare-what-is-it-and-is-it-a-good-idea-for-your-own-dog.html>

### Quotes

- <https://sharpquotes.com/dog-quotes/>
- <https://www.shutterfly.com/ideas/dog-quotes/>

### Colours

coolors.co was originally used to pick colours.
Color picker then used and adjust and pick colours which I felt worked with the site.

### Code

- How to link to id on another page: Tutorial html links on [quackit.com](https://www.quackit.com/)
- Code for animations from article on [geeksforgeeks.org](https://www.geeksforgeeks.org/how-to-create-fade-in-effect-on-page-load-using-css)
- Code for nav bar and burger menu taken from bootstrap documentation and customized for the site.

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

[Back to table of contents](#table-of-contents)
