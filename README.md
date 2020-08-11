# Travel Japan

**This is my first milestone project for The Coding Institute**

The project is an in-depth travel guide for Japan, and also provides a gallery of personal photographs to highlight some of my favourite places in Japan.

This website also provides the user with a mock-up booking form, in which they can select from various options to build their own holiday, and recieve a personalised holiday quote back.

![Responsive Design](/assets/images/responsive-designs.PNG)

<hr>

## UXD

* This website is for those interested in travelling to Japan.

* Users will find themselves able to navigate around this page easily with a responsive and user-friendly navigation bar.

* A newsletter modal will also show to users on larger screens to give them an option to sign up to hear about any news regarding this travel website.

* While designing the website, I used [Figma](https://www.figma.com/files/project/9354776/First-Project)
to wireframe my ideas.

![Figma wireframe](/assets/images/wireframe.JPG)

<hr>

## User Stories

These user stories helped me to make key design decisionss in order to make this website not only user-friendly, but informative.

### Project Stakeholder

* As the sole creator of this project, my main aim is to have this website succeed as I have a great interest in the topic and also, as my first project, I would like to prove to myself that 
I can create and succeed in this industry.

### New user

* "As a user who has never visisted Japan, using this website has definitley piqued my interest."

<hr>

## User Design Purpose:

### Strategy Plane:

- This website is aimed at those who have a base level interest in Japan, and would like to explore the idea
  of travelling to this area.

- With a basic, intuitive design, all users should be able to find their way around this website with ease.

### Scope Plane:

- The overall intention of this website is to draw users in with aesthetically pleasing, and informative information,
  so that they will want to hear more, and eventually book a trip with this company.

- This website consists of 3 pages. A landing page, a gallery and a booking page. Each laid out to keep a common theme for
  the website, and each page is responsive on
  various screen sizes.

### Structure Plane:

- The layout of this web page is built with user appeal in mind. The layout is simplistic, yet stylish enough to catch the eyes of all users.

- The information on the page is set out in such a way as to not be over-bearing, but also not uninformative.

### Skeleton Plane:

- The naviagation of this website is incredibly intuitive, and responsive. The layout is familiar to most users,
  and this provides the user with a sense of security, knowing they can easily navigate the web page and interact with its functionality.

### Surface Plane:

- This web page provides the user with a visually pleasing, and intuitive experience that will make them want to visit again to keep
  up with any new information posted on the website.

- The font and colours are all matched correctly to keep a familiar feel to each separate page.

<hr>

## Features

- The landing page has Bootstrap elements in place in order to display content responsively on all device widths.

- The navigation bar is set up in a way which is standard across most websites to give users an intuitive design that they are already familiar with.

- The gallery page employs some animations which, when hovered over, provide the user with small descriptions about each image.

![Gallery Animation](https://media.giphy.com/media/jnnRAacHmtXqS6b58W/giphy.gif)

- The booking page is laid out in a way that is visually appealing on all screen sizes.
  
* The form on this page allows users to build the type of holiday they want, and then they can receive an email which provides them with various options.

### _Features left to implement_

- I wish to embed a map onto the main content sections which would give users a better understanding of the geographical location of each article,
  however, with my limited skill set and time restraints, I am unable to implement this at this time.

- With a lack of JavaScript knowledge, it is hard to implement an automated email response for users who have filled in the booking form.
  I would like to implement this, but will unfortunately not be able to without the necessary knowledge.

<hr>

## Technologies used

- For this website, I have utilised HTML5, CSS3, Bootstrap, Font Awesome, Google Fonts, and a small amount of JavaScript.

[HTML5](https://en.wikipedia.org/wiki/HTML5)

- This language is used to build the overall body of the page, from text, to page structures.

[CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)

- CSS3 is used to style the elements on the page. CSS3 is responsible for the colour scheme, and the layout of the page.

[Bootstrap](https://getbootstrap.com/)

- Bootstrap is a powerful tool which gives developers multiple snippets of code to use in their projects, which can then be styled through CSS3.

[Font Awesome](https://fontawesome.com/)

- Font Awesome is a tool used to provide icons which add to the overall aesthetic of the web page.

[Google Fonts](https://fonts.google.com/)

- Google Fonts provides the user with different options for fonts to be used in web pages, further adding to the personalization of each page.

[JavaScript](https://en.wikipedia.org/wiki/JavaScript)

- While I am not well versed in JavaScript yet, I know that it is responsible for making a webpage more interactive for the user.
<hr>

## Testing

My testing process is explained below. The tests include:

* Testing user feedback

* Code validation

* Browser compatibility

* Responsiveness

* Link tests

* Form tests

## User Feedback

### Project Stakeholder

As the creator of this project, I wanted to make this website as seamless as possible, with appropriate links and navigation.
I would regularly check for any way to improve usability and user appeal in orde to make this as user-friendly as possible.

### New Users

The users I asked to test this consited of my partner and 2 friends, all of which had different screen sizes and browsers. My partner and I have visted Japan, but my 2 friends were new to this, which made them perfect first time users.
When first testing this website, these users gave me feedback relating to the layout of the web page, mostly the aesthetics and also how some of the links did not work as intended.

As these users were mostly new to this topic, testing how they navigated the website was my main focus.

When the users load up the page, they are met with an industry standard navigation bar, and a visually appealing hero image which sets the scene for the web page.

Pressing on the website logo or the 'Home' link on the nav bar will return the users to this landing page.

When a user feels they have sppent enough time on the landing page, they can click the 'Gallery' link in the nav bar which takes them to a sleek gallery which showcases
some personal images. The users then hover over the image, which reveals a snippet of information on each image, and also an external link, should they wish to learn more.

The booking page, while not functioning, due to a lack of JavaScript knowledge, is intuitivefor each user, and also highlights to the user if they haven't filled in each section.
Upon form completion, the user is met with a modal, aknowledging the form completion, and relaying to the user that they will be informed of any deals relating to their holiday search.

### Tablet User


### Code Validation

#### HTML Validation

When validating my HTML5 code, I used the [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input).
Entering my code into the validator gave the following feedback:

### *index.html* 

- Multiple warnings relating to comments in the code (does not affect the web page in any way)
  
- The following error also appears in my modal relating to the email input. "The aria-describedby attribute must point to an element in the same document.
  From line 215, column 7; to line 221, column 26"

- Due to limited JS knowledge, this does not affect my web page.


### *gallery.html* 

- Similar warnigns to the 'index.html' file in regards to the code comments (no effect on web page) 

- Multiple errors as my images did not have an 'alt' attribute. This was easily fixed, and all images have now been assigned an 'alt' attribute and value

#### *book-now.html*

- Warnings about comments in code (no effect on web page).

#### CSS Validation

### *style.css* 

- Various warnings about imported style sheets, relating to my use of -webkit-, -o-, and -moz- attributes to help with browser fluidity.

- No errors found in my code.

## Browser Compatibility

- Testing for this website was carried out by myself, navigating the web page from each link, and making sure everything lead to the right place.

- I have tested the web page on the following browsers:

* Google Chrome

* Microsoft Edge

* Apple Safari

## Responsiveness

*  Testing for responsiveness was made easy with the Chrome Developer Tool which enabled me to alter the screen size of my web page to check
  everything was responsive, so that every user, regardless of which device they are using, can have the experience I intend for them to have.

* The main problem I have run into is getting my footer stick to the bottom of the web page on each screen size, I have experienced some white space issues
on the iPad and iPad pro, but this has been rectified by making a specific footer class for the 'boook-now.html' page and having played around with the body tag's height.

## Link tests

I have manually checked all of the following links to ensure they are working as intended:

* Navigation links - These all work as intended and there are no broken links. The logo also works as a home button on each page.

* Modal activation buttons - These work as intended, however, due to limited JS knowledge, the modal on the booking form does not show for as long as I would like.

* Gallery images external links - I have tested all of these links, adn they all lead to their intened place, and they all open in a new tab as to not lead the user away from the website completely. These may change in the future depending on the website hosting the
information, and this is ultimatley out of my hands.


<hr>

## Deployment

- I developed Travel Japan on GitPod and used GitHub and GIT commands to commit and push all code to this repository.

- To make my code usable for others, I had to create a GitHub profile, I then created a new repository using the on-screen instructions. When setting up my repository,
  I utilized the Code Institute template which provides basic boiler text.

- Once my code was written, and pushed to GitHub, I opened up my GitHub profile and navigated to the settings in my repository.

- From the settings, I scrolled down to the GitHub Pages section and selected the _Master Branch_ source.

- With these settings confirmed, the page is now live on GitHub Pages, and free to view by all in a web browser.

- Any users wishing to view this code, or if they would like to use it for inspiration, they can do so on [My GitHub Page](https://github.com/DamSenton/Travel-Japan-Master).

<hr>

## Credits

### Content

- All of the articles on this page were conceived entirely by myself.

- All of the code for this project was written by myself, with the exception of the animations for the Gallery Images, in which I took inspiration from CoreLangs.com. This code is free to use for learning purposes.

* A small amount of JavaScript was used for my booking form, which allows a modal to be shown to th euser upon the form's completion. This code was taken from CodePen.Io's user Hana Piers, so credit's to her for the help.

### Media

- The hero image, the main content backgrounds and the 'Book Now' form background were taken from Google using the 'Advanced Image Search' to ensure no copyright infringment occurred.

- All of the images on the 'Gallery' page were taken by myself while on a personal trip to Japan and uploaded to [https://Imgur.com] to enable me to embed them on this page.

* The image used for the 'Attraction of the Month' section was taken from [Takuma Mori](https://www.flickr.com/photos/takuma104/) on Flickr. I am free to use and distribute this with the proper credit.

### Acknowledgments

- The web page layout takes inspiration from multiple Code Institute projects. I have taken elements from almost each project and repurposed them to fit my web page.

- This project was inspired by a lot of travel websites and also the mini projects completed alongside The Code Institute.
