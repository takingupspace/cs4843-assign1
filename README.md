# CS4843 Assignment 1

In our first Cloud Computing assignment, we will utilize Amazon Web Service's Simple Storage Service (S3) to create a static web page. Furthermore, we will employ AWS' Cloud Front as a means to access our website

# Link to Website

* [Website](https://dh7olf4xhjnat.cloudfront.net/) - Cloud Front link to my website

## Infrastructure Utilized

As mentioned above, we utilized Amazon's Simple Storage Service, because of it's free-tier usage and overall low-cost for production/commerical usage. S3 serves as the back-bone for many front-facing websites not only for its cost efficiency, but its durability of 99.999999999% of objects across multiple Availability Zones. We used AWS' Cloud Front to cache the web-page and it's objects at Amazon's Points of Presence, which are distributed globally. This content delivery network can help to deliver frequently requested web-pages/objects to be delivered at an expedited rate to customers in different geographic regions.

## Security

I utilized AWS' IAM (Identity Access Management) to restrict all direct access to the s3 bucket. This means that the only way to navigate to the contents within this bucket is to use the Cloud Front link provided above. Furthermore, the bucket's IAM policy explicitly allows Cloud Front to access any objects in the specified bucket by using the ARN (Amazon Resource Name) of the Cloud Front distribution.

## Error Handling

If a page that is requested results in a 404 (Page Not found), the user is routed to a custom error page stating this result. I implemented this functionality by adding a custom error page under the Cloud Front distribution panel within the AWS Console.

## Built With

* [HTML](https://docs.microsoft.com/en-us/cpp/mfc/html-basics?view=msvc-170) - Web element creation
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling of web-page elements
* [JQuery](https://www.google.com/search?client=firefox-b-1-d&q=JQuery+Docs) - for manipulating the DOM (Document Object Model)
* [JavaScript](https://devdocs.io/javascript/) - for handling onClick methods


### Elaboration of Technologies Used

```
HTML (Hypertext Markup Language) was used to create elements to append to the Document Object Model (DOM)
and to create the visual aspects of the web-page
```
```
CSS (Cascading Style Sheets) was used to style the HTML elements that we created.
I used a combination of in-line CSS, as well as including styling to tags and specific
classes in the head tag. Including the styling in the head tag
allows styling to be applied to the entire file
```
```
JQuery was imported through a CDN (content delivery network) in the head tag, so that
it could be utilized throughout the entire document. I used JQuery to be able to figure out
which button was clicked.
```
```
Vanilla JavaScript was utilized to handle the onClick events of the buttons mentioned above.
We can use javascript within a HTML file by enclosing it within a <script></script> tag.
```

## Author

* **Travis Sauer**
