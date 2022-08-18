# Motor Neurone Disease Ireland

Visit the deployed website [here](https://murphd44.github.io/mnd-ireland/)   ***change this link later

•	Motor Neurone Disease Ireland is a fictional charity organisation for patients with motor neuron disease and their families. It is dedicated to providing information, care, and support for both patients, their carers, and families.

•	The purpose is provide an information resource and a dedicated helpline and contact which can help direct the patient, carer, or family member to the appropriate information, or healthcare professional.


## Table of Contents

Add contents here later***


## User Experience (UX)

### Goal of the Project

•	The webpage should have a clear attractive design, and appear welcoming and professional.
•	Display to the user the key information on the homepage, which encapsulates what the site is about.
•	Provide contact information, clearly displayed on the home page.
•	Offer users the opportunity to donate to the organisation, which will allow maintenance and provision of a quality service.

### User Stories:

•	As a website user, I need to be able to be able to navigate through the pages easily.
•	As a website user, I do not wish to be overwhelmed with information, I would like to see the key information, quickly and easily.
•	As a website user, I want to be able to contact the service easily including email, phone, and by social media.

### Website Desing - Color Scheme:

Images here of colors*

The colors chosen were based around the MNDI logo image, which is a light orange colour. The logo was designed using [Adobe Express](https://express.adobe.com/express-apps/logo-maker/). The logo was designed in a number of different colors and styles. The colors were tested on the website, however it was difficult to match some colors to others. It was found that the orange had more complementary colors which could be matched, producing a more attractive color scheme.

A website called [Image Color Picker](https://imagecolorpicker.com) was used to identify the logo color. The website then suggests colors that are complementary to this. Colors were then chosen and the color codes were copied into the website CSS code.


### Website Design - Fonts:

Lato was chosen for the body text. It was chosen as it is a clear, precise, and professional looking font.

Roboto was chosen for h1 and h2 headings. Roboto was chosen for its strong clean lines, and the friendly welcoming style for a website such as a charity website. It is known to pair well with Lato.


### Site layout:

The site layout was designed by hand sketching. It shows placement of the different elements within the page. A sample sketch of the index.html page is shown below.

## Features:

### General:

•	The website is responsive across all devices including mobile, tablet, laptop, and desktop.

•	A consistent color scheme and layout across the website, which presents information clarly to the user.

### Header:

Header image here*

•	The header contains the charity logo and heading to the left side and a navigation bar to the right side. All elements are responsive across all devices.

•	The logo and heading both also act as links back to the index.html page.

•	The navigation bar has a hover effect, whereby the user can easily see that links are clickable. The navigation bar also has a feature on the donate link where is appears as a button. The style of this button also changes when hovered over with a mouse. This button also maintains a consistent style and color scheme with the form page submit button.

### Footer:

Footer image here*

•	The footer includes a fictional business address to the left side and social media links to the right side. 

•	Social media links are responsive across all devices. The social media icons change color when hovered over with a mouse. The color change is consistent with the color scheme in the header hover pseudo elements.

### Home page (index.html) Page:

#### Main image:

Hero image here*

•	The main image is to draw the users attention to the centre of the page. It is used to create a good initial impression on the user. The image used represents care and support in a time of great need. It is not unnecessarily down-beat, as the message of this website is one of hope, care and support.

•	It contains a text box, which also conveys a positive message for the user.

#### What We Do Section:

Image here*

•	This section contains three text boxes with key information to the user on what the charity organisation offers as services. 

•	The boxes are responsive across all devices, and contain font awesome logos, which quickly signpost and alert the user to what the content of the box is about.

#### Contact Section:

Image here*

•	This section contains a helpline number and contact email. As with the previous section, font awesome icons improve user experience and alert the user to the nature of the content. 

•	This information box is also responsive across all devices.


### About MND Page:

#### Information box sections:

Image here*

•	This section contains five text boxes which are arranged in an alternating left and right pattern to create a zig-zag effect. The boxes are interspersed with images reflecting the text content of the boxes. 

•	The style of the text boxes matches the style and color scheme used on the index.html page, to ensure a consistent user experience.

#### Images:

1 sample Image here with box and image side by side*

Images are interspersed between the text boxes. Both the text boxes and images are responsive across all devices.


### Donate Page:

#### Banner image:

Image here*

The image at the top of the form page adds to the form page which would otherwise be too plain.

The image contains text overlaid on it is clear white font. The text is to convey to the user the reason why donation is important.

The image is responsive across all devices.

#### Donate Form Section:

Image here*

•	The donate form allows the user to donate an amount of their choice and also to sign up for further information via a newsletter. 

•	The form color scheme matches the style of the website, using a matching color scheme for the form border.

•	The form is designed to be responsive across all devices.


Technologies Used:

Programming Languages Used:

[HTML5](https://en.wikipedia.org/wiki/HTML5)

[CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)

Frameworks, Programs, and Web Resources Used:

•	[Google Fonts](https://fonts.google.com/)

o	Google fonts was used to choose and import the fonts Lato and Roboto. The were imported for use into the style.css file.

•	[Adobe Express](https://express.adobe.com/express-apps/logo-maker/)

o	The header logo was designed using Adobe Express.

•	[Image Color Picker](https://imagecolorpicker.com/en)

o	This website was used to identify the CSS code for the logo color. It was then possible to use this CSS color code to apply colors and complementary colors across the website.

•	[GitPod](https://www.gitpod.io)

o	Git pod was used as the code editor for the project for writing, commiting, and finally pushing code to GitHub.

•	[GitHub](https://github.com)

o	GitHub was used as a storage repository for the project after it was pushed from Gitpod.

•	[Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)

o	Chrome dev tools was used throughout the whole process of website development to check how different elements of code worked together and to assist in trouble shooting. It was also more heavily used in testing responsiveness of the website.

•	[W3C Markup Validator](https://validator.w3.org)

o	This website was used to validate the HTML code for the three pages.

•	[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

o	This website was used to validate the CSS code for the website.

Other resources here********


Testing

Testing User Stories: Enter here*

Text here…..

Code Validation:

The [W3C Markup Validator](https://validator.w3.org) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) websites were used to validate all the HTMl pages and the CSS style sheet for this project.

Details on validation error and corrections here**

The W3C Markup Validator found an error on the header for all three index.html, about.html, and donate.html pages. This error related to a button element being enclosed within an anchor element which is not allowed. The element, button must not appear as a descendant of the anchor element. As an alternative an id selector targeting the css code instead of the button element selector was used as a replacement.

The W3C CSS Validator found an error relating to padding of the fieldset within the form page. A comma had been added between the padding values, which means it didn’t work. When this was fixed, it was decided the padding was not required, thus the padding was removed from the fieldset. No other errors were found.



Accessibility:

Lighthouse was used within Chrome Developer Tools to assess the performance and  accessibility of the website across mobile and desktop devices.

Comment on reports here******

Lighthouse Reports:

Home Page (index.html):

Image here*


About MND Page:

Image here*


Donate Page:

Image here*


Testing Using Specific Tools:

[Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) 
As previously explained above, Chrome dev tools was used throughout the whole process of website development to check how different elements of code worked together and to assist in trouble shooting. It was also more heavily used in testing responsiveness of the website.

[Am I Responsive?](https://ui.dev/amiresponsive)
Am I rsponsive was used to check responsiveness of the website on a number of device scree nsizes at once.


Manual Testing:

•	Browser Compatibility:

The website has been tested on the following browsers:

Safari:

No issues regarding appearance, functionality or responsiveness.

Google Chrome:

No issues regarding appearance, functionality or responsiveness.

Mozilla Firefox:

No issues regarding appearance, functionality or responsiveness.

Microsoft Edge:

No issues regarding appearance, functionality or responsiveness.


•	Device Compatibility:

The website was manually tested across a number of devices including:

Macbook Air 13.6”

Macbook 12” (2016 model):

Toshiba Satellite L755-13J

iPhone 12 mini

iPhone 13 ProMax


•	Manual Tests Completed for Common Clickable Elements:
o	Header and Footer
o	Tested across all three pages. 
	Clicking the header logo, and header heading will bring the user to the home page (index.html).
	Clicking each of the nav bar links will bring the user to the appropriate website page.
	Hovering over links in the nav bar will highlight the clickable link using an underline and alternate color.
	Clicking the social media icons will bring the user to the desired social media page, opening the link in a new tab.

o	About MND Page
	There are no clickable elements to this page.

o	Donate Page
	When filling out the donate form the user is required to complete certain fields before submitting. First name, last name, and email are required in order for the form to be submitted. Need to change form so one donation amount can be selected**************
	Hovering over the input boxes changes the border color to the orange form theme color, highlighting the input box to the user.
	Hovering over the submit button will change the color and font of the button to match the same style used for the donate link button in the nav bar.


Finished Website:

Image here* of home page for desktop and mobile

Image here* of MND info page for desktop and mobile

Image here* of donate page for desktop and mobile


Deployment Of website:

The website was developed using GitPod *hyperlink, the code was commited and pushed to GitHub using the GitPod terminal window using Git commands.

GitHub Pages:
The steps to deploying the website were as follows:

1.	Log-in to GitHub and find the GitHub repository under the top right navigation menu icon. 
2.	Scroll down and click Your repositories.
3.	Select mnd-ireland link.
4.	Select the Settings menu link (which sits above the green “code” button.
5.	Scroll down and locate the Pages menu item on the left hand side menu of the page.
6.	Under Build amd Depoyment heading, there is a source heading, with an input menu, check deploy from branch is selected.
7.	Below this, under a heading called Branch, selct the left drop down menu called none, and select main instead.
8.	The page will refresh automatically.
9.	Then after waiting some time for the site to build, refresh the page again and a link to the website will be generated for use.


Credits

Website Code Content

All website code is original and written by the developer.

Media Content

Pexels *hyperlink:

Open source free stock images used from this website.

Hero image on home page: “Joyful adult daughter greeting happy surprised senior mother in garden” by Andrea Piacquadio. From Pexels.


About MND Page Images:

Drawing of motor neuron taken from: https://www.simplypsychology.org/motor-neuron.jpg

Image of MND Patient, former rugby league player, Rob Burrows taken from: https://www.loverugbyleague.com/post/kevin-sinfield-leeds-rhinos-captain-and-headingley-hero/ 

MRI Image: “Close-Up Shot of MRI Results” by Anna Shvets. From: Pexels.

Donate Page Image:

Hand in the sunlight image: “sunlight” by Ricardo Esquivel. From: Pexels.


Other Resources Used:

W3 Schools *hyperlink and Code Institute *hyperlink tutorial videos were consulted on a regular basis to understand the functionality of some of the code.


Acknowledgements:

•	I would like to thank my tutor, Marcel for his guidance and feedback through the process of completing this project. His critique and suggestions have proved to be very valuable when completing this project.

•	I would also like to thank my partner, Deborah for her patience and understanding while I spent long hours staring at the screen. And also apologies to my dog for some missed walks!

•	I would also like to thank Code Institute for the support and knowledge I am gaining through this process. Also the Slack Community for guidance, inspiration and support on this journey through software development.



 



















