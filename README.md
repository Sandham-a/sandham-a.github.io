# Adam Sandham Portfolio
(Developer: Adam Sandham)

![Mockup image](docs/reactive_proof.png)

[Live webpage](https://sandham-a.github.io/portfolio_cv.html)

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requrements and Expectations](#user-requrements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colour](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Testing](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#performing-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatability)
    7. [Testing user stories](#testing-user-stories)
8. [Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

# Project Goals

## User Goals
- Finding a website about me and my body of work.
- For users to have a more detailed CV.
- Users to see the projects that I have been working on.

## Site Owner Goals
- To show visitors an example of the various technologies that I use and examples of my work.
- To allow myself to show a full digital CV which isn’t constrained by being two A4 Pages.
- To have a centralized directory as a means to showcase websites that I have built.

# User Experience

## Target Audience
- People that are looking to hire me.
- People interested in my projects that I have done.
- People that are looking for validation for claims on my CV.

## User Requirements and Expectations
- That navigation of the site is easy and intuitive and that all navigation takes place within the site and that the website and should be only one click away.
- Quickly and easily find relevant information depending on what they are planning to hire me for
- That links and functions work as expected
- Visually appealing presentation as this website also serves to showcase my web development skills especially in relation to front end development
- An easy way to contact me 
- That the information is accessible to all

# User Stories

## First-time User
1. As a first time user, what are Adam’s skill set is and what level he is ability is at.
2. As a first time user, I want to see examples of Adam’s programming skills as he stated  show in project he’s done.
3. As a first time user, I want examples of website’s he has created.
4. As a first time user, I want to know the qualifications that Adam has.

## Returning User
5. As a returning user, I want to see Adam’s complete CV.
6. As a returning user, I wish to revisit the projects Adam has done.
7. As a returning user, I want to get in contact with Adam through email. 
8. As a returning user, I want to see Adam’s public git hub repository. 
9. As a returning user, I want to see Adam’s linkedin profile.
10. As a returning user, I want to see the websites Adam has made.

## Site Owner
11. As the site owner, I want to show that I can professional quality websites.
12. As the site owner, I wish to show potential employers that I am professional.
13. As the site owner, I want users to find out users about me and my skill set.
14. As the site owner, I want users to see the projects I’ve done.
15. As the site owner, I want the users to be able to contact me about. 

# Design

## Design Choices
When designing the website, I was consciously aware that the previous bootstrap project was a portfolio website and would need to be very distinct from my own website. The website is designed to show case my various IT skills it would have to be clear, concise and look professional.

## Colour
As dark blue is my favourite colour, I decided that would be the central colour as to base my website on. I used shecodes pallets which give me a pallet of complementary colours that work together and the hexadecimal values for the pallet of my choosing. 
![color scheme](docs/features/color-pallet.png)

## Fonts
I used roberto font as it is a standard font for most corporate websites as it is clean and simple. The font is considered dyslexia friendly.

## Structure
As stated before I was very aware of the previous project being a portfolio website and needed to make sure that it did not look like a rehash of that. Having researched recommended portfolio sites
I decided to do a vertical header rather than a standard horizontal one for 3 reasons - 

1. The number of pages I needed mean that I doubted I'd come up with a layout that looked busy and cluttered. 
2. In the future with more time and when my skills have improved I can create collapsible subheadings to make navigation around the site even more precise. 
3. The layout means that the navigation of my site means that I can go to any page from any other page and that a users is only one click away from any page on the site.

The page is structured, uniform, intuitive and simple to pick up. 
The website consists of 7 pages

- An index page with a form to get in contact with me.
- A CV page that showcases my complete CV and allows for user interactivity with me highlighting the companies that I have worked for.
- A cloud computing page showcasing my cloud qualifications and plans to spin up a cloud server to launch this site in the future.
- A cyber security page explaining my educational background in cyber security, show the qualifications that I have and eventually and CTF articles that I write.
- A programming page that showcase little programming projects that I have done in the past. Eventually the links will run a modal that runs the program but this falls outside the scope of this project.
- A web development page that shows the websites that I have built or worked through. 
- A page for when a 404 error occurs. 

# Wireframes

<details><summary>Index</summary>
<img src="docs/wireframes/Index.png">
</details>
<details><summary>CV</summary>
<img src="docs/wireframes/Profile_CV.png">
</details>
<details><summary>Cloud</summary>
<img src="docs/wireframes/cloud.png">
</details>
<details><summary>Cyber</summary>
<img src="docs/wireframes/cyber.png">
</details>
<details><summary>Programming</summary>
<img src="docs/wireframes/Programming.png">
</details>
<details><summary>Web Development</summary>
<img src="docs/wireframes/web_dev.png">
</details>

# Technologies Used

## Languages
- HTML
- CSS

## Frameworks & Tools
- Bootstrap v5.0
- Git
- GitHub
- Gitpod
- Google Fonts
- Font Awesome
- Balsamiq

## Features

The page consists of seven pages
- Navigation Bar
- About Me/ CV
- Cloud computing page
- Cyber Security Page
- Programming Page
- Web Development Page

### Navigation Bar

- Featured on all pages.
- The navbar is fully responsive and icons change colour when cursor hovers over them links to the Homepage (in portrait), CV, cloud computing, cyber security,
    coding and web development pages.
- It allows users to easily navigate the pages.
- portrait reacts when hovered over which should indicate to the user there is some interactivity
- The icon changes colour for the page the user is currently on. 

![Navigation Bar](docs/features/Navigation-Bar.png)

### Contact Links

- featured on all pages
- These buttons are hyperlinks to my linkedIn profile, github public repository and also my email address.
- The buttons will change colour when hovered over and selected.
-  

![Contact Links](docs/features/contact-links.png)

### Contact Form

- Featured on index pages.
- Allows user to get in contact about potential work

![Contact Form](docs/features/contact-form.png)

### CV History

- Featured on the CV page
- Allows user to get an idea of my work history

![CV History](docs/features/cv-history.png)

### Logo Links

- Featured on the CV page
- The buttons are interactive as they will grow when a user hovers over them and when clicked will open up a new tab to the company's homepage.

![Logo Links](docs/features/logo-links.png)

### Programming Page

- Featured on the coding page.
- At present will is a hyperlink to the github repository
- Future improvements when clicked it will open up a modal and will run the code. I just didn't have time and was outside the scope of this project.

![Programming Page](docs/features/programming-page.png)

### Security Badges

- Featured on the cyber security page. 
- The buttons are interactive as they will grow when a user hovers over them and when clicked will open up a new tab to a page about the qualification.

![Contact Links](docs/features/security_badges.png)

### Cloud Badges

- Featured on the cloud page. 
- The buttons are interactive as they will grow when a user hovers over them and when clicked will open up a new tab to a page about the qualification.

![Contact Links](docs/features/cloud_badges.png)

### Website Showcase

- Featured on the web development page.
- The image of the sites is interactive and leads to the github repository pages but will eventually be links to working websites.

![Contact Links](docs/features/website_showcase.png)

# Validation

## HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors no warnings to show.

<details><summary>Index</summary>
<img src="docs/validation/index_html_val.png">
</details>
<details><summary>CV</summary>
<img src="docs/validation/portfolio_cv_html_val.png">
</details>
<details><summary>Cloud</summary>
<img src="docs/validation/cloud_html_val.png">
</details>
<details><summary>Cyber</summary>
<img src="docs/validation/cyber_html_val.png">
</details>
<details><summary>Programming</summary>
<img src="docs/validation/coding_html_val.png">
</details>
<details><summary>Web Development</summary>
<img src="docs/validation/web_dev_html_val.png">
</details>

## CSS Validation
The W3C CSS Validation Service was used to validate the CSS of the website. The CSS page returned no errors. 

<details><summary>CSS Validation</summary>
<img src="docs/validation/css_val.png">
</details>

## Accessibility
The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All pages pass with 0 major errors but had issues with contrast which were not clearly shown by the site and using alternative colours for the hyperlinks would not have made it clear to other users that they were in fact links.

<details><summary>Index</summary>
<img src="docs/validation/index_wave_val.png">
</details>
<details><summary>CV</summary>
<img src="docs/validation/CV_wave_val.png">
</details>
<details><summary>Cloud</summary>
<img src="docs/validation/cloud_html_val.png">
</details>
<details><summary>Cyber</summary>
<img src="docs/validation/cyber_wave_val.png">
</details>
<details><summary>Programming</summary>
<img src="docs/validation/coding_wave_val.png">
</details>
<details><summary>Web Development</summary>
<img src="docs/validation/web_dev_wave_val.png">
</details>

## Performance
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. And scored 70+ in all areas

<details><summary>Index</summary>
<img src="docs/validation/lighthouse_index.png">
</details>
<details><summary>CV</summary>
<img src="docs/validation/lighthouse_CV.png">
</details>
<details><summary>Cloud</summary>
<img src="docs/validation/lighthouse_cloud.png">
</details>
<details><summary>Cyber</summary>
<img src="docs/validation/lighthouse_cyber.png">
</details>
<details><summary>Programming</summary>
<img src="docs/validation/lighthouse_programming.png">
</details>
<details><summary>Web Development</summary>
<img src="docs/validation/lighthouse_web_dev.png">
</details>

Performing tests on various devices
The website was tested on the following devices:
- 2 different home built PCs
- Samsung Galaxy Tab A tablet
- ASUS Vivobook K553EA

In addition, the website was tested using Google Chrome Developer Tools Device toggling option for all available device options.

## Browser compatability
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Opera GX

# Testing user stories

1. As a first time user I want to see Adam's CV

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Click on about Icon | Moved to the About page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_CV_link.png">
<img src="./docs/user-story-telling/CV_page_highlight.png">
</details>

2. As a first time user I want to see the information he has about cloud computing

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Click on cloud Icon | Moved to the cloud page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_cloud_link.png">
<img src="./docs/user-story-telling/cloud_page_highlight.png">
</details>

3. As a first time user I want to see the information he has about cyber security

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Click on cyber security Icon | Moved to the cyber page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_cyber_link.png">
<img src="./docs/user-story-telling/cyber_page_highlight.png">
</details>

4. As a first time user I want to see the the programming projects he has done

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Click on coding Icon | Moved to the coding page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_coding_link.png">
<img src="./docs/user-story-telling/coding_page_highlight.png">
</details>

5. As a first time user I want to see the the websites he has created

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar | Click on web development Icon | Moved to the web development page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_web_dev_link.png">
<img src="./docs/user-story-telling/web_dev_page_highlight.png">
</details>

6. As a first time user I to go to Adam's LinkedIn page

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Links | Click on LinkedIn button | Open up Adams LinkedIn profile | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_linkedin_link.png">
<img src="./docs/user-story-telling/linkedin_page.png">
</details>

7. As a first time user I to go to Adam's public github repositories

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Links | Click on github button | Open up Adams github repositories | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_github_link.png">
<img src="./docs/user-story-telling/github_page.png">
</details>

8. As a first time user I want to send Adam an Email

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Links | Click on Email button | Open up new email | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_email_link.png">
<img src="./docs/user-story-telling/email_link.png">
</details>

9. As a first time user I to go to companies that Adam has worked

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| logo links| Hover over logo and then click | The logo increase in size once the pointer hovers over and opens up new tab to the company homepage once its clicked | Works as expected |


<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_job_link.png">
<img src="./docs/user-story-telling/wywm_page.png">
</details>

10. As a first time user I want to check if the qualifications that Adam have a legitimate

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Cloud Badges, Security Badges | Hover over logo and then click | The logo increase in size once the pointer hovers over and opens up new tab to credly which independently verifies exam results | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_job_link.png">
<img src="./docs/user-story-telling/wywm_page.png">
</details>

11. As a first time user I want to have a look at these programming projects 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Programming Projects | Click on link to programming projects | Open up a new tab to github repository | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_project_link.png">
<img src="./docs/user-story-telling/github-secret-messages.png">
</details>

12. As a first time user I want to have a look at the websites Adam has created 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Website showcase |  Hover over website preview and then click | The preview will increase in size once the pointer hovers over and opens up new tab to the repository | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_website_link.png">
<img src="./docs/user-story-telling/cat_website.png">
</details>

13. As a first time user I want to get back to the home page

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Navigation Bar |  Hover over portrait and then click | The portrait will increase in size once the pointer hovers over and takes user back to the index page | Works as expected |

<details><summary>Screenshots</summary>
<img src="./docs/user-story-telling/click_on_index_link.png">
</details>

# Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| blue boarder would appear on the right of the screen which was acceptable on a monitor but on smaller devices took up a lot of space | altered row class to have no padding or margins |
| Portrait would skew right at certain resolutions | reactive CSS to alter the size 
| links would not stay central at certain resolutions | Overrode the row class to set it to have no margins or padding
| When viewed on tablets, the contact page has bluespace after the footer | Set min-height for body to 100vh |

# Deployment

The website was deployed using GitHub Pages by following these steps:
1.	In the GitHub repository navigate to the Settings tab
2.	On the left hand menu select Pages
3.	For the source select Branch: master
4.	After the webpage refreshes automatically you will se a ribbon on the top saying: "Your site is published at <a href="https://sandham-a.github.io/"> 
https://sandham-a.github.io/</a>  

You can for fork the repository by following these steps:
1.	Go to the GitHub repository
2.	Click on Fork button in upper right hand corner

You can clone the repository by following these steps:
1.	Go to the GitHub repository
2.	Locate the Code button above the list of files and click it
3.	Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4.	Open Git Bash
5.	Change the current working directory to the one where you want the cloned directory
6.	Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY) 
7.  Press Enter to create your local clone.

# Credits
Images not referenced below are owned by the developer.

Media
In order of appearance:
-   [Portrait-Image](./assets/images/hero-image.jpg) : was an internal photo at <a href="www.risual.com">Risual</a>
-   [Site-logo](./assets/images/gamespy_logo.jpg) : was an image taken from <a href="www.gamespy.com">Gamespy's final article</a>
-   [Risual-logo](./assets/images/CV/risual_logo.png) : was an image taken from <a href="www.risual.com">risual.com<a>
-   [DIO-logo](./assets/images/CV/DIO_logo.jpg) : was an image taken from the DIO's own <a href="[www.wikipedia](https://en.wikipedia.org/wiki/Defence_Infrastructure_Organisation)">
    wikipedia article<a>
-   [With-you-with-me-logo](./assets/images/CV/WYWM_logo.jpg) : was an image taken from WYWM's <a href="https://www.facebook.com/withyouwithme1/">facebook</a> page
-	[Royal-Corp-Of-Signals-logo](./assets/images/CV/signals_logo.png) : was an image taken from the Royal Single's own <a href="https://en.wikipedia.org/wiki/Royal_Corps_of_Signals">
    wikipedia<a>
-   [Delice-de-France-logo](./assets/images/CV/delice_de_france_logo.png) : was an image taken off the <a href="https://www.bacoffice.co.uk/case-study/delice-de-france/"> BAC's <a>
    case study.
-   [Staffordshire-fire-logo](./assets/images/CV/staffordshre_fire_and_rescue_logo.png) : was an image taken off Staffordshire Fire and Rescues's 
    <a href="https://www.staffordshirefire.gov.uk/"> website </a>
-   [Cloud+-badge](./assets/images/quals/Cloud+.png) : Was taken from CompTIA's cloud+ information <a href="https://www.comptia.org/certifications/cloud">page</a>
-   [AZ900-image](./assets/images/quals/AZ-900.png) : Was taken from  Microsoft's AZ-900 exam <a href="https://learn.microsoft.com/en-us/credentials/certifications/exams/az-900/">page</a>
-   [CYSA+-image](./assets/images/quals/CYSA+.png) : Was taken from CompTIA's CYSA+ information <a href="https://www.comptia.org/certifications/cybersecurity-analyst">page</a>
-   [Security+-image](./assets/images/quals/security+.png) : Was taken from CompTIA's security+ information <a href="https://www.comptia.org/certifications/security">page</a>
-   [Pentest-image](./assets/images/quals/security+.png) : Was taken from CompTIA's security+ information <a href="https://www.comptia.org/certifications/pentest">page</a>
-   [Code-Institute-image](./assets/images/web_dev/code_institute.png) : Was taken from Code Institute's home <a href="http://www.codeinstitute.net">page</a>

Code
In order of appearance:
- The contact links are copied from code institute's Rosie's portfolio and then altered to suit what I needed them to do. 
- The form was also copied from Rosie's Portfolio. 

# Acknowledgements
I would like to take the opportunity to thank:
-	My mentor Mo Shami for his feedback, advice, guidance and support.
-	My girlfriend Nicola for allowing me time to do this project with my precious weekends with her.
-	To the lovely people on the Code Institute Slack for providing peer code reviews and help with some of my trickier problems.
-	My parents who own gave me child free time to work on this project.