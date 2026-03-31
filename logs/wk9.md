Where is the <script> tag?
    At the bottom of the file, just before </body>

How does JavaScript find HTML elements?
    document.getElementById('add-input') finds elements by their id
    document.querySelectorAll('.filter-btn') finds elements by class

What makes the "Add" button do something?
    An addEventListener('click', ...) on the button that calls addTodo()

Where does the code change the page?
    Inside render() — it creates <li> elements and appends them to the list with appendChild()

    