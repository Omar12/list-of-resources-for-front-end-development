# List of Resources for Front-End Development
The following list is a curated list of front-end development resources.
It's purpose is to provide a specified list of resources for quick finding.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [List of Resources for Front-End Development](#list-of-resources-for-front-end-development)
  - [Workspace](#workspace)
    - [CLI](#cli)
    - [Browsers](#browsers)
    - [Text Editors](#text-editors)
    - [OS X Applications](#os-x-applications)
  - [Team Collaboration](#team-collaboration)
  - [Design](#design)
    - [Fonts](#fonts)
    - [Stock Images](#stock-images)
  - [Workspace](#workspace-1)
  - [Development](#development)
    - [Reference](#reference)
      - [Responsive Web Design](#responsive-web-design)
    - [Best Practices](#best-practices)
    - [Performance](#performance)
    - [Front-End Frameworks](#front-end-frameworks)
    - [HTML](#html)
      - [Project Reference](#project-reference)
        - [Pattern Libraries](#pattern-libraries)
        - [Documentation](#documentation)
    - [Styles](#styles)
    - [SVG](#svg)
    - [JavaScript](#javascript)
      - [Reference](#reference-1)
      - [ES6](#es6)
      - [Libraries](#libraries)
      - [Utilities](#utilities)
      - [Web Components](#web-components)
    - [Accessibility](#accessibility)
    - [Reference](#reference-2)
    - [Browser Dev Tools](#browser-dev-tools)
    - [Bookmarklets](#bookmarklets)
    - [Cross Browser Testing](#cross-browser-testing)
    - [Deployment](#deployment)
  - [Keeping Up To Date](#keeping-up-to-date)
    - [Listings](#listings)
    - [Podcasts](#podcasts)
    - [Newsletters](#newsletters)
    - [Blogs](#blogs)
    - [Further Education](#further-education)
    - [Paid Services](#paid-services)
  - [Other Comprehensive Lists](#other-comprehensive-lists)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Workspace
### System
The following CLI applications are almost essential for all systems. They will be used to run various tasks mentioned further on.

* [The Art of the Command Line](https://github.com/jlevy/the-art-of-command-line)
* [Explain Shell](http://explainshell.com/) - Handy tool that explains command-line commands
* [**git**](http://git-scm.com/)
* [git - the simple guide](http://rogerdudler.github.io/git-guide/)
* [git cheat sheet](http://scotch.io/bar-talk/git-cheat-sheet)


### Apps
#### Browsers
  * [Chrome](https://www.google.com/intl/en/chrome/browser/)
  * [Chrome Canary](https://www.google.com/intl/en/chrome/browser/canary.html) - Nightly builds of Chrome. Good to test bleeding edge features.
  * [Other Chromium Nightly Channels](http://www.chromium.org/getting-involved/dev-channel) - Use at your own risk.
  * Safari - Included on Mac OS X
  * [Firefox](http://www.mozilla.org/en-US/firefox/new/)
  * [Opera](http://www.opera.com/)
  * [Internet Explorer](http://www.modern.ie/en-us) - VM's that include various versions of Internet Explorer.

#### Text Editors
* Sublime Text
  * [Visual Enhancements for better coding](http://webdesign.tutsplus.com/articles/simple-visual-enhancements-for-better-coding-in-sublime-text--webdesign-18052)
  * Install [Package Manager](https://sublime.wbond.net/installation)
  	* Keyboard Shortcut: **`Shift+Cmd+P`** and start typing *Package Manager*. You can add any Sublime Text Package from this interface.
    * Recommended Packages
      * [Emmet](http://emmet.io/) - Improve your HTML and CSS workflow. ![image](http://i.imgur.com/RlW2xSU.gif)
      * GitGutter - plugin to show an icon in the gutter area indicating whether a line has been inserted, modified or deleted.
  * Recommended Theme: [Spacegray](http://kkga.github.io/spacegray/)
* [Github's Atom](https://atom.io/)
* [Brackets](http://brackets.io/)

#### OS X Applications
* [Alfred](http://www.alfredapp.com/)
  * [Recommended Workflows](https://github.com/zenorocha/alfred-workflows)
* [Dash](http://kapeli.com/dash) - Search multiple programming documentation offline and online.
* [Transmit](https://panic.com/transmit/) - File Transfer app.
* [Sketch](http://www.bohemiancoding.com/sketch/) - Vector Graphics app.
* [ImageOptim](http://imageoptim.com/) - Desktop app to optimize images.
* [Divvy](https://mizage.com/divvy/) or [SizeUp](https://www.irradiatedsoftware.com/sizeup/) (includes an unlimited Free Trial).

## Team Collaboration
* [Basecamp](https://basecamp.com/) - Project management. (:money_with_wings:)
* [Github](https://github.com) - Code hosting. (:money_with_wings:, Free)
* [Slack](https://slack.com/) - Group chat.
* [RedPen](https://redpen.io/) - Review designs with your team.
* [Zeplin](https://zeplin.io/) - Upload .sketch files and generate easy to work styleguides for developers.
* [Trello](https://trello.com/) - Virtual white board. Organize anything with your team.
* [Meldium](https://www.meldium.com/) - Team Password manager.

## Design
* [Invision App](http://www.invisionapp.com/) - Wireframe and prototype app.
* [Subtle Patterns](http://subtlepatterns.com/) - Background patterns for your website.
* [Meet the Ipsums](http://meettheipsums.com/) - Many flavors of the Lorem Ipsum text filler.
* [Color Template](http://rocket-design.fr/color-template/) - Guide into using colors on your design.
* [Photoshop Etiquette](http://photoshopetiquette.com/) - A Guide to Discernible Web Design in Photoshop.

### Fonts
* [Fontello](http://fontello.com/) (:money_with_wings:)
* [TypeKit](http://typekit.com) (:money_with_wings:)
* [Fontdeck](http://fontdeck.com) (:money_with_wings:)

### Stock Images
* [Gratisography](http://www.gratisography.com/)
* [xstockvideo](http://www.xstockvideo.com/)
* [Icono](http://saeedalipoor.github.io/icono/) - Pure CSS icons

## Workspace
* [NodeJS](http://nodejs.org) - Most of the tools listed are installed using NPM (included with Node).
  * [NVM](https://github.com/creationix/nvm)
* [Yeoman](http://yeoman.io/index.html) - Yeoman defines an opinionated stack for web application development. The Yeoman packages provide a good and sometimes comprehensive starting point using different available libraries.
  * Installation: `npm install -g yo`
* [Bower](http://bower.io/) - Bower is a package manager for the web.
  * Installation: `npm install -g bower`
  * [Bower Component Search](http://bower.io/search/)
* [Grunt](http://gruntjs.com/) - Grunt is a Task Runner. You can run various scripts onto your project folder and performs tasks like compile sass files, minify js or save files to a build folder.
  * Installation: `npm install -g grunt-cli`
* [Gulp](http://gulpjs.com/) - Another Task Runner. API is minimal but functional, it's more straight-forward than Grunt but less plugins available. The community is steadily growing.
  * [Gulp Plugins](http://gulpjs.com/plugins/)
  * [Gulp Starter](https://github.com/3bola/gulp-starter)
* [Devtools Cheatsheet](http://anti-code.com/devtools-cheatsheet/)
* [Book of Front-End tooling](https://github.com/tooling/book-of-modern-frontend-tooling)

### Command Line Tools

## Development
### Reference
* [Devdocs.io](http://devdocs.io)
* [MDN: Mozilla Developer Network](https://developer.mozilla.org/en-US/)
* [Can I Use?](http://caniuse.com/)
* [simpl.info](http://www.simpl.info/) - Simplest possible examples of HTML, CSS and JavaScript.
* [WebPlatform](http://www.webplatform.org/)
* [The HTML 5 JavaScript API Index](http://html5index.org/)

#### Responsive Web Design
* [Mailchimp UX Patterns](https://ux.mailchimp.com/patterns/)

### Best Practices
* [@mdo Code Guideline](http://mdo.github.io/code-guide/)
* [SEO for Web Apps](http://www.impressivewebs.com/seo-for-web-apps/)
* [Google's Web Fundamentals](https://developers.google.com/web/fundamentals/) - Best practices for modern web development

### Performance
* [Perf Tools Today](http://perf-tooling.today/)
* [Awesome WPO](https://github.com/davidsonfellipe/awesome-wpo)

### Front-End Frameworks
* [Foundation](http://foundation.zurb.com)
* [Foundation for Apps](http://foundation.zurb.com/apps/)
* [Bootstrap](http://getbootstrap.com/)
* [Assemble.io](http://assemble.io/)
* [HTML5 Boilerplate](http://html5boilerplate.com)
* [Hackathon Starter](https://github.com/sahat/hackathon-starter)

### Checklists and General Guidelines
* [Web Dev Checklist](http://webdevchecklist.com/)

### Tools
#### Documentation of Projects
* [Daux](http://daux.io/)
* [StyleDocco](http://jacobrask.github.io/styledocco/)
* [Pattern Lab](http://www.pattern-lab.info/) - Generate atomic design patterns

### HTML

### Styles
* [Pure CSS](http://purecss.io/)
* [Grid](http://www.adamkaplan.me/grid/)
* [Sass Guidelines](http://sass-guidelin.es/)
* [Sass](http://sass-lang.com/) - Sass language reference
* [Sache](http://www.sache.in/) - Discover Sass & Compass Extensions
* <http://www.justinaguilar.com/animations/index.html>
* <http://www.createcss3.com/>
* <http://usablica.github.io/front-end-frameworks/compare.html?v=2.0>
* <http://yostudios.github.io/Spritemapper/>

### SVG
* [Awesome SVG](https://github.com/willianjusten/awesome-svg)
* [Snap SVG](http://snapsvg.io/)
* [SVG Icons](http://svgicons.sparkk.fr/)
* [SVG Morpheus](http://alexk111.github.io/SVG-Morpheus/)
* [Walkway](https://github.com/ConnorAtherton/walkway)
* [SVG Loaders](http://samherbert.net/svg-loaders/)

### JavaScript
#### Reference
* [Superhero JS](http://superherojs.com/) - Quality articles related to JavaScript.
* [You Might Not Need jQuery](http://youmightnotneedjquery.com/)
* [JavaScript Patterns](http://shichuan.github.io/javascript-patterns/)
* [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/)
* [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-browser-Polyfills)

#### ES6

#### Libraries
* [ToDoMVC](http://todomvc.com/) - Explore the various MV-* libraries available.
* [React](http://facebook.github.io/react/) - JavaScript Library for building user interfaces.
  * [awesome react](https://github.com/enaqx/awesome-react)
  * [Flux Architecture](https://github.com/facebook/flux)

#### Listings & Online Tools
* [Unheap](http://www.unheap.com/) - A nice looking collection of jQuery plugins categorized by type.
* [CDNJS](https://cdnjs.com/)
* [JSDB.io](http://jsdb.io) - Source of JavaScript libraries, frameworks and plugins.
* [Regex 101](http://regex101.com/)
* [Regexr](http://regexr.com/)

#### Tools and Libraries
* [fast.js](https://github.com/codemix/fast.js) - a collection of micro-optimizations that can help you write faster JavaScript code as it includes fast replacements for several built-in native methods.
* [Velocity](http://julian.com/research/velocity/) - Velocity is a jQuery plugin that re-implements $.animate() to produce significantly greater performance
* [InstantClick](http://instantclick.io/) - JavaScript library that dramatically speeds up your website, making navigation effectively instant in most cases.
* [Moment.js](http://momentjs.com/)
* [pageres](https://github.com/sindresorhus/pageres) - Screenshot automation.

#### Web Components
* [WebComponents](http://webcomponents.org/)
* [Custom Elements](http://customelements.io/)

### Accessibility
* [a11y project](http://a11yproject.com/)
* [tota11y](http://khan.github.io/tota11y/)

### Browser Extensions
* [Web Developer Tools](http://chrispederick.com/work/web-developer/)
* [Backtick](https://chrome.google.com/webstore/detail/backtick/daiejhinmmfgincamkeeobmpffhdljim)
* [FontFace Ninja](http://www.fontface.ninja/)
* [Postman](https://chrome.google.com/webstore/detail/postman-rest-client-packa/fhbjgbiflinjbdggehcddcbncdddomop)
* [JunkFill](https://chrome.google.com/webstore/detail/junkfill/cajejbcjfkhgmfbapmhopccephhjedeb)
* [Responsive Inspector](https://chrome.google.com/webstore/detail/responsive-inspector/memcdolmmnmnleeiodllgpibdjlkbpim)
* [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh)

### Bookmarklets
* [Backtick](http://backtick.io/) - Console for bookmarklets and scripts. (Chrome only)
* [Webfonter](http://webfonter.fontshop.com/) - Find the fonts being used on a page and it lists similar fonts.
* [Viewport Resizer](http://lab.maltewassermann.com/viewport-resizer/)

### Cross Browser Testing
* [Browserstack](http://www.browserstack.com)
* [Bugsnag](https://bugsnag.com/)

### Deployment
* [Electron](https://github.com/atom/electron) - Build cross platform desktop apps with web technologies. (Slack is deployed using Electron)

## Keeping Up To Date
### Listings
* [Panda App](https://usepanda.com/app/#/)
* [Web Platform Daily](http://webplatformdaily.org/)
* [HTML5 Bookmarks](http://www.html5bookmarks.com/)
* [Site Inspire](http://www.siteinspire.com/)
* [CodePen](http://codepen.io)
* [EchoJS](http://www.echojs.com/) - JavaScript News
* [LayerVault News](https://news.layervault.com/)

### Podcasts
* [Shop Talk Show](http://shoptalkshow.com/)
* [JavaScript Jabber](http://devchat.tv/js-jabber/)
* [Adventures in Angular](http://devchat.tv/adventures-in-angular)
* [The Web Ahead](http://5by5.tv/webahead)
* [The Intellectual Radio Program](http://goodstuff.fm/tirp)

### Newsletters
* [Web Design Weekly](http://web-design-weekly.com/)
* [Sidebar.io](http://sidebar.io/)
* [JavaScript Weekly](http://javascriptweekly.com/)
* [HTML5 Weekly](http://html5weekly.com/)
* [Web Tools Weekly](http://webtoolsweekly.com/)

### Blogs
* [Front-End Feeds](https://github.com/impressivewebs/frontend-feeds) - An awesome collection of RSS feeds for front-end developers.
* [Web Platform Daily](http://webplatformdaily.org/) - A must daily visit. Updated daily with the latest news on web technologies.
* [CSS Tricks](http://css-tricks.com)
* [A List Apart](http://alistapart.com)
* [Smashing Magazine](http://smashingmagazine.com)
* [Codrops](http://tympanus.net/codrops/)

### Further Education
* [An Advance Guide to HTML & CSS](http://learn.shayhowe.com/advanced-html-css/)
* [Teaching Materials](http://www.teaching-materials.org/) - This site hosts a variety of CC-licensed web development curriculum
* [BentoBox](http://www.bentobox.io/)

### Paid Services
* [egghead.io](https://egghead.io) (:money_with_wings:)
* [PluralSight](https://pluralsight.com) (:money_with_wings:)
* [CodeSchool](https://codeschool.com) (:money_with_wings:)

## Other Comprehensive Lists
* [awesome lists](https://github.com/sindresorhus/awesome)
* <https://github.com/dypsilon/frontend-dev-bookmarks>
* <https://github.com/codylindley/frontend-tools>
* <https://github.com/bebraw/jswiki/wiki>
* <https://github.com/cjbarber/ToolsOfTheTrade>
* [Oozled](http://oozled.com/)
