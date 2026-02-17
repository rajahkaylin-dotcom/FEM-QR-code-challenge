# My experience with the QR code project

## Day 1 - 17/02/2026

- The project got off to a good start, the boilerplate was done quickly (I'm doing everything from scratch on every project instead of copy pasting boiler plate in order to maximize my learning).
- created a header, main and footer section and nested a div within a div within the main section, leaving the header and footer blank for future edits or additions.
- Started styling the body background in CSS as well as the outer div container, but hit a roadblock while trying to figure out how to properly center the div.
- Started learning flexbox in order to meet the previously mentioned challenge, but cannot seem to get the CSS to work properly, using html and css validators to look for broken code.
- Taking a small break to figure out flexbox then returning.

### Afternoon session

- Had a small mishap, tried pushing new code to github, met with an error because somehow I cloned the repo in a directory within the directory I was working in.
- Tried for a while to fix it, ended up deleting github repo and creating a new directory with saved changes from my local directory, the changes on this readme file made it through, as well as my upddated css document, but my html file suffered from irreversable damage, so I had to start just the HTML bit from scratch.
- Still having some trouble centering the div elements like in the picture, even while using flexbox, so I used three divs nested within each other to try and use flexbox on both child divs, getting close, so I decided to use margin and padding to try and make up the difference.
- <mark>I just found out</mark> that the `display: flex` property in CSS can be used on almost any parent element, which would act as the flex container, to control the position of any child element.
- It **DOES NOT** only need to be used on divs as both parent and child elements.
