Task 6: Develop effective technical documentation for assignment 1 - Create a REAME.md markdown descripting the details of your AWS EC2 infrastructure deployment for hosting your website. Including the link of your website.  Note: The technical discussion and documentation, rather than just the basic infrastructure buildout or software development, is where the most value occurs whether handing in homework assignments or completing a commercial project.

# CS4843 Assignment 1

In our first Cloud Computing assignment, we will utilize Amazon Web Service's Simple Storage Service (S3) to create a static web page. Furthermore, we will employ AWS' Cloud Front as a means to access our website

## Infrastructure Utilized

As mentioned above, we utilized Amazon's Simple Storage Service, because of it's free-tier usage, but overall low-cost for production/commerical usage. S3 serves as the back-bone for many front-facing websites not only for its cost efficiency, but its durability of 99.999999999% of objects across multiple Availability Zones. We used AWS' Cloud Front to cache the web-page and it's objects at Amazon's Points of Presence distributed globally. This content delivery network can help to deliver frequently requested web-pages/objects to be delivered at an expedited rate, to customers in very different geographic regions.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```
## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [HTML](https://docs.microsoft.com/en-us/cpp/mfc/html-basics?view=msvc-170) - Web element creation
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling of web-page and elements
* [JQuery](https://www.google.com/search?client=firefox-b-1-d&q=JQuery+Docs) - for manipulating the DOM (Document Object Model)
* [JavaScript](https://devdocs.io/javascript/) - for handling onClick methods

## Author

* **Travis Sauer**

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
