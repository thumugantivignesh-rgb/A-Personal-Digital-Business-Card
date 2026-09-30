# T. Vignesh - Personal Digital Business Card Files

Here are your two source files. Create two separate files on your computer named exactly `index.html` and `style.css`, copy the respective code blocks below into each, and then upload them directly to your GitHub repository!

---

### File 1: `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>T. Vignesh - Digital Business Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="card">
        <div class="profile-header">
            <h1>T. Vignesh</h1>
            <p class="role">B.Tech First-Year Student</p>
            <p class="college">NIAT</p>
        </div>
        
        <div class="bio-section">
            <p><strong>Background:</strong></p>
            <ul>
                <li>School: The Hyderabad Public School</li>
                <li>Inter: Nano Jr College</li>
            </ul>
            <p class="skills-text"><strong>Mastering:</strong> HTML, CSS, & Python</p>
        </div>

        <div class="buttons">
            <a href="https://github.com/thumugantivignesh-rgb" target="_blank" class="btn">GitHub Profile</a>
        </div>
    </div>
</body>
</html>
```

---

### File 2: `style.css`

```css
body {
    background-color: #0d1117;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    color: #c9d1d9;
}

.card {
    background-color: #161b22;
    padding: 30px;
    border-radius: 16px;
    text-align: center;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.6);
    width: 320px;
    border: 1px solid #30363d;
}

h1 {
    margin: 0 0 5px;
    font-size: 24px;
    color: #f0f6fc;
}

.role {
    color: #58a6ff;
    font-size: 15px;
    font-weight: 600;
    margin: 0;
}

.college {
    color: #8b949e;
    font-size: 13px;
    margin-bottom: 20px;
}

.bio-section {
    text-align: left;
    font-size: 13px;
    background-color: #0d1117;
    padding: 15px;
    border-radius: 8px;
    margin-bottom: 20px;
    border: 1px solid #21262d;
}

.bio-section ul {
    margin: 5px 0 15px 15px;
    padding: 0;
    color: #8b949e;
}

.bio-section li {
    margin-bottom: 3px;
}

.skills-text {
    color: #7ee787;
    margin: 0;
}

.btn {
    display: block;
    background-color: #238636;
    color: white;
    padding: 10px 0;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.2s;
}

.btn:hover {
    background-color: #2ea043;
}
```