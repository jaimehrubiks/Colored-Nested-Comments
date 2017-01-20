## COLORED NESTED COMMENTS
CNC is a browser extension which aims to help users quickly identify the level of a nested comments' hierarchy. Color and bars are used to highlight the firt four levels of nesting in comments for some popular websites.

# Download and Install
+ You can download from chrome store: https://chrome.google.com/webstore/detail/hnaejhopebcgfgocefdcjejnfoedffgh
+ You can download from firefox addons: https://addons.mozilla.org/es/firefox/addon/colored-nested-comments
+ You can also download zip from github and install as a developer extension

# Supported Sites
- *.reddit.com 
- *.news.ycombinator.com
- *.meneame.net

# Supported Browsers
- Google Chrome
- Chromium Browser 
- Firefox

# Suggestions
You may want to suggest a new website using my email or a GitHub issue.

## Pull Request guidelines
PR are welcome but must follow some basic rules.

# Basic rules
1. CSS only should be used (No jS)
2. One style sheet for each domain. 

# Styling rules
+ Root element should be left untouched.
+ First level comments must be styled with -> border-left: 2px solid orangered;
+ Second level comments must be styled with -> border-left: 2px dotted orangered;
+ Third level comments must be styled with -> border-left: 1px solid #596774;
+ Fourth level comments must be styled with -> border-left: 1px solid #596774;
+ Further levels should be left untouched.

+ Different colors (in couple) might be used if they are more suited to the website color scheme. Orange is preferred in case no other similar color is available in the website scheme. If color scheme is red/orange-ish, that color should be used instead (as primary).
+ Proper padding might be used to help both correct border alignment and next-level alignment.

# Further discussion
Use GitHub issues whenever you need.
