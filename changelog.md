# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and adheres to [Semantic Versioning](http://semver.org/).

## 0.0.2 - 2022-01-08

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

> <small>Decided to not locate, for now, the website's html in the root of the repository.
> Not yet known if Jenkins/Gitub Pages can take this config or require all html and css in root of repoistory | and if this complies with CI Assessment expectations.</small>

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
