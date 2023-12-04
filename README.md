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
 o To fulfill this user story, the following acceptance criteria must be met:

    Semantic HTML elements: The codebase should consistently utilize semantic HTML elements, such as header, nav, main, article, section, and aside, to clearly define the structure and purpose of each section of the website.

    Logical HTML structure: The HTML structure should be organized in a logical manner, independent of styling or positioning. This means that the code should convey the intended content hierarchy and relationships between elements without relying on CSS or JavaScript for presentation.

    Accessible image and icon alt attributes: All images and icons should include descriptive and informative alt attributes that provide a textual equivalent of the visual content. This ensures that users with visual impairments can understand the content of the website effectively.

    Sequential heading structure: Heading elements should be used in a sequential manner, starting with <h1> for the main title and progressing through <h2>, <h3>, and so on. This helps screen readers and assistive technologies understand the hierarchical organization of the content.

    Concise and descriptive page titles: The title element should contain a clear and concise description of the content of each page. This is crucial for search engine optimization and providing users with a quick understanding of the page's purpose.
### Code changes exemples
& use `header` insted div for header and thake out header from body.
& use `nav` insted div for navigation
<header>
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
</header>

<body>

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