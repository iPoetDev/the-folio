# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and adheres to [Semantic Versioning](http://semver.org/). Modified, by incrementing and counting the index of commits on a daily basis (Major.Minor.Patch.CommitIndex) (By CJ)

## Changelog: v0.1.0, 2023.19.01

### Patch version: Bump to version 0.1.0:

- Patch: HTML composition of skeleton/layout/semantics is bumped to 0.1.0. Use 0.1.0 for HTML composition version of MVP.
- Next: CSS Layout & Composition with Responsiveness (Basics-first, Progressive enchancement and graceful degradtion). THe C of the CUBE methodology.

## Changelog: v0.0.9, 2023.19.01

### Added: 0.0.9.01, 0.0.9.05

- Added navigation and drop down controls. (01)
  - Reference: Input Checkbox without JS to open Menu:
  - URL: [Pure CSS DropDown Menu](https://codepen.io/bradtraversy/pen/vMGBjQ "CodePen: Pure CSS DropDown Menu") (01)
- Added Added Site menu to all pages
- Added Content Type of text/html and UTF-8 to all html files as external W3C validator complained. (05)

### Change: 0.0.9.01, 0.0.9.03,

- Change the VSCode formater from Prettier to HTMLHint due to prettier enforcing xhtml self closing tags.
- Changed: porfolio.html renamed to folio.html.

### Validated: 0.0.9.02,0.0.9.04

- Validate: W3C in VSCode: Removed all warnings and erros in VSCode
  > - index.html valid (2023-01-19 @13:31): _52 warnings and 27 errors removed_. (01)
  > - about.html (2023-01-19 @14:49): _4 warnings and 21 ~~or 49~~ errors removed_. (04)
  > - contact.html (2023-01-19 @ 15:28). _10 warnings and 72 errors removed_. (04)
  > - folio.html (2023-01-19 @ 13:56). _13 warnings and 13 errors removed_. (04)
  > - profile.html (2023-01-19 @ 15:12) . _4v warnings and 1 error removed_. (04)

## Changelog: v0.0.8 2023.18.01

### Changed: v0.0.8.01

- Changed with minor edits to about.html and contact.html (01)
- Changed / updated the main.css with the BoM for Classes, Id, pseudo-selectors and elements declarations across all files currently (02)
- Changed / updated profile.html class and id for consistency. (05)
- Changed portfolio,html to folio.html (04)
- Moved #id css to identifers file.

> Identifers.css is intended for a intermeidatary css libray for high specufied styles and aria identification.

### Removed:

- Remomved: portfolio.html

## Changelog: v0.0.0,7 2023.01.17

### Changed: 0.0.7.01

- Updated (this) changelog for 2023.01.16 .

No planned work today due to a private appointment/engagement.

## Changelog: v0.0.0,6 2023.01.16

### Added: 0.0.6.01, 0.0.6.03, 0.0.6.04, 0.0.6.06, 0.0.6.07, 0.0.6.08

- Added by expanding Home.html panels (01).
- Added top navigation component to all pages (.03)
- Added css declarations (elements, classes, idenitifers) as a Bill of Materials to main.css (04).
- Added the reorgansied & renamed files from 04 to the repos1tory.
- Added renamed files from \_info/ \_work/ and \_folio.
- Added page scaffold to about.html. (07)
- Added page scaffold to contact.html. (07)
- Added page scaffold to portfolio.html. (08)**\***
- Added page scaffold to work.html. (08)**\***
- **\***Added, by accidently, all changed files in one git push, was meant to be incremental, file by file. 5 files changed, 379 addtions, 183 deletions.

> **\***<small>End of day user error by inattention</small>

### Issues:0.0.6.07, 0.0.6.08

- Issue: Github Pages workflow failed. Reason not investigate. (07,08)

### Changed: 0.0.6.05, 0.0.6.06 (2nd)

- Changed separated as copy, the (04) BoM into distinct files for potential code separation and organisation. (04)
- Changed updated main.css (06 1sr, 06, 2nd)

> <small>Thinking I may apply these css files as "layers" via the ordered link files (from most general to most specifc) </small>

### Removed: 0..0.6.02

- Removed surplus Developer QoL files: .editorconfig, prettier.yml, prettierigore by file level +1 move.
- Removed surplus /\_folio/ files by .gitignore
- Removed surplus /\_info/ files by .gitignore
- Removed surplus /\_work/ files by .gitignore

## Changelog: v0.0.5.01, 2023.01.15

### Added: 0.0.5.01

- Added Wireframe Vars for protoyping. To be removed later.
- Added FO Canvas Color to Body.
- Added Updated Body's Role: Document & Title.
- Added series of meta tags for page declarations and consistency.
- Added HTML: Page Navigation Section
- Added HTML: Main Body 2x2 Hero Panels.
- Added ARIA detaling to all semantic tags and raoles of group, document,link,menu etc
- Added ARIA role none to all divs (as divs are used for layout and containment)
- Added Each Hero panel semantic markup: i.e. sub-sections, headers, headings, paragraphs
- ### Changed:

- Changed File and Folder names.
- Updated CSS Class naming with the fo- namespace prefix.
- Changed .

## 0.0.4 - 2023-01-14

### Added:

- Added to Main.css: a :root element with Two Levels of CSS Resets.
- Added to Main.css: a secondary :root for CSS Custom Properties. .
- Added to Main.css: Translocated piror work from a workspace/prototype repository into project repository, on advice from Mentor; commit histories.

- Note: Separating out application of multiple root elements for code organsiation. Technically feasible, as the casade will merge these declarations as one in the computed browser styles.
- Given distinct purposes, it is not anticpated to not cause cascade and specificity conflicts.

### Changed: 0.0.4

- Changed folder: docs to \_documentation
- Changed folder: public to docs as Github Pages builds from root (./) or (./docs/). Implements Change for Now.
- Changed .

## 0.0.2 - 2023-01-08

### Added: 12:30 - 18:00

- Added new `Changelog.md`.
- Added Change log entries from _v0.0.1_
- Added Change log entries from _v0.0.2_ (this)
- Added repository's `.\public\` sub folder organise the website into public for publication and best practice repository organisation.
  - Added `index.html` boilerplate with `DOCTYYPE`, `html`, `lang=en`, `meta`, `link`, and `title` all conformly added. **<sup><small>[Prioirty 1]</small></sup>**
  - Added a folder `_info` to contain all content that is Informative: i.e More Information [IA] ...
    - Added `about.html` boilterplate from `index.html`, etc. **<sup><small>[Prioirty 1]</small></sup>**
    - Added `contact.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
    - Added `clients.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
  - Added a folder `_porfolio` to contain all content that is about Porfolio of Past Effort [IA] ...
    - Added `porfolio.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
    - Added `client-loverunning.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
    - Added `client-coderscoffees.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
  - Added a folder `_profile` to contain all content that is about Profile of Experience [IA] ...
    - Added `profile.html` bolierplate ... **<sup><small>[Prioirty 2]</small></sup>**
    - Added `credibility.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
    - Added `learning.html` bolierplate ... **<sup><small>[Prioirty 3]</small></sup>**
    - Added `experience.html` bolierplate ... **<sup><small>[Prioirty 4]</small></sup>**
  - Added a folder `assets\styles` containing Main Sytles sheets and auxillary stylesheets.
    - Added `main.css` as a the primary stylesheet.
    - Added `reset.css`

### Changed: 12:30 - 18:00

- Changed .gitignore - minor update.
- Changed .htmlhintrc - minor update.
- Changed .markdownlint - minor update.
- Changed Changelog.md - Major update (this).

> <small>Decided to not locate, for now, the website's html in the root of the repository. Not yet known if Jenkins/Gitub Pages can take this config or require all html and css in root of repoistory | and if this complies with CI Assessment expectations.</small>

### Changed: 12:00pm

- Changed `.gitignore` to ignore certain local changes and new file/folder type additions.
- Changed `.htmlhintrc` to update a style rule or two from inital config.
- Changed `.markdownlint` to update a style rule or two. However, local IDE style rules (VSCode settings) are taking prescendent currently.
  > Markdownlingt style rules can be move to Gitpot by a per repository copy of vscode settings.json or .code-workspace file.

## 0.0.1 - 2022-01-08

### Added: 9pm-12:39am

- Added License: BDS-3.
- Added Issue Template: Front Ended Issues/Bug.
- Added Issue Labels
- Added `.editorconfig` for consistent IDE styles.
- Added `.gitattributes` describing the format and usage of this file.
- Added `.gitconfig` configures the behaviour of git per repository, an esstential in CDE/RDE.
- Added `.gitignore` to filter out files to be ignored/hidden by git and github.
- Added `.gitmohijrc` & `.gitmoji.json`: <https://gitmoji.dev/> An emoji guide for your commit messages. Consistency.
- Added `.markdownlint` Linting rules for markdown. Current govered by my local IDE. Not fully implemented. Documentation as code, for Code Styles.
- Added `.prettier.yaml` and `.prettierignore` for Code beutification and formating. Coding consistency for Coding Sytle. Documentation as Code.
- Added `.stylelintrc.json` for CSS Style Rules linting and formating. Coding consistentcy for Code Styles. Documenytation as Code.
- Added `.htmlhintrc` for HTMLHint Rules linting and formating. Code consistentcy for Code Style. Documentation as Code.

> - <small>_**Documentation as Code**_: Aims to reduce documentation bloat in the readme, and this is, exceptionally, beyond the requirements of assessment criteria.
> - Codig Style conformity, consistent and adherence are enforced using linting and prettifying extensions and configruation files when configured for npm, or in Gitpod terms, pnpm.
> - The Rules/Linting are a demonstratble adherence to Code Styles as per the assessment criteria _Pass_ and _Distinction_ performance levels and improve the overall build quality of my products when testing and verifying.</small>

### Changed: 9pm-12:39am

- Changed Updated Issue Template: Front Ended Issues/Bug with labels.
- Edited `.gitconfig` to remove a Fetch misconfig.
