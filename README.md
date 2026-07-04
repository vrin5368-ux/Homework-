# Welcome to BrightCourse! 🚀

This is a simple, 4-page website designed for beginners to learn and practice **HTML** (HyperText Markup Language) and **CSS** (Cascading Style Sheets).

The website represents a coding school template with four pages:
1. **Home (`index.html`)**: A landing page with a hero header, text, an illustration, and key features.
2. **Courses (`courses.html`)**: A page displaying what topics students will learn in cards.
3. **About (`about.html`)**: A page describing the school's mission with an illustration.
4. **Contact (`contact.html`)**: A form page to register or submit questions.

---

## 📂 Project Structure

All files in this project are simple and clean:
- `index.html`, `courses.html`, `about.html`, `contact.html` — The structure of the website.
- `style.css` — The styles (colors, layout, fonts) used by all four pages.
- `assets/` — Folder containing illustrations (`.svg` files).
- `screenshots/` — Folder containing images of how the completed website should look.

---

## 📖 Key Concepts to Learn

### 1. HTML (Structure)
- **Tags & Elements**: HTML uses tags like `<h1>` (Heading 1), `<p>` (Paragraph), `<a>` (Link), and `<img>` (Image) to put content on the page.
- **Semantic Structure**: We use tags that tell the browser what the section represents:
  - `<header>`: The top navigation bar.
  - `<main>`: The primary content of the page.
  - `<section>`: A thematic grouping of content.
  - `<footer>`: The copyright info and links at the bottom.
- **Forms**: Used to collect input from users (`<form>`, `<label>`, `<input>`, `<textarea>`, and `<button>`).

### 2. CSS (Styling & Layout)
- **Selectors**: Connecting CSS styles to HTML tags, classes (like `.button`), or IDs.
- **Box Model**: Controlling space around elements:
  - `padding`: Space inside an element's border.
  - `margin`: Space outside an element's border.
  - `border-box`: Tells the browser to include padding and border in the element's total width/height.
- **Flexbox Layout**: Makes aligning items side-by-side or stacked very easy.
  - `display: flex`: Activates flexbox.
  - `justify-content`: Distributes items horizontally (e.g. `space-between`, `center`).
  - `align-items`: Positions items vertically (e.g. `center`).
  - `flex-direction`: Direction of children (`row` for horizontal, `column` for vertical).
- **Responsive Design (Media Queries)**: Using `@media (max-width: 768px)` to make sure the website stacks neatly on small mobile screens.

---

## 🛠️ Student Practice Challenges

Try to complete these exercises to practice your HTML and CSS skills!

### Challenge 1: Change the Accent Theme Color 🎨
By default, the active buttons and links are **blue** (`#2b7cff`).
1. Open `style.css`.
2. Look for the color `#2b7cff` in the stylesheet.
3. Replace it with your favorite color (e.g., `#2ecc71` for green, `#9b59b6` for purple, or `#e67e22` for orange).
4. Do the same for the hover color (e.g., replace `#175ec9` with a darker version of your color).

### Challenge 2: Add a New Feature Card 📌
1. Open `index.html`.
2. Scroll to the `<section class="features">` block.
3. Copy one of the `<div class="feature-card">` elements and paste it below the third card.
4. Edit the heading `<h3>` and paragraph `<p>` inside your new card to describe a different benefit (e.g., "Online Support").
5. Open `index.html` in your browser. Do you see the fourth card? Notice how CSS Flexbox automatically adjusts the cards' spacing!

### Challenge 3: Add a Phone Number Field to the Contact Form 📞
1. Open `contact.html`.
2. Look for the `<form class="contact-form">` section.
3. Add a new `<label>` and `<input>` field for a Phone Number between the Email and Message fields:
   ```html
   <label for="phone">Phone Number</label>
   <input id="phone" type="tel" placeholder="Enter your phone number">
   ```
4. Save the file and refresh `contact.html` in your browser.

### Challenge 4: Add Hover Animation to Cards ✨
1. Open `style.css`.
2. Look for the `.feature-card` or `.course-card` rule.
3. Add a transition property: `transition: transform 0.3s ease, box-shadow 0.3s ease;` to the selector.
4. Create a new hover style rule below it:
   ```css
   .feature-card:hover,
   .course-card:hover {
     transform: translateY(-5px);
     box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
   }
   ```
5. Save and check the cards in your browser. When you hover over them, they will gently float up!
