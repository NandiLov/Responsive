# Learning Responsive web-dev

##Explanation:

In the HTML, we set up a basic structure with a <div class="hero"> to contain our hero background image and text content.

We include the necessary viewport meta tag to ensure the website scales correctly on different devices.

We link an external CSS file (styles.css) to apply styles to our HTML elements.

In the CSS, we reset some default margin and padding to create a clean slate for styling.

We apply the background image to the .hero class using background-image, set its size to cover the entire viewport with background-size: cover, and position it at the center with background-position: center.

We set the height of the .hero section to 100vh (viewport height) to make it cover the entire screen. We also use display: flex, align-items: center, and justify-content: center to vertically and horizontally center the content within the hero section.

We style the hero content (h1 and p) with appropriate font sizes and margins for desktop screens.

Using a media query (@media (max-width: 768px)), we make the hero section responsive. On screens with a maximum width of 768 pixels (typical for tablets and mobiles), we reduce the height of the hero section to 60vh and adjust the font sizes of h1 and p to make them more suitable for smaller screens.

This media query ensures that the hero background image and its content are displayed effectively across various device sizes, providing a responsive user experience. You can adjust the values in the media query to suit your design and content needs for different screen sizes.
