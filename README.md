### CSS Code (styles.css)
```css
/* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #f0f8ff;
}

header {
    position: relative;
    height: 100vh;
    color: white;
    text-align: center;
}

#background-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100vh;
    object-fit: cover;
    z-index: -1;
}

.overlay {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
}

h1 {
    font-size: 4rem;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    padding: 0;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1.2rem;
}

section {
    padding: 60px 20px;
    text-align: center;
}

h2 {
    color: #005b96;
    font-size: 2.5rem;
}

p, ul {
    max-width: 600px;
    margin: 0 auto;
    font-size: 1.2rem;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #005b96;
    color: white;
}

footer a {
    color: white;
    text-decoration: underline;
}

/* Accessibility Features */
body {
    font-size: 18px;
}

@media (max-width: 768px) {
    h1 {
        font-size: 3rem;
    }
    nav ul li a {
        font-size: 1rem;
    }
    h2 {
        font-size: 2rem;
    }
}

/* Text Resizing for Accessibility */
body {
    resize: both;
    overflow: auto;
}
```

