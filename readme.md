# **The Digital Folio**

The Digital Folio is a portfolio template site that could be used to showcase the work and clients of myself, Charles J Fowler (aka CJ) as a web developer and UX advisor. The site will be focused on promoting the past and current client projects, like Love Runnning and Codes Coffeehouse as examples of potential services rendered. This site showcases the potential for hosting references to other hosted projects and deliverables.

Screenshot

> Visit: [The Digital Folio](https://ipoetdev.github.io/the-folio/ "The Digital Folio: https://ipoetdev.github.io/the-folio/ by Charles J Fowler (@ipoetdev)") | [https://ipoetdev.github.io/the-folio/](https://ipoetdev.github.io/the-folio/)

### **Project Goals**

 - Provide a showcase for future projects online for prospective clients to view past work.
 - Provide a high level profile of who I am professionally and personally to prospective clients and/or employers.
 - Provide a contact point for business and contracting enquiries by a contact form.active

 ### **Website Owner Goals**

 The site is dual purpose, as a showcase of past initiatives has two key audiences: Potential clients seeking a solition and potential employers seeking an experienced hire.

 - Reach new clients and
 - Establish a web project freelancing footing
 - Create new employment opportunities
 - Increase revenue and income
---

## **User Experience**


### Audience(s)

The website is created with the following in target audience(s) in mind.

- A potential client seeking a website (new or redesign).
- An web agency seeking a contractor for a project.
- A recruiter seeking a hire for a post.
- A decision maker seeking to validate a hire's experience and past work.

### User requirements or expectations

- A block level landing page with 4 jump points.
- A website that showcases projects.
  - [Use Cases] For a gallery view of past & current projects.
    - A collection of past projects and client as a basic gallery.
    - External links to past projects.
    - Brief project synopsis
    - [Enhancement]: List of billable services per project.
    <!-- Note: For purpose of submission: The external websites are not developed, and in lieu, the external links link only to a screenshot of said site as a proxy for a fully developed website. This comment is for assesor review only, visible on GitHub-->
- A simple site map for navigation.
- A responsive layout for most common devices.
- A clear and spacious layout, minimalist in content presentation.
- Clear and unambigious call to actions (one of every page).
  - [Use Case] For new business or new leads.
    - A contact card to initiate direct phone call or an email .
    - A contact form for online enquiries f
    - Social Media contact icons

#### Enhancements to User Requirements [Future]

- A websi

### User Stories

> Arguably a form of decision records that are focused on the user profile and user flow and activities. Both are linked by shared/paired acceptanc criteria

## User Experience (UXD)

### Accessibility

> <div style="text-align:right"><b>Interaction | Informatiom Architecture | Structure Plane</b></div>

### Usability

> <div style="text-align:right"><b>Information Architecture | Skeleton Plane</b></div>

-   Similar parts, similar ways
-   Progressive disclosure (plit and navigation)
-   Visual prioritisation
-   Feature v Usability
-   Hick-Hyman Law
-   Navigation ( browse, searching, pagination, filters,)
-   Representitional Icons
-   Lower Cognition Friction (color, text, icons, same behaviours)

### Metaphors

> <div style="text-align:right"><b>Information Design | Skeleton Plane</b></div>

-   Navigation
-   Invisible
-   Quality
-   Minimal
-   Context & Order (Alphabetical, Categorical, Locational, Time Ordering (fix duration), form order)

### Wireframes
<div style="text-align:right"><b>Modeling | Skelton Plane</b></div>


---

# BUILD

<!-- > N.B: Developer laptop was rebuilt midst project and reconfigured. So the following applies from the 26th of January. -->

## Environments

<!-- > Did not use Gitpod, too high a friction and high context switching costs. -->

- VSCode Insiders - Local
- LiveServer: http://127.0.0.1

- Github Pages

## Browsers

- Google Chrome (Dev) versions 111-112
- Firefox Developer Edition versions 110.0 beta

### Browser Extensions

> <sub>[*] DevTools extenions</sub>

- AxeDevTools, version 4.49.0
- Responsiveviewer, version 1.0.20

## Languages

-   HTML5
<!-- -   WAI-ARIA and Web Content Accessibility Guidelines (WCAG) -->
-   CSS3

### IDE

> Extensions

-
- HTML Validate (html-validate.vscode-html-validate, 2020-2023), version 7.13.2
- Stylelint (stylelint.vscode-stylelint, 2019-2022), version 1.2.3
- PostCSS Language Support (csstools.postcss), version 1.0.9
- PostCSS Intellisense and Highlighting (vunguyentuan.vscode-postcss), version 2.0.2
- PostCSS Sorting(mrmlnc.vscode-postcss-sorting, 2016-2017 (*Last commit: 5 years ago*)), version 3.0.1.


### Repository

<!-- > Packages used for developer quality of life and delivery purposes -->

-   Javascript (Node, pnpm and npmregistry packages)
-   YAML (configuration files for NPM packages)
-   C/make for .gitignore and similar ignore files

#### *NPM Plugins*

<!-- > These were removed prior to submission -->

- Prettier
- Editorconfig
- HTML-validate
- Stylelint
- Postcss

### Frameworks Used

> Programs, Packages and Libraries used in different workflows.

- [Responsive Viewer](https://github.com/skmail/responsive-viewer "@Skmail, https://github.com/skmail/responsive-viewer")
- [Responsive Image Breakpoings Generator](https://www.responsivebreakpoints.com/ " https://www.responsivebreakpoints.com/")
- [Fluid Type Scale Calculator](https://www.fluid-type-scale.com/ " Aleksandr Hovhannisyan (2021-Present), Fluid Type Scale Calculator, version 1.2.1, Last Accessed: 2023-02-13:  https://www.fluid-type-scale.com/") by Aleksandr Hovhannisyan (2021-Present), Fluid Type Scale Calculator, version 1.2.1, Last Accessed: 2023-02-13:  https://www.fluid-type-scale.com/



#### Design Workflows

<!-- > Started to use these. Then ceased to to opportunity cost (of learning) verses benefit for project.  Not central to submission. -->

-   Figma (Free, Student and Education plan).
-   Fidget: Figma plugin (Paid).

---

# RELIABILITY

## Testing & Verification

### Testing

### Verification

#### Validation

##### HTML

##### CSS

- CSS @layer is not in the current working draft specification, as of Feburay 17th 2023, though is supported by all modern browsers as per Interop 2022.

    As such causes CSS Jigsaw to invalidate this syntax

##### Lighthouse

###### Index

###### About

###### Folio

### Issues



---

# DEPLOY

## Features



### Future Enhancements

#### ***[Context]* Home Page**

- Combine the two project hero cards (top row) into a all-in-one carousel.
- Create a modal dialog for a quick contact form as a on page CTA instead of asking user to fill out a larger form.

#### ***[Context]* About | Info**

- Redesign using @container queries and try flex box for macro page layouts.
    > Issue: Refactor page too many times, and regressed technique and design, that ended using absolute positioning regessivel for all macro layouts. Pixel perfect design is flawed but roughly responsive.
- Create a 2-3 step/page (A see more) inner page user flow to dive into the work experience,

#### [Context] Folio

- With only two projects showcases, this is a very simple gallery. As projects grow, and more content is possible, the  a redesign for page would be preferable, giving each project its own showcase item page from a gallery view page.
- Repeat the carousel as a hero banner on top of Folio with a internal jump link to each client page.

#### [New]

- Add list/hint services available component with pricing per client page.

#### All Pages

- Improve accessibility with ARIA/WAI CAG tags and test against other forms of disability and impairment and interactive modes Further research and development.
- Implement Dark and Light modes with an toggle
- Add an accessibility navigation control to allow users to control the following preferences
    - Reduce Motion
    - Color Contrast (additional color schemes)
    -
  >This is out fo scope of the course and is super extra nuanced.

## Deployment

### Repository Service

- Github.com is the remote code repository service being used.
- User account and profile is
  > - `@iPoetDev`
- The repository name is
  > - `the-folio`
The repository domain uri is
  > - `https://github.com/iPoetDev/the-folio`


### Deployment Environment

- Github Pages via the inbuilt Github Actions workflows of:
  i) Deploy a static web page off every commit
  ii) Once the commit is built, then deploy the new website and pushes to hosted domain URI.
- Github.io is the hosted domain URI and service.
-

---

# LAUNCH

## Live Site



## Forking this repository

## Cloning this repository

---

# Assesment

## Credits

### Process


### Frameworks/Tooling

-   ResponsiveViewer.org (Oct 2022) "About Responsive Viewer - Chrome Extension". Last Accessed: 2023-02-16 from https://github.com/skmail/responsive-viewer
-   Deque (2023), "axeDevTools". https://www.deque.com/axe/devtools/
-   Cloudinary (2023) "Responsive Images in HTML: A Practical Guide", Last Accessed: 2023-02-13. https://cloudinary.com/guides/responsive-images/responsive-images-in-html-a-practical-guide from https://github.com/cloudinary/responsive_breakpoints_generator.
-   Aleksandr Hovhannisyan (2021-Present), "Fluid Type Scale Calculator: version 1.2.1", Last Accessed: 2023-02-13:  https://www.fluid-type-scale.com/

#### *IDE Extensions*

> *A selection of key extensions that touched the code.*

-  HTML-validate.org, "HTML-validate, Offline HTML5 validator". https://marketplace.visualstudio.com/items?itemName=html-validate.vscode-html-validate from https://gitlab.com/html-validate/vscode-html-validate
-   Stylelint.io "Stylelint". from https://github.com/stylelint/stylelint
- Vu Nguyen,"PostCSS Intellisense and Highlighting" https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-postcss from https://github.com/vunguyentuan/vscode-postcss
- mrmlnc, "PostCSS Sorting".  https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-postcss-sorting from https://github.com/mrmlnc/vscode-postcss-sorting

### Design

- MDN, Mozilla.org (1998-2023) "MDN Web Docs". Last Access: 2023-02-17. https://developer.mozilla.org/en-US/

#### Fonts

> Downloaded.

- Google Fonts (2000-2023). ""
- FontSquirel

#### Color

- Contrast Grid (2017-2021). "Contrast Grid, version 1.1.0". Last Accessed: 2023-02-16.https://contrast-grid.eightshapes.com/?version=1.1.0, from https://github.com/EightShapes/contrast-grid.

#### Art Direction  & Images

- Cloudinary, as above, for Responsive Images Breakpoint Generator.
-

### Content

- All content copy is self created and authored.

### Media

- Charles J Fowler, (2015) "Looking Forward". Private use.
- Jan Andraschko, (2018) "About Who?". Private use.
- @Ajgreaves & Code Institute (2020-2023). "Love Running". Last Accessed: 2023-02-10. https://ajgreaves.github.io/love-running/. Media used: Screenshots of website and content references, URIs.
- Code Institute (2020-2023). "Coders Coffeehouse - "

## Acknowledgements

### Research

-

### Code Repository

-  Elly Loel "A modern css reset" Last Accessed: 2023-01-11. Last Updated: 2023-02-11. https://gist.github.com/EllyLoel/4ff8a6472247e6dd2315fd4038926522 ✮✮✮


### Tutorials




### Guides

-  Miriam Suzanne, CSS-Tricks.com (2020, Oct) "A Complete Guide to CSS Media Queries". Last Updated: 2022-10-19. https://css-tricks.com/a-complete-guide-to-css-media-queries/
-  Andres Galante, CSS-Tricks.com (2020, Oct) "A Complete Guide to CSS Media Queries". Last Updated: 2022-10-19. https://css-tricks.com/a-complete-guide-to-css-media-queries/
-  Chris Coyier, CSS-Tricks.com (2020, May) "A Guide to the Responsive Images Syntax in HTML" Last Updated: 2022-08-25. https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/
-  Chris House, CSS-Tricks.com (2021, May) "A complete guide to CSS Grid". Last Updated: 2023-02-09. https://css-tricks.com/snippets/css/complete-guide-grid/#aa-grid-properties
-  Chris Coyier, CSS-Tricks.com (2013, Apr) "A complete guide to Flexbox". Last Updated: 2022-12-09. https://css-tricks.com/snippets/css/a-guide-to-flexbox/
-  Chris Coyier, CSS-Tricks.com (2020, Feb) "A Complete Guide to Links and Buttons". Last Updated: 2022-02-22. https://css-tricks.com/a-complete-guide-to-links-and-buttons/. Download button on About.html

### Video

- Kevin Powell: "Simplest CSS reset to prevent headaches" Last Accessed: 2023-01-11:https://www.youtube.com/watch?v=2lyDv0wOQuQ,
- Una Kravets: Video Playlist "Designing in the Browser". https://www.youtube.com/playlist?list=PLNYkxOF6rcIDI0QtJvW6vKonTxn6azCsD.
- Rachel Andrews: Video: "How to understand CSS". https://youtu.be/9uARaWJ9mXI. The `display: flow-root` property.
