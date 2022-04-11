# My Bonsai Page

For the first milestone assignment with Code Institute, I have created a website that showcase some of my personal bonsai collection.
The site is targeted toward people who have an interest in bonsai trees and would like to know more about this hobby and get inspired to start their own collection.

The photos on this website were taken by mittnamnkenny.

[View the live project here.](https://mittnamnkenny.github.io/bonsai-page/)

![Responsice Mockup](assets/media/design.png)

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site.
        3. As a First Time Visitor, I want the site to be visually appealing regardless of screen size.
        4. As a First Time Visitor, I want the links to function as expected.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to learn more about bonsai by visiting Bonsai Empire via the link provided.
        2. As a Returning Visitor, I want know where the collection is located.
        3. As a Returning Visitor, I want to be able to contact the owner of the site.
        
    -   #### Frequent User Goals
        1. As a Frequent User, I want to see if there are any updates in the photo section.

## Features 

### Existing Features

#### Header

  - The header is featured at the top of the page.
  - Shows the logo in the left corner My Bonsai Page with a styled Font Awesome icon (fa-tree).
  - When the logo is clicked on it will take the user to the top of the page.
  - The right part contains a link to the Swedish translated version of the page, text Svenska.

  ![Header](assets/media/header.png)

#### Navigation

  - The navigation links are positioned on the left-hand side of the page, below the logo.
  - When on smaller devices the navigation goes underneath the header and is centred.
  - Home, about, photo and contact which direct the user to the correct sections of the page.
  - The navigation uses position sticky, it allows the user to easily navigate as it will always be visible when scrolling the page.
  - The navigation links all change text colour when hovered over.

![Navigation](assets/media/nav.png)

#### Hero image

  - This section includes a background image from Crespi Bonsai Museum in Italy.
  - The background uses position fixed on large screen sizes, this intend to give a nice effect when scrolling down the page.
  - A large text overlay with a Welcome to my bonsai page message.
  - A dark background colour on the text will make it stand out more and easier to read.

![Hero Image](assets/media/hero.png)

#### About Section

  - This section identifies the purpose of the page and provides brief information about bonsai.
  - A link to Bonsai Empire website, opens in new tab. This should encourage the user to learn more about bonsai.
  - On large screen sizes a circle is positioned at the top-right side with the Crespi Bonsai Museum background image.
  - For a smooth transition (on large screen sizes) to the photo section two SVG-waves are positioned at the bottom, softr.io

![About Section](assets/media/about.png)

#### Photo Section

  - This section is valuable to the user as they will be able to view high quality photos of shohin trees.
  - Shows 4 images of different bonsai trees with size information, 2 bonus images.
  - On small screen sizes / Mobile devices the images are shown 1 in a row.

![Photo Section](assets/media/photos.png)

#### Contact Section

  - The contact page consist of address information and a contact form with text area.
  - Name, email and message is required to be able to submit the form.
  - The input button change text colour when hovered over.

![Contact Section](assets/media/contact.png)

#### Meta Data

  - Bonsai page for bonsai enthusiasts.

### Features Left to Implement

- A Fav icon.
- A form submitted feature.

## Design

- I have used blue as main colour theme for this website. Indigo blue is often used when displaying bonsai and on bonsai excebitions.
- For text colour aliceblue were chosen as this goes with the theme of the website and is easy to read.
- Scalable Vector Graphic were used for background images with a fallback background colour if image should fail to load.
- Three svg-waves were used to improve the overall design.

## Technologies Used

- HTML5
- CSS3
- [Google Fonts:](https://fonts.google.com/) To import font family ’Poppins’ into the style.css file which is used on all pages.
Added fallback font sans-serif.
- [Font Awesome:](https://fontawesome.com/) Was used in header and contact section to add icons for aesthetic and UX purposes.
- [SVG Backgrounds:](https://svgbackgrounds.com/) Scalable Vector Graphic used for main background and on page-wrapper. Should the background image fail there is a fallback background color set so that text will be readable and page still functions.
- [SVG Wave Generator:](https://softr.io/tools/svg-wave-generator/) Used to generate a gradient SVG wave, used in both body and about section.
- [Tiny PNG:](https://tinypng.com/) Compressing images to smaller sizes.
- [Am I Responsive:](http://ami.responsivedesign.is) Checking the responsive.
- [Git](https://git-scm.com/) Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub:](https://github.com/) GitHub is used to store the projects code after being pushed from Git.

## Testing

### Browser testing
- I have tested that this page works using macOS (Macbook Air).
- I have tested that this page works in the following browsers using macOS: Chrome, Safari and Firefox.
- I have tested this page works on iOS devices using Safari browser (Iphone X and iPad Air).

### Responsivness
- Chrome developer tool have been used to check the responsivness.
- I have tested that this page works on different screen sizes from iPhone 5 (320px wide) and very large screens like 5K iMac Pro (5120 x 2880 px).

### Validator Testing 

The W3C Markup Validator and W3C CSS Validator Services were used to validate all pages of the project to ensure there were no syntax errors in there.

- W3C Markup Validator
![HTML results](assets/media/html.png)

- W3C CSS Validator
![CSS results](assets/media/css.png)

I have confirmed that the colours and fonts chosen are easy to read and accessible by running it through lighthouse in Chrome developer tools.

- Lighthouse
![Lighthouse](assets/media/lighthouse.png)

### Further Testing

- I have tested that the links in the header works correctly.
- I have tested that the navigation links work and the user is directed to the correct sections of the page.
- I have tested that the navigation links change text colour when hovering over.
- I have tested that the external link in the about section opens in a new tab and that the address is correct.
- I have tested that name, email and message is required to submit the form in the contact section.
- I have tested that the email input field must contain @ symbol to submit the form in the contact section.
- I have tested that the form submit button change text colour when hovering over.

### Solved bugs

- When testing on iPhone, I realized that background-attachment: fixed used on the hero image was not displaying correct.
  Property value local was added in the media query to fix this issue.

- When testing different screen sizes using Chrome developer tools, I realized that the submit button need to stand out more for accessibility.
  I increased the padding of the button and changed the background colour to aliceblue.

- When using Safari browser, I realized that text-decoration underline did not work at all. This was removed in favor of border-bottom on the link to bonsai empire in the about section.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - Log in to GitHub and locate the GitHub Repository.
  - In the GitHub repository, navigate to the "Settings" tab.
  - In Settings, choose "Pages" from the left hand menu.
  - Under "Source", select branch "Main" and select folder "(Root)".
  - Click Save and the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

![GitHub](assets/media/github.png)

## Credits

- [Google Fonts:](https://fonts.google.com/) Font family ’Poppins’ used on all pages.
- [Font Awesome:](https://fontawesome.com/) Was used in header and contact section to add icons.
- [SVG Backgrounds:](https://svgbackgrounds.com/) Scalable Vector Graphic used for main background and on page-wrapper.
- [SVG Wave Generator:](https://softr.io/tools/svg-wave-generator/) Used to generate a gradient SVG wave.
- [Tiny PNG:](https://tinypng.com/) Compressing images to smaller sizes.
- [Am I Responsive:](http://ami.responsivedesign.is) Checking the responsive.

### Code

* [SVG Wave Generator:](https://softr.io/tools/svg-wave-generator/) code used to generate a gradient SVG wave:

    `<svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 490" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(0, 46, 76, 1)" offset="0%"></stop><stop stop-color="rgba(0, 99, 164, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,245L30,228.7C60,212,120,180,180,187.8C240,196,300,245,360,294C420,343,480,392,540,408.3C600,425,660,408,720,334.8C780,261,840,131,900,89.8C960,49,1020,98,1080,171.5C1140,245,1200,343,1260,318.5C1320,294,1380,147,1440,98C1500,49,1560,98,1620,163.3C1680,229,1740,310,1800,334.8C1860,359,1920,327,1980,285.8C2040,245,2100,196,2160,196C2220,196,2280,245,2340,245C2400,245,2460,196,2520,204.2C2580,212,2640,278,2700,277.7C2760,278,2820,212,2880,212.3C2940,212,3000,278,3060,261.3C3120,245,3180,147,3240,155.2C3300,163,3360,278,3420,310.3C3480,343,3540,294,3600,277.7C3660,261,3720,278,3780,269.5C3840,261,3900,229,3960,228.7C4020,229,4080,261,4140,294C4200,327,4260,359,4290,375.7L4320,392L4320,490L4290,490C4260,490,4200,490,4140,490C4080,490,4020,490,3960,490C3900,490,3840,490,3780,490C3720,490,3660,490,3600,490C3540,490,3480,490,3420,490C3360,490,3300,490,3240,490C3180,490,3120,490,3060,490C3000,490,2940,490,2880,490C2820,490,2760,490,2700,490C2640,490,2580,490,2520,490C2460,490,2400,490,2340,490C2280,490,2220,490,2160,490C2100,490,2040,490,1980,490C1920,490,1860,490,1800,490C1740,490,1680,490,1620,490C1560,490,1500,490,1440,490C1380,490,1320,490,1260,490C1200,490,1140,490,1080,490C1020,490,960,490,900,490C840,490,780,490,720,490C660,490,600,490,540,490C480,490,420,490,360,490C300,490,240,490,180,490C120,490,60,490,30,490L0,490Z"></path></svg>`
  
* [SVG Backgrounds:](https://svgbackgrounds.com/) code for pattern "Dragon Scales":

    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 1000'%3E%3Cg %3E%3Ccircle fill='%23061324' cx='50' cy='0' r='50'/%3E%3Cg fill='%2308172a' %3E%3Ccircle cx='0' cy='50' r='50'/%3E%3Ccircle cx='100' cy='50' r='50'/%3E%3C/g%3E%3Ccircle fill='%23091b2f' cx='50' cy='100' r='50'/%3E%3Cg fill='%230a1e35' %3E%3Ccircle cx='0' cy='150' r='50'/%3E%3Ccircle cx='100' cy='150' r='50'/%3E%3C/g%3E%3Ccircle fill='%230b223b' cx='50' cy='200' r='50'/%3E%3Cg fill='%230b2541' %3E%3Ccircle cx='0' cy='250' r='50'/%3E%3Ccircle cx='100' cy='250' r='50'/%3E%3C/g%3E%3Ccircle fill='%230c2947' cx='50' cy='300' r='50'/%3E%3Cg fill='%230d2d4d' %3E%3Ccircle cx='0' cy='350' r='50'/%3E%3Ccircle cx='100' cy='350' r='50'/%3E%3C/g%3E%3Ccircle fill='%230d3153' cx='50' cy='400' r='50'/%3E%3Cg fill='%230e355a' %3E%3Ccircle cx='0' cy='450' r='50'/%3E%3Ccircle cx='100' cy='450' r='50'/%3E%3C/g%3E%3Ccircle fill='%230e3960' cx='50' cy='500' r='50'/%3E%3Cg fill='%230e3d67' %3E%3Ccircle cx='0' cy='550' r='50'/%3E%3Ccircle cx='100' cy='550' r='50'/%3E%3C/g%3E%3Ccircle fill='%230e416d' cx='50' cy='600' r='50'/%3E%3Cg fill='%230d4574' %3E%3Ccircle cx='0' cy='650' r='50'/%3E%3Ccircle cx='100' cy='650' r='50'/%3E%3C/g%3E%3Ccircle fill='%230d497a' cx='50' cy='700' r='50'/%3E%3Cg fill='%230c4d81' %3E%3Ccircle cx='0' cy='750' r='50'/%3E%3Ccircle cx='100' cy='750' r='50'/%3E%3C/g%3E%3Ccircle fill='%230a5288' cx='50' cy='800' r='50'/%3E%3Cg fill='%2308568f' %3E%3Ccircle cx='0' cy='850' r='50'/%3E%3Ccircle cx='100' cy='850' r='50'/%3E%3C/g%3E%3Ccircle fill='%23065a96' cx='50' cy='900' r='50'/%3E%3Cg fill='%23035f9d' %3E%3Ccircle cx='0' cy='950' r='50'/%3E%3Ccircle cx='100' cy='950' r='50'/%3E%3C/g%3E%3Ccircle fill='%230063A4' cx='50' cy='1000' r='50'/%3E%3C/g%3E%3C/svg%3E");
   
    
* [SVG Backgrounds:](https://svgbackgrounds.com/) code for "Liquid Cheese":

    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 1600 800'%3E%3Cg %3E%3Cpath fill='%2300395e' d='M486 705.8c-109.3-21.8-223.4-32.2-335.3-19.4C99.5 692.1 49 703 0 719.8V800h843.8c-115.9-33.2-230.8-68.1-347.6-92.2C492.8 707.1 489.4 706.5 486 705.8z'/%3E%3Cpath fill='%2300436f' d='M1600 0H0v719.8c49-16.8 99.5-27.8 150.7-33.5c111.9-12.7 226-2.4 335.3 19.4c3.4 0.7 6.8 1.4 10.2 2c116.8 24 231.7 59 347.6 92.2H1600V0z'/%3E%3Cpath fill='%23004e81' d='M478.4 581c3.2 0.8 6.4 1.7 9.5 2.5c196.2 52.5 388.7 133.5 593.5 176.6c174.2 36.6 349.5 29.2 518.6-10.2V0H0v574.9c52.3-17.6 106.5-27.7 161.1-30.9C268.4 537.4 375.7 554.2 478.4 581z'/%3E%3Cpath fill='%23005892' d='M0 0v429.4c55.6-18.4 113.5-27.3 171.4-27.7c102.8-0.8 203.2 22.7 299.3 54.5c3 1 5.9 2 8.9 3c183.6 62 365.7 146.1 562.4 192.1c186.7 43.7 376.3 34.4 557.9-12.6V0H0z'/%3E%3Cpath fill='%230063A4' d='M181.8 259.4c98.2 6 191.9 35.2 281.3 72.1c2.8 1.1 5.5 2.3 8.3 3.4c171 71.6 342.7 158.5 531.3 207.7c198.8 51.8 403.4 40.8 597.3-14.8V0H0v283.2C59 263.6 120.6 255.7 181.8 259.4z'/%3E%3Cpath fill='%230377bb' d='M1600 0H0v136.3c62.3-20.9 127.7-27.5 192.2-19.2c93.6 12.1 180.5 47.7 263.3 89.6c2.6 1.3 5.1 2.6 7.7 3.9c158.4 81.1 319.7 170.9 500.3 223.2c210.5 61 430.8 49 636.6-16.6V0z'/%3E%3Cpath fill='%23078bd2' d='M454.9 86.3C600.7 177 751.6 269.3 924.1 325c208.6 67.4 431.3 60.8 637.9-5.3c12.8-4.1 25.4-8.4 38.1-12.9V0H288.1c56 21.3 108.7 50.6 159.7 82C450.2 83.4 452.5 84.9 454.9 86.3z'/%3E%3Cpath fill='%230ca0e7' d='M1600 0H498c118.1 85.8 243.5 164.5 386.8 216.2c191.8 69.2 400 74.7 595 21.1c40.8-11.2 81.1-25.2 120.3-41.7V0z'/%3E%3Cpath fill='%231fb1ef' d='M1397.5 154.8c47.2-10.6 93.6-25.3 138.6-43.8c21.7-8.9 43-18.8 63.9-29.5V0H643.4c62.9 41.7 129.7 78.2 202.1 107.4C1020.4 178.1 1214.2 196.1 1397.5 154.8z'/%3E%3Cpath fill='%233BBCED' d='M1315.3 72.4c75.3-12.6 148.9-37.1 216.8-72.4h-723C966.8 71 1144.7 101 1315.3 72.4z'/%3E%3C/g%3E%3C/svg%3E");

### Acknowledgements

- My mentor at Code Institute for helpful feedback.










