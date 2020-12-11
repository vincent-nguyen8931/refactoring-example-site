# Refactoring example site

![Image](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Landing-page.jpg?raw=true)
Description
------------

The purpose of this project is to refactor a functional webpage to include accessibility options and SEO (search engine optimization).

 Table of contents
---------------
[Tools used](#Tools-used)<br />
[View the site](#Deployed-here)<br />
[Changes made](#Changes-made)<br />
[Lessons learned](#Lessons-learned) <br />
[Credits](#Credits)<br />

Tools used
-------------------

* CSS
* GitBash
* GitHub
* HTML
* VS Code

Deployed here
-------------

Below is the link to the deployed webpage. 
[Link to site](https://vincent-nguyen8931.github.io/refactoring-example-site/)


Changes made
------------------

Some of these changes include adding alt text to images and using semantic elements in the html.

At the top of the html, I made a change to the title to allow a more concise and descriptive title.

![title](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Title-change.png?raw=true)

The following change is to use semantic html elements instead of simply div class="name".

![header](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Header-html.png?raw=true)

This change requires an update to the css style sheet. All of the below headers were classes and changed to allow use of the semantic html header.

![header-css](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Header-css.png?raw=true)

The anchor was working improperly and required an addition of an id. The addition of the below id made the anchor in the html properly in the webpage.

![ID-add](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/ID-add-to-seo.png?raw=true)


Additional changes to div classes to the html to use semantic htmls are below at their respective lines. These changes were made to improve SEO. 

![main](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/main-1.png?raw=true)

![aside](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Aside-change-1.png?raw=true)

![article](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/article-change-1.png?raw=true)

![footer](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Footer-change-1.png?raw=true)

Lessons Learned
----------------

An attempt was made at adding an alt text to an image file being pulled through the css file. The below change does not work in the way I expect it to with the alt text replacing the images location. Upon additional reading about alt text, if an image is considered unimportant or not paramount, the image will be pulled through css due to the expectation of an alt text not being required. 

![css](https://github.com/vincent-nguyen8931/refactoring-example-site/blob/main/screenshots/Alt-for-css-image.png?raw=true)

Credits
---------------
LinkedIn: [https://www.linkedin.com/in/vincent-nguyen-74226a107/](https://www.linkedin.com/in/vincent-nguyen-74226a107/)