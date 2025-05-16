
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

⚠️ INSTRUCTIONS ⚠️

In this section, you should go over the different parts of your project, and describe each feature. You should explain what value each of the features provides for the user, focusing on your target audience, what they want to achieve, and how your project can help them achieve these things.

**IMPORTANT**: Remember to always include a screenshot of each individual feature!

⚠️ --- END --- ⚠️


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

⚠️ TIP ⚠️

Consider adding screenshots of your Projects Board(s), Issues (open and closed), and Milestone tasks.

⚠️ --- END ---⚠️

[GitHub Projects](https://www.github.com/Emanuelsemer/janedoe-photography/projects) served as an Agile tool for this project. Through it, EPICs, User Stories, issues/bugs, and Milestone tasks were planned, then subsequently tracked on a regular basis using the Kanban project board.

![screenshot](documentation/gh-projects.png)

### GitHub Issues

[GitHub Issues](https://www.github.com/Emanuelsemer/janedoe-photography/issues) served as an another Agile tool. There, I managed my User Stories and Milestone tasks, and tracked any issues/bugs.

| Link | Screenshot |
| --- | --- |
| [![GitHub issues](https://img.shields.io/github/issues/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/issues) | ![screenshot](documentation/gh-issues-open.png) |
| [![GitHub closed issues](https://img.shields.io/github/issues-closed/Emanuelsemer/janedoe-photography)](https://www.github.com/Emanuelsemer/janedoe-photography/issues?q=is%3Aissue+is%3Aclosed) | ![screenshot](documentation/gh-issues-closed.png) |

### MoSCoW Prioritization

I've decomposed my Epics into User Stories for prioritizing and implementing them. Using this approach, I was able to apply "MoSCoW" prioritization and labels to my User Stories within the Issues tab.

- **Must Have**: guaranteed to be delivered - required to Pass the project (*max ~60% of stories*)
- **Should Have**: adds significant value, but not vital (*~20% of stories*)
- **Could Have**: has small impact if left out (*the rest ~20% of stories*)
- **Won't Have**: not a priority for this iteration - future features

## Testing

> [!NOTE]
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

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

⚠️ INSTRUCTIONS ⚠️

Use this space to discuss any differences between the local version you've developed, and the live deployment site. Generally, there shouldn't be [m]any major differences, so if you honestly cannot find any differences, feel free to use the following example:

⚠️ --- END --- ⚠️

There are no remaining major differences between the local version when compared to the deployed version online.

## Credits

⚠️ INSTRUCTIONS ⚠️

In the following sections, you need to reference where you got your content, media, and any extra help. It is common practice to use code from other repositories and tutorials (which is totally acceptable), however, it is important to be very specific about these sources to avoid potential plagiarism.

⚠️ --- END ---⚠️

### Content

⚠️ INSTRUCTIONS ⚠️

Use this space to provide attribution links for any borrowed code snippets, elements, and resources. Ideally, you should provide an actual link to every resource used, not just a generic link to the main site. If you've used multiple components from the same source (such as Bootstrap), then you only need to list it once, but if it's multiple Codepen samples, then you should list each example individually. If you've used AI for some assistance (such as ChatGPT or Perplexity), be sure to mention that as well. A few examples have been provided below to give you some ideas.

⚠️ --- END ---⚠️

| Source | Notes |
| --- | --- |
| [Markdown Builder](https://markdown.2bn.dev) | Help generating Markdown files |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | "How to Write a Git Commit Message" |
| [Rosie Resumé](https://codeinstitute.net) | Code Institute walkthrough project inspiration |
| [Bootstrap](https://getbootstrap.com) | Various components / responsive front-end framework |
| [ChatGPT](https://chatgpt.com) | Help with code logic and explanations |

### Media

⚠️ INSTRUCTIONS ⚠️

Use this space to provide attribution links to any media files borrowed from elsewhere (images, videos, audio, etc.). If you're the owner (or a close acquaintance) of some/all media files, then make sure to specify this information. Let the assessors know that you have explicit rights to use the media files within your project. Ideally, you should provide an actual link to every media file used, not just a generic link to the main site, unless it's AI-generated artwork.

Looking for some media files? Here are some popular sites to use. The list of examples below is by no means exhaustive. Within the Code Institute Slack community, you can find more "free media" links by sending yourself (or Slackbot) the following command: `!freemedia`.

- Images
    - [Pexels](https://www.pexels.com)
    - [Unsplash](https://unsplash.com)
    - [Pixabay](https://pixabay.com)
    - [Lorem Picsum](https://picsum.photos) (placeholder images)
    - [Wallhere](https://wallhere.com) (wallpaper / backgrounds)
    - [This Person Does Not Exist](https://thispersondoesnotexist.com) (reload to get a new person)
- Audio
    - [Audio Micro](https://www.audiomicro.com/free-sound-effects)
- Video
    - [Videvo](https://www.videvo.net)
- Image Compression
    - [TinyPNG](https://tinypng.com) (for images <5MB)
    - [CompressPNG](https://compresspng.com) (for images >5MB)

A few examples have been provided below to give you some ideas on how to do your own Media credits.

⚠️ --- END ---⚠️

| Source | Notes |
| --- | --- |
| [favicon.io](https://favicon.io) | Generating the favicon |
| [Rosie CV](https://codeinstitute.net) | Sample images provided from the walkthrough projects |
| [Font Awesome](https://fontawesome.com) | Icons used throughout the site |
| [Pexels](https://images.pexels.com/photos/416160/pexels-photo-416160.jpeg) | Hero image |
| [Wallhere](https://c.wallhere.com/images/9c/c8/da4b4009f070c8e1dfee43d25f99-2318808.jpg!d) | Background wallpaper |
| [Pixabay](https://cdn.pixabay.com/photo/2017/09/04/16/58/passport-2714675_1280.jpg) | Background wallpaper |
| [DALL-E 3](https://openai.com/index/dall-e-3) | AI generated artwork |
| [TinyPNG](https://tinypng.com) | Compressing images < 5MB |
| [CompressPNG](https://compresspng.com) | Compressing images > 5MB |
| [CloudConvert](https://cloudconvert.com/webp-converter) | Converting images to `.webp` |

### Acknowledgements

⚠️ INSTRUCTIONS ⚠️

Use this space to provide attribution and acknowledgement to any supports that helped, encouraged, or supported you throughout the development stages of this project. It's always lovely to appreciate those that help us grow and improve our developer skills. A few examples have been provided below to give you some ideas.

⚠️ --- END ---⚠️

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN) for the support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) Tutor Team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and impostor syndrome.
- I would like to thank my partner, for believing in me, and allowing me to make this transition into software development.
- I would like to thank my employer, for supporting me in my career development change towards becoming a software developer.

