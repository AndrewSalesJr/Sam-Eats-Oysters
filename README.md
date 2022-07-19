# Sam-Eats-Oysters.git


### Project Overview

Sam-Eats-Oysters.git is a project in which I defactor the code of the site Horiseon, a digital marketing company.

In this project, my task is to look through the code of the html and css file for the website. I must change the html tags to semantic tags and add alt text to all images used in order to better adhere to accessibility standards. with these changes made I will need to update the css accordingly so that it is able to apply to the correct html elements. I will also organize the html and css files, so they are easier to read for any other person that decides to take a look at the code in the future. Lastly I will attempt to consolodate some of the css code and remove any unnecessary class attributes.


I started off by adding the header and nav tags in place of basic div tags, updating the css selectors from the related div tags to header and nav.

My next step was to consolodate some of the css selectors in order to get rid of the duplicate code that was present in the css file. I changed the class attributes of the sections within the main tag to content-list. I also noticed that the Search Engine Optimization link in the navigation bar was not working and fixed it by ensuring that section had the proper id and the SEO button was linked to that id.

I then began working on changing the remaining div's in the html code to the proper semantic tags, using the main, aside, section, and footer tags. I also added alt text to all images at this point, leaving the alt text blank for the images within the aside section as they are purely decorational images.

Next I changed the class attributes of the sections within the aside tag to benefit-list with the same reasoning as in line 5.

I removed any class attributes that were used only once on unique tags such as the "content" class attribute that was originally present on the div tag that I changed to the main tag.

I further organized the html code so as to make it easier to read in places where it may have been difficult to before. I also reorganized the css code so it followed the same/similar structure to the html's semantic code.

lastly I added comments to CSS for any part which I believe may possibly be confusing to others who would want to continue to work on my code and added a favicon to the page's tab.