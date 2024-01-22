

# Introduction to CSS

CSS, or Cascading Style Sheets, is a stylesheet language used for describing the presentation of a document written in HTML. It controls the visual style and layout of web pages.

### What is CSS Selector - Class and ID Concept

CSS selectors are patterns used to select and style HTML elements. Classes (`.classname`) and IDs (`#idname`) provide a way to apply styles to multiple elements or uniquely style a specific element, respectively.

## Working With Internal CSS

Internal CSS involves placing styles directly within the HTML document.

- CSS Properties (Width, height, background, float)
  ```css
  .box {
      width: 200px;
      height: 150px;
      background-color: #f0f0f0;
      float: left;
  }
- Count div tags needed to develop any web design
Div tags are commonly used to structure and layout web designs. The number depends on the complexity of your design.
### CSS Properties Explained

- Font Properties (font-size, color, font-weight, font-style)
 p {
    font-size: 16px;
    color: #333;
    font-weight: bold;
    font-style: italic;
}
- Text Properties (text-align, text-decoration, text-transform, word-spacing)
  .title {
    text-align: center;
    text-decoration: underline;
    text-transform: uppercase;
    word-spacing: 2px;
}
### What is External CSS and How to Link It
External CSS is stored in a separate file and linked to HTML.

- Linking CSS to HTML
- Example
  <p style="color: blue;">This is a blue paragraph.</p>
### Concept of Mouse Hover with Example
Mouse hover effects can be achieved using the :hover pseudo-class.

- Example
  a:hover {
    color: red;
}
###Font properties:
Font properties in CSS allow you to control the appearance and styling of text.
### Text properties:
Text properties in CSS control various aspects of the text content, including alignment, decoration, transformation, and spacing.

These properties give you fine-grained control over how text is presented on your web page.

You can use them individually or in combination to achieve the desired visual effects and ensure a cohesive design.
