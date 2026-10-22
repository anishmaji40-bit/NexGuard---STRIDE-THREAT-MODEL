# NexGuard Resources, Libraries, and Code Guide

## Technologies and libraries

NexGuard uses standard HTML, CSS, and plain JavaScript. It does not depend on a JavaScript framework, third-party UI library, external font service, image library, or package installation. The diagrams and icons are created with HTML, CSS, and text symbols.

The site uses browser-native features: local storage saves demo changes on the current device; form APIs read user input; drag-and-drop moves architecture components; and Blob and URL browser APIs create JSON and CSV downloads. These are browser capabilities, not separate libraries.

## Project files

- **index.html:** The starting page. It loads the style sheet and JavaScript application.
- **styles.css:** Defines the colors, typography, layout, responsive behavior, buttons, cards, diagrams, and workspace styling.
- **app.js:** Holds sample data, draws the pages, handles navigation and interactions, calculates illustrative threat scores, and saves workspace edits in the current browser.
- **README.md:** Explains how to open or publish the static demo and describes its limits.
- **DATA-MODEL.md:** Describes the data saved in browser storage and explains that it is not cloud-backed.
- **robots.txt and sitemap.xml:** Provide basic site and page information for search crawlers.

## How the code works

The browser opens index.html, which loads styles.css and app.js. JavaScript chooses a page from the address hash, renders its interface, and responds to clicks, form submissions, search, and drag-and-drop. Changes to projects, models, threats, and settings are serialized into browser local storage. Risk scores use likelihood multiplied by impact, and report downloads are generated in the browser.

The current version has no active login flow, Python server, API, or database connection. Account registration, cloud saving, and team access are marked as in progress. A legacy data folder from the old login version may remain in the project; do not include it when publishing the static website.
