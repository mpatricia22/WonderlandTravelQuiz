![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Quizia


<div align="center">
    <img src="" width="400px"</img> 
</div>

# Creator

Marcia P Fritzen <br>
Code Institute Student,
2023

# Features

The application intends to attract users to 

# Existing Features

## Navigation Bar

The navigation bar is featured on all four pages, with the Quiz name "Quizia" on the left corner with the logo and links to other pages of the website on the right. The links when clicked redirected to the respective pages. The full responsive navigation bar includes links to the Logo, Home page, Quiz page, About us and Sign Up page and is identical on each page to allow for easy navigation.

The navbar will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

* The landing page image
<br>
1. The landing page in the header section includes h1 heading.

2. Welcoming message using the color black.

3. Image to grab user's attention extracted from pexels.com.

5. There is also a call to action button redirecting to the Quiz page.

<div align="center">
    <img src="" width="400px"</img> 
</div>
 
* The Footer
<br>
The footer provides users with a consistent point of reference/contact information that can be accessed on all pages of the website. The footer contains a copyright notice, link to social media icons (using font awesome icons). The link to social media redirects to a new tab when clicked.
 <div align="center">
   <img src="g" width="400px"</img> 
</div>


* Quiz page
<br>
The Quia page
<br>
 <div align="center">
   <img src="" width="400px"</img> 
</div>


* Sign up page
<br>
This page includes a registration form with another level 3 heading where the user will need to complete the form informing personal details such as first name, last name, gender, email address, phone number, address, and postal code in order to sign up for the club. The form contains validation in HTML, so we cannot submit an empty form or enter a non-email address into an email address field.
 <div align="center">
   <img src="" width="400px"</img> 
</div>


# Features Left to Implement

1. More quizzes in the Quiz page separated by topics.
2. Travel videos page.
3. Travel blog page.


# Testing


Extensive testing has been performed and no major issues have been found. 

The site works at full capacity, and user friendly and intuitive. The users can easily navigate and achieve their goals without any trouble. 

The website is fully responsive and works well on different browsers such as Chrome, Firefox, and Safari and also on different screen sizes.

The forms available on the website contain validation in HTML, so there is no way users can submit an empty form or enter a non-email address into an email address field.

I confirmed that the navigation, header, about us, sign-up, and contact text are all readable and easy to understand.

# Bugs

When I deployed my project on github I found out that the video in the landing page was not working, I discovered this was due to the css path.

Fixed to:  <link rel="stylesheet" type="text/css" href="assets/css/style.css">

In CSS, I have experienced some syntax issues. 





# Validator Testing

* HTML
No errors were returned when passing through the official W3C validator
 <div align="center">
   <img src="" width="400px"</img> 
</div>
* CSS
No errors were found when passing through the official (Jigsaw) validator
 <div align="center">
   <img src="" width="400px"</img> 
</div>

* Accessibility
I confirmed that the colors and fonts chosen are easy to ready and accessible by running lighthouse in devtools.
 <div align="center">
   <img src="" width="400px"</img> 
</div>


# Deployment

SummitFit website was deployed to GitHub pages. The deployment steps taken:
1. Access GitHub repository SummitFit
2. Go to the Settings tab
3. From the source section drop-down menu, select the Master Branch
4. Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
5. The live link can be found here - https://mpatricia22.github.io/SummitFit/


# Credits

## Content

The icons in the footer were taken from Font Awesome.
The text extracted and inspired by:
https://smartfit.ie/
https://www.flyefit.ie/?
https://www.planetfitness.com/


## Media
All the photos included on project are from https://www.pexels.com/
Welcome #Quizia,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
