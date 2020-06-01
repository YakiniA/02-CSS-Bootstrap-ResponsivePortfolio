# Unit 02 CSS and Bootstrap : Responsive Portfolio

This assignment mainly focuses on a responsive view of various devices or screen sizes. That means if it's a `xs` screen, content is displayed in entire screen. On `sm` and larger screens, there are some margins present on either side of the screen. The web application is primarily developed by using Bootstrap and responsive view achieved by using media queries as needed. Also used an HTML validation service to ensure that it's a proper and valid HTML.

# About Page/Home Page

* The file "index.html" is for About Page/Home Page.
* This page has a navigation bar(nav bar) with name on the left side and About, Portfolio and Contact Us links on the right side. On clicking the links results in respective page.
* The nav bar is responsive when viewed on different devices with the help of media queries on the "style.css" file.
* The image on the About page is made responsive by using CSS styling.
* Contain personal details including name, image and social media links.
* Used Bootstrap's grid system (containers, rows, and columns) to get a proper view on various screens.
* Used Semantic HTML elements everywhere as needed.
* The footer is located at the bottom of the page. It is made as Sticky footer, that means the footer always sticks to the bottom regardless of the content of the page. This is achieved mainly by using CSS. 

# Portfolio Page

* The file "portfolio.html" is for Portfolio Page.
* This page also has responsive navigation bar with name and nav links like in homepage. On clicking the links results in appropriate pages.
* Appropriate font styling is given for the heading.
* Bootstrap's grid system is used for aligning the images properly.
* Used the class attributes imagecontainer, text-block for aligning the text content with 
the image properly.
* The images amd the layout are highly responsive.
* Like Homepage, sticky footer is present at the bottom of the page.

# Contact Page

* The file "Contact.html" is for Contact Page.
* The contact page also has responsive navigation bar with name and nav links, on clicking the links results in appropriate pages.
* It has Name, Email, Message and Submit fields. All these are written using Bootstrap.
* Adavantage of using Bootstrap in forms is that default validation feedback for fields are given.
* The styling and alignment issues are minimized with the help of Bootstrap. They provide wide range of shorthand responsive margin and padding utility classes to modify an element’s appearance.
* Like Homepage, sticky footer is present at the bottom of the page.

# Challenges Faced

* In this application, used media queries to make the nav bar as responsive and used display:fex; flex-direction:row to achieve as expected. Another way is by using buttons  in Bootstrap, but this results in `buttons` on small screen size and on clickig that we can see the nav links. [For more details refer Bootstrap documentation](https://getbootstrap.com/docs/4.5/components/navbar/)

* To make footer as a sticky one, used min-height:100vh, position:relative in body CSS file and made the width as 100% in the footer.

* In portfolio page, the text contents has to properly align with the image and should be responsive as well. 



