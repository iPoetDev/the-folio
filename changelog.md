# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and adheres to [Semantic Versioning](http://semver.org/).

> -   Modified, by incrementing and counting the index of commits on a daily basis
> -   (Major.Minor.Patch.CommitIndex) (By CJ)

## Changelog: v0.7.01.01 2023.02.25 - Profile Page: MVP.

### Added:

- Added: Responsive Images for Fluid Responsive Images.
- Added: Added folder Profile under '/assets/img/' -> '/assets/img/profile'
- Added: Hero Banner for profile.
- Added: Styled the Initial.
- Added: Navigation Banner.

### Change:

- Changed: Moved page specific css from core.css to profile.css.
- Changed: Merged About.html into Profile.html (Hero Section).

### ToDo:

- Style the Page's Navigaton.
- Complete the Page Navigation.
- Testing HTML.
- Testing CSS.
- Testing on Github Profile.

## Changelog: v6.01 2023-02-10-24: Update Later: Gap in Record

## Changelog: v0.5.01 2023.02.09 - Bump a Patch: Site Naviagtion

### Added v0.5.01 - Site Navigation - Top - Level

- Added: Top Level Navigation from prior built components
    To Do: Test from all pages. Local testing works.
    To Do: Style the links and link behaviours
    Fix: Absolute Form Labels - on the Navigation surface (z-index)
    To Do: Style and position other links and elements on the navigation.
    To Do : Style and space the logo or textual logo.
    To Do: Test on Github pages.

- Changed: Index.html, about.html,  contact.html, profile.html and folio.html with theme classes
    - Current bold primary colors, and decisions pending on approaches and final palettes
    - Thinking of adding a contrastinh header of opposing/complementary color
    - Idea is the Mondrian style color blocking approaches mixed with a dribbble inspired bold theme and layout.
    - Navigation overlay the same as the section page
    - To Do: add a breadcrumb indicator to the naviagtion page and or icon indicator

## Changelog: v0.4.5.01 2023.02.08 - Work.html

### Added v0.4.3.03 - Folio.html

- Added: Responsiveness to a collapsable grid layout of card components of 1row x 3 columns into a 3 by 1 orrientation. A few bugs, largely passable.

## Changelog: v0.4.3.03 2023.01.07 - Folio.html

### Expected/ToDo: - Folio.html

- ToDo: Add a CTA to link to the form
- ToDo: Add the content per client
    Client 1: CI Love Running Project (link to the GitHub Pages version of these)
    Client 2: CI Coder Coffee House (link to the GitHub Pages version of these)
- ToDo: Add the Accessibility / Aria Tags/Roles
- ToDo: Add/Update the Dark Mode Folio client Themes, and measure with the image in use.
- ToDo: Size and style each of the clients images for responsive sizes and organise the scaling
- ToDo:

### Added v0.4.3.03 - Folio.html

- Added: Responsiveness for a 2x1 landscape for all devices.
- Added: Responsiveness for a 2x1 portrait for all devices.
- Used 4 breakpoints,
    - All Mobile up to 968px portrait for flex column
    - All Mobile up to 968px landscape for flex row
    - All Mobile up to 408px portrait for handing smaller images, and other like flex column
    - All Fixed from 968 px for flex row.
- Used Custom properties for DRY code over the media queries
- Added Placeholder text and image (to be replaced with content)


## Changelog: v0.4.3.01 2023.01.07 - About.html

### Expected/ToDo:

- ToDo: Style the download button for the CV and text the CV
    - Develop a 1 Page CV for as an artefact (take a 1 page example for current cvs).
- ToDo: Add the About Me copy for content. Research for inspiration.
- ToDo: Add the Accessibility / Aria Tags/Roles
- ToDo: Add/Update the Dark Mode Info Themes, and measure with the image in use.
- ToDo: Add a image embellem/ background to hero image. (Extra and make the image backgrond of source image)

### Added: 00.04.3.01

- Added: Media Responsive Pictures
    - `ToDo: Adjust the image scaling and sources.
- Added: CSS Layer: info-blocks and associated styles for the about.html
    - These blocks detail the resposnsive layouts from from desktop down to mobile (Graceful degradation);
    - Three grid areas named: Info-Intro (Page Banner), Info-Image (Page Hero) on the Info-Main row (top), with the bottom row and grid area Info-About(me).
    - Bugs/Issues/ToDo:
        1. Lack control of flexbox height/blocksize in Info-Intro. A fustrate and maybe a documented issue.
        2. Intro-about runs out of grid flow (to the left). Fix-in with position absolute. Future work: Grid flow and alignment instead of position absolute.

### Updated: 00.04.3.01

- Updated: Switched from buildout-info.html (the working file) and merged into about.html as an style ready page ( for pre submission evaluation and styling.)
    - `ToDo`: Test the CSS with Jigsaw
    - `ToDo: Comment  the CSS for the relevant @layer
    - `ToDo: Decide on Color Theme for Page
    - `ToDo: Fonts & Typography
    - Define the wireframes for page.

### Moved: 00.04.3.02, 04

- Moved: all layout-*.html to /_archive/_layouts [02]
- Moved buildout-[folio | info].html to  /_archive/_buildouts [04]

## Changelog: v0.4.2.01-02 2023.01.06

### Added: 00.04.2.01

- Added: Color Palette, aka Branding, to Main.css via a layer custom property system [01]
  - Intent: to develop a dark mode first scheme, and if feasible, a light mode scheme. Developed both above, and can remove if time and scope do not permit.
- Created: [Version 1 of the Digital Folio Color Palette](/_documentation/Color/The-Digital-Folio_EightShapes_Contrast_Grid_2023-02-06%2011_17_59-version1.png)
- Added Contact Form and vanilla CSS validation, in progress via the buildout-contract.html[02]

Note: Struggling with nested grid layouts and responsiveness and neighbouring grids being aware of context and positioning of inner grid dimensions. See Buildout-landing.html for issues.

## Changelog: v0.4.0 2023.01.02

### Info: Bump to Minor 0.4

-   Info: Refactored all Pages Macro and Nested Layouts for responsiveness using grids and nested grids.
-   Todo: To test and full check.
    -   1. All mobile portrait;
    -   2. All mobile landscape.
    -   3. All tablet in portrait.
    -   4. All tablet in landscape.
    -   5. All Desktop and Laptop in Landscape.
    -   Info: Rough hewn layouts, refine as you go and debug.

### Added: 00.04.1.01

-   Added a responsive macro layouts: Expansive columns, and centering content on page on desktops. Row x Column.
-   Added `layout-land.html` as a 2x2 grid \(Desktop\) and 4x1 grid \(Mobile\).
-   Added `layout-info.html` as a 2x2 grid, with a 1x2 span \(Desktop\) and 4x1 grid. \(Mobile\).
-   Added `layout-contact.html` as a 2x2 grid, with a 1x2 span \(Desktop\) and 4x1 grid. \(Mobile\).
-   Added `layout-folio.html` as a 2x1 grid \(Desktop\) and 2x1 grid. \(Mobile\). Room to add more clients by row.
-   Added `layout-work.html` as a 3x1 grid \(Desktop\) and 3x1 grid. \(Mobile\). Room to add more work profiles by row.

### Changed: 00.04.1.01

-   Updated Main.css to use @layers as an organising principle \(code folding, code organisation, and code hierarchy\) and to manage the cascade.
    > @Layers are widely cross browser supported, howeever they are only a recommended candidate and not cleared for CSSWG working draft status.
    > As such: @layers willl caused invalidation errors in W3C CSS Jigsaw validator, as it only runs, as a lagging indicators, behind the browsers and only as the CSS Cascade Level 5 specificiation dictates. This is acceptable to me.
    > @layers are beyond the course material and are part of Modern/Interop-erable CSS, which the course material is not 100% compliant with.
    > Further notes in the Readme on this.

### Moved: 0.4.1.02

-   Moved: Accessory files to relevant \_archive files.

### Remove: 0.4.1.03

-   Remove: ToDo: Remove current: index.html, about.html, contact.html, folio.html, profile.html
-   Removed htmlhintrc and stylelint.json in lieu of in VSCode configs, not NPM packages.

## Changelog: v0.3.0 2023.01.23

> Version 0.3.0010 used for CSS Composition and Responsiveness Tests. Bump to 0.4.0 when all files pass CSS Validation.

### Changed: 0.3.1.01 2023.01.21-22

-   Changed relative paths in linked files.
-   Bumped Minor version due to breaking changes in IA/UI design.

> Outcome: GitHub pages deployed successfully and pages loaded successfully.

### Moved: 0.3.0 2023.01.21-22

-   Moved all tier 1 files (Info, work, folio) from folders to root and flattended the sitemap/Infgormation architecture by links.

## Changelog: v0.2.0 2023.01.23

### Changed: 0.2.1.01

-   Changed relative paths in linked files.
-   Bumped Minor version due to breaking changes in IA/UI design.

### Moved: 0.2.0

-   Moved files and folders from `/docs/` to `/root/` as GitHub Pages (Jenkins) was giving 404 errors on sub tiers. #BigReorganisation.

## Changelog: v0.1.2, 2023.01.22

### Added: 0.1.1.01-02: 2023.01.21-22

-   Added CSS Form Validations
-   Added CSS Form Elements.
-   Added .

### Changed: 0.1.2.01-03

-   Changed Contact.html - Improvemets to form html and element ordering.
-   Changed 2nd refactor of animated pure CSS Form inputs and Validation
    > Mate Marsechalko:
    >
    > -   [Advanced CSS-only Input Fields — Interactive, Animated, Validated](https://matemarschalko.medium.com/advanced-css-only-input-fields-interactive-animated-validated-d7ecff3cde8c)
    > -   [Advanced Form Validation With Only HTML and CSS](https://medium.com/better-programming/advanced-form-validation-with-only-html-and-css-e92fa3dc9b54)
-   Changed - more refactoring CSS Grid layouts using vw, vh,vmin, vmax, for fluid ayouts (Refer Ero Meyer).
-   ToDo: Mark up the code with references and log into the resume builder.

## Changelog: v0.1.0, 2023.01.19

### Patch version: Bump to version 0.1.0

-   Patch: HTML composition of skeleton/layout/semantics is bumped to 0.1.0. Use 0.1.0 for HTML composition version of MVP.
-   Next: CSS Layout & Composition with Responsiveness (Basics-first, Progressive enchancement and graceful degradtion). THe C of the CUBE methodology.

## Changelog: v0.0.9, 2023.19.01

### Added: 0.0.9.01, 0.0.9.05

-   Added navigation and drop down controls. (01)
    -   Reference: Input Checkbox without JS to open Menu:
    -   URL: [Pure CSS DropDown Menu](https://codepen.io/bradtraversy/pen/vMGBjQ "CodePen: Pure CSS DropDown Menu") (01)
-   Added Added Site menu to all pages
-   Added Content Type of text/html and UTF-8 to all html files as external W3C validator complained. (05)

### Change: 0.0.9.01, 0.0.9.03

-   Change the VSCode formater from Prettier to HTMLHint due to prettier enforcing xhtml self closing tags.
-   Changed: porfolio.html renamed to folio.html.

### Validated: 0.0.9.02,0.0.9.04

-   Validate: W3C in VSCode: Removed all warnings and erros in VSCode
    > -   index.html valid (2023-01-19 @13:31): _52 warnings and 27 errors removed_. (01)
    > -   about.html (2023-01-19 @14:49): _4 warnings and 21 ~~or 49~~ errors removed_. (04)
    > -   contact.html (2023-01-19 @ 15:28). _10 warnings and 72 errors removed_. (04)
    > -   folio.html (2023-01-19 @ 13:56). _13 warnings and 13 errors removed_. (04)
    > -   profile.html (2023-01-19 @ 15:12) . _4v warnings and 1 error removed_. (04)

## Changelog: v0.0.8 2023.18.01

### Changed: v0.0.8.01

-   Changed with minor edits to about.html and contact.html (01)
-   Changed / updated the main.css with the BoM for Classes, Id, pseudo-selectors and elements declarations across all files currently (02)
-   Changed / updated profile.html class and id for consistency. (05)
-   Changed portfolio,html to folio.html (04)
-   Moved #id css to identifers file.

> Identifers.css is intended for a intermeidatary css libray for high specufied styles and aria identification.

### Removed

-   Remomved: portfolio.html

## Changelog: v0.0.0,7 2023.01.17

### Changed: 0.0.7.01

-   Updated (this) changelog for 2023.01.16 .

No planned work today due to a private appointment/engagement.

## Changelog: v0.0.0,6 2023.01.16

### Added: 0.0.6.01, 0.0.6.03, 0.0.6.04, 0.0.6.06, 0.0.6.07, 0.0.6.08

-   Added by expanding Home.html panels (01).
-   Added top navigation component to all pages (.03)
-   Added css declarations (elements, classes, idenitifers) as a Bill of Materials to main.css (04).
-   Added the reorgansied & renamed files from 04 to the repos1tory.
-   Added renamed files from \_info/ \_work/ and \_folio.
-   Added page scaffold to about.html. (07)
-   Added page scaffold to contact.html. (07)
-   Added page scaffold to portfolio.html. (08)**\***
-   Added page scaffold to work.html. (08)**\***
-   **\***Added, by accidently, all changed files in one git push, was meant to be incremental, file by file. 5 files changed, 379 addtions, 183 deletions.

> **\***<small>End of day user error by inattention</small>

### Issues:0.0.6.07, 0.0.6.08

-   Issue: Github Pages workflow failed. Reason not investigate. (07,08)

### Changed: 0.0.6.05, 0.0.6.06 (2nd)

-   Changed separated as copy, the (04) BoM into distinct files for potential code separation and organisation. (04)
-   Changed updated main.css (06 1sr, 06, 2nd)

> <small>Thinking I may apply these css files as "layers" via the ordered link files (from most general to most specifc) </small>

### Removed: 0..0.6.02

-   Removed surplus Developer QoL files: .editorconfig, prettier.yml, prettierigore by file level +1 move.
-   Removed surplus /\_folio/ files by .gitignore
-   Removed surplus /\_info/ files by .gitignore
-   Removed surplus /\_work/ files by .gitignore

## Changelog: v0.0.5.01, 2023.01.15

### Added: 0.0.5.01

-   Added Wireframe Vars for protoyping. To be removed later.
-   Added FO Canvas Color to Body.
-   Added Updated Body's Role: Document & Title.
-   Added series of meta tags for page declarations and consistency.
-   Added HTML: Page Navigation Section
-   Added HTML: Main Body 2x2 Hero Panels.
-   Added ARIA detaling to all semantic tags and raoles of group, document,link,menu etc
-   Added ARIA role none to all divs (as divs are used for layout and containment)
-   Added Each Hero panel semantic markup: i.e. sub-sections, headers, headings, paragraphs

-   ### Changed

-   Changed File and Folder names.
-   Updated CSS Class naming with the fo- namespace prefix.
-   Changed .

## 0.0.4 - 2023-01-14

### Added

-   Added to Main.css: a :root element with Two Levels of CSS Resets.
-   Added to Main.css: a secondary :root for CSS Custom Properties. .
-   Added to Main.css: Translocated piror work from a workspace/prototype repository into project repository, on advice from Mentor; commit histories.

-   Note: Separating out application of multiple root elements for code organsiation. Technically feasible, as the casade will merge these declarations as one in the computed browser styles.
-   Given distinct purposes, it is not anticpated to not cause cascade and specificity conflicts.

### Changed: 0.0.4

-   Changed folder: docs to \_documentation
-   Changed folder: public to docs as Github Pages builds from root (./) or (./docs/). Implements Change for Now.
-   Changed .

## 0.0.2 - 2023-01-08

### Added: 12:30 - 18:00

-   Added new `Changelog.md`.
-   Added Change log entries from _v0.0.1_
-   Added Change log entries from _v0.0.2_ (this)
-   Added repository's `.\public\` sub folder organise the website into public for publication and best practice repository organisation.
    -   Added `index.html` boilerplate with `DOCTYYPE`, `html`, `lang=en`, `meta`, `link`, and `title` all conformly added. **<sup><small>[Prioirty 1]</small></sup>**
    -   Added a folder `_info` to contain all content that is Informative: i.e More Information [IA] ...
        -   Added `about.html` boilterplate from `index.html`, etc. **<sup><small>[Prioirty 1]</small></sup>**
        -   Added `contact.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
        -   Added `clients.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
    -   Added a folder `_porfolio` to contain all content that is about Porfolio of Past Effort [IA] ...
        -   Added `porfolio.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
        -   Added `client-loverunning.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
        -   Added `client-coderscoffees.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
    -   Added a folder `_profile` to contain all content that is about Profile of Experience [IA] ...
        -   Added `profile.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
        -   Added `credibility.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
        -   Added `learning.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
        -   Added `experience.html` bolierplate ... **<sup><small>[Prioirty 4]</small></sup>**
    -   Added a folder `assets\styles` containing Main Sytles sheets and auxillary stylesheets.
        -   Added `main.css` as a the primary stylesheet.
        -   Added `reset.css`

### Changed: 12:30 - 18:00

-   Changed .gitignore - minor update.
-   Changed .htmlhintrc - minor update.
-   Changed .markdownlint - minor update.
-   Changed Changelog.md - Major update (this).

> <small>Decided to not locate, for now, the website's html in the root of the repository. Not yet known if Jenkins/Gitub Pages can take this config or require all html and css in root of repoistory.
>
> -   If this complies with CI Assessment expectations.</small>

### Changed: 12:00pm

-   Changed `.gitignore` to ignore certain local changes and new file/folder type additions.
-   Changed `.htmlhintrc` to update a style rule or two from inital config.
-   Changed `.markdownlint` to update a style rule or two. However, local IDE style rules (VSCode settings) are taking prescendent currently.
    > Markdownlingt style rules can be move to Gitpot by a per repository copy of vscode settings.json or .code-workspace file.

## 0.0.1 - 2022-01-08

### Added: 9pm-12:39am

-   Added License: BDS-3.
-   Added Issue Template: Front Ended Issues/Bug.
-   Added Issue Labels
-   Added `.editorconfig` for consistent IDE styles.
-   Added `.gitattributes` describing the format and usage of this file.
-   Added `.gitconfig` configures the behaviour of git per repository, an esstential in CDE/RDE.
-   Added `.gitignore` to filter out files to be ignored/hidden by git and github.
-   Added `.gitmohijrc` & `.gitmoji.json`: <https://gitmoji.dev/> An emoji guide for your commit messages. Consistency.
-   Added `.markdownlint` Linting rules for markdown. Current govered by my local IDE. Not fully implemented. Documentation as code, for Code Styles.
-   Added `.prettier.yaml` and `.prettierignore` for Code beutification and formating. Coding consistency for Coding Sytle. Documentation as Code.
-   Added `.stylelintrc.json` for CSS Style Rules linting and formating. Coding consistentcy for Code Styles. Documenytation as Code.
-   Added `.htmlhintrc` for HTMLHint Rules linting and formating. Code consistentcy for Code Style. Documentation as Code.

> -   <small>_**Documentation as Code**_: Aims to reduce documentation bloat in the readme, and this is, exceptionally, beyond the requirements of assessment criteria.
> -   Codig Style conformity, consistent and adherence are enforced using linting and prettifying extensions and configruation files when configured for npm, or in Gitpod terms, pnpm.
> -   The Rules/Linting are a demonstratble adherence to Code Styles as per the assessment criteria _Pass_ and _Distinction_ performance levels.
> -   To improve the overall build quality of my products when testing and verifying.</small>

### Changed: 9pm-12:39am

-   Changed Updated Issue Template: Front Ended Issues/Bug with labels.
-   Edited `.gitconfig` to remove a Fetch misconfig.
