<!---->
Nina-George Beautiful Jewels

This is my MS1 project and is a website for a family member's bespoke jewellery business. The site is intended to allow propective customers to view samples of the jewellery creations then book an appointment with the company to discuss their own design and order requirements.
-----------------------------------------------------------------------------------------------------------------

UX

I mocked up the pages in a notebook (old school!) as when I started I did not know about wireframe software (which I do now so plan to use for my next projects).  However I have transferred my original designs and notes to Balsamiq and these are in the project directory in a folder called 'wireframes'.  

Changes to original designs as follows:

Originally I wanted a bridal page but this was beyond my scope once I started coding in terms of content so I suppressed this but the page is still in the directory for future dev.

Also my contact form was originally going to be a left hand column with an image on the right but this cluttered the layout so I changed it to stretch across the page, and removed the image idea to the right of the contact form.

Also the footer was going to be white but this looked wrong (like the pages didn't have a frame so I changed the colour to the plummy ones and made the text white.)


I wanted a compelling main home page image with a classic feel and regal colours.  I wanted to give the user a glimpse of the family work and creations and sign post the user to the contact page.  I wanted the FB icon originally in the footer but it did not look right.  I sought a new style of (FREE!) icon and matched the colouring to the purple shades used throughout the site, then uploaded it and relocated to the navbar whcich felt better in terms of user journey.

The company is based in Bucharest (where opulent and custom made jewellery is sought after) and runs primarliy on repeat business and word of mouth and has done for 30 years.  It is organically grown and the site is intended for customers who have heard of them and want to have a look before booking personal appointment.  It is also intended that links to the site would be posted on social media.  THe social link on the site is linked to the company's actual FB page.

As the company provides a bespoke product, at present the best way to achieve a growth in appointments is to start with a site that allows them to work in their comfort zone then build on the site.  Future plans include an 'off the peg' page where simple classic designs can be purchased by customers with less complex design requirements and may help with channel shift as younger generations look to more fashionable, mainstream designs.

With this in mind I developed the site using dev tools and within the responsive deign mode, checking the layout and responses in IE simultaneously.  The users primarly would be phone and tablet users, their story as follows: 

Interested users
Follow the link to the website via FB or as a result of word of mouth.  They review the workshop video and teaser quote left outside of the standard quote box view mobile view and either follow the link to the contact page from there or visit the creations page via link in the offer.

The check box on the contact form is required prior to submit (which currently is not connected to db but refreshes the form on click)


Existing Features
Video Feature (visit.html with embedded workshop file)- allows users to review the workshop
Photo gallery (creations.html) - allows users to browse samples for ideas or to tease potential orders
Contact page (contact-us.html)- allows users to make request an appointment call or even just send a message by filling out the contact form


Features Left to Implement
As the company moves on to ordering online from a stock of premade jewellery, add a ring sizing mechanism and a wedding band and engagement ring design selection.  Also add an order form with payment frames to allow purchase of premade stock items.

---------------------------------------------------------------------------------------------------------------------
Frameworks


This was coded in Cloud 9 AWS to start with but I had so many issues with timeouts I moved the whole project to VSCode editor.

HTML5 (https://en.wikipedia.org/wiki/HTML5) was used to provide the structure of the site.  

The project uses JQuery (https://en.wikipedia.org/wiki/JQuery) to simplify DOM manipulation and event handling (such as the alert following the click of submit button on the contact-us page)

To provide a style framework I downloaded Bootstrap's CDN from https://www.bootstrapcdn.com/, and then used CSS to style content boxes, buttons and colours. Also used CSS to style the media embed on the Visit page containing the video. 

I also used https://www.thesitewizard.com/html-tutorial/insert-video-using-html5.shtml to learn how to embed video into HTML5


I made use of Stack overflow (https://en.wikipedia.org/wiki/Stack_Overflow) primarily for bug fixing, such as ensuring the submit button refreshes the form data in all browsers and sticking the footer down as I had some issues with renderingon IE.  This was actually fixed by adding a bottom margin to the body element.
------------------------------------------------------------------------------------------------

Testing

All testing was carried out manually in IE, Chrome and firefox with friends checking the site on a variety of devices.

The navbar items were testing by hopping between them and ensuring each linked up.  Social media icon was tested manually and home page logo.

During testing I had issues with the footer, originally taking the bootstrap footer ID but later replacing it with a simple fixed row following peer review feedback that the footer covered some of the homepage content.

There are links to the contact us page on the creations and visit workshop pages to allow the user to watch the workshop video, see the portfolio of samples and then book an appointment.  The birthday promotion is also on both these pages - (future dev, allow promo codes added to contact page for discounted purchases)  Each link tested in IE, CHrome and Firefox on a variety of devices.

One issue I came across was during testing was that vscode is not case sensitive when viewing in live server mode but when you deploy to git hub any case issues in nav bar items are revealed!  My visit page was inaccessible during the first deployment as a result of this which was found and fixed.

The images were ovalo shaped to begin with (rectangle images set to border radius 50%) but because on the dimensions the images showed in different sizes so I changed these to circle images which stacked much better on desktop and mobile view.

The video plays on all devices but I would have liked automatic fill screen then reduce back on end of play.

The contact form requires Name and Telephone number as a minimum for contact purposes and you can't submit this without population of these as the form will highlight these fields and remind you.  I found some intermittent issues here though dependant upon user cache settings where repeated entry allows the submission of an empty form on Android.  I have not yet rectified this or found a fix.

On desktop the contact form is spread out across the screen and stacked up on mobile.

The success message returned is a js message which appears as a pop up at the top on the screen or as an overlay on iphone and android.

Deployment
I used Git hub as a hosting platform for this project.  I set up an account on github, opened a repository (https://github.com/Flossie38/Nina-George.git) and the live site is deplyed to https://flossie38.github.io/Nina-George/.

There are no differences between the deployed version and the dev version other than case sensitivity present in the deployed version that does not exist when working in VScode.



Credits

Content
copy content was written by me from scratch.

Media
The photos and workshop video used in this site were obtained from Golden Queen Face book page with kind permission of Roxanna Simionescu, Nina Simionescu and George Simionescu of the Golden Queen family Bucharest.

Acknowledgements
I received inspiration for this project from the Golden Queen Facebook page and conversations with the Roxanna Simionescu.