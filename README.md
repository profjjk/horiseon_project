# Horiseon Project
This is a refactoring of the Horiseon home page to include accessibility features. Original page was missing Semantic HTML5 elements and images were missing alternative text. Code improvements were made and comments added to provide for more clear and concise reading of the HTML and CSS files.

## Code Snippets
* Added semantic HTML elements for `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.
```
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#seo">Search Engine Optimization</a>
```
```
<footer>
        <h3>Made with ❤️️ by Horiseon</h3>
```
* Consolidated and renamed redundant classes to `benefits-all`, `benefit-ind`, and `article`. Shortened id names.
```
<section class="content">
        <article id="seo" class="article">
```
```
<aside class="benefits-all">
        <div class="benefit-ind">
```
* Added alternative text to images.
```
<img src="images/search-engine-optimization.jpg" class="float-left" alt="Search Engine Optimization"/>
```

## Link to website
[Horiseon Home Page](https://profjjk.github.io/horiseon_project/)
[GitHub Repo](https://github.com/profjjk/horiseon_project)

## Built With
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Author
**Jordan Kelly** 
- [Github](https://github.com/profjjk)
- [LinkedIn](https://www.linkedin.com/in/jordan-kelly-3934a597/)

## Screen Shots
![Screen Shot](images/screenshot_top.png?raw=true "Screen Shot Top")
![Screen Shot](images/screenshot_bottom.png?raw=true "Screen Shot Bottom")