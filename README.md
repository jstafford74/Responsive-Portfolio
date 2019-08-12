# Responsive-Portfolio
When you create a website, it's standard practice to code your HTML files before writing any CSS and to write up one HTML file before moving onto the next. Write your HTML semantically, too:

If something is a heading, you use a heading tag.
If something is a list, you use an unordered or ordered list tag.
So on and so forth.



The content for the index.html should be unique to you.

Write a paragraph or two about yourself. Make it fun, show your personality!
The main logo where it says "Your Name" should say your name. This may make the logo section smaller or wider depending on how long your name is—that is fine and expected.
Add, commit, and push your code to GitHub often, especially when you complete a page.



After all of your HTML is written, you can begin styling your pages using the style.css file you created.

Be sure to validate your html.
Consult the specs below these instructions for advice on styling your CSS files.



Push your changes to Github.



Additional Specifcations


Colors Pro-tip: Use the Eye Dropper Chrome extension to find the colors used on web pages.

Teal color (used for headings and backgrounds): #4aaaa5

Regular font color (used for paragraphs and all text besides the headings): #777777

Main header background color: #ffffff

Main header border color: #cccccc

Footer background color: #666666

Main content background color: #ffffff

Main content border color: #dddddd




Fonts:

For heading fonts use font-family: 'Georgia', Times, Times New Roman, serif;.
For all other fonts use 'Arial', 'Helvetica Neue', Helvetica, sans-serif;.



Profile Image Found on index.html:

Use a picture of yourself.
If you don't have a picture, you can grab a placeholder image from LoremPixel. Save the images to your images folder.



Portfolio Images:

Placeholder images can be found at LoremPixel.
Save the images to your images folder.



Background Images:

The background pattern used was found on Subtle Patterns. You can browse through that site and find whichever pattern you like.



Dimensions:

The entire content and the main section content area is 960px wide.

Bonus


Make your pages more sophisticated by adding style to text links, to image links, and to buttons for when a user hovers their cursor over them. A CSS hover tutorial can be found here.


You can use Adobe Kuler to find colors that match the theme (in this case, the primary color is Teal #4aaaa5).


Make a "sticky footer." You will notice the dark grey footer will always rest just below the content. This is fine whenever your site has enough content to push it down past the height of most monitors. But if there isn't much content in the body, the footer could rest in the middle of the page:

Try to code the footer in a way that it will always remain at the bottom of the page, no matter how short the content is. A sticky footer tutorial can be found here.
Give the Footer the following CSS:
border-top: 8px solid #4aaaa5;
Assignment Two Instructions - (No Bootstrap)


Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.


Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the Basic-Portfolio repo.


If you chose the Wireframe exercise for your first homework assignment, talk to a TA, who will provide you with a template for your portfolio.


Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.


Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.


You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.


768px is about the width of a tablet and 640px is about the width of a phone in landscape.




Make the layout match the following screenshots:


index.html: 980px, 768px, 640px


portfolio.html: 980px, 768px, 640px


contact.html: 980px, 768px, 640px




Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.


Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)


Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.


Deploy your new portfolio (now with media queries!) to GitHub Pages.
