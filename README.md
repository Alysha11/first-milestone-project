# User Centric Front End Milestone Project

## Project Name: Band site for The Monkees 
The purpose of this project was to create a website for fans (existing and new) for 1960’s rock band ‘The Monkees’.  It a responsive mobile-first designed website performing well on differing screens. This website is static apart from the navigation bar (created through Bootstrap 4). 
This project it simple to use and aesthetically appealing holding some nostalgic elements to represent the bands history.  Together with the ease of use and look the site is a place the band could use to showcase their music, publicise availability to perform at events and highlight a social media presence thus fulfilling the brief that was provided.  
This piece was created purely for educational purposes.  

### UX
**The business:**
 “The Monkees” - a band with 50 years of experience.
**Requirements:** 
-	A site where the band can showcase their music
-	Platform to publicise availability to perform at events
-	Links to social media presence specifically Facebook, Twitter and YouTube.

**The audience:**
The users of this website will mainly be fans of the band, possibly long-time considering the 50 year history. The users will also consist of new/ potential fans and those looking to book the band for an event. 

**User stories:**
Established Fan: 
>I have been a fan for many years. I use the website frequently to find and listen to hits. I want to be kept informed of latest news about the band whilst visiting and have access to social media sites for even more. 

New Fan:
>I love all things 1960s – the carefree vibe, bold colours and the catchy music. I collect vintage vinyls and enjoy discovering music from this time.  I use the website to find out more about the band and find their back-catalogue. 

Potential client: 
> I go to the website as The Monkees are on my list of dream possibilities to perform at my wedding. I want some more information, I expect the website to look professional and to reinforce the appeal of booking the band. 

**Scope:**
Based on the needs of the business and the target audience created a website that contains:
1.	A showcase of the music. The ‘music’ page which contains:
Discography 
Audio clips
Videos
2.	Info on the band
An ‘about’ section
A ‘news’ section to publicise latest information
Social links
3.	A place to dedicated to the band’s availability to perform at events in the form of the ‘bookings’ page:
A contact form
4.	A nod to the 1960s in regards to aesthetics
5.	As the users will likely come from wide ranging backgrounds from all over the world from the long-time fans of an older demographic to new younger fans I have made a site that is easy to navigate and incorporates modern conventions. 

**Wireframes:**
On designing the pages I used wireframes considering both mobile and desktop views. These were created using www.draw.io  and can be found:
[Desktop](blob/master/assets/other/desktopWireframes.pdf).
[Mobile](blob/master/assets/other/mobileWireframes.pdf).

### Features
**Navigation**
*Mobile and Tablet*
The navigation is a simple hamburger style dropdown on the top right of mobile view. When open the page headings are displayed, centre aligned with the branding on top. Clicking on the brand will take users to the home page however there is also a ‘home’ page listed which is more explicit. 

*Desktop*
The navigation runs across the top right of the screen with the branding to the top left. Both are more centred and larger than default Bootstrap 4 design as I wanted the branding to be more prominent. On hover the navigation options turns grey so that the user is clear where they are pointing to. The navigation bar also has a fixed position which adds to the ease of use for user’s navigation. 

**Home Page**
The page welcomes users to the site. It features a banner with some text which is a feature continued throughout the site. It provides clear information as to where the users are. 
There is a psychedelic background over which a cartoon representation of the band is featured. The background was created by using CSS gradients and is reminiscent of 1960s styling. 

**Flower & Social links**
*Flower*
At the bottom of all the pages there is a red flower image that was used as another nod to the era of the bands beginnings. It forms an attractive separation between the page content and the social links footer. 

*Social Links*
Facebook, YouTube and Twitter Font Awesome icons are used at the bottom of the page allowing users links to the social pages easily. The social icons link to the bands official social accounts on Facebook, YouTube and Twitter. 

**About Page**
Here is where band info is displayed – users can learn more about the band members here. 
*Mobile*
On mobile view each band member has a section with text followed by an image. They have complementary alternating colour backgrounds. Users experience a logical flow. 

*Tablet/Desktop*
On larger screens the band members’ section layout is different providing something else at these screen sizes. The images and text take up a full row alternating between image or text first on the different band members. Users will find it easy to follow as the background colour between members change. 
 
**Music Pages**
*Discography*
A gallery of album covers forms the discography. Users can see the names and release year of the band’s back catalogue. 
*Audio*
Some of the bands famous tracks are listed here in audio players. Users can listen using the controls.  On desktop screen the audio tracks are listed in-line as the audio players themselves are not so interesting to look at I ensured that they do not take up a lot of screen space. 
*Video*
Users can watch videos in this area of the music page. As the videos are embedded it is not necessary for users to leave the site.

**News Page**
The news page features three Bootstrap 4 “cards” these were styled to have a zoom effect on the cover images. Each article is visually appealing and contains information users would look for in news - an image related to the story, a headline, date published and a link to where users can find the full article. 

**Bookings Page**
This page contains a simple form that enables users to begin a booking enquiry with the band, it contains validation for required fields and directs to another page to provide some user feedback. 

*Features Left to Implement*
+As this project is strictly a static site I have used standard HTML audio players which vary in look based on browser. If I were to add further features I would want to include a custom designed audio player.
+The bookings form to be functional. 
+To add cookie, privacy, terms and conditions information in the form of modals so that they do not take up screen space

### Technologies Used
[HTML5]( https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) – structure 
[CSS]( https://developer.mozilla.org/en-US/docs/Web/CSS) – custom styling
[Bootstrap 4]( https://getbootstrap.com/) – used for grid layout, cards and navigation functionality. 
[FontAwesome](https://fontawesome.com/) – used for icons on about, news, music and booking page.  
[Google Fonts]( https://fonts.google.com/) – For ‘Raleway’ and ‘Ranchers’ fonts. 

### Testing
Reflecting back on the user stories I tested to ensure all uses would be met which they were as follows:
_established fan_ can listen to favourite hits with the audio players included in the music page, they have a dedicated page to news that is eye catching and clearly dated so can tell that they are seeing regularly updated articles, and they have working links to social media on all pages. 
_new fan_ has an attractive discography to view working on different screen sizes, it includes the title and release year of each album. They also enjoy visuals that provide a nod to the 1960s –flower divider, font style and background on home page. 
_potential client_ will find the pages are professional looking and the booking form simple and easy to use with the validation working reminding user in the case of errors. They are also given success feedback once submitted.  

**Process**
Code was tested using W3C markup validation and CSS validation.

I tested that the pages work as expected using a number of browsers and screen sizes.

For each browser and screen size I went through each of the pages and tested that the navigation works, collapses in mobile format and links direct as expected. 

Checked that other links direct correctly (social, youTube videos and news articles).

Tested the layout was as expected in the different browsers and at different screen sizes.

Tested the audio players worked by playing them.

Tested the videos worked by playing them.

Tested the booking form contained correct validation by leaving input(s) empty, by trying incorrect input of email and finally by completing correctly and checking that I was directed to feedback info once submitted. 

Results were put in a table and can be seen [Here]( blob/master/assets/other/testingSpreadsheet.xlsx).

**Resolved issue**
One difficulty I came across was with the audio players. On a smaller desktop screen size the individual players would touch each other. I was able to fix this by adding media queries to reduce, then increase the audio player width according to screen size. 

### Deployment
Deployed via Github Pages and can be viewed here: xxxx

### Credits

**Content**
About section draws on content from Wikipedia.
News articles link directly to specified articles. They are drawn from:
www.wndu.com
www.monkees.net
www.rollingstone.com	


**Media**
-Photos for album covers were obtained from [Wikipedia]( https://en.wikipedia.org/)
-Cartoon representation of the band and red flower were found on [Kisspng]( https://www.kisspng.com/)
-Images for articles were found on [Pexels]( https://www.pexels.com/)
-Audio files and images of the band members were obtained from the Code Institute
-Videos are from YouTube 

### Acknowledgements
- [Favicon Generator]( https://www.favicon-generator.org/) –  used  to resize flower image used as a favicon. 
- Inspiration for the article section of this project came from [The Sheepdogs]( https://thesheepdogs.com/) page.
- Inspiration for the psychedelic gradient and instruction on how to create came from [W3Schools](https://www.w3schools.com/css/css3_gradients.asp). 








