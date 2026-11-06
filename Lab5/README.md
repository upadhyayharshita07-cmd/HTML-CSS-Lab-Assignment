# EXPERIMENT NO. 05

## 1. Experiment Title
Links and Images

## 2. Aim
Link two pages together and add a picture with alt text.

## 3. Software / Tools Required
- Operating System: Windows 10/11
- Tools: Web Browser (Chrome / Edge), VS Code / Notepad

## 4. Theory
- **Hyperlink (`<a>`):** Links one page to another using the `href` attribute.
- **Image (`<img>`):** Displays a picture on the page.
- **Image Attributes:**
  - `src`: Specifies the path to the image file.
  - `alt`: Provides descriptive alternative text for screen readers or when the image fails to load.
  - `width` and `height`: Sets the size of the image on the screen.

## 5. Algorithm / Procedure
1. Create a home page with heading "Welcome to My Site" and a link to portfolio.
2. Create a portfolio section with a heading and a link back to the home page.
3. Add a picture with `width="200"`, `height="200"`, and descriptive `alt` text.
4. Test the links to verify smooth navigation and verify image display.

## 6. Program / Queries / Commands
```html
<!-- Home section -->
<h1>Welcome to My Site</h1>
<p>Visit my <a href="#portfolio">portfolio</a>.</p>

<!-- Portfolio section with image -->
<div id="portfolio">
  <h1>Student Portfolio</h1>
  <img src="images/profile.png" width="200" height="200" alt="Student Profile Picture">
  <p><a href="#">Back to Home</a></p>
</div>
```

## 7. Input
Anchor links, 200x200 image, alt text "Student Profile Picture".

## 8. Output
Browser display showing working clickable links and an aligned 200x200 image.

![Output Screenshot](images/screenshot.png)

## 9. Result
Pages were linked together successfully and the image was displayed with dimensions and alt text.

## 10. Viva-Voce Questions
1. **Why is alt text important for images?**  
   *Answer:* It helps visually impaired users who use screen readers and displays text if the image fails to load.

2. **What does the href attribute specify in an anchor tag?**  
   *Answer:* It specifies the destination URL or target page of the hyperlink.

3. **Why should width and height be specified for images?**  
   *Answer:* They reserve layout space before the image loads, preventing page jumping.
