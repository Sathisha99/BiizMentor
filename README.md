BizMentor Website Overview

Connection Between HTML, CSS, and JS

- HTML (index.html)  
  The HTML file provides the structure and content of the website. It defines the sections, headings, paragraphs, images, buttons, and links. All elements are marked with classes and IDs, which are used by CSS and JavaScript for styling and interactivity.  

- CSS (style.css) 
  The CSS file is linked in the `<head>` section of the HTML. It is responsible for the visual appearance of the website, including layout, typography, colors, spacing, responsiveness, and hover effects. Without CSS, the HTML content would display in a basic format which is not visually appealing.  

- JavaScript (app.js)
  The JS file is included at the end of the HTML <body> section. It is used for interactivity and dynamic behavior, such as:  
  - Updating text dynamically (e.g., hero section button click)  
   
 

Code Flow (What Happens When a User Loads the Page)

1.HTML loads first
   - The browser reads ‘index.html’ and builds the page structure (DOM).  
   - All sections (navbar, hero, features, categories, footer) are rendered.  

2. CSS is applied  
   - The browser applies ‘style.css’ to style elements according to their classes and IDs.  
   - Fonts (Google Fonts) and icons (Font Awesome) are loaded.  

3. JavaScript runs
   - Once the HTML is rendered, ‘app.js’ is executed.  
   - The JS file attaches event listeners to buttons and interactive elements.  
   - Dynamic features such button clicks become functional.  

Role of Each File in the Platform

index.html- Provides the structure and content of the web pages, including sections, headings, images, buttons, and links. 
style.css - Handles the visual design of the website including colors, layout, fonts, hover effects, responsive behavior, and animations. 
app.js - Adds interactivity and dynamic behavior, making the website responsive to user actions like button clicks and menu toggling. 

This structure ensures a clear separation of concerns: HTML for content, CSS for presentation, and JS for behavior. This makes the platform maintainable, scalable, and easy to enhance.
