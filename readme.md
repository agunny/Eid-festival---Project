**The Eid festival**

Being part of the Eid festival management team, we are in the early stages of bringing things together. Initially only focusing on advertising and running the event on the day. This has work for the past 2 years however we are growing in popularity and as being the biggest Eid festival in recent years in South Yorkshire. Recently starting our own Instagram page and advertising with our charity partner Families Relief, there are certain elements are lacking but are currently looking into. We aim to be a non-profit therefore we rely heavily on sponsors and stall the upfront costs of the first 1-2 have been immense. Buying gazebos and miscellaneous items that we can reuse are always a burden but the cost of the rides are something unavoidable and is 75% of our costs. 

Since we have no official website, I decided that my project should be to create a website that reflects our efforts to advertise to the local community and give a place for potential store holders to register their interests. With the team, I went through ideas of my own and did some research as to what other people have done in the past.

Websites examples from other similar organisations:

<https://eidinbedford.co.uk/eid/>

<https://www.londoneid.com/>

<https://eidinthepark.org.uk/>

We wanted something that shows what we are doing and how families of all sizes and ages can come along and have fun, catering to as many people as we can. Most importantly, we wanted to show the turnout on the day for everyone to see and somewhere people can get in contact with us first and we can then break things down further as before we were having to use personal numbers and word of mouth to get into contact with us.




**Features**

**General design scheme from posters.**


**Navigation**

Our logo fixed to the top left as well as bottom middle in the foot, both of which are linked to the main page as generally when using a website, the logos are always linked back. The navigation bar reacting to being in mobile website was taken from:

` `<https://www.youtube.com/watch?v=oLgtucwjVII&ab_channel=CodingNepal>

then adapted to fit the colour scheme of the website, Hex 76B9F0 being the official colour.

Colour scheme was predetermined by the poster layouts that we have been using. Leaving the font colour to be only white and black with not much variation. 

Having one page dedicated to photos was a must to attract potential stallholders and visitors in general. 

Highlighting when hovering over adds to the user experience by adding a layer of responsiveness.

Switching to a drop down menu, still following the same layout and animation when screen horizontal pixels changes to below 600px.

![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/6ad54581-3ab7-4b6b-98d9-cfd003851212)


**Header**

Header font changes with the resolution of the screen to avoid the text becoming too large for the screen.

The same animation used for buttons on the screen for quick navigation to the other tab, with location being used, linked further down the main page, for the main information.

Background image used was from previous events held.

All subsequent pages follow the same style with the navigation bar and the header above.

Additional features for the future, to include a rolling background image/gif in the background to be more eye catching to users. Potentially sourced from the next Eid festival.

**Footer**

Footer includes links to the Instagram page, link the Families Facebook page where current advertising goes to, soon to be update with the Eid Festival Facebook page, as well as the Families relief website, our charity partner where all profits are donated to. 

Could add a separate space for sponsors either in the footer or above once terms and conditions have been applied to include such advertising.

**Main article**

Text changes colour to F0AD76 which is the complentary colour to the 76B9F0 as per <https://www.canva.com/colors/color-wheel/> . This links to the map location of the event. Also clicking on the location button in the header automatically scrolls to this point in the page. Map link included to show the area. Image used in the background from previous event.

**Photos**

Photos using in a grid layout to show evidence from the previous events. Hovering over the images zooms in also to add another dimension.

Switches to 1 image at a time when viewed in a screen smaller than 600px horizontally.

**About us**

Simple page discussing the history and goals of the Eid festival.

**Contact us/Submission form**

` `Contact form for either getting involved with volunteering, enquiring about a stall or being a sponsor. More information to be distributed on contact.

Contact form to be filled out as necessary.

**Testing**

Website testing among a range of resolutions to ensure compatibility across mobile phones and desktop browsers alike.

Picked 600pixel horizontally to be the default resolution for the drop-down menu to appear as this is the “contact us” page defaults over 2 lines instead of staying as one.

Confirmed for the buttons on the header to stack depending on the size of the screen.

Images on the photos page when viewed in a smaller screen cut the image size too much, moving them to a 1 by 1 image type and then potentially in the future using a different image type/compressing the image to maintain image quality but improving responsiveness when loading the page.

Adding in a drop-down menu for the navigation bar was necessary to ensure that the navbar is always visible regardless of the screen size. Slight teething issues when scaling the resolution down more, the displacement of 100% wasn’t enough to keep it off the screen when checking, had to increase and test to ensure it wouldn’t be visible. Also changing the font size to keep it in check with the about of space on screen.

Potentially adding a link to the terms and conditions pages for the PDF versions, however due to having personal information on their, will need reworking before deploying.


**Bugs**

I found that when linking images, the image files must not have spaces as it causes it to flag as a problem, solved by including dashes instead of spaces.

I also found that the size of the text and the spacing was made difficult to read as it the page would split words depending on the resolution, therefore, to fix this included percentages where I could and clamp attribute when deciding a font size to ensure that the sizing remained appropriate for the resolution. 

Margins on the right was showing a white bar when the screen resolution was small enough. This was found out to be the problem of the map inserted, therefore CSS styling was using to combat this was to change the overflow to scroll.

**Validator testing**

HTML – no issues, warning however for genuine h1 heading.

CSS – No issues found by W3C CSS Validation Service.

Performance a little low due to high quality images used as background images.

**Deployment**

Deployed to github, accessible here:

<https://github.com/agunny/Eid-festival---Project>


**Credits**

Nav bar styled from:

<https://www.youtube.com/watch?v=oLgtucwjVII&ab_channel=CodingNepal>

Information regarding attributes were taken from:

<https://developer.mozilla.org/en-US/>

<https://stackoverflow.com/>

<https://www.w3schools.com/>

Many tutorials followed from:

<https://www.youtube.com/@WebDevSimplified>

<https://www.youtube.com/@TheWebShala>

<https://www.youtube.com/@KevinPowell>

**Media**

Images taken by myself from previous Eid festivals. 

Icons were taken from [Font-Awesome](https://fontawesome.com/)

