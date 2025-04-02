<!--  
    MEDIA QUERY: 

    Media queries help make a website responsive by adjusting styles based on screen width (breakpoints).  
    A responsive website is mobile-friendly and adapts to different device sizes.  

    Breakpoints define specific width ranges where styles change.  
    Below are common breakpoints:
    
    1. Extra Small (XS)  -> width < 576px  
    2. Small (SM)        -> 576px to 767px  
    3. Medium (MD)       -> 768px to 991px  
    4. Large (LG)        -> 992px to 1199px  
    5. Extra Large (XL)  -> 1200px to 1399px  
    6. Extra Extra Large (XXL) -> width >= 1400px  
-->

<!--  
    WIDTH USAGE IN MEDIA QUERIES:  

    - Media queries can use `min-width` (for styles applying above a width)  
    - Or use `max-width` (for styles applying below a width)  

    Example:
    - `@media (min-width: 768px) {}` applies styles to screens 768px and larger.
    - `@media (max-width: 767px) {}` applies styles to screens smaller than 768px.
-->

<!--  
    HOW TO USE MEDIA QUERIES EFFECTIVELY:  

    1. Write CSS normally for the default layout.  
    2. Use media queries only when you need to override styles at certain breakpoints.  
    3. Avoid repeating CSS inside media queries if it’s already defined in the main stylesheet.  

    Example:
    - If `.navbar` already has styles in the main CSS, only add new styles in the media query.
-->

@media (min-width: 500px) and (max-width: 800px) {
    .navbar {
        /* Add only the styles that need to change for this screen range */
    }
}
