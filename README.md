# Horiseon Project
This is a refactoring of the Horiseon home page to include accessibility features. Original page was missing Semantic HTML5 elements and images were missing alternative text. Code improvements were made to provide for more clear and concise reading of the HTML and CSS files.

## Link to website
https://profjjk.github.io/horiseon_project/


## Changes made to HTML file
#### HEAD
* Removed one layer from the asset folders to simplify relative path and updated links to reflect that change.
* Changed `<title>` to "Horiseon Home Page".
#### HEADER
* Added semantic HTML elements for `<header>` and `<nav>`.
* Fixed broken link in nav bar for "Search Engine Optimization" by adding id="search-engine-optimization" to the relevant article.
#### MAIN
* Added semantic HTML elements for `<section>`, `<article>`, and `<aside>`.
* Added alternative text to images.
#### FOOTER
* Added semantic HTML elements for `<footer>`.
* Changed h2 to h3 to better reflect naming hierarchy.

## Changes made to CSS file
* Added comments to clarify purpose of some CSS elements.
* Consolidated cumbersome and redundant CSS selectors into new class names: `.benefits-all`, `benefit-ind`, and `article`.

## Screen Shots
![Screen Shot](images/screenshot_top.png?raw=true "Screen Shot Top")
![Screen Shot](images/screenshot_bottom.png?raw=true "Screen Shot Bottom")