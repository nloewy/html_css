### Cascading Style Sheets
- Use of color, positioning, size is styling
- CSS is the technology that allows you to style the same html structure in vastly different ways
 
### Rules
- CSS works by associating rules with html elements
- Govern how the content of specified elements should be displayed
- Ex: CSS rule
    ```css 
    p { 
        color: blue;
        font-size: 20px;
        width: 200px;
        text-align: center;
    }
    ```
    - The `p` is a selector. Here it's the `p` for the paragraph tag. This means the following rule applies to all paragraphs in the html document
    - Inside the curly braces is the css declaration
        - The `color` is the property
            - predefined types of properties. each property has a set # of possible values
        - Every property:value is separated by a colon and terminated by a sei colon
    - The entire collection of css rules is a style sheet.