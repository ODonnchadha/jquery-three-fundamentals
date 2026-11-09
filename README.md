## jQuery 3 Fundamentals by Craig Shoemaker

- OVERVIEW:
    - Work with DOM elements.
    - Manipulate CSS.
    - Build in interactivity.
    - Read and display data.
    - Handle user interaction.
    - Prerequisites: HTML, CSS, JavaScript.

- INTRODUCING JQUERY:
    - Why jQuery? Write code once and work within *any* browser.
        - Interface for simple, and complex, web applications.
        - `Version 3.6.0.`
    - Code editor. Visual Studio Code. Extensions. Live Server.
    - Set up project files.
    - Add jQuery.
    - Verify jQuery is loaded.
    ```javascript
        $
        $('body').hide();
    ```

- SELECTING DOM ELEMENTS:
    - Ready function:
    ```javascript
        $(function() { });
        $(() => { });
    ```
    - Selecting by id, class name, and attributes:
        - Hash symbol: Find an element by its id value.
        ```html
            <section class="columns-desktop" id="pies"></section>
        ```
        ```javascript
            $("#pies");
        ```
        - Class selector. Set of results. 0-based array.
        ```html
            <div class="pie"></div>
            <div class="pie"></div>
        ```
        ```javascript
            $(".pie");
        ```
        - Specific element selection.

### jQuery Fundamentals

### Tools
The following tools help make easier to work with sample code.
- [git](https://git-scm.com/downloads): A tool for managing source code
- [Visual Studio Code](https://code.visualstudio.com/): A source code editor
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): A simple web server utility for Visual Studio Code
- [Echo Post](https://github.com/craigshoemaker/echo-post): A simple Node.js server utility that displays post data.

### Setup
- With the files open in Visual Studio Code, press the **Go Live** button at the bottom of the window to launch the files with [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

### Resources
A list of links to resources used throughout this course is available on the [Resources](resources.md) page.