# Carol's Kitchen

Carol's Kitchen is a site that offers Spanish recipes in English. The website is designed to be easy to navigate. 
 
A live version of the site is available [here](https://carolinacobo.github.io/CarolsKitchen/)

For this project it was required to create a user centric website using HTML5, and CSS supported by other libraries as Bootstrap. 

## UX
### User stories:
- As a user I want to find Spanish recipes. 
- As a user I want to easily navigate the site. 
- As a user I want to contact the site owner.
- As the site owner I want people to find recipes and navigate them easily.

Desktop wireframe:

![Desktop Wireframe](assets/wireframes/desktop.png) 

Mobile wireframe:

![Mobile Wireframe](assets/wireframes/mobile.png) 

Ipad wireframe:

![Ipad Wireframe](assets/wireframes/ipad.png) 


Contact page (Desktop, mobile and Ipad):

![Contact Wireframe](assets/wireframes/contact.png) 

# Structure
## Design process
### Page structure 

- My aim was to make the site simple and easy for the user to navigate it.
- All pages follow the same style (other than the main page) being simple and easy to read. 
- The navbar on top of the page is static and have the links to the main three areas of the site. It also has the logo and a slight different color, that is the same as the footer. It's responsive and the items collapse on smaller devices. 
- The home page is the main area where the recipes are listed and are linked so the user can find on a glance what is looking for. It's responsive depending on the device tha page is viewed. 

### Home
It features two areas of content and links to the third one on the Navbar. 
- First section is the cards containing the recipes. 
- Second section is a carousel with more recipes (this is a future feature).

### Recipes 
The recipe sites follow the same structure and picture (same as the home page one) with the Ingredients and Steps. 

### Contact
The contact page has three boxes with name, email, question and button to submit a question. Once the question is submited the user will be redirected to a Thank you page and a Home button. 

# Styling

## colours
Using [Colorhunt.co](https://colorhunt.co) I chose a palette with complementary colours that could be found in different sites: 
- ![#16697a](https://via.placeholder.com/15/16697a/000000?text=+) `#f03c15` - Cover text and when the user hover on the icons. 
- ![#fafafa](https://via.placeholder.com/15/fafafa/000000?text=+) `#fafafa` - Header, footer, icons and buttons text. 
- ![#8f8f8f](https://via.placeholder.com/15/8f8f8f/000000?text=+) `#8f8f8f` - Buttons when they are not hovered on. 

## Fonts 

Anton is used for the site logo and Favicon. Noto Sans JP is used site wide. Both imported from Google fonts and the Favicon from Favicon.io. Used on the Universal selector to format the entire site. 

## Features
 
### Existing Features
- Feature 1 - Allows users to see all the available recipes.

    * Used HTML and CSS for the Hero-Image and site structure. 
    * Used Bootstrap to add a responsive and collapsable Navbar, cards with recipes, carousel and footer. 

- Feature 2 - Allows users to click and see the ingredients and steps for the recipes. 
    * Used HMTL and CSS for the page structure. 

- Feature 3 - Allows users to send a message with a question. 
    * Used Bootstrap to create the form and CSS to format both the form and the button. 
 
- Feature 4 - Redirects the user to a thank you site after submiting a form.
    * CSS to format the message, button and positioning them. 

- Feature 5 - Footer with links to different social networks. 

Future features: 
- Recipes linked to the carousel.
- Video explanation in the different steps of the recipes. 
- Ranking most shared recipes. 

## Technologies Used

### Languages

- HTML - language for the structure of this site. 
- CSS - to style and fix media queries and the max width.

### Libraries
- [Bootstrap (4.5.3)](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - with supporting JS Script and tooltips. Used for the responsive grid system, styling elements and navbar creation.
- [FontAwseome (5.6.3)](https://fontawesome.com/)- used for the footer icons.
- [Google Fonts](https://fonts.google.com) - used for fonts on the site.
- [Hover.css](https://ianlunn.github.io/Hover/) - used for animation effects on social icons and various buttons throughout the site.
- [TailwindCSS](https://tailwindcss.com/docs/box-shadow) - For inspiration on the 
- [CSS Variables](https://developer.mozilla.org/en-US/)
    - This project uses **CSS Variables** to avoid reusing properties. I've seen them on the console and wanted to try them as well to help the site to be responsive. In the root and in different places to give the site a max widht. 

### Tools 
[Gitpod](https://www.gitpod.io/) - used as IDE for the project.
[Git](https://git-scm.com/) - used for version control.
[Github](https://github.com/) - used to host repository and to generate the live website.
Balsamiq - used to create the wireframes.

For test porpuses: 
[Am I Responsive](http://ami.responsivedesign.is/) - for testing purposes. 
[Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - used for testing and debugging.
[w3 html validator](https://validator.w3.org/) - used to test and validate my html code.
[w3 css validator](https://jigsaw.w3.org/) - used to test and validate my css code.
Lightouse - 


## Testing

### User stories

As a user I want to find Spanish recipes. 
- As a user I want to easily navigate the site. 
    * The site is easy to use and visual so things can be seen on a glance. 
- As a user I want to contact the site owner.
    * The site has on the Navbar the Contact site that can be accessed from all pages and shows a message when a question is submitted so the user is sure the question has been sent. 
- As the site owner I want people to find recipes and navigate them easily.
    * Information is clear and easy to read for the users. 

### Testing responsiveness 
- With Google Developer Tools in Chrome in all screen sizes.

### Browsers 
Manually tested: 
- Chrome.
- Safari.

### HTML and CSS validation

Code has tested and passed: 

[W3C Markup Validation Service - HTML](https://validator.w3.org/)
[W3C Markup Validation Service - CSS](https://jigsaw.w3.org/css-validator/)

Screenshots following this [link](https://github.com/CarolinaCobo/CarolsKitchen/tree/master/assets/tests).

# Tests 
The following manual tests have been performed, link video at the end. 

1. Open all the links available: 
    1. Click Navbar. 
    2. Click recipes link.
    3. Click recipes picture. 
    4. Click social media icons.

2. Carousel. 
3. Contact form:
    1. Go to the "Contact" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.
    5. Click home button and come back to home 


Below a table with a list of the test performed: 

What do you do? | Expected Behaviour | Pass/Fail  |
| ------------- |-------------| -----|
| Click picture to open recipe| Open recipe in a new tab | Pass |
| Click link to open recipe| Open recipe in a new tab | Pass |
| Click Recipes on navbar | Scroll down to Recipe section | Pass |
| Slide on carousel| Slide to the left and the right|   Pass |
| Open social media links | Open a new tab | Pass |
| Contact the site owner | Request a name, email with the correct format and the question | Pass |
| Submit a question | Redirect to a new site | Pass |
| Submit incomplete form | Request correct information | Pass |

Video testing the site in the following [link](https://www.loom.com/share/d0486bb5644848f4a9adae4a688c12ba)

### Bugs

## Deployment
My site is hosted on GitHub, deployed directly from the master branch. 
- Steps to complete the hostin process: 
    1. Log into GitHub.
    2. Pick the respository. 
    3. Go to settings. 
    4. Scroll down to GitHub Pages section.
    5. Select as a source "master branch". 
    6. The page refreshes automatically and the project is deployed. 


## Credits

### Content
All the content on this site is my own.

### Media
- The photos used in this site were obtained from [Pixabay](https://pixabay.com/)
- The color palette used in this site was obtained from [Colorhunt.co](https://colorhunt.co)
- Size of the pictures of this site have been reduced using [Tiny Png](https://tinypng.com/)
- The favicon for this site has been made in [Favicon.io](https://favicon.io/)
- The Library Tailwind has been used for inspiration on styles. 

### Acknowledgements

- I received inspiration for this project from [Donal Skehan](https://donalskehan.com/recipes/)
[MDN Documentation](https://developer.mozilla.org/en-US/)
[W3Schools](https://www.w3schools.com/)
[CSS-Tricks](https://css-tricks.com/)
[StackOverflow](https://stackoverflow.com/)
[Codú Community](https://www.youtube.com/channel/UCvI5azOD4eDumpshr00EfIw)
[FreeCodeCamp](https://www.freecodecamp.org/)


### I received advice and support from
My mentor Dick Vlaanderen.
Code Institute - Slack Community.