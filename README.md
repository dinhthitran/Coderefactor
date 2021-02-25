# Coderefactor - Homework 

# Horiseon Solution Services

## Refacator of the Horiseon web page to follow accessibility standards and optimize for search engines.

## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## changes made in HTML

## Overall
```
- removed / from self closing tags
- switched order of title and link
- reorganised indentation for the document
- descriptive title added
- changed div tags and used header, nav, section, footer, aside and main for semantics
- added hero image to HTML and removed from CSS to speed up loading time (Image properties in CSS need to accomodate change.)
- all images have alt tags for accessibility for image load fails.
- comments added in both HTML,CSS to show understanding of content structure and use of selectors & elements with order of precedence.
- organisation off CSS for structure and readability.
- consolidation of repetitive CSS/HTML and made selectors more specific
- all links working
```

#### Custom Asthetic changes
```
- Softened the background color of benefits section.
- main contents width and benefits paddings increased slightly for a cleaner finish.
```

## Mock-up
The following image shos the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

