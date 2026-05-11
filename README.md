<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Interactive Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }
        h1 {
            color: #0066cc;
            text-align: center;
            font-size: 2.5em;
        }
        h2 {
            color: #0099cc;
            border-bottom: 2px solid #0066cc;
            padding-bottom: 10px;
        }
        p {
            font-size: 1.1em;
            margin-bottom: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        a {
            color: #cc6600;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        button {
            background-color: #0066cc;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 30px auto;
        }
        button:hover {
            background-color: #004d99;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to My Simple Webpage</h1>
        
  <h2>About This Page</h2>
        <p>This webpage demonstrates basic HTML structure with headings, paragraphs, an image, and a link. We've styled it using CSS for better visuals and added             JavaScript for interactivity.</p>
        
  <img src="https://picsum.photos/600/400" alt="Beautiful landscape image">
        
  <p>Visit <a href="https://www.example.com" target="_blank">Example.com</a> for more information.</p>
        
  <button id="interactiveButton">Click Me for a Surprise!</button>
    </div>

  <script>
        document.getElementById('interactiveButton').addEventListener('click', function() {
            alert('Hello! You clicked the button. Great job learning HTML, CSS, and JavaScript!');
        });
    </script>
</body>
</html>
