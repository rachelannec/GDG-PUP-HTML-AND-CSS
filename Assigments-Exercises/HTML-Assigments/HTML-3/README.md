# HTML #3 Assignment: Clickable Image Link

## Overview

This assignment will guide you in creating a clickable image link using HTML. You will learn how to insert an image related to your hobby and make it clickable, linking to an external website with more information.

---

## Instructions

1. **Open Your Code Editor**:
   - Use a code editor like Visual Studio Code.

2. **Create a New HTML File**:
   - Create a new file and save it as `hobby.html`.

3. **Write the HTML Code for a Clickable Image Link**:
   - Copy and paste the following HTML code into your file:

     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Clickable Image Link</title>
     </head>
     <body>
         <h1>My Hobby: Photography</h1>
         <p>Click the image below to learn more about photography:</p>
         <a href="https://www.photographyblog.com" target="_blank">
             <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Nikon_D5100.jpg/800px-Nikon_D5100.jpg" 
                  alt="Nikon D5100 Camera" 
                  style="width:400px; height:auto; border:1px solid #000;">
         </a>
     </body>
     </html>
     ```

4. **Explanation**:
   - `<a href="URL">`: Creates a hyperlink. The `href` attribute specifies the link's target URL.
   - `<img src="image_url" alt="text">`: Embeds the image. The `src` attribute is the path to the image file, and the `alt` text provides a description for accessibility.
   - `style`: Inline CSS to style the image, including width, height, and border for better presentation.
   - `target="_blank"`: Ensures the link opens in a new tab.

5. **Save Your File**:
   - Save the file as `hobby.html`.

6. **Preview Your HTML File**:
   - Open the file in a browser to verify:
     - The image displays properly.
     - Clicking the image redirects you to the external website.

---

## Tips

- Make sure the image URL is correct and accessible (you can use an image hosted online or save a local image in your project folder).
- Use descriptive alt text for better accessibility and SEO.
- Ensure your file is saved with the `.md` extension.

## Example in Action

```markdown
[![Photography](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Nikon_D5100.jpg/800px-Nikon_D5100.jpg)](https://www.photographyblog.com)