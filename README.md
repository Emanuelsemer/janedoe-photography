
# [janedoe-photography](https://emanuelsemer.github.io/janedoe-photography)

Developer: Emanuel Semerson ([Emanuelsemer](https://www.github.com/Emanuelsemer))

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography)

# Welcome to Jane Doe Portrait Photography. #
This website is designed to introduce potential clients to Jane’s work as a New York-based portrait photographer with over ten years of professional experience. Specializing in authentic portraits, personal branding, and creative headshots, Jane’s goal is to create images that not only look beautiful — but feel honest, personal, and deeply human.

The primary aim of this site is to serve as a professional and welcoming space where visitors can explore her curated portfolio, learn more about her approach, and easily reach out to book a session. Whether you’re an entrepreneur, artist, actor, or simply someone who wants to be captured in a way that feels true to who you are, this site is built with you in mind.

Calm, collaborative, and connection-driven, Jane’s sessions are about more than photography — they’re about helping people feel seen. This website reflects that same spirit, offering a smooth and engaging experience for anyone looking to turn real moments into lasting images.


![screenshot](<documentation/mockups /Screenshot 2025-05-16 at 15.55.30.png>)
source: [janedoe-photography amiresponsive](https://ui.dev/amiresponsive?url=https://emanuelsemer.github.io/janedoe-photography)



## UX

### The 5 Planes of UX


#### 1. Strategy

**Purpose**
- Showcase high-quality portrait photography to attract potential clients.
- Make it easy for users to inquire, contact the photographer and view the photographer's work. 

**Primary User Needs**
- View portfolio and photography style.
- Easily contact the photographer.
- Getting to know the photographers background and story. 

**Business Goals**
- Attract new potrait photography clients.
- Increase inquiries and bookings. 
- Build a recognizable personal brand through visual storytelling. 

#### 2. Scope

**[Features](#features)** (see below)

**Content Requirements**
- High-quality images for the homepage and portfolio.
- Clear and authentic descriptions of photography style.
- Contact form for inquiries and bookings.

#### 3. Structure

**Information Architecture**
- **Navigation Menu**:
  - Home | Portfolio | Contact
- **Hierarchy**:
  - Hero image with artistic feeling. 
  - Clear call-to-action 
  - Prominent display of featured work. 
  - Prominent placement of social media links and contact details in the footer.

**User Flow**
1. User lands on the Home page → learns about Jane Doe and her photography style.
2. Navigates to the Portfolio page → browses through curated portrait photos. 
3. Visits the Contact page → views the contact form and inspiring photo.
4. Fills out and submits the contact form → sends inquiry.

5. Sees confirmation → waits for Jane Doe to respond. 

#### 4. Skeleton

**[Wireframes](#wireframes)** (see below)

#### 5. Surface

**Visual Design Elements**
- **[Colours](#colour-scheme)** (see below)
- **[Typography](#typography)** (see below)

### Colour Scheme

For this website, I chose a minimal and elegant monochrome color scheme, designed to highlight the photography work without visual distractions. The simplicity ensures that the viewer's focus stays on the photos.

Primary Background: #ffffff (white) — Used for the background across the entire site. It provides a clean and neutral canvas for both text and images.

Text Color: #000000 (black) — Classic and high-contrast for optimal readability against the white background.

Footer Background: #f5f5f5 — A very light grey used in the footer to gently separate it from the rest of the page while maintaining the minimalist feel.

This timeless black-on-white design is widely used in editorial and gallery-style websites, especially for photographers and artists, because it reflects professionalism, clarity, and elegance.


I used [coolors.co]() to generate my color palette.

- `#000000` (Black) Primary text.
- `#FFFFFF` (White) Background.
- `#f5f5f5` (Very light grey) Footer Background.

![screenshot](<documentation/color palette /Screenshot 2025-05-16 at 18.09.42.png>)

### Typography

#### Font

The website uses the default Bootstrap font stack (--bs-body-font-family), which typically includes:

- system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif

This system font stack ensures fast loading, great cross-device compatibility, and a clean, modern appearance without needing external font imports.

#### Icons

The site uses Font Awesome for social media icons and other visual elements.

Font Awesome provides scalable vector icons that are easy to customize with CSS.

Linked via CDN:
https://kit.fontawesome.com/3b20d96fa9.js

Official site: https://fontawesome.com/

## Mock-ups

![screenshot](<documentation/figma/Jane Doe photography.png>)

To ensure a clean and intentional user experience, I created high-fidelity mockups for all three pages of my portrait photography website using a visual design tool inspired by Figma.

Each page was designed with layout, spacing, and responsiveness in mind. These mockups guided my HTML and CSS development and reflect the final structure of the site.


| Page | Mobile | Tablet | Desktop |
| --- | --- | --- | --- |
| Home | ![Mobile Home](<documentation/mockups /mobile/homepage/homepage-iphone-se.png>)|![Tablet Home](<documentation/mockups /tablet/homepage/homepage-ipad-mini.png>)  |![!\[Desktop Home\](documentation/wireframes/desktop-home.png)](<documentation/mockups /desktop/homepage/homepage.png>) |
| Portfolio | ![!\[Mobile Portfolio\]](<documentation/mockups /mobile/portfoliopage/portfolio-iphone-se.png>) | ![Tablet Portfolio](<documentation/mockups /tablet/portfoliopage/portfolio-ipad-mini.png>)| ![Desktop Portfolio](<documentation/mockups /desktop/portfoliopage /portfolio.png>) |
| Contact | ![Mobile Contact](<documentation/mockups /mobile/contactpage/contact-iphone-se.png>) | ![Tablet Contact](<documentation/mockups /tablet/contactpage/contact-ipad-mini.png>) | ![Desktop Contact](<documentation/mockups /desktop/contactpage/contact.png>)|
| Confirmation | ![Mobile confirmation](<documentation/mockups /mobile/confirmation/confirmation-iphone-se.png>) | ![Tablet confirmation](<documentation/mockups /tablet/confirmation/confirmation-ipad-mini.png>)| ![Desktop confirmation](<documentation/mockups /desktop/confirmation/confirmation.png>)|
| 404 | ![Mobile 404](<documentation/mockups /mobile/404/404-iphone-se.png>) |![Tablet 404](<documentation/mockups /tablet/404/404-ipad-mini.png>)  | ![Desktop 404](<documentation/mockups /desktop/404/404.png>) |

## User Stories

| **Target**                  | **Expectation**                                                 | **Outcome**                                                           |
| --------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------- |
| As a user                | I want to see a clear main navigation menu                      | so that I can easily move between the main sections of the site.      |
| As a user                   | I want the content to be structured with clear headings         | so that I can find what I’m looking for without confusion.            |
| As a user            | I want the website to adjust to my screen size                  | so that I can use it comfortably on any device.                       |
| As a user | I want high contrast and alt text for images                    | so that I can understand the content using assistive technology.      |
| As a visitor                | I want all graphics to have a consistent style and color scheme | so the site looks professional and unified.                           |
| As a visitor                | I want foreground content to remain clear and readable          | so I can focus on the text without distraction from backgrounds.      |
| As a potential client       | I want to view a gallery of portrait images                     | so I can evaluate the photographer’s style and quality.               |
| As a visitor                | I want to read about the photographer                           | so I can understand their background and creative approach.           |
| As a potential client       | I want to contact the photographer via a form           | so I can easily request a portrait session.                           |

## Features

### Existing Features

| **Feature**                            | **Notes**                                                                                                                                                                                                                                                   | **Screenshot**                                             |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **Navbar**                             | Appears on all three pages (Home, Portfolio, Contact). Provides links to key sections with a clean, minimal design. On mobile, it collapses into a hamburger menu, improving usability across devices. Ensures users can navigate easily without using the browser’s back button. |  ![Navbar](<documentation/feature screenshots/navbar/Screenshot 2025-05-16 at 22.04.28.png>)         |
| **Hero Image (Home)**                  | The homepage starts with a large hero image of a ballet dancer, visually establishing the artistic and professional tone. This grabs the user’s attention immediately and sets the mood for the photographer’s style.                                                             | ![hero image](<documentation/feature screenshots/hero image(home)/Screenshot 2025-05-16 at 22.07.22.png>)|
| **About Section**                      | Located on the homepage, this section introduces Jane Doe and her photography philosophy. Helps build trust and personal connection with the user, especially potential clients.                                                                                                  | ![About section](<documentation/feature screenshots/about section/Screenshot 2025-05-16 at 22.08.46.png>) |
| **Call to Action (Contact Me Button)** | A clear button at the end of the About section encourages visitors to initiate contact. It is visually distinct and linked directly to the Contact page.                                                                                                                          | ![Contact me button](<documentation/feature screenshots/contact me button/Screenshot 2025-05-16 at 22.09.40.png>) |
| **Portfolio Grid**                     | The Portfolio page displays a 4-column responsive grid of curated portrait photos. This allows users to visually explore the photographer’s range and style with ease. Grid layout adjusts for mobile and tablet views.                                                           | ![Portfolio grid](<documentation/feature screenshots/portfolio grid/portfolio.png>)|
| **Contact Form**                       | A simple and accessible form allows visitors to send their first name, last name, email, and message. With a submit button on the bottom.                                                               | ![contact form](<documentation/feature screenshots/contact form/Screenshot 2025-05-16 at 22.14.30.png>)  |
| **Footer**                             | Present on all pages. Includes contact email, phone number, and icons linked to Instagram, Facebook, and LinkedIn. All links open in new tabs. Reinforces brand presence and allows continued engagement off-site.                                                                |![Footer](<documentation/feature screenshots/footer/Screenshot 2025-05-16 at 22.19.51.png>) |
| **Responsive Design**                  | All pages adapt seamlessly across mobile, tablet, and desktop devices using Bootstrap’s grid system and media queries. Ensures a smooth experience regardless of screen size.                                                                                                     | ![Responsive design](<documentation/feature screenshots/responsive design/Screenshot 2025-05-16 at 15.55.30.png>)  |
| **404 Page**                           | A custom 404 page is included to help guide users who navigate to a non-existent route. It maintains the site’s visual style and includes the same navigation and footer for consistency.                                                                                         |   ![404 page](<documentation/feature screenshots/404 page/404.png>)         |
| **Confirmation Redirect**              | After submitting the contact form, the user is redirected to a confirmation page or thank-you state. While no database is used, this gives the user feedback and closure.                                                                                                         | ![Confirmation page](<documentation/feature screenshots/confirmation redirect/confirmation.png>)|

### Future Features



- **Calendly Integration**: Allow users to book sessions directly through the website by embedding a Calendly widget. This eliminates scheduling delays and streamlines communication, providing clients with instant access to available time slots for different types of sessions (e.g., headshots, family portraits, branding shoots).
- **Client Testimonials Carousel**: Feature a rotating carousel of real client testimonials on the homepage or portfolio page to build trust and credibility. Testimonials would include photos from their sessions and a quote about their experience.
- **Client Preparation Guide Download**: Offer a downloadable PDF or web-based guide that helps clients prepare for their session — with tips on clothing, makeup, timing, and mindset. This helps reduce no-shows and increases shoot quality.
- **AI Booking Assistant**: Add a AI assistant to answer quick questions about pricing, availability, or session types. This improves client communication and increases conversions from site visitors.
- **Session Countdown & Reminders**: After booking, show users a live countdown to their session with the option to receive email or SMS reminders. This helps build anticipation and reduce missed appointments.
- **Before & After Slider Tool**: Integrate a photo comparison slider that shows before and after retouching or editing. This helps potential clients understand the value of professional editing and builds confidence in the final product.
- **Session Preparation tool**: Introduce an interactive feature within the booking form that allows clients to view and select from a gallery of sample portrait poses or session styles. This tool will help clients better prepare for their photoshoot by setting expectations and communicating their preferences in advance, resulting in a more seamless and personalized photography experience.

## Tools & Technologies

| Tool / Tech | Use |
| --- | --- |
| [![badge](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://markdown.2bn.dev) | Generate README and TESTING templates. |
| [![badge](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) | Version control. (`git add`, `git commit`, `git push`) |
| [![badge](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) | Secure online code storage. |
| [![badge](https://img.shields.io/badge/VSCode-grey?logo=htmx&logoColor=007ACC)](https://code.visualstudio.com) | Local IDE for development. |
| [![badge](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) | Main site content and layout. |
| [![badge](https://img.shields.io/badge/CSS-grey?logo=css3&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) | Design and layout. |
| [![badge](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com) | Hosting the deployed front-end site. |
| [![badge](https://img.shields.io/badge/Bootstrap-grey?logo=bootstrap&logoColor=7952B3)](https://getbootstrap.com) | Front-end CSS framework for modern responsiveness and pre-built components. |
| [![badge](https://img.shields.io/badge/Figma-grey?logo=figma&logoColor=F24E1E)](https://www.figma.com) | Creating mockups. |
| [![badge](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com) | Icons. |
| [![badge](https://img.shields.io/badge/ChatGPT-grey?logo=openai&logoColor=75A99C)](https://chat.openai.com) | Help debug, troubleshoot,generate text content and explain things. |
| [![badge](https://img.shields.io/badge/W3Schools-grey?logo=w3schools&logoColor=04AA6D)](https://www.w3schools.com) | Tutorials/Reference Guide |


## Agile Development Process

### GitHub Projects

[GitHub Projects](https://www.github.com/Emanuelsemer/janedoe-photography/projects) served as an Agile tool for this project. Through it, User Stories, issues/bugs, and Milestone tasks were planned, then subsequently tracked on a regular basis using the Kanban project board.

![Kanban project board](<documentation/agile development process/github project /Screenshot 2025-05-16 at 23.19.37.png>)

### GitHub Issues

[GitHub Issues](https://www.github.com/Emanuelsemer/janedoe-photography/issues) served as an another Agile tool. There, I managed my User Stories and Milestone tasks, and tracked any issues/bugs.

| Link | Screenshot |
| --- | --- |
| [![GitHub issues](https://img.shields.io/github/issues/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/issues) | ![open issues](<documentation/agile development process/github issues /open/Screenshot 2025-05-16 at 23.26.34.png>)|
| [![GitHub closed issues](https://img.shields.io/github/issues-closed/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/issues?q=is%3Aissue+is%3Aclosed) | ![closed issues](<documentation/agile development process/github issues /closed/Screenshot 2025-05-16 at 23.26.59.png>) |

### MoSCoW Prioritization

I've decomposed my Epics into User Stories for prioritizing and implementing them. Using this approach, I was able to apply "MoSCoW" prioritization and labels to my User Stories within the Issues tab. I created the User Stories from the requirements for the milestone project. 

- **Must Have**: guaranteed to be delivered - required to Pass the project 

## Note on Commit Messages

After receiving feedback from my mentor, I improved the way I write commit messages. Earlier messages may lack clarity or structure, but later commits follow a more consistent and descriptive format to better reflect best practices.


# Testing


## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [404.html](https://github.com/Emanuelsemer/janedoe-photography/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://emanuelsemer.github.io/janedoe-photography/404.html) | ![screenshot 404](<documentation/testing/html validator/404/Screenshot 2025-05-17 at 01.41.23.png>) | Error were on the external code |
|  | [contact.html](https://github.com/Emanuelsemer/janedoe-photography/blob/main/contact.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://emanuelsemer.github.io/janedoe-photography/contact.html) |![screenshot contact](<documentation/testing/html validator/contact /Screenshot 2025-05-17 at 01.44.18.png>) | Error were on the external code|
|  | [index.html](https://github.com/Emanuelsemer/janedoe-photography/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://emanuelsemer.github.io/janedoe-photography/index.html) | ![screenshot index](<documentation/testing/html validator/index/Screenshot 2025-05-17 at 01.47.00.png>) | Error were on the external code
|  | [portfolio.html](https://github.com/Emanuelsemer/janedoe-photography/blob/main/portfolio.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://emanuelsemer.github.io/janedoe-photography/portfolio.html) | ![screenshot portfolio](<documentation/testing/html validator/portfolio/Screenshot 2025-05-17 at 01.48.24.png>) | Error on external code|
|  | [success.html](https://github.com/Emanuelsemer/janedoe-photography/blob/main/success.html) | [HTML Validator](https://valisdator.w3.org/nu/?doc=https://emanuelsemer.github.io/janedoe-photography/success.html) | ![screenshot success](<documentation/testing/html validator/success/Screenshot 2025-05-17 at 01.50.59.png>)| Error on the external code


### CSS


I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/Emanuelsemer/janedoe-photography/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://emanuelsemer.github.io/janedoe-photography) | ![screenshot css](<documentation/testing/css validator/Screenshot 2025-05-17 at 01.54.29.png>) |  |


## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![Mobile Home](documentation/testing/responsivness/mobile/homepage/homepage-iphone-se.png)|  ![Tablet Home](documentation/testing/responsivness/tablet/homepage/homepage-ipad-mini.png)| ![Desktop Home](documentation/testing/responsivness/desktop/homepage/homepage.png) | Works as expected |
| Portfolio | ![Mobile Portfolio](documentation/testing/responsivness/mobile/portfoliopage/portfolio-iphone-se.png) | ![Tablet Portfolio](documentation/testing/responsivness/tablet/portfoliopage/portfolio-ipad-mini.png)| ![Desktop Portfolio](<documentation/testing/responsivness/desktop/portfoliopage /portfolio.png>) | Works as expected |
| Contact | ![Mobile Contact](documentation/testing/responsivness/mobile/contactpage/contact-iphone-se.png)| ![Tablet Contact](documentation/testing/responsivness/tablet/contactpage/contact-ipad-mini.png)| ![Desktop Contact](documentation/testing/responsivness/desktop/contactpage/contact.png)| Works as expected |
| Confirmation | ![Mobile Confirmation](documentation/testing/responsivness/mobile/confirmation/confirmation-iphone-se.png) | ![Tablet Confirmation](documentation/testing/responsivness/tablet/confirmation/confirmation-ipad-mini.png)| ![Desktop Confirmation](documentation/testing/responsivness/desktop/confirmation/confirmation.png) | Works as expected |
| 404 | ![Mobile 404](documentation/testing/responsivness/mobile/404/404-iphone-se.png) | ![Tablet 404](documentation/testing/responsivness/tablet/404/404-ipad-mini.png)| ![Desktop 404](documentation/testing/responsivness/desktop/404/404.png) | Works as expected |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Safari | Notes |
| --- | --- | --- | --- | --- |
| Home | ![Chrome Home](<documentation/testing/browser compatiblity /chrome/home/homepage.png>) | ![Firefox Home](<documentation/testing/browser compatiblity /firefox/home/Screenshot 2025-05-17 at 02-44-35 Jane Doe Photography.png>) | ![Safari Home](<documentation/testing/browser compatiblity /safari/home/Screenshot 2025-05-17 at 03.06.13.png>)| Works as expected |
| Portfolio | ![Chrome Portfolio](<documentation/testing/browser compatiblity /chrome/portfolio/portfoliopage.png>) | ![Firefox Portfolio](<documentation/testing/browser compatiblity /firefox/portfolio/Screenshot 2025-05-17 at 02-47-11 Jane Doe Photography.png>) | ![Safari Portfolio](<documentation/testing/browser compatiblity /safari/portfolio/Screenshot 2025-05-17 at 03.08.13.png>) | Works as expected |
| Contact | ![Chrome Contact](<documentation/testing/browser compatiblity /chrome/contact/contactpage.png>) | ![Firefox Contact](<documentation/testing/browser compatiblity /firefox/contact/Screenshot 2025-05-17 at 02-48-27 Jane Doe Photography.png>)| ![Safari Contact](<documentation/testing/browser compatiblity /safari/contact/Screenshot 2025-05-17 at 03.08.27.png>)| Works as expected |
| Confirmation | ![Chrome Confirmation](<documentation/testing/browser compatiblity /chrome/confirmation/confirmation.png>)| ![Firefox Confirmation](<documentation/testing/browser compatiblity /firefox/confirmation/Screenshot 2025-05-17 at 02-50-20 Message Sent Jane Doe Photography.png>) | ![Safari Confirmation](<documentation/testing/browser compatiblity /safari/confirmation/Screenshot 2025-05-17 at 03.08.50.png>)| Works as expected |
| 404 | ![Chrome 404](<documentation/testing/browser compatiblity /chrome/404/404.png>)| ![Firefox 404](<documentation/testing/browser compatiblity /firefox/404/Screenshot 2025-05-17 at 02-57-01 Page Not Found Jane Doe Photography.png>) | ![Safari 404](<documentation/testing/browser compatiblity /safari/404/Screenshot 2025-05-17 at 02.59.11.png>) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![Mobile Home](<documentation/testing/lighthouse/home/mobile/Screenshot 2025-05-17 at 03.19.05.png>)| ![Desktop Home](<documentation/testing/lighthouse/home/desktop/Screenshot 2025-05-17 at 03.20.27.png>)|
| Portfolio | ![Mobile Portfolio](<documentation/testing/lighthouse/portfolio/mobile/Screenshot 2025-05-17 at 03.27.20.png>) | ![Desktop Portfolio](<documentation/testing/lighthouse/portfolio/desktop/Screenshot 2025-05-17 at 03.40.33.png>) |
| Contact | ![Mobile Contact](<documentation/testing/lighthouse/contact/mobile/Screenshot 2025-05-17 at 03.41.39.png>) | ![Desktop Contact](<documentation/testing/lighthouse/contact/desktop/Screenshot 2025-05-17 at 03.42.28.png>)|
| Confirmation | ![Mobile Confirmation](<documentation/testing/lighthouse/confirmation/mobile/Screenshot 2025-05-17 at 03.46.07.png>) | ![Desktop Confirmation](<documentation/testing/lighthouse/confirmation/desktop/Screenshot 2025-05-17 at 03.46.41.png>) |
| 404 | ![Mobile 404](<documentation/testing/lighthouse/404/mobile/Screenshot 2025-05-17 at 03.48.20.png>)| ![Desktop 404](<documentation/testing/lighthouse/404/desktop/Screenshot 2025-05-17 at 03.48.46.png>) |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| **Page**         | **Expectation**                                                         | **Test**                                                                                        | **Result**                                                                              | **Screenshot**     |
| ---------------- | ----------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------ |
| **Home**         | Feature is expected to present clear purpose and a call to action.      | Verified the about section content and the visibility/functionality of the "Contact Me" button. | The purpose was clearly conveyed, and the CTA button worked as expected.                |![Home](<documentation/testing/defensive programming/home/homepage.png>)    |
|                  | Navigation bar should be responsive and accessible.                     | Used keyboard navigation and screen reader tools to test link access and focus states.          | Navbar was fully accessible via keyboard and all links worked correctly.                | ![Navbar](<documentation/testing/defensive programming/navbar/Screenshot 2025-05-17 at 04.12.14.png>) |
|                  | Page should be responsive.                                              | Tested using Chrome DevTools and resizing to simulate desktop, tablet, and mobile.              | Layout adapted correctly across all screen sizes.                                       | ![responsive](<documentation/testing/defensive programming/responsive/Screenshot 2025-05-16 at 15.55.30.png>)  |
| **Portfolio**    | Feature is expected to load high-quality images in a consistent layout. | Verified that gallery images load at proper resolution and scale well on all devices.           | All images retained quality and layout adjusted across breakpoints using Bootstrap.     | ![portfolio](<documentation/testing/defensive programming/portfolio/portfolio.png>)|
|                  | Feature is expected to prevent broken or missing image links.           | Inspected HTML `src` values and tested image load in browser.                                   | All images displayed properly without broken links.                                     | ![image ok on all images](<documentation/testing/defensive programming/image ok/Screenshot 2025-05-17 at 04.21.14.png>)  |
| **Contact Form** | Feature is expected to block empty form submissions.                    | Attempted to submit form with empty fields.                                                     | Form submission was correctly blocked by `required` attributes.                         | ![form empty](<documentation/testing/defensive programming/form empty/Screenshot 2025-05-17 at 04.13.22.png>)  |
|                  | Feature is expected to validate field types.                            | Entered invalid emails and numbers in name fields.                                              | Submission was blocked and browser displayed built-in validation messages.              | ![form invalid](<documentation/testing/defensive programming/form invalid/Screenshot 2025-05-17 at 04.13.50.png>)|
|                  | Contact page should display a success redirect.                         | Submitted valid form data and monitored for redirection.                                        | User was redirected to `success.html` after submission as expected.                     | ![Confirmation page](<documentation/testing/defensive programming/form success/confirmation.png>) |
| **Footer**       | Social media icons are expected to link to external platforms.          | Clicked on all icons and verified they open correct platform in new tab.                        | All links opened correctly with `target="_blank"` and `rel="noopener"` for security.    | ![Footer](<documentation/testing/defensive programming/footer/Screenshot 2025-05-17 at 04.11.59.png>)  |
| **404 Page**     | Feature is expected to show an error when user visits an invalid route. | Manually entered a non-existent URL (`/notfound`) in browser.                                   | A custom 404 page was shown with standard navbar and footer, and a clear error message. |  ![404 page](<documentation/testing/defensive programming/404/404.png>)      |


## User Story Testing

| **Target**            | **Expectation**                                                 | **Outcome**                                                      | **Screenshot**                                                |
| --------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | ------------------------------------------------------------- |
| As a user             | I want to see a clear main navigation menu                      | so that I can easily move between the main sections of the site. | ![navbar](<documentation/testing/user stories testing/navbar/Screenshot 2025-05-16 at 22.04.28.png>)                  |
| As a user             | I want the content to be structured with clear headings         | so that I can find what I’m looking for without confusion.       | ![home](<documentation/testing/user stories testing/homepage/homepage.png>)       |
| As a user             | I want the website to adjust to my screen size                  | so that I can use it comfortably on any device.                  | ![responsive](<documentation/testing/user stories testing/responsive/Screenshot 2025-05-16 at 15.55.30.png>)|
| As a user             | I want high contrast and alt text for images                    | so that I can understand the content using assistive technology. | ![alt text](<documentation/testing/user stories testing/alt text code /Screenshot 2025-05-17 at 04.40.26.png>)|
| As a visitor          | I want all graphics to have a consistent style and color scheme | so the site looks professional and unified.                      | ![portfolio](<documentation/testing/user stories testing/portfolio/portfolio.png>)  |
| As a visitor          | I want foreground content to remain clear and readable          | so I can focus on the text without distraction from backgrounds. | ![About me text](<documentation/testing/user stories testing/homepage/homepage.png>)   |
| As a potential client | I want to view a gallery of portrait images                     | so I can evaluate the photographer’s style and quality.          | ![portfolio grid](<documentation/testing/user stories testing/portfolio/portfolio.png>)      |
| As a visitor          | I want to read about the photographer                           | so I can understand their background and creative approach.      | ![about me ](<documentation/testing/user stories testing/about/Screenshot 2025-05-16 at 22.08.46.png>)   |
| As a potential client | I want to contact the photographer via a form                   | so I can easily request a portrait session.                      | ![contact form](<documentation/testing/user stories testing/contact form/Screenshot 2025-05-16 at 22.14.30.png>)   |




## Bugs

For this project, I tracked bugs manually using paper notes and Apple Notes as a lightweight way to keep track of issues and fixes during development. While this method helped me stay organized in the short term, I’ve come to realize that using version control tools like GitHub Issues would have been far more effective. In future projects, I plan to fully adopt GitHub’s integrated issue tracking system to document bugs, feature requests, and fixes more efficiently, and to make the development process more transparent and collaborative.

| **Bug**                                                        | **Description**                                                                                                                                                | **Fix Implemented**                                                                             | **Status**           |
| -------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------- |
| **Image not displaying on GitHub Pages**                       | Image links were broken due to folder name being `Portfolio` (uppercase), while the actual folder was named `portfolio` (lowercase). GitHub is case-sensitive. | Renamed the folder to match the correct lowercase path and updated all image paths in the code. | ✅ Fixed              |
| **Form submission issue**                                      | Form was reloading the page instead of redirecting to success message.                                                                                         | Used JavaScript `event.preventDefault()` and added a redirect to `success.html`.                | ✅ Fixed              |
| **CMD + Shift + R not working in Safari**                      | You expected it to hard refresh the page, but Safari does not support this shortcut.                                                                           | Used right-click on the reload icon + “Empty Caches” instead, or `Cmd + Option + E`.            | ✅ Workaround applied |
| **Navbar not accessible by keyboard**                          | Navigation was working but hadn’t been explicitly tested for accessibility.                                                                                    | Verified keyboard focus, semantic HTML, and added ARIA labels to external links.                | ✅ Confirmed          |
| **Background image overlayed the contact form poorly**         | The background image in the contact page header clashed with form readability.                                                                                 | Adjusted form placement and contrast, ensured it was not layered over background image.         | ✅ Adjusted visually  |
| **Pexels image search link used instead of direct image link** | Attribution included a search results page instead of a direct link.                                                                                           | Updated with the correct individual image URLs for attribution.                                 | ✅ Corrected          |
| **Contact button not linking to contact page**                 | A `<button>` element was used with an `href`, which doesn't work in HTML.                                                                                      | Replaced `<button>` with an `<a>` element and added `href="contact.html"` to fix the issue.     | ✅ Fixed              |


### Known Issues

> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.



## Deployment

### GitHub Pages

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://www.github.com/Emanuelsemer/janedoe-photography), navigate to the "Settings" tab.
- In Settings, click on the "Pages" link from the menu on the left.
- From the "Build and deployment" section, click the drop-down called "Branch", and select the **main** branch, then click "Save".
- The page will be automatically refreshed with a detailed message display to indicate the successful deployment.
- Allow up to 5 minutes for the site to fully deploy.

The live link can be found on [GitHub Pages](https://emanuelsemer.github.io/janedoe-photography).

### Local Development

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://www.github.com/Emanuelsemer/janedoe-photography).
2. Locate and click on the green "Code" button at the very top, above the commits and files.
3. Select whether you prefer to clone using "HTTPS", "SSH", or "GitHub CLI", and click the "copy" button to copy the URL to your clipboard.
4. Open "Git Bash" or "Terminal".
5. Change the current working directory to the location where you want the cloned directory.
6. In your IDE Terminal, type the following command to clone the repository:
	- `git clone https://www.github.com/Emanuelsemer/janedoe-photography.git`
7. Press "Enter" to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://www.github.com/Emanuelsemer/janedoe-photography)

**Please Note**: in order to directly open the project in Gitpod, you should have the browser extension installed. A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, you make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository. You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://www.github.com/Emanuelsemer/janedoe-photography).
2. At the top of the Repository, just below the "Settings" button on the menu, locate and click the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no remaining major differences between the local version when compared to the deployed version online.

## Credits

Credit: Chatgpt code for being able to submit a form and land on the sucess page. (there is javascript wish i haven't learned yet)

            <script>
                document.getElementById('contactForm').addEventListener('submit', function(event) {
                  event.preventDefault(); // prevent actual submission
                  window.location.href = 'success.html'; // redirect
                });
              </script>

Credit: Love running project code for social media links 

![Credit](<documentation/agile development process/credit/footer /Screenshot 2025-05-17 at 01.08.09.png>)

### Content

| Source | Notes |
| --- | --- |
| [Markdown Builder](https://markdown.2bn.dev) | Help generating Markdown files |
| [Light_trails website](https://github.com/RazmikMovsisyan/light_trails) | Photography website inspired by contact details in footer section |
| [Love running project](https://github.com/Code-Institute-Solutions/love-running-v3/blob/main/7.2-styling-the-form/index.html) | Code Institute walkthrough project inspiration for footer social media links. |
| [Bootstrap](https://getbootstrap.com) | Various components / responsive front-end framework |
| [ChatGPT](https://chatgpt.com) | Help with code logic, explanations and generate text content. |

## Media

All photos used in this project were sourced from Pexels, a free and royalty-free media platform. Attribution is not required under their license, but full credit is listed below to respect the creators.

### Home Page & Contact Page 

| **Usage**                            | **Photographer**  | **Link**                                                                             |
| ------------------------------------ | ----------------- | ------------------------------------------------------------------------------------ |
| Portrait of Jane Doe (About section) | Majestical Jasmin | [View on Pexels](https://www.pexels.com/photo/vag-natur-kvinna-kamera-5870338/)      |
| Hero Image (Home)                    | Yan Krukau        | [View on Pexels](https://www.pexels.com/photo/kvinna-dans-rorlig-bokeh-6616717/)     |
| Contact Page Background              | Lil Artsy         | [View on Pexels](https://www.pexels.com/photo/hands-covered-in-black-paint-5541019/) |

### Portfolio Images

| **Description**                              | **Photographer**  | **Link**                                                                                            |
| -------------------------------------------- | ----------------- | --------------------------------------------------------------------------------------------------- |
| Tattooed woman seated in red pants           | Mozzapics         | [View](https://www.pexels.com/sv-se/foto/portratt-av-en-tatuerad-kvinna-i-rodbruna-byxor-31948311/) |
| Elderly man with a straw hat                 | Gustavo Fring     | [View](https://www.pexels.com/photo/1933873/)                                                       |
| Black and white vintage woman with cigarette | Guilherme Almeida | [View](https://www.pexels.com/photo/1858175/)                                                       |
| Woman with dramatic lighting in black dress  | Shahin Khalaji    | [View](https://www.pexels.com/photo/14497001/)                                                      |
| Studio-lit woman dancing                     | Shutter Craftsman | [View](https://www.pexels.com/photo/31856525/)                                                      |
| Woman in hat with red curly hair             | Pete79            | [View](https://www.pexels.com/photo/19908239/)                                                      |
| Man with sunglasses and saxophone            | DJ Saxxo          | [View](https://www.pexels.com/photo/16543610/)                                                      |
| Woman in veil with striking green eyes       | Jonaorle          | [View](https://www.pexels.com/photo/4029925/)                                                       |
| Baby girl in pink with balloons              | Ifeyin Ka Studios | [View](https://www.pexels.com/photo/29899042/)                                                      |
| Laughing woman in modern chair               | Cottonbro Studio  | [View](https://www.pexels.com/photo/7319479/)                                                       |
| Glitter-covered woman posing creatively      | Kool Shooters     | [View](https://www.pexels.com/photo/7693358/)                                                       |
| Smiling man in sunlight                      | Chloe Kala Artist | [View](https://www.pexels.com/photo/1043474/)                                                       |


| Source | Notes |
| --- | --- |
| [favicon.io](https://favicon.io) | Generating the favicon |
| [Font Awesome](https://fontawesome.com) | Icons used throughout the site |
| [Pexels](https://images.pexels.com/photos/416160/pexels-photo-416160.jpeg) | Hero image |
| [TinyPNG](https://tinypng.com) | Compressing images < 5MB |

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN) for the support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) Tutor Team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and impostor syndrome.
- I would like to thank my friends and family, for believing in me, and allowing me to make this transition into software development.


