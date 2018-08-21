# The Monkees

This project was specifically designed for a music band in order
to facilitate interaction with actual and potential fans. All the
important information is in a maximum two clicks reach.


## UX
This website is for a music band. Main goal is to reach actual and potential fans who may also want to hire the band for their events.

* All the links related to the main two groups are in maximum 2 clicks reach. 

* Callout section is visible on every page it makes it easier to contact the band.

* The Contact Form is accesible from the Callout Section bellow the header and from the Footer's Contact Us section as well 

* Navigate section in the Footer facilitates acces to Audio/Video files, Contact Information as well as Social Links, 
  so when a User reaches the bottom of the website on a mobile device they don't have to go back to the top.

### User Stories
1. I am a fan. My goal is to see the upcoming events of my favourite band. The landing page shows these events with dates and location. 
   
2. I am a fan. My goal is to hire my favourite band for an event. 
3. I cand do this clicking on the Contact section or directly from the callout section 
   by clicking on the button. I could call to book as well, there is contact information in the footer.
 
3. I am a potential fan/new visitor not familiar with this band. My goal is to discover more about the band. On the landing page, first thing on top, is a short description of the band, with a button bellow leading to more information if I'm interested.
   I could also listen to some music accesible from Music section or Audio/Video in Footers Navigate section in order to get an idea about the music they make.

#### Links to the wireframes:
* [Homepage](https://www.dropbox.com/s/2xmr8v16d1uazp0/home-themonkees.png?dl=0)
* [Homepage-XS](https://www.dropbox.com/s/xy9bdangthncj5s/themonkees-home-xs.png?dl=0)
* [About](https://www.dropbox.com/s/0xfr8awv40fzgyt/about-themonkees.png?dl=0) 
* [Audio](https://www.dropbox.com/s/10tghe8mr7mu6im/audio-themonkees.png?dl=0)
* [Video](https://www.dropbox.com/s/xu40hl056njza01/video-themonkees.png?dl=0)

The "Contact Us" page hase the same structure as "Video"
with a Form insted of a video clip. 
Important thing is that the "Alert - Call to Action" is not dislayed on the Contact page,
as it normally would toggle a modal with the Form, hence it is redundand.


## Features


### Existing Features
1. Users can navigate through the site using the Navigation Bar
2. Access to social links throug social media icons in the header and footer of the page
3. Music - Audio section contains embeded audio files allow users to listen to some of the band's audio recordings
4. Music - Video section contains embeded video files allow users to watch a video clip
5. Contact section has a form that allows users to reach out to the band 
6. Navigation bar collapses into a burger button when displayed on smaller devices
7. "Reach Out" button in the Callout Sections toggles a modal contaning the contact form for a fast way to send a message to the band.
8. Included hidden labels for every input in the Form in order to make it posibile for screen readers to process. 
8. By hovering over the photos of a band member additional information is desplayed
9. Footer has a Navigate section that allows to browse through the website when the users reaches the bottom of the page
 
### Other possible Features 

Implementing an API in order to make the forms functional 
Adding "back to top" element for mobile devices


## Technologies Used

Bootstrap Framework - For css styling, grid and JavaScript (JavaScript and JQuery) components.
[Bootstrap v 3.3.7](https://getbootstrap.com/docs/3.3/)

Google Fonts - For additional fonts with particular styling.
[Google fonts](https://fonts.google.com/)

Font Awesome - For icons.
[Font Awesome](https://fontawesome.com/free)

## Testing

Contact form:
Go to the "Contact" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears

Modal
Same checks that were made for the form on the Contact page

Navigation-Burger Button:
Check if navigation menu collapses at a certain viewport width
Check the dropdown if it is displayed properly

Navigation-Menu:
Check all the links
For the link to the Contact page see that it goes directly to the form and not to the top of the page

Band Memebers' Images:
Check that on hover the image becomes more saturated and additional information is displayed

Adaptability to different viewport sizes:
Checked how each page is displayed on different devices using Chrome tools

Audio and Video
Checked that the audio and video files are played correctly. Not played automatically when the page opens and don't go into a loop.

After deployment the images weren't displayed correctly due to the wrong directory path, was an absolute one, changed it to relative

## Deployment

Deployed using GitHub Pages 

## Media
The photos used in this site were obtained from:
* [pxhere.com](https://pxhere.com/) Images are free of copyright, can be used or modified for any purposes
* GitHub Repository provided by Code Institute as part of the "Fullstack Web Development Course"

The audio and video files were obtained from:
* GitHub Repository provided by Code Institute as part of the "Fullstack Web Development Course"

Text used in the About page obtained from:
* [Monkee's Wikipedia Page](https://en.wikipedia.org/wiki/The_Monkees)