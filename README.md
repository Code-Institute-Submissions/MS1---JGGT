# Jack Gibson Guitar Tuition
First Milestone Project for Code Institute

 ![](/workspace/CI-MS1/assets/images/devices.png)

I wanted to design a website aimed at people interested in or currently learning how to play the guitar. 
With online lessons being the only viable way to teach guitar in the current climate I thought this would be a good
oppurtunity to capitalise  on that. 

---

# UX
## User Stories
- User goals 
    - As a user, I want to immediately understand what is offered by the website
    - As a user, I want to be able to seamlessly navigate through the site to easily find
     more information
    - As a user, I want to be able to read testimonials and see past user experiences as 
    well as find any social media links to further research the tutor.

    I made the wireframe using Balsamiq which you can view the wireframe [here.](assets/docs/JGGT-wireframe.pdf)
## Design Choices
---
When designing this website I looked at existing succesful music apps such as Spotify and 
Apple Music for inspiration. I also looked at various different designs on [Dribble.](https://dribbble.com/search/music)
Originally I had opted for a multi-page website and eventually scrapped it as it didn't have
the flow that I or a user would want. Instead I decided to change to a single landing page
with a fixed navbar to help easily navigate the different sections.

## Fonts
I chose [Cinzel](https://fonts.google.com/specimen/Cinzel) for my headings as I wanted something that
would immediately stand out and be noticeable. I chose [Montserrat](https://fonts.google.com/specimen/Montserrat?query=mo)
for my main font as I found that it contrasted well and looks very clean.

## Icons
I used [Font Awesome](https://fontawesome.com/) mainly for social media links and also for the 
second section above the text to make it more visually appealing.

## Colours
I have always enjoyed how Spotifys' colours contrasted and wanted to do something similar. I chose 
#343a40 for my header and footer background, to contrast that I used #02AAB0 with #00CDAC as the 
home button to almost give a gradient effect. I chose #fafafa for my main text colour but using 
#343a40 for any text against a white background. I also used #343a40 for the button in the form 
as well the icons also using #00CDAC as a hover effect colour for the social media icons in the 
footer.

![](/workspace/CI-MS1/assets/images/Colours.png)

# Features
- Fixed navbar making navigation intuitive and simple
- Testimonials to provide new users with reliable information
- Videos showcasing the tutors skills
- Contact form with text area and radio buttons
- Social media links

## Future Features
- Short tutorial videos for different playing abilities
- Student of the month section

# Technologies used
## Languages used
- [HTML5](https://en.wikipedia.org/wiki/HTML)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

## Tools, Frameworks and Libraries used
- [Git](https://git-scm.com/)
- [Font Awesome](https://fontawesome.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Google Fonts](https://fonts.google.com/)
- [Balsamiq](https://balsamiq.com/) 

# Testing
I used the [CSS Validator](https://jigsaw.w3.org/css-validator/) which passed with no errors. I also 
used the [HTML Validator](https://validator.w3.org/) which brought up the following errors:
- The frameborder attribute on the iframe element is obsolete. Use CSS instead.
- The value of the for attribute of the label element must be the ID of a non-hidden form control.

### Fixes
- I removed the frameborder attribute and added border: 0; to my iframe class in CSS
- I matched the label elements "for" attributes to the input elements "id" attributes

# Bugs
Following on from Testing I also encoutered these bugs, below each one are the
relevant fixes. 
## During development
- Background images were causing a horizontal scroll bar to appear
    - Mentor provided me with the fix "html, body { overflow-x: hidden; }"
- Submit button on contact form not centering
    - Still working out why it's not centering
    
- Navbar expanding on medium size devices such as iPads
    - Added the Bootstrap class "navbar-expand-md" 

# Deployment

**JGGT** was developed on Gitpod, using GitHub to host the repository.
These were the steps taken to successfully deploy the website.
- Open [**GitHub**](https://github.com/) and log in
- Select the **repository**
- Click the **Settings** button from the top menu
- Scroll down to the **GitHub pages** section
- Click the **Source** dropdown menu and select **Main Branch**
- After the page has refreshed the link to the website can now be found 
under the **GitHub pages** section

# Credits

## Code
- I used [Bootstrap 4](https://getbootstrap.com/) to make the site
responsive on different devices.
 
## Images
- The main background image and contact form background image came from
[WallpaperAccess](https://wallpaperaccess.com/les-paul), they are the 3rd and 5th image down from the top.
- The three testimonal images came from [Unsplash](https://unsplash.com/) 
and can be found [here](https://unsplash.com/photos/rxwumN1CEGs), [here](https://unsplash.com/photos/Pc0ToyoR5Xo) and [here.](https://unsplash.com/photos/d2MSDujJl2g)

## Videos 
- All videos were from my bands YouTube page.

## Websites

- I also used [ResizeImage](https://resizeimage.net/) to help get the testimonal images
to display properly.

# Special Thanks
Special thanks to the Slack community and my Mentor for all their advice and guidance on this project.
