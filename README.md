#User Centric Front End Milestone Project

##Project Name: Band site for The Monkees 
For this project the aim was to create a website for fans (existing and new) for 1960’s rock band ‘The Monkees’.  It a responsive mobile-first designed website performing well on differing screen sizes. The website created is static apart from the navigation bar (created through Bootstrap 4), easy to use and aesthetically appealing holding some nostalgic elements to represent the bands history.  
Together with the ease of use and look I believe the site is a place the band could use to showcase their music, publicise availability to perform at events and highlight a social media presence thus fulfilling the brief that was provided.  
This piece was created purely for educational purposes and is not used commercially.  

###UX
**The business:**
The 1960s band The Monkees with  50 years of experience.
**Requirements:** 
-	A site where the band can showcase their music
-	Platform to publicise availability to perform at events
-	Links to social media presence (being created). Specifically Facebook, Twitter and YouTube.

**The audience:**
The users of this website will largely be fans of the band, possibly long-time considering the 50 year history. The users will also consist of new/ potential fans and those looking to book the band for an event. 

**User stories:**
Established Fan: 
>I enjoy listening to the music of The Monkees it takes me back to my youth, the 1960s. I use the website frequently to find and listen to my favourite hits. I want to be kept informed of latest news about the band whilst visiting and have access to social media sites for even more. 

New Fan:
>I love all things 1960s – the carefree vibe, bold colours and the catchy music. I collect vintage vinyls and enjoy discovering music from this time.  I use the website to find out more about the band and to learn about their back-catalogue. 

Potential client: 
>I am getting married soon and would love to have a live band performing. I go to the website as The Monkees are on my list of dream possibilities and want some more information, I want the website to look professional and to reinforce the appeal of booking the band. 

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
3.	A place to publicise availability to perform at events in the form of the ‘bookings’ page:
Some information on this
A contact form
4.	A nod to the 1960s in regards to aesthetics
5.	As the users will likely come from wide ranging backgrounds from all over the world including the long-time fans of an older demographic to new younger fans I have made a page that is easy to navigate and incorporates modern trends/conventions. 

**Wireframes:**
On designing the pages I used wireframes considering both mobile and desktop views. These were created using www.draw.io  and can be found [Here](../blob/master/LICENSE).

###Features

**Navigation**

*Mobile and Tablet*
The navigation is a simple hamburger style dropdown on the top right of mobile view. When open the page headings are displayed, centre aligned with the branding on top. Clicking on the brand will take users to the home page however there is also a ‘home’ page listed which is more explicit. 
*Desktop*
The navigation runs across the top right of the screen with the branding to the top left. Both are more centred and larger than default Bootstrap 4 design as I wanted the branding to be more prominent on the screen. On hover the navigation options turns grey so that the user is clear where they are pointing to. The navigation bar also has a fixed position which adds to the ease of use for user’s navigation. 

**Home Page**
The page welcomes users to the site. It features a banner with some text which is a feature continued throughout the site. It provides clear information as to where the users are. 
There is a psychedelic background over which a cartoon representation of the band is featured. The background was created by using CSS gradients and is reminiscent of 1960s styling -something fans of the band may appreciate. 

**Flower & Social links**
*Flower*
At the bottom of all the pages there is a red flower image that was used as another nod to the era of the bands beginnings. It forms an attractive separation between the page content and the social links footer. 
*Social Links*
Facebook, YouTube and Twitter Font Awesome icons are used at the bottom of the page allowing users to find the social pages easily (but only after scrolling through this page!). The styling was inspired by the CI resume mini project lessons. On hover the icons change colour. The social icons link to the bands official social accounts on Facebook, YouTube and Twitter. 

**About Page**
Here is where band info is displayed – users can learn more about the band here. I did not include a lot of information in the banner or about the members. The content could be more detailed and this layout would still work effectively. 
*Mobile*
On mobile view each band member has a section with text followed by an image. They have complementary alternating colour backgrounds. Users experience a logical flow. 

*Tablet/Desktop*
On larger screens the band members’ section layout is different providing something else at these screen sizes. The images and text take up a full row alternating between image or text first on the different band members. Users will find it easy to follow as the background colour between members change. 
 
**Music Pages**
*Discography*
A gallery of album covers forms the discography. Users can see the names and release year of the band’s back catalogue. 
*Audio*
Some of the bands famous tracks are listed here in audio players. Users can listen using the controls.  On desktop screen the audio tracks are listed in-line as the audio players themselves are not so interesting to look at I ensured that they do not take up a lot of screen space.** move to testing** I noticed that on sizing down from a larger screen the audio players started to look squashed and added a media query to adjust the width of the audio players at the point that this happens. 
*Video*
Users can watch videos in this area of the music page. As the videos are embedded it is not necessary for users to leave the site.

**News Page**
The news page features three Bootstrap 4 “cards” these were styled to be more rounded than the Bootstrap default and also have a zoom effect on the cover images. Each article is visually appealing and contains information users would look for in news - an image related to the story, a headline, date published and a link to where users can find the full article. 

**Bookings Page**
This page contains a simple form that enables users to begin a booking enquiry with the band, it contains validation for required fields and so will reduce errors when users enter contact information. 

*Features Left to Implement*
+As this project is strictly a static site I have used standard HTML audio players which vary in look based on browser. If I were to add further features I would want to include a custom designed audio player which would require the use of interactive elements.

+Another feature that I would like to include would be to add cookie, privacy, terms and conditions information this would be included in the form of modals so that they do not take up screen space.

+The bookings form to be functional. 


###Technologies Used

+HTML5 – structure 
+CSS – custom styling
+Bootstrap 4 – used for grid layout, basic card structure of news articles and navigation functionality. 
+FontAwesome – used for icons on about, news, music and booking page.  


###Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits

Content

The text for section Y was copied from the Wikipedia article Z
Media

The photos used in this site were obtained from ...
Acknowledgements

I received inspiration for this project from X


















 






