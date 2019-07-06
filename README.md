# Project-1 Rock Band

<!-- One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch. -->

The project's main focus is to promote the already established and legendry rock band, Queen.  Queen have a huge following worldwide and the website has focused on showcasing the band popularity over the centuries and providing existing and potential fans with a place to go online and book the band for an upcoming event.  While on the site fans have a chase to see past video events and listen to a selection of songs.  There is also a sign up section where fans can register for a monthly newsletter to keep better informed of upcoming events around the world.  In a nutshell this site is all about giving the fans a one stop site on all the bands news.
 
## UX
 
<!-- Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things. 

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser. -->
The user experience has been centered around existing and potential fans wishing to book an event, listen to a selection of music or videos, view photos as quickly as possible with just one click.  This site has established this with a fixed navigation bar, booking button located in the header.  The site is responsive so the user can access all features at ease on a mobile phone or desktop

### User Story

The user wants to book the band for a christmas party at work:

- User accesses the site via either mobile or desktop
- User clicks the "book now" button
- User completes all fields on the form
- User submits form and is returned to the home screen
- User can relax the booking is complete OR!!!
    - User clicks the menu link for photos on the fixed navigation bar and views past images of events
    - User clicks the menu link for music on the fixed navigation bar and listens to a choice of music
    - User clicks the menu link for video on the fixed navigation bar is able to watch youtube videos which can also be viewed in full screen mode
    - User can scroll down and subscribe to the bands new letter
    - User can also use menu links to navigate the site in the footer
    - User can click on Social Media links in the footer which opens the site in a new browser window
    - Now the user experience is complete the user can leave the site till next time!


### Mockups

All mockups have been created with Balsamiq Mockup Software

- [mockup of home page](assets/mockups/home-mockup.jpg)

- [mockup of about page](assets/mockups/about-mockup.jpg)

- [mockup of photo page](assets/mockups/photos-mockup.jpg)

- [mockup of subscribe page](assets/mockups/subscribe-mockup.jpg)

- [mockup of music page](assets/mockups/music-mockup.jpg)

- [mockup of video page](assets/mockups/video-mockup.jpg)


## Features

<!-- In this section, you should go over the different parts of your project, and describe each in a sentence or so. -->
All the user features are easily accessed by a fixed navigation bar which the user can click to move to any section of the site at any time. 

### Existing Features
<!-- - Feature 1 - allows users X to achieve Y, by having them fill out Z -->

<!-- For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional. -->

<!-- In addition, you may also use this section to discuss plans for additional features to be implemented in the future: -->

- Feature 1 - allows the users to book an event by clicking the book now button and completing and submitting a modal booking form 
- Feature 2 - allows the user to stay on the site and read all about the band
- Feature 3 = allows the user to listen to a selection of the bands music
- Feature 4 = allows the user to signup for the band's monthly news letter
- Feature 5 - allows the user to browse picture gallery of the band
- Feature 6 - allows the user to watch past events via youtube embeded video clips
- Feature 7 = allows the user to navigate to all the bands social media sites by clickable links in the footer  

### Features Left to Implement

- The site could be extended at a later date to facility the selling of event tickets or merchandise by implementing ecommerce functionality

## Technologies Used

<!-- In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used. -->
This project was to focus on the basics of HTML5 and CSS3

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to simplify grid layout and add a modal booking form


## Testing

<!-- In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here. -->
At implementation of each section of development the site has been viewed for layout, correctness and usability both on desktop and by resizing for mobile using a chrome extension "for Mobile/Responsive Web Design Tester".

- links checked and all found to be working correctly
- buttons all checked and found to be working correctly
- HTML5 validation has been implemented on all fields of the booking form and found to be work correctly
- booking form modal close buttons are working correctly
- parallax scrolling is working correctly until breakpoint with media query @media(max-width: 568px) where it display is set to none
- all images have been set for responsive and tested to be correct and all include alt tags for screen readability
- music and video links have been tested and are all working correctly
- subscribe input field set to validate for email address and submits button works correctly
- links to social media checked and all work correctly
- menu links in footer all work correctly

The site has also been tested using the W3C valiation tester [W3C_Validation](assets/testing/w3c-validation.png)
- The warning for HTML5 date picker is the only comment as it may not be supported in all browsers.  Having checked this in Chrome, Firefox and Safari the only browser that does not appear to test well for this feature is Safari.  You can also use [Can I use](https://caniuse.com) to check for browser support

Jigsaw.w3.org has been used for testing the css3 file which has been given a no errors found result [jigsaw css test](assets/testing/W3C-css3-validator.png)

The following links will show screenshots of testing on my mobile iphone8:

[home page](assets/testing/home-screen.jpg)

[booking form](assets/testing/booking-form.jpg)

[about page](assets/testing/about.jpg)

[photos page](assets/testing/photos.jpg)

[photo2 page](assets/testing/photo2.jpg)

[music page](assets/testing/music.jpg)

[subscribe page](assets/testing/subscribe.jpg)

[video page](assets/testing/video.jpg)

[footer page](assets/testing/footer.jpg)

## Deployment

<!-- This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally. -->
For the project the site has been depoloyed using the hosting platform GitHub

As all files have been stored on the github respository there has been no need to change any links or alter any configuration on the project.  The site has been deployed from the github master branch.  As this was a small solo project no branches have been used.

[github repository](https://github.com/jacqueline-walsh/queen)

[github live website](https://jacqueline-walsh.github.io/queen/index.html)


## Credits

[For inspiration for the video header - Traversy Media](https://www.youtube.com/watch?v=Xy3GlrddZFI)

[For inspiration for the parallax layout - Traversy Media](https://www.youtube.com/watch?v=JttTcnidSdQ)

[For css3 gradiants](https://cssgradient.io/)

### Content
<!-- - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z) -->
Text has been copied from the following sites the official Queen site. Or ficticiously created for the purpose of the project
[text - Queen Online](http://www.queenonline.com)



### Media
<!-- - The photos used in this site were obtained from ... -->

[Queen logo - uihere](https://www.uihere.com/free-cliparts/queen-musician-rock-logo-queen-band-7198373/download)

[photos and Images - Facebook](https://www.facebook.com/Queen/)

[all Other Images - Google Images](https://www.google.com/search?q=queen+band+images&tbm=isch&source=univ&sa=X&ved=2ahUKEwiP0pXWgp7jAhU2WxUIHf8wDn4QsAR6BAgHEAE&biw=2560&bih=1266)

[All videos - Youtube](https://www.youtube.com/results?search_query=queen)

[music - mp3guru](https://mp3guru.icu)

### Acknowledgements

- I received inspiration for this project from a meeting with my mentor and from using googles mindmup for brainstorming ideas