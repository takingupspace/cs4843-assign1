# CS4843 Assignment 1

In our first Cloud Computing assignment, we will utilize Amazon Web Service's Simple Storage Service (S3) to create a static web page. Furthermore, we will employ AWS' Cloud Front as a means to access our website

## Infrastructure Utilized

As mentioned above, we utilized Amazon's Simple Storage Service, because of it's free-tier usage, but overall low-cost for production/commerical usage. S3 serves as the back-bone for many front-facing websites not only for its cost efficiency, but its durability of 99.999999999% of objects across multiple Availability Zones. We used AWS' Cloud Front to cache the web-page and it's objects at Amazon's Points of Presence distributed globally. This content delivery network can help to deliver frequently requested web-pages/objects to be delivered at an expedited rate, to customers in very different geographic regions.

### Technologies

```
HTML (Hypertext Markup Language) was used to create elements to append to the Document Object Model (DOM) and create the visual aspects of the web-page
```
```
CSS (Cascading Style Sheets) was used to style the HTML elements that we created. I used a combination of in-line CSS, as well as including styling to tags and specific classes in the head tag above the body tag. Including the styling in the head tag, allows for document-wide styling to be applied
```
```
JQuery was imported through its CDN (content delivery network) in the head tag, so that it can be utilized throughout the entire document. I used JQuery to be able to figure out which button was clicked so that I could route the user to the appropriate page.
```
```
Vanilla JavaScript was utilized to handle the onClick event of the buttons that route to different pages. We can use javascript within a HTML file by enclosing it within a <script> tag.
```
## Built With

* [HTML](https://docs.microsoft.com/en-us/cpp/mfc/html-basics?view=msvc-170) - Web element creation
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling of web-page and elements
* [JQuery](https://www.google.com/search?client=firefox-b-1-d&q=JQuery+Docs) - for manipulating the DOM (Document Object Model)
* [JavaScript](https://devdocs.io/javascript/) - for handling onClick methods

## Author

* **Travis Sauer**
