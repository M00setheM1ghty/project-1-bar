# The Dancing Palate
The Dancing Palate is a fictional bar in New York City, which intends to tickle your palate with new flavours and allows you to relax in a laid back setting.
It is a place for young and old. Only requirement: Bring good times, a thirst for new experiences and your friends. 

This website is supposed to help the customer find the location, request bookings via the contact page, have a peak at the menus and draw attention to our ongoing events.

<em>The Website is already live:</em>
[HERE][def]

## Tabel of Contents
+ [UX](#ux "UX")
  + [Site Purpose](#site-purpose "Site Purpose")
  + [Site Goal](#site-goal "Site Goal")
  + [Audience](#audience "Audience")
  + [Communication](#communication "Communication")
  + [Current User Goals](#current-user-goals "Current User Goals")
  + [New User Goals](#new-user-goals "New User Goals")
+ [Design](#design "Design")
  + [Colour Scheme](#colour-scheme "Colour Scheme")
  + [Typography](#typography "Typography")
  + [Imagery](#imagery "Imagery")
+ [Features](#features "Features")
  + [Existing Features](#existing-features "Existing Features")
+ [Testing](#testing "Testing")
  + [Validator Testing](#validator-testing "Validator Testing")
  + [Unfixed Bugs](#unfixed-bugs "Unfixed Bugs")
+ [Technologies Used](#technologies-used "Technologies Used")
  + [Main Languages Used](#main-languages-used "Main Languages Used")
  + [Frameworks, Libraries & Programs Used](#frameworks-libraries-programs-used "Frameworks, Libraries & Programs Used")
+ [Deployment](#deployment "Deployment")
+ [Credits](#credits "Credits")
  + [Content](#content "Content")
  + [Media](#media "Media")


## UX

### Site Purpose:
To help the customer find the location, request bookings, have a peak at the menus and draw attention to our ongoing events.

### Site Goal:
To regularly update our current users with the latest information, get them to make their bookings over the website, draw attention to social media (->followers) and build a base of regular visitors.

### Audience:
Cocktail enthusiasts and those who want to become one. Our target group are all people between the ages of 21-60. 

### Communication:
With a minimalistic design,  information is easy to find by all who visit the site. With this approach we avoid an overload of information and ensure that the most important parts are conveyes to the customers. Also the operating hours and location are available throughout all the pages, to remind our audience immediately of when we are open and where to find us.

### Current User Goals:
- To see updates on upcoming events and changes in the menus

### New User Goals:
- to navigate the site with ease & clearly understand the information that is being provided.
- for the information to be relevant & up-to-date.
- to be inspired by a striking design that captures my immediate interest,
and keeps my focus on the site.

## Design

### Colour Scheme:
The color palette was kept very simplistic with black and #blanchedalmond as background colors for content and header/footer respectively. 
Colors come almost exclusively from the background pictures.
For the text-color I used black for the header and footer. This was switched around in the main sections where I used #F4EADB (=var(--menu-color)) as the text color and made the background black. This ensures nice contrast and readibility and provides extra separation between header/footer elements and the main content. 

To make clickable links and menu-navigation obvious to the user all of these items turn #chocolate when hovered upon. This slightly darker color also matches nicely with the #blanchedalmond background. This light brown can also be distinguished easily from the black background in the Hours/Location section.(->google maps link) 

<!-- insert color pallete picture here -->
### Typography:
https://fontjoy.com/ was used to find matching fonts for the header font Dancing Script.
There I choose the following 3 fonts for the website:
They are declared in the :root selector in the beginning of the styles.css file:
:root {
    --header: Dancing Script, cursive;
    --subheader: Merriweather Sans, sans-serif;
    --text: Rubik, sans-serif;
}

The Dancing Script font matches with the 'dancing' Theme Name of the site and gives the site an artsy and musical touch. The subheader and text fonts are simpler to make it easy to find menu elements and ensure content is easy to read. 
### Imagery:
All the images found on the website are free stock images from https://pixabay.com/. 
The images were all used as backgrounds to highlight the fact this is a bar-environment with a focus on high-end cocktails, spirits and food.    
## Features

### Existing Features
#### Navigation bar:

This navigation bar is included over all 4 pages (Hours/Location is only a local link to the opening times) and also the form-dump page. It ensures visitors can navigate seamlessly between the pages.

![Navigation bar](assets/readme-pictures/nav-bar.png)
#### Footer
The footer includes the social media links and can be found on all pages to round off them off.
#### Landing/Welcome Page
The top-part of the welcome page shows a picture of a cocktail to alert the user to what kind of website they are on. The arrow indicates where to go to see the content intended to be viewed next. 
<!-- insert picture here-->
The bottom part is right below and shows the opening times and where the bar can be found, which is often essential information customers look for. 
<!-- insert picture here-->

#### Hours/Location Page
This is the bottom part of the welcome page. I figured that an opening-hours/location link should be included in the navbar since it is vital information and often looked for. 
 
#### Menus Page
Here the food and drinks menus can be found. The background picture suggests that drinks as well as food is available and part of the menu is already visible for easy access. 
<!-- insert picture here-->
#### Contact Page
The top part of the contacts page mimicks the style of the landing page.
The arrows clearly indicate where to find the contact forms. 
<!-- insert picture here-->
On the bottom part the Contact form as well as the signup for the newsletter can be found. 
<!-- insert picture here-->
#### Events Page
This page shows off special and ongoing events. It clearly states when and where they are happening and gives an easy view of all the information.
The background image gives the feeling of night life and party.
<!-- insert picture here-->

### Validator Testing
- html files pass through the [W3C validator](https://validator.w3.org/) with no issues found.
![W3C validator message](/assets/images-readme/validator-html.png)

- html files pass through the [Jigsaw validator](https://jigsaw.w3.org/css-validator/) with no issues found.
![Jigsaw validator message](/assets/images-readme/validator-css.png)

- page has an excellent Accessibility rating in Lighthouse
![Accessibility score](/assets/images-readme/accessibility-score.png)

- Tested the site opens in Brave, Chrome & Safari without issues.
- All links open to external pages as intended.

### Unfixed Bugs

## Technologies Used
### Main Languages Used
- HTML5
- CSS3

### Frameworks, Libraries & Programs Used
- Google Fonts - for the font families: Dancing Script, Merriweather Sans and Rubik. San-serif was used as fallback font.
- Font Awesome - to add icons to the social links in the footer element.
- GitPod - to creat my html files & styling sheet.
- GitHub - to store my repository for submission.
- Am I Responsive? - shows responisveness over all device sizes.


## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found [HERE - La Lucha](https://cluelessbiker.github.io/project1-la-lucha/index.html)

## Credits
The template for this readme and also the structure of the signup forms were taken(after asking) from my mentors project https://github.com/CluelessBiker/project1-la-lucha.
She also turned me onto using flexbox for styling the site. This site was used for learning the flexbox basics: https://flexboxfroggy.com/

Thank you Lauren!

The following CSS to hide the scrollbar was taken from the web. Unfortunately I cannot find the page it was taken from anymore.  
/* Hide scrollbar for Chrome, Safari and Opera */
body::-webkit-scrollbar {
    display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
body {
    -ms-overflow-style: none;
    scrollbar-width: none;
    background: black;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    flex-grow: 1;
}




### Content

### Media




[def]: https://m00sethem1ghty.github.io/project-1-bar/