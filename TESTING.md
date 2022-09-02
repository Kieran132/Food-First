##Testing

####W3C Validator
This tested the HTML5 coding within the website - passed
<img src="assets/readme.md-images/Html pass.png">

####(Jigsaw) Validator
This tested the css styling within the website - passed
<img src="assets/readme.md-images/passed css.png">

####Lighthouse Testing
This tests 4 areas, performance, accessibility, best practices and SEO to determine overall performance score
<img src="assets/readme.md-images/lighthouse.png">


##Bugs

- When inserting images into the website, any images that saved as .png or .webp did not show on the deployed website
Resolution - To resolve this issue I converted the images into .jpeg

- Images didnt show on page deployment
Resolution - I removed the / from the start of the file path

- @media only screen min-width 1200px moved everything out of alignment.
Resolution - Change the min-width to max-width and this resolved the issue

- Testing performace was 41%
Resolution - I compressed all the image files on the website which resulted in a quicker page load

- Two errors were found on initial CSS validator on row 232/233 due to no negative values are allowed
Resolution - I removed the negative values and styled accordingly