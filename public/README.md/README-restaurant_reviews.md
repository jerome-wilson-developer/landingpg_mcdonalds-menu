# Mobile Web Specialist Certification Course
The link to view this app: https://drjwebsitedesign.github.io/mws-restaurant-stage-1/
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

## Resources used to complete the restaurant review rubric
Thank you and Shout-outs for inspiration, motivation, and information for their walkththroughs:
* alexandro perez, * muhammed riaad, * matthew cranford, * doug brown, * codingPhase, * traversyMedia, * develophp.com, * w3schools, * netNinja, and others.

## Technologies used for this restaurant project
* html5 semantics, css3, flexbox, @media query, javascript, python3.7(64-bit), xammp control panelv3.2.2 (apache/mysql), console panel/audit, wave web accessibility tool, colorpick eyedropper, gulp, parcel.js, etc.

## Modifications made to index.html, restaurant.html, css, main.js, restaurant.json.
Below are the some of the changes made to pass the project's rubric requirements for 1)Responsive Web Design, 2)Accessibility, and 3)Service worker cache.

### Responsive Web Design
* Declared <lang="en"> to improve accessibility.
* improved responsive web design by adding <name="viewport" content="width=device-width, initial-scale=1"> and <http-equiv="X-UA-Compatible" content="IE=edge">.
* i divided the css3 styles into 3 different screen viewport sizes: smartphone, tablet, and desktop.
* the footer is divided into to 3 different css3 selectors to improve responsive web design and user accessibility.
* i used css3 properties such as flexbox, order stacking, nth-child, etc to make fluid and control the flow of content and the container-boxes.

### Accessibility
* added class="breadcrumbNav" as the navigation link inside the smartphone @media query design on restaurant.html. that helps reduce extra clicks, redundancy, and real estate used. it was modified with styles.css(display:none;). however, i did return the original 'nav h1' to the tablet and desktop screens.
* added 'create:img.alt' attribute "Picture of ${restaurant.name}" to give each image a 'text description' in case the image does not render (for whatever reasons).
* added aria-label and aria-role to improve accessibility for users with disabilities that use screen readers. also added tabIndex to aid flow control.
* restarants.json - increased font-size for better readability. also truncated content that does not fit without using extra lines so as to maintain consistency with restaurant location data.
* changed 'View Details' to 'Restaurant Details' to add specificity to the content in main.js
* increased focus for all 'li-link-pseudo:buttons by changing background hover colours, borders, and font styles/sizes. 

### Addition of Service Worker cache
You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. 


## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write. 
