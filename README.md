# Hariseon refactor-challenge-code

## Description
 For this project I had to refactor an already existing code. 
    - I had to refactor the code and make sure that the code is refactored properly.
    - I need to change title of the page to something descritive.
    - HTML to be mpre semantics.
    - CSS more efficient.
    - All links should work as expected.
    - Atribute `alt` should describe the picture properly. 
 ### Use Story 
 AS A marketing agency
 I WANT a codebase that follows accessibility standards
 SO THAT our own site is optimized for search engines
 ### Accepted criteria
* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title
### Code changes exemples
& use `header` insted div for header and thake out header from body.
& use `nav` insted div for navigation
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
