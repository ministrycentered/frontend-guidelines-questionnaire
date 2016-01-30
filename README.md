# Frontend Guidelines Questionnaire
A one-page questionnaire to help your team establish effective frontend guidelines, so that you can write consistent & cohesive code together.

## HTML
### HTML Principles
- **Are there markup practices you've seen and liked?**
- **Are there new semantic tags we should be using?**

### HTML Tools
- **HAML, SLIM, eRB for server-side templates default? (Considreing our heavy use of React)**
- **What is the process for converting a file **

---------------

## CSS

### CSS Principles
- **What are some general principles your team should follow when writing CSS?** *(For example, modularity, avoiding long selector strings, etc. See [these](http://cssguidelin.es/) [resources](http://www.yellowshoe.com.au/standards/#css) [for](http://manuals.gravitydept.com/code/css) [inspiration](http://codeguide.co/#css))*

### CSS Methodology
- **Is BEM still working for us?**
- **How are we consistently deviating from BEM?**
- **Are there aspects to BEM that aren't well understood?**
- **Can we make extensions to BEM that won't require a re-write?**

### CSS Frameworks (Interfaces)
- **What is Interfaces consistently missing, in your app?**
- **Where is Interfaces out-of-date (now that we have a new visual language)?**
- **Where is Interfaces too opinionated? What are you consistently having to override?**

### CSS Style
- **What does CSS commenting look like?**

---------------

## JavaScript

### JavaScript Status
- **Which apps are actively using ES2015 syntax?**

### JavaScript tools
- **Do we need to add any modervizr plugins? Currently Interfaces ships with `touchevents`.**
- **Do we need to add any shared third-party plugins to Interfaces?**

### JavaScript Style
- **What does JS commenting look like?**

---------------

## Tooling
- **Are you using any tools to reinforce frontend style** *(such as [Editor Config](http://editorconfig.org/), [eslint](http://eslint.org/), or [linters](https://github.com/CSSLint/csslint))*?

---------------

## Version control
- **Are there git practices/patterns we could adopt as a design team?** *(such as rebasing, squashing, and commit messages)*

-----------

## Support and Optimization
It's important to recognize the difference between ["support" and "optimization"](http://bradfrost.com/blog/mobile/support-vs-optimization/). You should do your best to support as many environments as possible while simultaneously optimizing for the environments that make the most sense for your business and users.

- **What browsers are you *optimizing* for?**
- **What devices are you *optimizing* for?**
- **Are you using a [graded browser support](https://github.com/yui/yui3/wiki/Graded-Browser-Support) system?**
- **Are there specific components that require [more specific grading](https://www.filamentgroup.com/lab/grade-the-components.html)?**

-----------

## Documentation
- **Where does your documentation live**? What are the links to the documentation?
- **Who's responsible for maintaining and governing the documentation**?
- **What happens when the guidelines are updated**?
