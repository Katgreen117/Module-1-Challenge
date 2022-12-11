# Module 1 Challenge

## Description

This is an update of my repo which explains how i refactored code to make our site more visable on google.

## The Aim
To refactor code to make the website fully functional and the code as short as possible and without repetition and to push the changes made into a created respoitory on GitHub.

## How was this accomplished

1. Github repository was created and cloned to my computer using GITBASH
2. Changes to Code using VS CODE
* Span class was removed from the code as this was effecting part of the text of the website title -Hori"seon". Visually this looked off as the title text contained two different text styles.
* Div tags were removed and replaced by nav tags, although both function the same, a DIV tag is a html tag whilst a NAV tag is part of the new HTML5 semantic tags. (semantic tags are tags that specifiy what elements are contained so a NAV tag would contain navigation elements , Div tags are without specific meaning - they just define a devision of section )
* classes (.) where removed from the style sheets to reflect the changes made to the html. As the div tags where removed their (classes(.) are no longer required on the style sheets for that portion of the code amended. on the other hand clases are used to consolidate and style things with repetition so the code can be reduced- such as images with the same attributes. 
* Div tags were also replaced with < Main > and < section > this enabled repetative code to be removed and thus shortening the code and simplifying it further.
* Alt attributes where also included , this attribute provides information or brings up functions such as notepad (if set) which basically gives other information for that image if it cant be viewed. The code contains two alt attributes, one brings up a notepad where a usercan report the issue, the other brings up the image description of the broken image.


## Challenges Faced
* The Github respoitory was created but i made some errors with the files i put in the folder to begin with so i learnt how to delete the intial repository and then recreate it and start again.
2. When i refactored the code i had an issue with the side block images apearing at the bottom , this was due to a missing angle bracket (>) in the code. (The slightest errors such as a missing . or bracket can reak havok)

## Add ons used
1. Markdown Preview Enhancer
2. Open in browser

# Deployed result:
https://katgreen117.github.io/Module-1-Challenge/



## Methods of installation and use:

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## Installation

Programs Required

* Git Hub account
* VS Code
* Git Bash

## Usage 

* Git hub account for cloning and hosting
1. Create repository and clone to desktop using SSH key and gitbash (as seen below)
![alt text](assets/images/github-cloning.png)
(SSH needs to be cloned to create the repository on the dektop)
2. Use VS Code to edit and style code and update the read me 


## Credits

* stack overflow markdowns (https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github)
* 



## License

The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)


---

🏆 The sections listed above are the minimum for a good README, but your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, consider adding a heading called "Features" and listing them there.

## Contributing

If you created an application or package and would like other developers to contribute it, you will want to add guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them.

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.



[def]: #theaim
[def2]: #theaim
[def3]: #installation