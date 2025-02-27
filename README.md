Michael Lai
http://a1-azinxtheonix.glitch.me

This project demostrates that I remember the basic elements of html, css, and javascript, as well as some clever tricks to lead to more advanced techniques. Details can be found below.

## Technical Achievements:

**1 - Style Rules:**
I'll be naming what I consider the most important style rules here (even though the style sheet has more than 5 rules).
    
    background-color:
        This is used for, of course, the background color, which changes depending on the location of the page. Used primarily for the body selector and the animation at the bottom.

    color:
        Very similar to background-color, but instead it's used for the text. Used primarily for the .text selector.

    font-family:
        Helps to set the font of all the text in the page.

    td/th -> padding:
        This is to make sure there's enough space for the text in the table.

    .titleArea::after -> *all the style rules under this*:
        This is to stop the float style rules from causing parts of the bottom section to move into the top section.

**2 - Javascript Animation:**
I've designed it so that depending on what section of the webpage you're viewing, it will change the color of the background and text. In order to accomplish this, on a scroll event, I took the current scroll position and the max scroll position in order to find a percentage, and then used that in order to do some rgb calculations. After that, I located the background color and text elements to change their colors.

Just in case that doesn't count as an animation, I made a small animation at the bottom of the page that simply bounces a square with the button toggle.

**3 - Other HTML Tags:**
First, lets go over what tags do not count for this catagory. I'm assuming all tags that are initally included do not count. These tags are: h1, h2, p, and ul/li. I'm also counting h3 -> h6 as well as any similarly functional tags.

    table/tr/th/td:
        I'm putting all of these tags in one catagory, as they all relate with the same function of a table.

    a:
        This is used for a link, which leads to something really disappointing. I can't directly describe the link, as it would ruin it, but from what I'm describing, the warning text before the link, and the modern internet, you could probably figure it out.

    img:
        This is for an image of myself.

    video/source:
        This is for a video. The tag looked interesting but I had no idea what to put in it, so I put a video of Gibby from iCarly hitting the floor.

    audio:
        This is for an audio file inserted into page. It's a cringe .wav file I had on my computer as a joke. I'm also slowly running out of interesting tags (with content) to use. Luckly, this is the 5th tag.


## Design Achievements:

**1 - Color palette:**
*see file named Color_Palette.jpeg*
Two of the colors are used for the first color set, two others are used for the second color set where the animation switches between the two, and the final color is used for the borders of the table. Some of the colors are used for the small backup animation at the bottom. 

**2 - Google Font:**
From the linked google font, I chose Hina Mincho as the font for my site. For the Chinese characters (because why not), I chose Long Cang.


## Note: Old Readme Below

---

Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Glitch
*DUE: Monday, August 30th by 11:59 AM (before the start of class!)*  

This assignment is a "warm-up" exercise. 
You will simply deploy the starting Web site that you will use this term to [Glitch](http://www.glitch.com/). 

Treat this assignment as a chance to get up to speed on Git, GitHub, and Glitch. 
If you already know these, great! 
However, if you're new to them, spend several hours practicing, experimenting, and reading documentation. Don't just get your website up and done, as
you'll need skills with these tools throughout the rest of the course.

Assignment details
---

This assignment requires that your website is both contained in a GitHub repository and hosted in Glitch. There are two ways to do this:

1. Fork this repo and clone it to your computer, make changes locally on your computer, push the repo onto GitHub, and then import your GitHub repo into Glitch.
2. Fork this repo and then import it directly to Glitch, use the Glitch editor to make changes, and then export your repo from Glitch back to GitHub.
3. Same as #1, but instead of importing from Github to Glitch you just upload the files (or copy/paste) them directly to Glitch.

## Option 1 - Clone to computer, push to Github, import to Glitch (recommended)

1. Fork the starting project code in GitHub. This repo contains:
    * the server code, `server.js`
    * A starting `index.html` file that you will edit as described below
    * A package.json file that helps configure Glitch
    * This README
2. Edit `index.html` to show the following information about you:
    * your name and class at WPI (e.g. class of 2020) Note: Do not put any contact or personal information that you do not potentially want other people outside of this class to see.
    * your major(s) and minor(s)
    * previous computer science courses that you have taken at WPI
    * your experience with the following technologies and methods (none, some, a lot)
        * HTML
        * CSS
        * Java
        * JavaScript
        * Ruby
        * Python
        * unit testing
4. Complete some technical and/or design achievements (see below).
5. Test your project to make sure that when someone goes to your main page, it displays correctly. You can do this locally by simply running `node server.js` from within the assignment directory.

6. Modify the README file according to the specification below.
7. Commit and push all your changes to GitHub. 
8. Deploy your project to Glitch. You can do this by [importing the repo from GitHub](https://medium.com/glitch/import-code-from-anywhere-83fb60ea4875)
9. Ensure that your project has the proper naming scheme (guide follows) so we can find it.
9. Create and submit a Pull Request to the original repo.

## Option 2 - Fork repo and import to Glitch, edit on Glitch, and then export back to GitHub
Most of these steps are the same as option 1, except that you being by creating a new project Glitch using this repo as a staring point (just choose New Project > Import from GitHub for this and then paste in the link to your repo). At the end, you can export your Glitch project to GitHub by [following these instructions](https://www.youtube.com/watch?time_continue=77&v=aWJFbtrgW4E&feature=emb_logo). *Note that the location of the projecct export feature in Glitch has moved from what they show in this video.* It's now located in Tools > Import and Export (tools is located in the bottom left of the Glitch editor).

## Option 3 - Clone to computer, edit locally, push to GitHub, upload to Glitch
This is the same as option 1, except that for step 6 (Deploy to Glitch) you simply upload each file to your Glitch repository (using New File > Upload a File).

Naming and URL Scheme
---

You must use a consistent naming scheme for all projects in this course.
If we can't find it, we can't grade it.

By default Glitch often assigns your application a random name. To change it, click on the project dropdown menu in the upper left corner of Glitch. You will then see an additional text field displaying the project name in the resulting menu; click here to edit the name.

The name scheme should be `a1-yourGitHubUsername`.
The `a1` will need to be updated to `a2`, `a3`, and so on in future projects.

Achievements
---
Below are some suggested technical and design achievements. You can use these to help boost your grade up to an A and customize the assignment to your personal interests. These are recommended acheivements, but feel free to create/implement your own... just make sure you thoroughly describe what you did in your README and why it was challenging. ALL ACHIEVEMENTS MUST BE DESCRIBED IN YOUR README IN ORDER TO GET CREDIT FOR THEM.

*Technical*
1. (max 5 points) Style your page using CSS. Each style rule you apply will get you 1 extra point for a maximum of 5 points. Be sure to describe your style rules in your README.
2. (5 points) Add a simple JavaScript animation to the page.
3. (max 5 points) Experiment with other HTML tags (links, images, tables etc.) Each extra tag you use will get you 1 extra point for a maximum of 5 points. Be sure to describe the links you use in your README.

*Design*
1. (10 points) Create a color palette using [color.adobe.com](https://color.adobe.com). Use all the colors in the palette in your webpage by implementing the appropriate CSS. Add a small screenshot of the color wheel for your color palette to your repo.
2. (5 points) Use a font from [Google Fonts](https://fonts.google.com) in your website.

Resources
---

If you need a JavaScript/HTML/CSS refresher, see [HTML & CSS](https://wpi.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma9936730811904746&context=L&vid=01WPI_INST:Default&lang=en&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,Jon%20Duckett&offset=0) and/or [JavaScript Codeacademy](https://www.codecademy.com/en/tracks/javascript).

If you need a Git/GitHub refreseher, see [GitHub Bootcamp](https://help.github.com/categories/bootcamp/), the [GitHub Guides](https://guides.github.com/) (especially the ones on Hello World, and Understanding the GitHub Flow, and Forking Projects), and [CodeSchool's Try Git Course](https://www.codeschool.com/courses/try-git).