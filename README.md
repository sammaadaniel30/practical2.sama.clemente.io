# practical2.sama.clemente.io

This README.md files is the DDD(Design Detailed Document) for the project of creating a website.

**DESCRIPTION OF MY WORK:**

This project consists in developing a website, to document and record everthing that has I have learned in the subjects of the degree which I am currently coursing. (Computer Science)

To make this posible, my website will include the following sections:

A main section, showing information about the website

A conctact section, including a contact form

A net section, showing information about the websites of my partners and also their links.

An about me section, showing a small introduction about myself, including 2 images, a CV and some links to Social Media.

A course section, showing the academic program with the different subjects grouped by courses. Including a detail subsection including the subject of Fundamentals of Computer Science.

A CSS folder, storing all css files.

A public folder, will store all of the individual section's .html files

An Images folder, will store all of the images used in the development of this project.

**PROBLEMS DURING THE DEVELOPMENT**

Problem 1: During the development of the home page (index.html) I faced a problem which consisted in applying the CSS and images on to the HTML file which were in another folder. At the beggining I thougnt that this was a problem with the GitHub repository and this made me deleted and create another repositoy and start everything from the top. At the end I concluded that it was a simple issue that only took 10 seconds to finally fix it. 

Problem 2: During the development of the Contact Page and the Degree Page it was quite difficult to add the correct styles to each of the classes for example the list of the contact form so it could when it was visualised in the website it was clear and friendly to users to read and see the content. 

Problem 3: During the development of the Net page, small problem occured on the font of the menu where the links to the other websites are located. This was a bit weird since the same CSS style and code was used over and over again of the previous sections and the font did not change at any point. But on the Net Page it changed to another font using the same CSS code, so I investigated to find what was the original font used in the other pages. The result was that the font used was called "Poppins", so I decided to manually fix the problem by adding "font-family: Poppins;" in the appropiate part of the code and the issue was solved. This also happened for the copyright section of the page, at the end this code was used in the CSS file "font-family: Montserrat;". For the future I will use this fragments to avoid any problems further on.

Problem 4: I had not paid attention correctly and some miscommunication made me make a different CSS file for each individual webpage, this means that there was, for example, a CSS file for the Fundamentals Page and another different CSS file for the Degree page. The simple solution was to copy and paste all of the CSS files and add the prefix of the page there were going to be applied to, for example, the part of the CSS that was going to be applied to the Net page would be ".net .nameofclass". For the HTML a whole style with the name of the prefix in the CSS code was going to be applied in the whole of the body, taking the Net Page as an example;
"<body class="net">". This was all done with the same application for all of the webpages. Later, it was tested and it worked at the first time.

Problem 5: When the repository was sent to GitHub, there was a problem where all of the links were not working and it seems weird as in the local machine all of the pages worked perfectly. At the end the problem was that an absolute path was created by accident and it was not correcly added and GitHub couldn't read it correctly. So the link was fixed and then it worked on GitHub. 

**TIMELINE OF DEVELOPMENT**

**27/11/2023**

The repository in GitHub was created

The README.md file was edited. Containing the basic description of the project and the layout.

Created folder for images, css files and html files for each section

Created websites for all sections, and also included the main page structure of HTML.

Created styles.css file.

Added profile.JPG into Images folder.

**01/12/2023**

Added the background image for the main page

Added the profile image for the about me page

Added the background image for the contact me page

Added image for topic page

Added image for fundamentals page

Added image for degree page

**02/12/2023**

Added the CSS file for the home page named as styles_home.css

Identified and issue involving the CSS files and Images (more info see Problem 1 in PROBLEMS DURING DEVELOPMENT section) 

**03/12/22**

Modified the home page to leave it as in a BETA

Modified and probably finished all of the neccessary styles in the CSS file for the home page

**04/12/22**

Added a footer in the home page and also added its classes into the CSS file for the home page

Added logo.jpg into the repository, will be used in the footer of all the websites

Completed the HTML code for the home page (index.html)

Completed the CSS file for the home page

**06/12/2023** 

Moved the index.html out of the sections folder

Added the docs folder with all its propierties including the subfolders

Finished the page of Degree 

Finished its CSS style (Degree Page)

Fixed some minor errors in the HTML of the Home Page

Fixed some minor erros in the CSS file of the Home Page

Finished the page of Contact Me

Finished the CSS file for the Contact Me page 

Addressed Problem 2.

**07/12/2023**

Uploaded a new image for the background of the Net Page. The other one has been removed as it had the same name to avoid any future to problems it was deleted from the repository. 

Finished the CSS file for the Net Page (ONLY NEEDING TO POST PARTNERS' LINKS TO WEBSITES)

Finished the HTML for the Net Page 

Addressed Problem 3

Uploaded a new image to use for the background of the Topic Page

Uploaded to a new created folder called topicfiles, both documents used for the first practical in the subject of fundamentals

Finished the CSS file for the Topic Page

Finshed the HTML for the Topic Page

**08/12/2023**

Finished the CSS file for the Fundamentals Page 

Finished the HTML code for the Fundamentals Page

Finished the CSS file for the About Me Page

Finished the HTML code for the About Me Page

**09/12/2023**

Updated by fixing minor errors in the different webpages and also CSS. CSS has been modified so that it is easier to read. 

Uploaded 2nd picture to be used in the About Me page. 

To this point all of the websites have been completed. The only thing missing are the website links to the webpages of my parts, however their the links from my website in the Net Page has already been created the only thing missing are the specific links to their websites. 

**10/12/2023**

In the links of the footer, links have been updated so that two links now redirect to the README.md file and the LICENSE file.

**11/12/2023**

Uploaded a new CSS file with all of webpages CSS all combined (see Problem 4)

Removed other CSS files with individual relation to only 1 webpage (see Problem 4)

Fixed some gramatical errors in all of the webpages

Addressed and solved Problem 4

**13/12/2023**

Added clarity for the HTML code in all of the individual sections, no visual change was done on the output of the HTML. 

**14/12/2023** 

Added a new image in the Topic Page. 

Adressed Problem 5. 

**CONCLUSIONS**