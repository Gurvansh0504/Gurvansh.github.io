/* Reset some default styles */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: white;
}

section {
    padding: 20px;
}

.code-files {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 10px;
}

.code-file, .issue {
    background-color: #f5f5f5;
    padding: 10px;
    border: 1px solid #ddd;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}
