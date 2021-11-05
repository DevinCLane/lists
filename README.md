# Lists

Creating proper lists with simple HTML:

- Unordered lists
- Ordered lists
- Nesting lists properly: 
    - The `<li>` element must live directly within a `<ul>` or `<ol>` element. [Source](https://learn.shayhowe.com/html-css/creating-lists/#nested-lists)
    - e.g., 
    ```
    <li>Meditate
                <ol>
                    <li>Breathe</li>
                    <li>When attention wanders, return to the breath</li>
                </ol>
            </li>
    ```