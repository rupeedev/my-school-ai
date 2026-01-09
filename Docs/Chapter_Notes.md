# Computer Science Notes
## Class 8

---

### Chapter 5: Images and Links in HTML
**Summary:**
This chapter explains how to make web pages more attractive and navigable by adding images and hyperlinks.

*   **Images (`<img>` tag)**: used to embed images.
    *   **Syntax**: `<img src="image.jpg" alt="Description" height="100" width="100">`
    *   **`src`**: Specifies the path/URL of the image.
    *   **`alt`**: Alternate text displayed if the image fails to load.
    *   **`height` & `width`**: Define the size of the image.
*   **Links (`<a>` tag)**: used to create hyperlinks connecting to other documents.
    *   **Syntax**: `<a href="https://example.com">Click Here</a>`
    *   **`href`**: Hypertext Reference, specifies the destination URL.
    *   **Types of Links**: Internal (same page) and External (different website).

---

### Chapter 6: Tables in HTML
**Summary:**
Tables are used to arrange data in rows and columns.

*   **`<table>`**: Defines the table container.
*   **`<tr>` (Table Row)**: Defines a row in the table.
*   **`<th>` (Table Header)**: Defines a header cell, bold and centered by default.
*   **`<td>` (Table Data)**: Defines a standard data cell.
*   **Attributes**:
    *   `border`: Specifies the width of the table border.
    *   `cellpadding`: Space between cell wall and content.
    *   `cellspacing`: Space between cells.
    *   `colspan`: Merges columns.
    *   `rowspan`: Merges rows.

---

### Chapter 7: Forms in HTML
**Summary:**
Forms represent a document section containing interactive controls for submitting information.

*   **`<form>`**: The container for all form elements.
*   **`<input>`**: The most used tag; `type` attribute changes its behavior (text, password, radio, checkbox, submit).
    *   `<input type="text">`: Single-line text field.
    *   `<input type="radio">`: Select one option from many.
    *   `<input type="submit">`: Button to send form data.
*   **`<textarea>`**: Multi-line text input.
*   **`<select>` & `<option>`**: Creates a drop-down list.

---

### Chapter 8: Introduction to CSS
**Summary:**
CSS (Cascading Style Sheets) describes how HTML elements are to be displayed on screen.

*   **Benefits**:
    *   Saves time (one file controls whole site).
    *   Easier maintenance.
*   **Syntax**: `Selector { property: value; }`
    *   Example: `h1 { color: blue; font-size: 12px; }`
*   **Methods to Add CSS**:
    1.  **Inline**: Inside HTML tag using `style` attribute.
    2.  **Internal**: Inside `<style>` tag in `<head>`.
    3.  **External**: Using a separate `.css` file linked via `<link>` tag.

---

### Chapter 9: Basic CSS Properties
**Summary:**
This chapter covers specific properties to style text and backgrounds.

*   **Text Properties**:
    *   `color`: Sets text color.
    *   `text-align`: Aligns text (left, right, center, justify).
    *   `text-decoration`: Adds underline, overline, line-through.
*   **Font Properties**:
    *   `font-family`: Sets the font type (e.g., Arial).
    *   `font-size`: Sets the size of text.
    *   `font-weight`: Sets thickness (bold).
*   **Background Properties**:
    *   `background-color`: Sets background color of an element.
    *   `background-image`: Sets an image as background.

---

### Chapter 10: Web Development Project Work
**Summary:**
This chapter applies the knowledge gained in previous chapters to build a practical project.

*   **Planning**: Deciding topic, layout, and content.
*   **Design**: Sketching the look and feel.
*   **Implementation**: Writing HTML for structure and CSS for styling.
*   **Testing**: Checking the website on different browsers (Chrome, Edge).
*   **Tools**: Using code editors like Visual Studio Code or Notepad++.
*   **Outcome**: A functional website combining text, images, links, tables, and styles. (Like the Holiday Homework we just created!).
