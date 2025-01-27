Page
Page number
2
of 2
Assignment 3 – Your Personal Website
1.) Make a copy of the files from the personal2 folder and put them in a new folder called personal3
2.) Use GIMP or PIXLR (or the image editor of your choice) to create a header image for your page that incorporates
your initials or first name. Be creative with colors, etc. Add it to the top of each of your pages. It can become the
entire header of your page, or just a common image on each page.
a. We previously applied a style to all images to make their width 25%. To remove this restriction from your
header image:
i. First, change the img{} style rule to specify only images in the main section using the main >img{}
selector.
ii. Then, create a new style rule using header img{} and set the width to 100%.
3.) If applicable, modify the colors of your pages (background color, text color, etc) so that it matches your new
header image. (Matches doesn’t necessarily mean that it has to be the same colors, but they should go well
together)
4.) HTML
a. Add a background image to the html section of your CSS stylesheet. You can use the search engine of your
choice to search ‘free background images’ if you’re not sure what to use. Be sure to use appropriate
background repeat and background position values to ensure the background covers the entire page.
5.) Body
a. Remove the 25px margin
b. Set the width of the page to 90%
c. Center the page using margin-left and margin-right
6.) Headings
a. For all h1 and h2’s create a text shadow that is gray in color with a 4px offset X and a 6px offset Y, with a
blur value of 5px.
7.) Navigation
a. Change the current format of the nav section to display the links in a 5-column layout using float
i. Remove the ‘ | ‘ from your nav section of your HTML file.
ii. Create an unordered list (ul) and make each link in your navigation a list item.
iii. In your CSS file, comment out the nav{} section you have from the previous assignment. Then
apply the styles below
iv. In the nav ul{} section of your CSS file apply the following:
1. Set the list style to none
2. Set the margin to 0
3. Set the padding to 0
v. In the nav li{} section:
1. Set the display to block
2. Set the width to 20% (because there are 5 items and it should add to 100%. If you had
more than 5 items in your navigation, you’d adjust accordingly)
3. Set the float to left.
vi. In the nav a{} section:
1. Set the display to block
2. Set the background color of you navigation section.
3. Set a line height of 2.8em
4. Set the text decoration to none
5. Center align the text.
vii. In the nav a:hover{} section:
1. Set the background color to the color to something that coordinates with your site.
2. Set the font color to a contrasting color
8.) Image
a. Apply a right float
9.) For the main element:
a. change the current padding, to be 20px all around
b. Add a top margin of 35px;
10.) To ensure that the image does not spill over into the footer section, we need to apply a clear in the footer styles.
In the body > footer section:
a. Apply a clear to both
Validate
Once you have completed these steps make sure that all the links work on each page, and that the HTML validates
successfully for all of your pages. Validate here - https://validator.w3.org/
Validate your CSS file here https://jigsaw.w3.org/css-validator/.
Submission
Upload your personal3 folder to your ksshosting site. Your page should be reachable by visiting:
http://your_uc_username.ksshosting.com/personal3/