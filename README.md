# Challenge One: Refactor Starter Code for Horiseon

## For this challenge, I worked to refactor the started code for the Horiseon website. I refractored the code to make it more accessible for users and to optimize the site on search engines. I made many changes to improve upon the starter code. My main motivation was to make the site easier for users with accessibility needs, but my other goal was to meet the needs of the Horiseon marketing agency, which was to optimize the site for search engines. By cleaning up the starter code, adding in semantinc HTML elements, adding alt attributes to image elements, adding a better title, and condesing some of the repeated code, I was able to accomplish both my goals. 

### This link will take you to the refactored site: 

PUT LINK HERE

### These three images show the final site. Although it looks the same as the starter code, the functionality has changed. 

#### ![alt text] (assets/images/ScreenShot_1.pgn)
#### ![alt text] (assets/images/ScreenShot_2.pgn)
#### ![alt text] (assets/images/ScreenShot_3.pgn)


## Installation
### Here is a list of the steps I took to install this project. The steps are also reflected in my frequnt commits and pushes to GitHub. 
#### I updated <title> in header to reflect the website name (Horiseon) and, for clarity, moved the <title> section above the link to the CSS style sheet. 
#### As I worked, I added notes throughout the HTML (<!— —>) and CSS style sheet (/* */).
#### As I worked, I added spacing and indents to make the HTML and CSS sheets clearer to read.
#### I removed the class=“header” from the first <div> and renamed the <div> to <header> to ensure semantic HTML was used. I updated the CSS to reflect this change (removed the “.” before header).
#### I renamed the navigation <div> to <nav> to ensure semantic HTML was used. I updated the CSS to reflect this change (changed “div” to “nav” where applicable).
#### I renamed the content and benefits sections from <div> to <section> to ensure semantic HTML was used.
#### To ensure semantic HTML was used, I renamed the footer from <div> to <footer> and removed the class “footer" and updated the CSS to reflect this change. 
#### I added “alt” text for the images in the content section (wrote out full descriptions of images because they were detailed photographs). I added “alt” of “” for images in the benefits section (used “” because the images were small graphics instead of photographs or detailed images). 
#### I cleaned up the code for the image under Cost Management in the benefits section by removing the unnecessary “img” from the closing code (the code at first read <img src=“./assets/images/cost-management.png”> </img> and I updated it to read <img src=“./assets/images/cost-management.png” alt=“” />). 
#### I reorganized the order of the CSS style sheet so it was more logical by moving all of the classes from the content section under the same section. 
#### I added the id “search-engine-optimization” under the first div in the content section to ensure when the “Search Engine Optimization” link in the top navigation is clicked, it takes the user to the Search Engine Optimization section of the site. 
#### In the content section, I changed the <div>'s to <articles> to ensure semantic HTML was used. 
#### Since many of the styles in the CSS style sheet for the content section are overlapping, I changed the articles in the content section to all have the same class, which I called “information” (removed the classes that were assigned before—“search-engine-optimization”, “online-reputation-management”, and “social-media-marketing”). This allowed me to remove the repeated styles in the CSS Style sheet for these articles (margin-bottom: 20px; padding 50px; height: 300px; font-family: ‘Gill Sans’, ‘Gill Sans MT’, Calibri, ‘Trebuchet MS’, sans-serif; background-color: #0072bb; color: #ffffff;) and just list them one time under one class (“.information”). This also allowed me to remove the repeated styles in the CSS style sheet for the images in these articles (max-height: 200px) and list them all under “.information img” rather than three separate lists. This also allowed me to list all of the repeated styles in the CSS style sheet for the <h2>s in these articles (margin-bottom: 20px; font-size: 36px;) and list them once under “.information h2” rather than three separate times. 
#### After updating the articles (<article>) in the connect section to all have the same class, they no longer needs id’s. I deleted their id’s in the HTML file (removed id=“search-engine-optimization”, id=“online-reputation-management”, and id=“social-media-marketing”). 
#### Since many of the styles in the CSS style sheet for the benefit section are overlapping, I changed the articles in the benefit section to all have the same class, which I called “benefit-details” (removed the classes that were assigned before—“benefit-lead”, “benefit-brand”, and “benefit-cost”). This allowed me to remove the repeated styles in the CSS Style sheet for these articles (margin-bottom: 32px; and color: #ffffff;) and just list them one time under one class (“.benefit-details”). This also allowed me to list all of the repeated styles in the CSS style sheet for the <h3>s in these articles (margin-bottom: 10px; text-align: center;) and list them once under “.benefit-details h3” rather than three separate times. This also allowed me to remove the repeated styles in the CSS style sheet for the images in these articles (display: block; margin: 10px auto; and max-width: 150px;) and list them all under “.benfit-details img” rather than three separate lists.
#### I found that after assigning the class of “information” to all three articles in the content section, the navigation links were now broken. To fix this, I added separate id’s to each article. The id’s I added matched the href information from the <nav> in the header (“search-engine-optimization”, “online-reputation-management”, and “social-media-marketing”. 


## Usage
### This refactored code now works in a more accessible way. For example, the added alt attributes for images will allow screen readers to describe the images. Additonally, the semantic HTML elements will also improve the site's funcionality with screen readers. Also, the refactored code will now be optimized for serach engines because search engines increase traffic flow to site with improved accessibility features. 

## Credits
### The starter code for this site was provided by Horiseon's marking agency. The modifations I made to it were as a result of information in the BootCamp Spot modules and information learned in BootCamp classes. I also referred to W3 School to better understand HTML semantic Elements (https://www.w3schools.com/html/html5_semantic_elements.asp). 

## License 