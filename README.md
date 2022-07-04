# README FILE FOR HORISEON

This README file includes the changes made by Cyprian Gomes as part of refactoring the website of Horiseon. The changes were carried out between Friday, 01 July 2022 and Saturday, 02 July 2022.

The site can be access by visiting https://capg84.github.io/c1-horiseon-refactor/

---

## Changes on the `index.html` file
> As part of the challenge I have made the following changes to the `index.html` file

* Updated the `<title>` to **Horiseon Home**, this makes the page personalized to the client, and more SEO friendly

* Updated the `<div class="content">` by adding the `id="search-engine-optimization"` inside the `<div class="search-engine-optimization">`. This is done to fix the **Search Engine Optimization** link in the navigation bar.

* Added the `alt` text to the following `<img>` elements.
    * Image linked to the `<div id="search-engine-optimization" class="search-engine-optimization">`

    * Image linked to the `<div id="online-reputation-management" class="online-reputation-management">`

    * Image linked to the `<div id="social-media-marketing" class="social-media-marketing">`

    * Image linked to the `<div class="benefit-lead">`

    * Image linked to the `<div class="benefit-brand">`

    * Image linked to the `<div class="benefit-cost">`

* Removed the `</img>` from `<img>` element of `<div class="benefit-cost">`. This is done to make all the `<img>` element in line

* Changed `<div class="header">` to `<Header>` element

* Changed the `<div class="content">` to `<article>` element

* Changed the `<div class="benefits">` to `<aside>` element

* From line 31 to 81 is wrapped inside the `<main>` element

* Changed the `<div class="footer">` to `<footer>` element

* Changed the `<div class="hero">` to `<section class="hero">`

* Changed the `<div>` nested inside the origianl `<div class="header">` **(current `<header>`)** to `<nav>`

* Added some blank rows after each block of codes to increase the readability of the `html` code

----------------------------

## Changes on the `style.css` file
> As part of the challenge I have made the following changes to the `style.css` file

* Added comments throughout the `style.css` file

* The following changes were made for the change I made to the `<div class="header">`

    * At line 14, removed the `.` (dot) **from .header to header** to apply the CSS properties on the header element

    * At line 22, changed from `.header h1` to `h1`

    * At line 28, changed from `.header h1 .seo` to `.seo`

    * At line 33, changed from `.header div` to `nav`

    * At line 41, changed the `.header div ul` to `header nav ul`

    * At line 47, changed the `.header div ul li` to `li`

* At line 87, changed from `.content` to `article`

* At line 228, changed from `.footer` to `footer`

* Grouped a number of selectors who have same css properties. I kept the original css properties as comments. This is because:
    
    * This will help a reader, if wants, to know how the original css was, and

    * This will help to easily have different css properties for the other parts in future, if needed by the business case.

---------
The refactored site will look like the below screenshot.

![this image](/assets/images/horiseon-refactored-screenshot.png)

--------

## Contact Details
**Cyprian Gomes**
<br>email: cyprian.gomes@live.co.uk
<br>Mobile: 07545839711




