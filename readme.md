# Sheffield Eid Festival 2023

This is a static website which can be updated which refresh photos to advertise and support the Eid Festival held in Sheffield twice a year. This will be to show potential stall holders and sponsors the amount of footfall for these events and for them to get into contact with us or just to attend the event before committing. Also to show our target audience, families, what there is to offer before attending.

![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/1cabcb80-039a-4f7b-96d9-7ae4dd6b5be9)



## Background

Being part of the Eid festival management team, we are in the early stages of bringing things together. Initially only focusing on advertising and running the event on the day. This has worked for the past 2 years however we are growing in popularity and as being the biggest Eid festival in recent years in South Yorkshire, we draw crowds from as far as Birmingham! Our Previous event saw in excess of 10,000 people attend.<br>
Recently starting our own Instagram page and advertising with our charity partner Families Relief, there are certain elements are lacking but are currently looking into.<br>
Since we have no official website, I decided that my project should be to create a website that reflects our efforts to advertise to the local community and give a place for potential store holders to register their interests. With the team, I went through ideas of my own and did some research as to what other people have done in the past.

## Goals
### Attract new business
One of our ways of supporting the Eid Festival is to get local business to sponsor the events, with seeing the amount of footfall from previous events and the new spreading by word of mouth, having a centralised location where all the information and evidence is available means that everyone has a chance.
### Bring the community together
After Covid, normality was out the window. Eid fell just after the covid restrictions were lifted so we decided to do something to bring everyone together. Especially for the younger generation, in which the majority of their lives were revolving around masks and staying at home.
### A day of fun for everyone
We market this as the Eid Festival, however it's more of a family fun day for everyone, regardless of race, religion and age. One of the most infectious sights and sounds are young children laughing and having fun. It has a positive effect on everyone. It makes these events worth it to see everyone getting involved!


Poster from previous event:<br>
<img src="![Poster](https://github.com/agunny/Eid-festival---Project/assets/133648178/79db9da3-b974-4451-8fc2-f8cb51418086)
" height="500" width="320" >

## **Colours and Typography**
Due to the previous designs of the posts and banners that we've used, it was already decided to use #76B9F0 has our main colour for background and overlays for images. Only white was text that would appear clearly on the foreground.
The complementary colour tone being #FOAD76, making things that have been hovered over to change to that colour to keep it standing out and for the change to be noticeable:
![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/050061da-d35a-4a2e-89aa-1d624fc6a4be)

I chose to use poppins font as it was clean, modern and upon a glace, subtly styled.
![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/38fc7f88-b088-44d8-af64-3d8c55858ed3)

## **Images**
We've got a decent stockpile of images from the smaller events we did in the past. Therefore selecting images that best shows everthing we have on offer, froms food to rides.
Adding a #76B9F0 filter over the top with a 80% opacity to continue the colour scheme for the landing images on pages. Tingpng.com was used to compress the images.

## **Features**

### **Navigation**

In the nav bar, I used a horizontal menu for the desktop view and a hamburger menu for the mobile view. Logo in the top right linked back to the index page.

On screens bigger than 600px:

![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/ebd5d901-236d-4ea9-90b6-19247a11e23d)

on screens smaller than 600px:

![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/1ae83210-ef68-4fa4-947b-8167294f474e)

**Footer**

Footer includes links to the Instagram page, link the Families Facebook page where current advertising goes to, soon to be update with the Eid Festival Facebook page, as well as the Families relief website. Icons from Font awesome and "light" up when hovered over. Logo also linked to index page.

![image](https://github.com/agunny/Eid-festival---Project/assets/133648178/5ce4e8c0-a537-4141-864f-b7c5b8029cf7)


# **Pages breakdown**
**Home**
Brief description of the event, certain pictures selected to advertise to users. Location linked and date.  

**Photos**

Photos from prior events, pictures selected to show the turnout, rides, stall and stage performances. Pictures animated to zoom slightly when hovered over to add user experience.

**About us**

Brief about us page to explain our story, goals, achievements.

**Contact us/Submission form**

Contact form for either getting involved with volunteering, enquiring about a stall or being a sponsor. More information to be distributed on contact.

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

**Future implementations**

Instead of a still images in the background, I would like to implement a video/GIF in the background that’s constantly on replay. Maybe add a some feedback section.

**Validator testing**

HTML – no issues, warning however for genuine h1 heading.

CSS – No issues found by W3C CSS Validation Service.



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

