#First Milestone Project

For this project I chose to build a website for a local Dungeons & Dragons group, which meets every 
weekend to run sessions for veterans of the game, those who have only played a little, and for complete newcomers. 
This fictional group meets at a local board game cafe, and on Sundays they run sessions for anyone who wants to 
learn the system and run a game so they can learn by playing.

##UX

The intended users of this website would be anyone in the local area looking for a Dungeons & Dragons group to play 
with regularly, or anyone who wants to learn in a more interactive environment but their friends aren’t interested. 
They would visit this website and see that there is a group nearby that meets specifically to play D&D, and is also 
happy to teach anyone to play.

##Features

###Existing Features
    
    * Header bar - allows users to achieve navigation to three of the sections without having to scroll on mobile, 
    by having them open the burger menu and press the navigation link appropriate to the section they want to see.
    * Jumbotron – allows users to easily see when the group meets at a glance, and provides a navigation button to 
    the section that tells new users more details on the learner sessions.
    * Contact us section – allows users to access google maps, by selecting the anchor text next to the “Find Us:” text. 
    Allows users to email the group at any point by selecting the anchor text next to the “Email Us:” text. 
    * Footer – allows users to achieve navigation to the groups social media presence, by providing links through easily 
    discerned images for Facebook, Instagram, and Twitter.

###Features Left to Implement
    
    * A newsletter sign up form, for regular email updates about the group and campaigns



##Technologies Used

    *HTML 5
        *The project uses HTML 5 to create the webpage.
    *CSS 3
        *The project uses CSS 3 to customise the look of the website
    *Bootstrap v4.4
        *The project uses Bootstrap to simplify CSS processes
    *Font Awesome v4.7
        *The project uses Font Awesome to provide images for social media links and alongside the header links

##Testing

With each stage of development I utilised google chromes developer tools to see how my website would function on varying screen sizes.
On smaller screen sizes using columns for each section of writing would cause errors in the display of text and the jumbotron image. 
So custom CSS was needed to set the properties of the background image, and bootstrap was used to create columns on larger screen sizes 
but that would leave it at one column on smaller screens.
4K resolution brought the new issue of the font size being too small to read. This required the addition of media queries to increase 
some of the text sizes. Which created another issue in itself, the footer hid section text even though it was fixed to be at the base 
of the body section. This was fixed by using the developer tools in chrome to increase the space reserved for the footer until it no longer 
covered any text.
There is an issue on screen sizes smaller than 360 pixels wide in chrome dev tools, where the jumbotron doesn’t fill the width of the screen, 
and most of the right side of the screen is actually blank. There is the issue where the footer covers text as well at that resolution. 
There is a similar issue on firefox, using it’s dev tools, where a horizontal scrollbar is created at the same resolution (320 x 797) 
along with the same footer issue seen on chrome.

##Deployment

Having written the code in Gitpod, it was quite easy to deploy it on GitHub, I did this by using the git commands to add (git add), 
and then commit (git commit -m) my files to my Gitpod session, and then used the git push command to push ithe changes through to my master branch.
The deployed version is different to the development version as initially it was going to be a three page site, I then realised the information 
could be more easily read and navigated if it was all on one page. I then had to create links in the header to different sections of the page by 
using the ‘id’ element in my HTML.
If you want to run my code locally, choose the IDE you’re most comfortable with, if that is Gitpod then type into the terminal ‘python3 -m http.server’ 
to open a port that will run the site in your web browser. For other IDEs you will have to check their help files as to how to do this.

##Credits

###Content
    
    * The CSS for the body and #footer sections was taken from 
    https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ and modified to work more efficiently

###Media
    
    * The photo used in this site was taken by me

###Acknowledgements
    
    * I received inspiration for this project from my D&D sessions with my friends