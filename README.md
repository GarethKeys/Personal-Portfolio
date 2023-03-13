# Personal-Portfolio - Project One

This is a website I have created in order to showcase the Frontend developer skills I have learned to date through the Learning People Full Stack Developer course. My website will be used to promote myself and my skills to find emplyment opportunities in the future. Potential employers will be able to browse my website to learn about my experience while also viewing some of the Frontend skills I have developed.

## UX
***

My website is for potential employers who may be interested to learn a bit more about myself, my past experience and my hopes for the future. I have incorporated who I am as a person, where I have come from and where I am headed. My aim was to promote myself as a human being with both a personal side to my life as well as a career side. I have included multiple different methods to get in contact with myself in the hope of attracting some communication.

The style and layout of the website was chosen to promote my persoanl values of family and nature. The colour of the text and masks are used to work with and showcase the background image and personal photo.

## Features of the Website
***

### All Pages

- **Background Image**: Stunning scenic background image of beautiful mountains, chrisp calm water and reflections of light. I believe thsi image is an eye-catcher and a thought provoker which I feel my websites will be. I want the user to be transported to a happy place while also learning a bit about me along the way. Life and nature are very important to me, so I wanted to capture that in my website.
- **Vertical Navigation Bar**: I chose the vertical navigation option as It seemed most portfolios I studied used the standard horzontal bar at the top of the screen. I am showing I like to think outside the box and am not afraid to challenge myself to make a design different and standout from the rest. The Navigation bar is to the extreme left of the screen on larger devices, so as not to block or take away from the background image. I have also styled the Navbar to be transparent and allow the user to still see the background image. The navigation links within allow the user to move between pages on the website.
- **Collapsible Navbar**: On smaller devices below width 768px the Navigation bar will collapse to a toggle button on the top right of the screen. This responsiveness allows the user to still have full view of the background image and full access to the navbar on smaller devices.
-**G.K. icon image**: I added an image at the top of the navbar with my initials and made it clickable. When clicked from any page within the website it will return the user to the home page.
- **Mask applied behind text**: I have added a mask behind the text on each page to allow the text to be easily read and not hidden by the background image. The colour styling of the text was also chosen to pop out from the colouring of the background image.
- **Social media links**: Incorporated into the footer are clickable icon links (from Font awesome) to make contact with me (phone/email) or view my various social media sites (LinkedIn, Github and Facebook).
- **Contact me link**: I added a clickable link at the bottom of the footer on each page which opens a new window to send me an email and make contact. This is an extra point of contact in an attempt to draw the visitor into reaching out to me and making contact.

### index.html
- This is very much a welcome screen for the user. The aim here is to welcome the visitor and provide a very brief description of who I am and where I am currently based. I also encourage the visitor to make contact if they are impressed by the setup of the website.

### about.html
- This page provides a more in-depth guide to the visitor about who I am as a person and a bit about where I have come from in life and in my career. My aim is to get accross that I am a very experienced and confident troubleshooter through my current and previous employments and thrive in challenging environments. I also want to make it clear how important life and family-life are to me and have added the photograph of me and my youngest daughter (Gráinne) to show my caring family side. I explain how I am currently on my learning journey with Learning People and the Full stack developer course. Also how I am thorougly enjoying it and the many challenges that come with it. I have added an active link to the learningpeople.com/uk website to showcase the learning opportunities available there.

### contact.html
- This is a basic contact form made up of 4 fields. These are Name, Phone number, Email address and a box for a personal message. The submit button currently does not have any function linked to it, so this will be added when I progress in the Full Stack course.

## Features to be implemented in future

If I had more time to spend on the project and more experience with the varous developer tools I would like to add the following functionality:

- Add functionality to the navbar items, so they change colour when hovered over and also remain a different colour to let the user know which page they are currently on.
- Add some animation to the background graphic, so it comes to life and draws the user in to the image.
- Add functionality to the mouse, so it interacts with the background image when hovered over and moved around which will increase the UX for the visitor and extend the visitor experience and duration.
- Add functionality to the "Contact me" link at the bottom of the footer. I would make this subtly change colour or flash to entice the visitor to click the link and make contact.
- I would like to add some sound to the page in the form of a background track, but also sounds when items are clicked or pages are selected. This will improve the UX further.
- In the about.html page I would change the single photo for an active slide show of photos of my life and images of my various projects completed to date. These would be active and slectable by the user to get more detail on particular projects.
- In the contact.html I would add functionality to the "Submit" button. Currently this button is not active, so the data entered is not processed.
    - In the contact.html I would also like a pop-up message when the Submit button is clicked to thank the visitor for their details and for making contact. Also to ensure the user I would reply soon.

## Technologies used
---

- **HTML 5**: 
    - The website uses HTML5 for the majority of the content.
- **CSS3**:
    - The wesite uses CSS3 to style the varous elements and contents to improve the visual aspect and UX.
- **Bootstrap V5.3**:
    - My project uses Bootstrap's easy to uderstand flexible grid system and CSS to add the responsiveness needed to automatically adjust to different device sizes. 
    - This was used for my vertical navigation bar, but alos in the layout of each page to ensure it responded when switching between the various screen sizes and dimentions.
- **Javascript**:
    - The website uses the Javascript which is in built to the Bootstrapo components to add some functionality.
- **Font Awesome**:
    - Font Awesome was used for the active icons added within the footer.
- **Cool text**: 
    - Cooltext website was used to create the G.K. icon at the top of the navbar.
- **Git**:
    - I used Git as the version control system for adding and commiting changes made to my project in Visual Studio Code.
- **GitHub**:
    - I used GitHub as the remote repository to which I pushed and saves the commited changes on my website from Git. I also deployed my website using GitHub pages allowing it to be viewed in a live environment.


## Testing
---

I tested the responsiveness of my website using Google Chrome's developer tools within the Inspect toolbar. This allowed me to display my website on the various differenjt device types and screen sizes to ensure the responsive functionality was as it should be and layout was not corrupted.

### Issues encountered

- **Vertical Navbar**: Choosing the vertical navbar was challenging as it split my pages vertically into columns which created some interesting responsive issues when switching between device sizes.
- **Background Image**: Adding the background image added a level of difficulty to the website. Due to the fact it is so detailed and coulourful text was difficult to read when overlayed on it. To get around this I added a mask around the text to make it standout from the background image.
- **Contact From**: I had planned to split the form page into two columns with one column containing the form and the other containing a map with my address and contact phone number. When I implemented this it looked too cluttered on the page, so I decided to simplify it to one column dedicated to the contact form. Visually I think this was the correct decision. Perhaps if the navbar was horizontally at the top of the page it would not be as cluttered with two columns.
- **Responsiveness**: I spent a lot of time playing around with the various Bootstrap5.3 setups to make the pages responsive while maintaining the layout. This was a learning curve and I have gained alot of experience through doing this.
- **Time available**: This was my biggest issue encountered. I have a full time job and three children under the age of seven, so findind time in the evenings to dedicate to the project was difficult. In the end it makes it more rewarding the challenge I have met and overtaken.

## Deployment
---

I hosted my website on GitHub pages. In order to deploy my website I used the following steps:



