# VibeThread - Modern Clothing Store Website

This is a clean, simple, and fully responsive single-page clothing website template. It is built using basic **HTML5** and **CSS3** features, keeping the code simple, structured, and easy to understand .

---

## 🛠️ Project Layout & Structure (How It Works)

The website is divided into **7 main sections** from top to bottom, making the layout easy to follow:

### 1. Navigation Bar (`<header>`)
* **Logo:** A modern, minimal text logo on the left side (`vibe` + `thread`).
* **Menu Links:** Located in the center. It uses basic CSS hover rules to create a simple **Dropdown Menu** for sub-items.
* **Call-to-Action:** A sharp rectangular button on the right side reading "Explore Store" to capture user attention.

### 2. Main Hero Banner (`<section class="hero">`)
* **Background Visual:** Uses a full-width background image to give the store an aesthetic, modern fashion vibe.
* **Text Readability:** A dark layer (`linear-gradient`) is placed over the image so that the white heading text stays clean and easy to read.

### 3. About Section (3 Cards Row)
* **3-Column Grid:** Uses CSS Grid to automatically place **3 content boxes** perfectly side-by-side in a single row.
* **Card Details:** Each card contains a unique fresh image, a small category tag, a clear title, descriptive text, and a "Read Story" link.

### 4. Promotion & Features Split
* **Big Sale Banner:** A high-impact center banner showing a flat **-70% OFF** season discount.
* **Features Grid:** Located right below the sale banner. The layout splits into a bold title on the left and **4 different feature blocks** (e.g., fast delivery, easy swap) with minimal web icons on the right.

### 5. Product Catalog (4 Columns)
* **Aligned Display:** The main store area showcases **4 trending products** arranged neatly in a single horizontal row.
* **Hover Interaction:** When a user moves their mouse over a product image (`:hover`), a dark overlay smoothly fades in to display the text label.

### 6. Image Gallery & Social Lookbook
* **Asymmetric Collage:** Displays one large banner image next to two smaller stacked blocks to create a dynamic, modern layout.
* **Instagram Grid:** A clean line of **6 model pictures** arranged horizontally to mimic a live social media feed.

### 7. Footer Area
* Closes the page with the brand's short description, a clean list of helpful links, social media profile icons, and a student project assignment copyright note.

--- Technical decisions i represent :

* **Question: Why did you use CSS Grid in this project?**
  * **Answer:** "I used **CSS Grid** for sections that require structured columns, like the 3 About Cards, 4 Catalog Products, and 6 Instagram Pictures. By using rules like `grid-template-columns: repeat(4, 1fr);`, the browser automatically divides the screen space evenly. This prevents me from having to calculate manual percentage widths."

* **Question: Why did you use Flexbox in other parts?**
  * **Answer:** "I used **Flexbox** for aligning elements in a single horizontal line where spacing needs to adjust dynamically, such as distributing space across the Navigation Bar or centering content inside individual feature blocks."

* **Question: How did you make the website responsive for mobile screens?**
  * **Answer:** "I implemented standard CSS **Media Queries**. When the screen width shrinks below `768px` (mobile viewports), all side-by-side grids and flex elements automatically change their behavior to `flex-direction: column`. This stacks the boxes vertically, making it highly scrollable and easy to read on small devices."


  # Conclusion

This project demonstrates how a complete fashion store website can be developed using only HTML and CSS without JavaScript.

The structure is created with HTML and the design is controlled using CSS.


