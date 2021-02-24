# Code Refactor

## Description
A code refactoring challenge to take the provided "Horiseon" site and correct code issues so the page displays correctly, and is more accessible.

## GitHub Repo
https://github.com/PrimalOrB/code_refactor

## Live Website
https://PrimalOrB.github.io/code_refactor

## Stages of refactoring
* Update base readme with more detail of project scope
* Add GitHub Issues
* Add Descriptive Title to HTML (GitHub Issue #1)
* Address HTML Structure (GitHub Issue #4)
    * Rename <div class="header"> to <header> and update corresponding CSS rules
    * Rename <div class="hero"> to <section> and update corresponding CSS rules
    * Rename <div class="content"> to <main> and update corresponding CSS rules
    * Rename <main> child divs as <article>, remove classes, and simplify redundant CSS rules
    * Change <div class="search-engine-optimization"> to <div id="search-engine-optimization"> so nav button works
    * Rename <div class="benefits"> to <aside> and update corresponding CSS rules
    * Rename <aside> child divs as <article>, remove classes, and simplify redundant CSS rules
    * Rename <div class="footer"> to <footer> and update corresponding CSS rules
    * Change header nav { font-size: 20px } to header nav { font-size: 18px } in the CSS so the page is scalable to 768px wide
    * Add <meta> description tag / content for search engine optimization

### Andrew Ogilvie - 2021 (UofT SCS Bootcamp)