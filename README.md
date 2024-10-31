# Responsive Web Design Exercise: Media Queries, Semantic HTML, and Performance Optimization

## Objective
This comprehensive exercise will guide you through creating a responsive, accessible, and high-performing website. You’ll use CSS media queries to style a webpage for various screen sizes, update the HTML to use semantic tags, optimize images for the web, and evaluate the performance of your site on mobile using Chrome’s Lighthouse tool.

## Instructions

### CSS Media Queries
For each media query, follow the comments to fill in the correct CSS properties and values to create responsive styles for small tablet, tablet, and desktop views.

#### Check the Footer Layout
When the CSS breakpoint is set to `min-width: 500px`, ensure that the links and the brand logo inside the footer are displayed correctly. Links should be displayed inline and evenly spaced, and the brand logo should be aligned to the right within the footer. Use `flex` or `float` properties as needed to achieve the desired layout.

- **Validate your CSS** with the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) to ensure all tags are used correctly and fix any errors that may appear.

### Semantic HTML
Review the HTML file and replace any non-semantic tags (such as `<div>` and `<span>` used for structural purposes) with semantic HTML tags (such as `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`, etc.) to improve accessibility, SEO, and readability.

- Validate your HTML with the [W3C HTML Validator](https://validator.w3.org/) to ensure all tags are used correctly and fix any errors that may appear.

### Optimize Images for Web
Image optimization is crucial for improving the website’s loading time, especially on mobile devices. Follow these steps to optimize images:

- **Resize images** to the dimensions needed for each layout. For instance, avoid using high-resolution images if they are displayed at smaller sizes.
- **Compress images** using tools like Adobe Lightroom or other tools you've learned in school, which reduce file size without noticeable quality loss.
- **Use modern image formats** such as WebP for better compression and quality.

### Evaluate Website Performance with Chrome Lighthouse
To check your site’s performance on mobile, use Chrome’s Lighthouse tool and aim for a performance score between 90-100:

1. Open your website in Chrome.
2. Right-click on the page and select **Inspect** to open Developer Tools.
3. Navigate to the **Lighthouse** tab, select **Mobile** under “Device,” and click **Generate report**.
4. Review the report and take note of any suggestions for improvements. Fix any issues, especially those affecting performance, accessibility, and best practices.
5. Re-run Lighthouse if needed until you achieve a score between **90 and 100**.
