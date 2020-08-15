# Quirky Cafes

### Index

[UX](https://github.com/paulday966/milestone1#ux)

* [Wireframe mockups for desktop site](https://github.com/paulday966/milestone1#wireframe-mockups-for-the-desktop-site)
* [Wireframe mockups for mobile site](https://github.com/paulday966/milestone1#wireframe-mockups-for-the-mobile-site)

[Features](https://github.com/paulday966/milestone1#features)

* [Existing features](https://github.com/paulday966/milestone1#existing-features)
* [Features left to implement](https://github.com/paulday966/milestone1#features-left-to-implement)

[Techologies used](https://github.com/paulday966/milestone1#technologies-used)

* [HTML5](https://github.com/paulday966/milestone1#html5)
* [CSS3](https://github.com/paulday966/milestone1#css3)
* [Bootstrap](https://github.com/paulday966/milestone1#bootstrap)
* [Font Awesome](https://github.com/paulday966/milestone1#font-awesome)
* [Google Fonts](https://github.com/paulday966/milestone1#google-fonts)
* [Github](https://github.com/paulday966/milestone1#github)
* [Gitpod](https://github.com/paulday966/milestone1#gitpod)
* [Embed Google Maps](https://github.com/paulday966/milestone1#embed-google-maps)
* [W3 Schools](https://github.com/paulday966/milestone1#w3-schools)
* [Stackoverflow](https://github.com/paulday966/milestone1#stackoverflow)
* [CSS Tricks](https://github.com/paulday966/milestone1#css-tricks)
* [Coolors.co](https://github.com/paulday966/milestone1#coolorsco)
* [Freefavicon](https://github.com/paulday966/milestone1#freefavicon)
* [W3C Markup Validation Service](https://github.com/paulday966/milestone1#w3c-markup-validation-service)
* [W3C CSS Validation Service](https://github.com/paulday966/milestone1#w3c-css-validation-service)
* [Online JavaScript Validator](https://github.com/paulday966/milestone1#online-javascript-validator-beautifytools)

[Testing](https://github.com/paulday966/milestone1#testing)

[Deployment](https://github.com/paulday966/milestone1#deployment)

[Credits](https://github.com/paulday966/milestone1#credits)

* [Content](https://github.com/paulday966/milestone1#content)
* [Media](https://github.com/paulday966/milestone1#media)
* [Ackowledgements](https://github.com/paulday966/milestone1#acknowledgments)


The idea for this project came to me when I wanted to see a list of coffee shops in different towns and counties on one website. Unfortunately I found this difficult, as I had to do multiple searches to find what I wanted. On my weekend bike rides I have discovered lots of coffee shops, and some of them have a theme, which I have inscluded in this website.

I wanted to change that by creating a website that is easy to use and has information and links to cafes in different towns and counties.

### UX

This website is for both the young and old who want to find out information about cafes quickly and easily. When they come to the website they can choose between three counties, which are East Sussex, Kent and Surrey. After clicking on one of the options in the counties dropdown menu in the navigation menu they will see the cafes for that county with an image of the cafe, a description and information about the place split up into four information cards. Each information card provides easy to see and read infomation to help the user select a cafe. The first information card provides at a glance information, such as outdoor seating, public transport links and the food available. The next information card is how to find us, which has the cafe pinned on Google Maps. The map can be expanded to fill a browser tab or be opened in the Google Maps app. The next information card contains the opening hours and the final information card contains the contact us detials. This includes the address, phone number, email address and website link.

* As a user type, I want to perform an action, so that I can achieve a goal

I want the user to be able to quickly access the list of cafes, with clear and easy to read information. This information can be printed off or written down so they can view it later when they need it.

I want the user to be able to access the site on their smartphone and see the key information such as address and use Google Maps to guide them to the cafe.

At a glance cafe information with Google Maps and Contact Us details


![Image of at a glance information](https://github.com/paulday966/milestone1/blob/master/documentation/images/google-maps-address.jpg)

I want the user to be able to signup to the monthly newsletter, so they can stay up to date with the latest cafe information. This would be done by entering their name and email address into the newsletter sign up fields on the contact us page. Then they would click on the submit button and a box pops up which thanks them for subscribing.

Newsletter signup


![Image of Newsletter signup](https://github.com/paulday966/milestone1/blob/master/documentation/images/newsletter-signup.jpg)

I want the user to be able to add the details of a cafe they would like to be added to the website. This would be done by entering at least the name of the cafe, web site address and city, as the rest of the fields are optional. Once they have entered the information and clicked on submit a message pops up thanking them for submitting the cafe details.

New cafe request


![Image of cafe request submit](https://github.com/paulday966/milestone1/blob/master/documentation/images/cafe-request.jpg)

#### Wireframe mockups for the desktop site

* [Index.html](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/desktop_view/desktop_index.pdf)

* [East Sussex cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/desktop_view/desktop_east_sussex_cafes.pdf)

* [Kent cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/desktop_view/desktop_kent_cafes.pdf)

* [Surrey cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/desktop_view/desktop_surrey_cafes.pdf)

* [Contact Us](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/desktop_view/desktop_contact_us.pdf)

#### Wireframe mockups for the mobile site

* [Index.html](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/mobile_view/mobile_first_index.pdf)

* [East Sussex cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/mobile_view/mobile_first_east_sussex_cafes.pdf)

* [Kent cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/mobile_view/mobile_first_kent_cafes.pdf)

* [Surrey cafes](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/mobile_view/mobile_first_surrey_cafes.pdf)

* [Contact Us](https://github.com/paulday966/milestone1/blob/master/documentation/wireframes/mobile_view/mobile_first_contact_us.pdf)

### Features

#### Existing features

* Feature 1 - Location of the cafe using an embeded Google Map. The user can see at a glance where the cafe is and using the plus and minus buttons the map can be zoomed in or out. The user can click on the link View in larger map and Google Maps will open up in a new tab and give users the full Google Maps experience. If Google Maps in installed on the mobile device it will open up in that

* Feature 2 - Link to cafe website. The user can click on the link to open the website in a new tab and find out more details about the place

* Feature 3 - Newsletter sign up. When the user clicks on the contact Us page the user has the option to sign up to the monthly newsletter, by entering their name and email address. Both are required and a message pops up to remind them to fill these in if they haven't done so

* Feature 4 - Cafe request. When the user clicks on the contact Us page the user has the option to fill in details about a cafe they have found. The minimum details required are the cafe name, website address and city. A message pops up to remind them to fill these in if they haven't done so

#### Features left to implement

My first feature would be to add a photo gallery for each cafe. This would display images in a scrolling carousel of their cakes and inside and or outside of the cafe. The user would be able to click on each image to expand it, and scroll through as many of the photos as the wish and easily close it when they have finished.

The next feature would be a page which split up into three sections, and each county would have one. Each section would have descriptions, links and images for walks and places to visit near each cafe. The links for places to visit would take the user to the website for that place and the links for walks would take the user to different webites with walk ideas.

Another feature would have a page with a Google Map on it to show where all of the cafes are which could be used as another way to search.

My final update would be to have all of the cafes and infomation stored in a database along with lots more cafes. The user would be able to search for a cafe based on search filters.

### Technologies used

#### HTML5

HTML5 was used to build the pages and display the text and images on the screen.

#### CSS3

CSS3 was used to style the cafe images, descriptions, titles and lists on each page. This is to allow the users to view the images and text properly and clearly on large, medium and small screens.

#### Bootstrap

* [Bootstrap](https://getbootstrap.com/)

Bootstrap was used to create and format the following:

* The two sections of the contact us page by clicking on the copy html link and pasting the html on to the contact us page
* It was used to add the column classes to the divs within rows so the content would change responsivley on large, medium and small screen sizes and be clear and   easy to read
* To create the information cards that display for each cafe
* To create the navigation menu at the top of the screen including the dropdown menu

#### Font Awesome

* [Font Awesome](https://fontawesome.com/)

Font Awesome was used to add icons at the beginning of each item in the At a glance information card for each cafe:

* Food
* Outside seating
* Dogs allowed
* Public transport
* Parking

It was also used to add icons at the beginning of the cafe's contact us details:

* Address
* Phone number
* Email address
* Website

#### Google Fonts

I have used Google Fonts to style the font on all pages.

* [Google Fonts](https://fonts.google.com/)

#### Github

I have used a Github repository to store all of the files, images, wireframe pdfs and the Readme.md file.

* [Github](https://github.com/)

#### Gitpod

I used Gitpod to write and save the html, CSS and JavaScript files and store the style.css file in a folder. It was also used to upload the images and wireframes into seperate folders. All of the work was saved to the repository linked to this project by using git commands.

* [Gitpod](https://www.gitpod.io/)

#### Embeded Google Maps

I used this website to input the cafe's location, so that the location is shown on the map with a pin. Before generating the html code I needed, I was able to adjust the size of the map to meet my requirements. Once the code was generated I pasted it into the info card and deleted the parts I didn't need.

* [Embed Google Maps for website Maps generator for free](https://www.embedgooglemap.net/en/?gclid=Cj0KCQjwpNr4BRDYARIsAADIx9w2dCTRcQJCJxIXJn9gCWRinhuiUD1BjqXTQ-_3aUrx3Bvb5CRBA6EaAkWgEALw_wcB)

#### W3 Schools

I used this website to check on what I would need to do to create some of my ideas and also to make sure some of my code in other parts of the websiyte were correct. 

[w3schools.com](https://www.w3schools.com/)

#### Stackoverflow

I used this website to help explain the z-index for keeping the navigation menu at the top of the screen when scolling

[Stackoverflow](https://stackoverflow.com/)

#### CSS Tricks

I also used this website to help explain the z-index for keeping the navigation menu at the top of the screen when scolling

[CSS Tricks](https://css-tricks.com/)

#### Coolors.co

I used this website to find the background colour for all of the pages.

[Coolors](https://coolors.co/)

#### Freefavicon

I used this website to find a suitable fav icon.

[Free favicon](https://www.freefavicon.com/)

#### W3C Markup Validation Service

I used this website to make sure each page of html was correct, and then I was able to correct the errors.

[Markup Validation Service](https://validator.w3.org/)

#### W3C CSS Validation Service

I used this website to make sure the style.css page was correct, and then I was able to correct the mistakes.

[CSS Validation Service](https://jigsaw.w3.org/css-validator/)

#### Online JavaScript Validator BeautifyTools

I used this website to make sure the file my_functions.js was correct, and then I was able to correct the mistakes.

[Online JavaScript validator](http://beautifytools.com/javascript-validator.php)

### Testing

I have not automated my testing, so below are the steps to achieve the following using the desktop menu. If the user is viewing this website on a smart phone the menu will responsively change to fit on the small screen. The user will need to tap on the three dashed lines at the right hand side of the mobile menu. The menu will appear and will show Home, Counties with a little downward facing arrow and Contact Us. By tapping on Counties the sub menu will appear and the user can select the county of choice. 

1. Go to one of the counties
* i Click on the Counties link in the navigation menu
* ii Click on one of the three options that appear in the dropdown list. The options are: East Sussex, Kent and Surrey
* iii The selected page will open and you can browse the list and read about the cafes

2. How to find Us using Google Maps
* i Follow the steps in step 1. Go to one of the counties
* ii Find the cafe you want and you will see the Google Map
* iii The user can click on the plus or minus signs in the bottom right hand corner of the How to find us card to zoom in or zoom out. This will help them see more or see less of the area
* iv The user can also click on the View larger map link near the top left hand corner and the map will open up in Google Maps if it's installed, or in a new tab in the default browser

3a. Contact Us. This page has two parts. The first part is the Newsletter signup at the top of the page and I have added placeholder text to show the user how the email address should look when it's typed in
* i Click on the Contact Us link on the navigation menu
* ii If I click on the Submit button without entering my name or email address a message pops up underneath the Name field and says the following. Please fill in this field and nothing will be sumbitted

The following image shows what happens when the submit button is clicked on without entering the required text


![Image of what happens when the user doesn't enter their name and clicks on the submit button](https://github.com/paulday966/milestone1/blob/master/documentation/images/pressing-submit-without-user-input.jpg)

* iii For this part of the test I used the email address test@example.co.uk. If I type my name in, but leave the email address field blank and click on Submit a message pops up underneath the email address field saying Please fill in this field
* iv If the name has been added to the name field, but only the first part of the email address has been added and the user clicks on Submit a message pops up underneath the email address field. It says Please include an '@' in the email address. 'test' is missing an '@'
* v If the name has been added to the name field, but only the first part and the @ symbol have been entered and the submit button is clicked a message pops up underneath the email address field. It says Please enter a part following '@'. 'test@' is incomplete
* vi If the name has been added to the name field and the email address is missing the last part so it looks like test@example and the submit button has been cliked a message pops up underneath the email address field. It says Please match the format requested
* vii When the name has been added to the name field the same message, Please match the format requested pops up if the email address looks like this. test@example.co when the submit button is clicked
* viii If I type the same as the previous step but add a dot after the co and click on the submit button a message pops up and says the following. '.' is used at the wrong position in 'example.co.'.
* ix If I type in my name and the email address in the correct format, test@example.co.uk and click on Submit it is successful. A box pops up with the message Thanks for subscribing to our newsletter. If I click on the OK button in the pop up message it dissappears and the text in both fields is removed
* x If I type text in any of the fields I can cancel this request and clear the fields by clicking on the Cancel button

3b. Contact Us. The second part of Contact Us is the cafe request form. I have added placeholder text in the cafe website address field to show how it should look
* i Click on the Contact Us link in the navigation menu
* ii If I click on the Submit button without typing text into any of the fields a message pops up underneath the Cafe Name field which says Please fill in this field
* iii If I type in a cafe name and nothing else and click on submit the form won't be submitted because a message pops up underneath the Cafe website address field and says Please fill in this field
* iv For this part of the test I used the website address https://cafetest.com. If I type in the cafe name and the first part of the website address, http:// or https://, or any part of this then click on submit a message pops up saying Please enter a URL
* v If I type in the cafe name and the first part of the website address, http:// or https:// and cafetest, then click on Submit the cursor moves to City and a message pops up saying Please fill in this field and nothing is submitted. The cafe website address field accepts http://cafetest or https://cafetest and doesn't ask for .com or dot something else. I have added the following text underneath the cafe website address which says the following. You can copy the website address of the cafe into this box
* vi If I type in the cafe name, the website address and the city then click on submit a dialog box pops up. The message says Thank you for sending us details of the cafe and there is an OK button. If I click on OK the box disappears and the boxes that have been filled in are now empty
* vii The cafe name, website address and city are required fields, as I thought that would be the minimum required for me to find more about the cafe
* viii The remaining fields are address, postcode and Do you have any additonal information that would be useful? are optional
* ix If I type text in any of the fields I can cancel this request and clear the fields by clicking on the Cancel button

To help me make sure my website is responsive with different screen sizes, while I was building it I tested the website with Google Chrome's developer tools and changed the responsive screen size. I regularly checked this using the iPad, iPad Pro and various smartphone screen sizes from the Google Chrome developer tools drop down menu next to the screen size. When I found problems with the responsive screen size I made changes to the Bootstrap col sizes for medium and large screen sizes.

When I had built enough of the website I started to use Github Pages and with the link it provides tested the website with Chrome, Sarafi and Opera on my Mac, and Chrome, Edge and Opera on Windows. All of the browsers on Mac OS and Windows responded correctly, with the menu changing to the mobile view correctly for small screens. The text, images and info cards all responded correctly when the screen size was reduced from large screen to tablet to smartphone. The footer text and social media links moved positions correctly when the screen size was reduced.

The following images show how the website looks on a large, medium and small sized screen.

How the website looks on a large screen


![Image of how the website looks on a large screen](https://github.com/paulday966/milestone1/blob/master/documentation/images/desktop-view.jpg)

How the wesbite looks on a medium screen


![Image of how the website looks on a medium sized screen](https://github.com/paulday966/milestone1/blob/master/documentation/images/tablet-view.jpg)

How the website looks on a small sized screen


![Image of how the website looks on a small screen](https://github.com/paulday966/milestone1/blob/master/documentation/images/smartphone-view.jpg)

When I tested the website on my iPhone and iPad it looked as expected, repsonded correctly and the mobile menu and all of the links worked correctly. The validation on the contact Us form worked correctly. When the correct text was typed in, the required boxes were filled in and the Submit button was pressed the dialog box poped up with the thank you message and the OK button. When I pressed OK on the pop up message the text in the fields was removed and it was ready for more text to be entered.

While I was working on the Contact Us page I decided it needed to be easier for the user to know which field they were typing in. In the CSS for text, email and url types I added the on focus rule for each one so that a border appeared around the field when the user clicked in it. While I was adding the border rule I found that it wouldn't work for the textarea type so I looked it up on the Internet and coudln't find how to do it. When the user clicks on the textarea, which is called Do you have any additional information that would be useful?, a blue outline appears, which does help.

Onfocus black border


![Image to show the onfocus black border](https://github.com/paulday966/milestone1/blob/master/documentation/images/onfocus-border.jpg)

While I was building the website I found lots of errors in the HTML and CSS which I was able to fix. Once I had fixed errors, I rechecked the pages to make sure the errors didn't happen again. Now that the website is finished I haven't found any bugs and my friends that have tested it didn't find any errors.

### Deployment

To make it easier for me to test my website in different browers and different devices I deployed my website to Github Pages. This allowed me to test the website on smartphones, tablets, Windows laptops and desktops, in Windows running in Parallels and on my Mac.

To deploy the website I followed these steps

1. Logged into my GitHub account
2. Clicked on the link for my milestone1 project
3. On the row of icons near the top of the screen underneath the repository name I clicked on the Settings option (the last option)
4. Scrolled down to the GitHub Pages section
5. At the top of the GitHub Pages section there is a section called Source
6. In this section I clicked on the dropdown menu called Branch and selected master
7. Then I clicked on Save
8. Once I had done that the published link appeared just above the source section, which is https://paulday966.github.io/milestone1/

If I wanted to download my code so I could run it locally I would follow these steps

1. Log into my GitHub account
2. Click on the link for my milestone1 project
3. On the row of icons near the top of the screen underneath the repository name click on the <> Code option (the first option)
4. Just underneath this row of options, click on the green button labbelled Code with two downward facing arrows
5. Three options will appear in the dropdown.

#### Option 1 Clone with HTTPS

The first one will allow you to Clone with HTTPS

#### Option 2 Open with GitHub Desktop

Clicking on the second option will allow you to Open with GitHub Desktop. If you don't have the program installed it will take you to a webpage where you will be given the option to download the program for your operating system.

#### Option 3 Download ZIP

The third option will allow you to download a zip file with all of the files in it to your computer.

There is no need to use external hosting for this project as GitHub Pages can generate a link that allows me to access the website on mobile devices and desktops anywhere I want. I'm able to use GitHub pages because this project doesn't have a back end to it such as a database. It only has static pages. This will also save a lot of time as I don't have to go through the process of setting up an account with an external hosting company and making sure the site gets transfered accross properly and GitHub is free to use.

### Credits

#### Content

The navigation menu for each page was copied from the mobile first Whiskey Drop mini project I created earlier in the course. This menu was exactly what I needed, so I changed all of the links and names of the links to the pages in my project and added in the contact page. As I didn't need the sign up section this was deleted.

I copied the footer from the resume project created ealier in the course, then deleted the links to LinkedIn, Pinterest and YouTube. I changed the name from Social to Social Media and removed the uppercase and general-sub classes. I added my own class to the social media title of footer-heading and changed the social-links class to social-media-links. I deleted the download CV link as this wasn't needed and deleted the wording for the about section and added my own wording. I removed the uppercase and general-sub classes and added the footer-heading class, then I deleted the About title.

##### East Sussex Cafes

I copied the description text, address, phone number and the email address for the cafe for Pooh Corner from [Pooh Corner](https://www.poohcorner.co.uk/). I added these details to the Winnie the Pooh cafe on the East Sussex cafe page.

I copied the description text, address, phone number and email address for Hanushka Coffee House from [Hanushka Coffee House](https://www.facebook.com/pg/Hanushka-Coffee-House-108537019250225/about/?ref=page_internal). I added these details to the Hanushka Coffee House cafe on the East Sussex cafe page.

I copied the address, tearooms phone number and email address for Bluebells Tearoom from [Bluebells Tearoom](https://www.bluebellstearoom.co.uk/). I added these details to the Bluebells Tearoom cafe on the East Sussex cafe page. I created the desciption for this cafe myself

##### Kent Cafes

I copied the description text for the cafe for The Shoreham Aircraft Museum tearoom from [Shoreham Aircraft museum tearoom](http://www.shoreham-aircraft-museum.co.uk/teas.htm). I copied the address, phone number and email address from [Shoreham Aircraft museum tearoom opening](http://www.shoreham-aircraft-museum.co.uk/opening.htm). I added these details to The Shoreham Aircraft Museum tearoom on the Kent cafe page.

I copied the address, phone number and email address for Steep Street Coffee House from [Steep Street Coffee House contact](https://www.steepstreet.co.uk/contact/). The cafe description came from [Steep Street Coffee House](https://www.steepstreet.co.uk/the-steep-street-coffee-house/). I added these details to the Steep Street Coffee House cafe on the Kent cafe page.

I copied the address and phone number for The Curious Cupcake Cafe from [The Curious Cupcake Cafe](https://www.cupcakecafemargate.co.uk/) and the email address from [The Curious Cupcake Cafe contact](https://www.cupcakecafemargate.co.uk/contact). I added these details to The Curious Cupcake Cafe on the Kent cafe page.

##### Surrey Cafes

I copied the address, phone number and email address for The Dabbling Duck from [The Daddling Duck](https://www.thedabblingduck.uk.com/). I copied the description from [The Dabbling Duck about us](https://www.thedabblingduck.uk.com/pages/about-us). I added these details to The Dabbling Duck cafe on the Surrey cafe page.

I copied the address and phone number for the cafe for The Headley Village Store and Tea room from [Headley tearoom contact](https://www.headleytearoom.co.uk/contact). The email address came from [Headley tearoom about](https://www.facebook.com/pg/headleyvillagestores/about/?ref=page_internal). I copied the cafe description from [Headley tearoom about](https://www.headleytearoom.co.uk/). I added these details to The Headley Village Store and Tea room on the Surrey cafe page.

I copied the address, phone number and email address for Cromwells from [Cromwells](https://cromwellcoffeehouse.co.uk/). The description came from [Cromwells about](https://cromwellcoffeehouse.co.uk/about-us/). I added these details to the Cromwells cafe on the Surrey cafe page.

### Media

#### Happy coffee image

The image happy coffee came from [Pexels](https://www.pexels.com/photo/happy-coffee-6347/), which I used as a temporary image while I built the website

#### Index page images

The cafe image used for East Sussex cafes on the index.html page came from [Bluebells Tearoom gallery](https://www.bluebellstearoom.co.uk/gallery)

The cafe image used for Kent cafes on the index.html page came from [Shoreham Aircarft mueseum teas](http://www.shoreham-aircraft-museum.co.uk/teas.htm)

The cafe image used for Surrey cafes on the index.html page came from [Cromwells Coffee House about us](https://cromwellcoffeehouse.co.uk/about-us/)

##### East Sussex cafe images

I copied the cafe image for the Winnie the Pooh cafe from [Pooh Corner](https://www.poohcorner.co.uk/)

I copied the cafe image for the Hanushka Coffee House from [Hanushka Coffee House Facebook photos page](https://www.facebook.com/pg/Hanushka-Coffee-House-108537019250225/photos/?ref=page_internal)

I copied the cafe image for the Bluebells Tearoom from [Bluebells Tearoom gallery](https://www.bluebellstearoom.co.uk/gallery)

##### Kent cafe images

I copied the cafe image The Shoreham Aircraft Museum tearoom from [Shoreham Aircarft mueseum teas](http://www.shoreham-aircraft-museum.co.uk/teas.htm)

I copied the cafe image for the Steep Street Coffee House cafe from [Steep Street Coffee House Facebook photos page](https://www.facebook.com/pg/Steepstreet/photos/?tab=album&album_id=1029824603734471&ref=page_internal)

I copied the cafe image for The Curious Cupcake Cafe from [The Curious Cupcake Cafe](https://www.cupcakecafemargate.co.uk/)

##### Surrey Cafes

I copied the cafe image The Dabbling Duck cafe from [The Dabbling Duck about us](https://www.thedabblingduck.uk.com/pages/about-us)

I copied the cafe image for The Headley Village Store and Tearoom from [The Headley Village Store and Tearoom Facebook photos page](https://www.facebook.com/pg/headleyvillagestores/photos/?tab=album&album_id=254500014918830&ref=page_internal)

I copied the cafe image for Cromwells cafe from [Cromwells Coofee House about us](https://cromwellcoffeehouse.co.uk/about-us/)


### Acknowledgments

I got the inspiration for this project from cycling with the [Cheam and Morden CTC group](https://cheamandmorden.blogspot.com/) over many years. I found very few websites that had inforamtion about lots of different cafes in one place, and had to remember the cafe and website so I could look it up and get the details I needed.

I would like to thank my tutor Aaron Sinnott for helping me with this project, answering my questions and giving me advice and suggestions. It has been really useful and has helped me to think about each part and how I can improve it.

I would like to thank my friend Anja in the walking group I'm a member of for suggesting the title Quirky Cafes. This is much better than Cafe Locator, the title I was originally using.

I would also like to thank two other friends in the walking group Andrew Dodd and Helen Sheen for reviewing my site on Windows, Mac and smartphone. They pointed out errors, which I was able to fix.

Sent the following email to the nine cafes used in this website asking for their permission to use their text and images.

Hi,

I'm currently studying an online full stack developer course with Code Institute and Learning People. This course teaches me how to build websites and how to write programs. For my first project  I'm building a website with links and information about coffee shops.

With your permission I would like to use the text and images from your website, so I can have a description of the place, what your offer, such as hot and cold food and an image to show what the place looks like.

Thank you

Paul Day
