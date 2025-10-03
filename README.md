# Task-5
Task 5: Deploy a Static Website Using GitHub Pages
## 🛠️ Step-by-Step Instructions
### 1. Create a New GitHub Repository
- Go to GitHub
- Click New Repository
- Name it something like my-static-site
- Choose Public
- Check Add a README (optional)
- Click Create Repository
 ### 2. Add Your Website Files
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pooja's Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #0078d4;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
    }

    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin: 1rem;
      padding: 1.5rem;
      max-width: 300px;
      flex: 1 1 250px;
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #ddd;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Pooja's Web Projects</h1>
    <p>Front-End & Back-End Developer</p>
  </header>

  <div class="container">
    <div class="card">
      <h2>To-Do List App</h2>
      <p>Built with HTML, CSS, and JavaScript. Features add/delete/complete tasks with responsive design.</p>
    </div>
    <div class="card">
      <h2>Book API</h2>
      <p>RESTful API using Node.js and Express. Handles CRUD operations and tested with Postman.</p>
    </div>
    <!-- Add more cards for other projects -->
  </div>

  <footer>
    <p>© 2025 Pooja | Hosted on GitHub Pages</p>
  </footer>
</body>
</html>
```
 ### 3. Enable GitHub Pages
- Go to your repo on GitHub
- Click Settings → Pages
- Under Source, select main branch and /root
- Click Save
