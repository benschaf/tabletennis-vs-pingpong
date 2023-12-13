# Testing

Return back to the [README.md](README.md) file.

## Code Validation

### HTML
[![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2F&label=w3c%20-%20index.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Findex.html)
[![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fgallery.html&label=w3c%20-%20gallery.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fgallery.html)
[![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fsubscribed.html&label=w3c%20-%20subscribed.html)](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fsubscribed.html)

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Landing Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Findex.html) | ![screenshot](documentation/images/testing/w3c-index-test.png) | Pass: No Errors |
| Gallery Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fgallery.html) | ![screenshot](documentation/images/testing/w3c-gallery-test.png) | Pass: No Errors |
| Subscribed Page | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2Fsubscribed.html) | ![screenshot](documentation/images/testing/w3c-subscribed-test.png) | Pass: No Errors |

### CSS

[![Jigsaw](http://jigsaw.w3.org/css-validator/images/vcss-blue)](http://jigsaw.w3.org/css-validator/validator?lang=de&profile=css3svg&uri=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong%2F&usermedium=all&vextwarning=true&warning=1
)

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbenschaf.github.io%2Ftabletennis-vs-pingpong) | ![screenshot](documentation/images/testing/jigsaw-style.test.png) | Pass: No Errors |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Gallery | Contact | Notes |
| --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/images/testing/browser-chrome-home.png) | ![screenshot](documentation/images/testing/browser-chrome-gallery.png) | ![screenshot](documentation/images/testing/browser-chrome-subscribed.png) | Works as expected |
| Firefox Developer Edition | ![screenshot](documentation/images/testing/browser-firefox-home.png) | ![screenshot](documentation/images/testing/browser-firefox-gallery.png) | ![screenshot](documentation/images/testing/browser-firefox-subscribed.png) | Works as expected |
| Edge | ![screenshot](documentation/images/testing/browser-edge-home.png) | ![screenshot](documentation/images/testing/browser-edge-gallery.png) | ![screenshot](documentation/images/testing/browser-edge-subscribed.png) | Works as expected |
| Safari | ![screenshot](documentation/images/testing/browser-safari-home.png) | ![screenshot](documentation/images/testing/browser-safari-gallery.png) | ![screenshot](documentation/images/testing/browser-safari-subscribed.png) | Works as expected |

## Responsiveness

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

Use this space to discuss testing the live/deployed site on various device sizes.

The minimum requirement is for the following 3 tests:
- Mobile
- Tablet
- Desktop

**IMPORTANT**: You must provide screenshots of the tested responsiveness, to "prove" that you've actually tested them.

Using the "amiresponsive" mockup image (or similar) does not suffice the requirements.
Consider using some of the built-in device sizes in the Developer Tools.

If you have tested the project on your actual mobile phone or tablet, consider also including screenshots of these as well.
It showcases a higher level of manual tests, and can be seen as a positive inclusion!

Sample responsiveness testing documentation:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Gallery | Subscribed | Notes |
| --- | --- | --- | --- | --- |
| Mobile (DevTools) | ![screenshot](documentation/responsive-mobile-home.png) | ![screenshot](documentation/responsive-mobile-gallery.png) | ![screenshot](documentation/responsive-mobile-subscribed.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/responsive-tablet-home.png) | ![screenshot](documentation/responsive-tablet-gallery.png) | ![screenshot](documentation/responsive-tablet-subscribed.png) |  Works as expected |
| Desktop | ![screenshot](documentation/responsive-desktop-home.png) | ![screenshot](documentation/responsive-desktop-gallery.png) | ![screenshot](documentation/responsive-desktop-subscribed.png) | Works as expected |
| 4K Monitor | ![screenshot](documentation/responsive-4k-home.png) | ![screenshot](documentation/responsive-4k-gallery.png) | ![screenshot](documentation/responsive-4k-subscribed.png) | Noticeable scaling issues |
| Google Pixel 6 | ![screenshot](documentation/responsive-pixel-home.png) | ![screenshot](documentation/responsive-pixel-gallery.png) | ![screenshot](documentation/responsive-pixel-subscribed.png) | Works as expected |

## Lighthouse Audit

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

Use this space to discuss testing the live/deployed site's Lighthouse Audit reports.
Avoid testing the local version (especially if developing in Gitpod), as this can have knock-on effects of performance.

If you don't have Lighthouse in your Developer Tools,
it can be added as an [extension](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk).

Don't just test the home page (unless it's a single-page application).
Make sure to test the Lighthouse Audit results for all of your pages.

**IMPORTANT**: You must provide screenshots of the results, to "prove" that you've actually tested them.

Sample Lighthouse testing documentation:

## my stuff:
I confirmed that the colours and fonts chosen are easy to read and accessible by running it through lighthouse in chrome devtools.
![Lighthouse Report](documentation/images/lighthouse-report.png)


🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse-home-desktop.png) | Some minor warnings |
| About | ![screenshot](documentation/lighthouse-about-mobile.png) | ![screenshot](documentation/lighthouse-about-desktop.png) | Some minor warnings |
| Gallery | ![screenshot](documentation/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse-gallery-desktop.png) | Slow response time due to large images |
| x | x | x | repeat for any other tested pages/sizes |

## User Story Testing

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

Testing user stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **features** should already align with the **user stories**,
so this should as simple as creating a table with the user story, matching with the re-used screenshot
from the respective feature.

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature01.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature02.png) |
| As a new site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature03.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature04.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature05.png) |
| As a returning site user, I would like to ____________, so that I can ____________. | ![screenshot](documentation/feature06.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature07.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature08.png) |
| As a site administrator, I should be able to ____________, so that I can ____________. | ![screenshot](documentation/feature09.png) |
| repeat for all remaining user stories | x |

## Bugs

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

This section is primarily used for JavaScript and Python applications,
but feel free to use this section to document any HTML/CSS bugs you might run into.

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

## Unfixed Bugs

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

🛑🛑🛑🛑🛑 START OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
