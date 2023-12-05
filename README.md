# Hariseon refactor-challenge-code

## Description
 For this project I had to refactor an already existing code. 
    - I had to refactor the code and make sure that the code is refactored properly.
    - I need to change title of the page to something descritive.
    - HTML to be more semantic.
    - CSS more efficient.
    - All links should work as expected.
    - Atribute `alt` should describe the picture properly. 
 ### Use Story 
 AS A marketing agency
 I WANT a codebase that follows accessibility standards
 SO THAT our own site is optimized for search engines
 ### Accepted criteria

The codebase use semantic HTML elements such header, navihation, body, article, section, and part to cleary define the structure and purpuse of each section of the website
All image recev information atribuite equivalent of the visual content. This ensure that visually impaired users can effecively understand the content of the website.
Heading elements are organisate from <h1> to <h6>  and so on, to help screen readers and assitive technologies undestand the hierarchical organisation of content.
Title element contine clear and coincise description to give ueser quick understunding of purpose of the page.   

     
### Code changes exemples
& use `header` insted div for header and thake out header from body.
& use `nav` insted div for navigation


header>
    <h1>Hori<span class="seo">seo</span>n</h1>
    <!-- I change non-semantic div with semantic element nav, beacuse it is a navigate area -->
    <nav>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </nav>
/header>



    <!-- I change non-semantic div with semantic element figure
    and add alt description -->
    <figure class="hero" al="ofice whit peaple at work "></figure>
    <!-- I change non-semantic div with semantic element main as principal blok -->
    <main class="content">

    CSS changes code with comasion 
 .benefit-lead h3,
 .benefit-brand h3,
 .benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
 }

 Another changeis is `footer` with div 
  
And added background color to footer with css.

footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    background-color: #5192b5;
}