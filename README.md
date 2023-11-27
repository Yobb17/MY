
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <section>
        <h2>About Me</h2>
        <p>This is a simple introduction about me.</p>
    </section>
    <footer>
        <p>&copy; 2023 My Website</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em;
}

section {
    max-width: 800px;
    margin: 2em auto;
    padding: 1em;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 1em;
    background-color: #333;
    color: white;
}
// Get the header element
const header = document.querySelector('header');

// Change the header text when clicked
header.addEventListener('click', function() {
    header.textContent = 'Clicked! Welcome to My Website';
});
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
  res.send('Hello World!');
});

app.listen(port, () => {
  console.log(`Server listening at http://localhost:${port}`);
});

