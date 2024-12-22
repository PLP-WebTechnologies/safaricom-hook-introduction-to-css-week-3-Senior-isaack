## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.  

---

#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.  

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.  

2. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border.  

```

This assignment will solidify your CSS basics while giving you a chance to style your first webpage creatively. Good luck and happy styling! 🎨🚀




MY ANSWERS:::

Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)
HTML File:
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Basics</title>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS -->
</head>
<body>
    <h1>This is a Heading (h1)</h1>
    <p>This is a paragraph. The font size for all headings will be larger.</p>

    <div class="section">
        <h2>This is a Section Title (h2)</h2>
        <p>This section has a background color applied using a class selector.</p>
    </div>

    <div id="unique">
        <h3>This is a Unique Section (h3)</h3>
        <p>This section has a border applied using an ID selector.</p>
    </div>
</body>
</html>
External CSS File (styles.css):
css
Copy code
/* Element Selector: Change font size for all headings */
h1, h2, h3 {
    font-size: 24px;
}

/* Class Selector: Apply background color to specific sections */
.section {
    background-color: lightblue;
    padding: 20px;
}

/* ID Selector: Add border to an element with unique ID */
#unique {
    border: 2px solid #333;
    padding: 20px;
}
Part 2: Inline, Internal, and External CSS (30 Points)
HTML File:
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling with Inline, Internal, and External</title>
    <style>
        /* Internal CSS */
        h1 {
            color: darkblue;
        }

        p {
            font-size: 16px;
            color: darkgray;
        }

        .special-section {
            background-color: lightgreen;
            padding: 20px;
        }
    </style>
    <link rel="stylesheet" href="styles.css"> <!-- External CSS -->
</head>
<body>
    <!-- Inline CSS to style the element -->
    <h1 style="color: red;">Styled with Inline CSS</h1>

    <p>This is a paragraph styled using internal CSS.</p>

    <div class="special-section">
        <h2>This is a special section with internal CSS applied.</h2>
        <p>It has a light green background and some padding.</p>
    </div>
</body>
</html>
External CSS File (styles.css):
css
Copy code
/* External CSS to style the whole page */
body {
    background-color: #f0f0f0;
}

/* External CSS to style links */
a {
    text-decoration: none;
    color: #007bff;
}

a:hover {
    color: #0056b3;
    text-decoration: underline;
}
Part 3: Basic Styling Properties (50 Points)
HTML File:
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Styling Properties</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Internal CSS for card component */
        .card {
            width: 300px;
            padding: 20px;
            margin: 20px;
            background-color: #fafafa;
            border: 1px solid #ccc;
            border-radius: 10px;
        }

        .card h2 {
            font-family: 'Arial', sans-serif;
            font-size: 22px;
            color: #333;
        }

        .card p {
            font-family: 'Georgia', serif;
            font-size: 16px;
            color: #666;
            text-align: justify;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Webpage</h1>

    <div class="card">
        <h2>Card Title</h2>
        <p>This is a simple card component. It has padding inside and a margin outside. The background color is light, and the border is subtle.</p>
    </div>

    <p>Here is another paragraph with custom font and text color.</p>
</body>
</html>
External CSS File (styles.css):
css
Copy code
/* External CSS for general page styles */
body {
    background-color: #ffffff;
    font-family: 'Verdana', sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

h1 {
    color: #2a2a2a;
    font-size: 36px;
}

p {
    color: #444;
    padding: 10px;
}

/* Styling links with hover effect */
a {
    color: #0077cc;
    text-decoration: none;
}

a:hover {
    color: #005599;
    text-decoration: underline;
}















