# Assignment-05 Mini Project-02

This project is a **responsive mini website** created using **HTML** and **CSS** as part of my web development journey. The primary focus of this project is to showcase responsive design techniques, clean code structure, and basic styling practices.

---

## Features

1. **Responsive Design**:  
   The website is designed to adapt seamlessly across various devices, including desktops, tablets, and mobile phones.

2. **Semantic HTML**:  
   Proper use of semantic HTML tags improves accessibility and readability.

3. **CSS Styling**:  
   Custom styling has been applied, focusing on creating a visually appealing layout.

4. **Simple and Clean Code**:  
   Organized code with comments for better understanding and maintenance.

---

## Folder Structure

```plaintext
Assignment-05-Mini-Project-02/
│
├── index.html       # Contains the structure of the webpage
├── style.css        # Contains the styles applied to the webpage
└── assets/          # Includes all images and resources used in the project
```

---

## Code Explanation

### HTML (`index.html`)

The `index.html` file serves as the foundation of the project. It includes the following:

1. **Header Section**:  
   - Includes a `<nav>` element for the navigation menu.  
   - Navigation links are implemented using `<ul>` and `<li>` tags.  

2. **Main Section**:  
   - The main content is structured using `<section>` tags.  
   - Each section is styled separately in the CSS for clarity and design consistency.  

3. **Footer Section**:  
   - Contains copyright information and social media links.  
   - Uses a `<footer>` tag for semantic accuracy.  

---

### CSS (`style.css`)

The `style.css` file is responsible for the visual styling of the webpage. Key highlights include:

1. **Global Reset**:  
   - A CSS reset is applied to ensure consistent styling across browsers using:  
     ```css
     * {
         margin: 0;
         padding: 0;
         box-sizing: border-box;
     }
     ```

2. **Typography**:  
   - Fonts are imported from Google Fonts for modern aesthetics.  
   - Font styles, sizes, and weights are adjusted for readability.  

3. **Responsive Design**:  
   - Media queries are used to adjust styles for smaller screens:  
     ```css
     @media (max-width: 768px) {
         /* Responsive styles go here */
     }
     ```

4. **Navigation Bar**:  
   - Styled using `flexbox` to align links horizontally.  
   - Hover effects enhance user interactivity.

5. **Sections**:  
   - Each `<section>` is styled individually with padding, margins, and background colors.  
   - Flexbox is often used for layout alignment.  

6. **Footer**:  
   - Styled minimally with proper spacing and alignment.  

---

## How to Use

1. Clone this repository to your local system:
   ```bash
   git clone https://github.com/jalal1122/Assignment-05-Mini-Project-02.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Assignment-05-Mini-Project-02
   ```
3. Open the `index.html` file in your browser.

---

## Conclusion

This mini project is a demonstration of my progress in front-end development, focusing on HTML structure, CSS styling, and responsive design principles.
