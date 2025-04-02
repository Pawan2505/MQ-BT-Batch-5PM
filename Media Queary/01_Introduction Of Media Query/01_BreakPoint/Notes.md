 <!-- 
    Media Queries in CSS:

    Media queries help in making websites responsive, meaning they adapt to different screen sizes.
    They ensure a mobile-friendly (device-friendly) design by adjusting layouts, fonts, and other styles 
    based on the screen width.

    Breakpoints: These are specific width ranges at which the design changes to enhance usability. 
    Below are the standard breakpoints:
-->

<!-- 
    1. Extra Small (XS) Devices: 
       - Applies when the screen width is less than 576px.
       - Typically used for very small mobile devices.
-->

@media (max-width: 575px) {
    /* CSS styles for extra small screens */
}

<!-- 
    2. Small (SM) Devices:
       - Screen width between 576px and 767px.
       - Suitable for most smartphones.
-->

@media (min-width: 576px) and (max-width: 767px) {
    /* CSS styles for small screens */
}

<!-- 
    3. Medium (MD) Devices:
       - Screen width between 768px and 991px.
       - Common for tablets and smaller laptops.
-->

@media (min-width: 768px) and (max-width: 991px) {
    /* CSS styles for medium screens */
}

<!-- 
    4. Large (LG) Devices:
       - Screen width between 992px and 1199px.
       - Used for larger tablets and smaller desktops.
-->

@media (min-width: 992px) and (max-width: 1199px) {
    /* CSS styles for large screens */
}

<!-- 
    5. Extra Large (XL) Devices:
       - Screen width between 1200px and 1399px.
       - Common for large desktop screens.
-->

@media (min-width: 1200px) and (max-width: 1399px) {
    /* CSS styles for extra large screens */
}

<!-- 
    6. Extra Extra Large (XXL) Devices:
       - Screen width greater than or equal to 1400px.
       - Used for high-resolution large screens.
-->

@media (min-width: 1400px) {
    /* CSS styles for extra extra large screens */
}
