<!---->
Nina-George Beautiful Jewels

This is my MS1 project and is a website for a family member's bespoke jewellery business. The site is intended to allow propective customers to view samples of the jewellery creations then book an appointment with the company to discuss their own design and order requirements.


UX

I mocked up the pages in a notebook (old school!) as this is my best way of designing.  Originally I wanted a bridal page but this was beyond my scope once I started coding in terms of content so I suppressed this but it is still in the directory.

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
Contact page (contact-us.html)- allows users to make an appointment or even just send a message by filling out the contact form


Features Left to Implement
As the company moves on to ordering online from a stock of premade jewellery, add a ring sizing mechanism and a wedding band and engagement ring design selection.  Also add an order form with payment frames to allow purchase of premade stock items.


JQuery
The project uses JQuery to simplify DOM manipulation.

HTML was used to provide the structure of the site.  To provide a style framework I downloaded Bootstrap's CDN from https://www.bootstrapcdn.com/, and then used CSS to style content boxes and colours. Also used CSS to   I 

https://www.thesitewizard.com/html-tutorial/insert-video-using-html5.shtml to learn how to embed video into HTML
I made use of Stack overflow primarily for bug fixing, such as ensuring the submit button refreshes the form data in all browsers and sticking the footer down as I had some issues with renderingon IE.  This was actually fixed by adding a bottom margin to the body element.


Testing

The testing was carried out in IE, Chrome and firefox with friends checking the site on a variety of devices.

During testing I had issues with the footer, originally taking the bootstrap footer ID but later replacing it with a simple fixed row following peer review feedback that the footer covered some of the homepage content.

There are links to the contact us page on the creations and visit workshop pages to allow the user to watch the workshop video, see the portfolio of samples and then book an appointment.  The birthday promotion is also on both these pages - (future dev, allow promo codes added to contact page for discounted purchases)


------------------------------
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
The photos used in this site were obtained from Golden Queen Face book page with their kind permission
Acknowledgements
I received inspiration for this project from X