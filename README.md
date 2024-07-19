<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full-Stack Trip Planner Web App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
        }
        h1, h2, h3 {
            color: #444;
        }
        a {
            text-decoration: none;
            color: #1a0dab;
        }
        a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .center {
            text-align: center;
        }
        .tech-list, .prerequisites-list {
            list-style-type: none;
            padding: 0;
        }
        .tech-list li, .prerequisites-list li {
            margin: 10px 0;
        }
        .images img, .screenshot img {
            margin: 10px;
            border-radius: 8px;
            max-width: 100%;
            height: auto;
        }
        .demo-link {
            display: block;
            margin: 20px 0;
            font-size: 1.2em;
        }
        .features ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="center" style="font-weight: bold;">Full-Stack Trip Planner Web App</h1>

        <p class="center">
            <a href="#tech">Technologies</a> | 
            <a href="#features">Features</a> | 
            <a href="#screenshots">Screenshots</a> | 
            <a href="#started">Getting Started</a>
        </p>

        <p class="center">
            A full-stack web application that helps users plan their trips by providing AI-powered recommendations for travel itineraries, places to visit, and hotels. This app integrates Google Generative AI for dynamic travel planning, Firebase for data storage, and Google Places API for fetching detailed information about places and hotels.
        </p>

        <p class="center">
            <a href="https://ai-trip-planner-barika.vercel.app/" class="demo-link">📱 Visit this Project</a>
        </p>

        <h2 id="layout">🎨 Layout</h2>
        <p class="center images">
            <img src="https://source.unsplash.com/random?travel" alt="Random Image" width="400px">
            <img src="https://source.unsplash.com/random?city" alt="Random Image" width="400px">
        </p>

        <h2 id="features">✨ Features</h2>
        <ul class="features">
            <li>AI-Powered Recommendations: Utilizes Google Generative AI to generate personalized travel itineraries, suggesting places to visit and hotels based on user preferences.</li>
            <li>Dynamic Hotel Information: Fetches detailed information about hotels including name, address, price, image, geo-coordinates, rating, and description.</li>
            <li>Place Details: Provides comprehensive details about places to visit, including images, geo-coordinates, ticket pricing, and ratings.</li>
            <li>Firebase Integration: Uses Firebase Firestore to store and manage user trip data and Firebase Authentication for user sign-in with Google OAuth.</li>
            <li>Responsive Design: Built with TailwindCSS for a responsive and user-friendly interface across different devices.</li>
            <li>Interactive UI: Features a dynamic user interface that displays personalized travel plans, hotel options, and places to visit.</li>
        </ul>

        <h2 id="screenshots">📸 Screenshots</h2>
        <div class="center screenshot">
            <img src="https://source.unsplash.com/random?interface" alt="Screenshot 1" width="600px">
            <img src="https://source.unsplash.com/random?dashboard" alt="Screenshot 2" width="600px">
        </div>

        <h2 id="technologies">💻 Technologies</h2>
        <h3>Frontend:</h3>
        <ul class="tech-list">
            <li><strong>React:</strong> For building the user interface and handling frontend logic.</li>
            <li><strong>TailwindCSS:</strong> For styling and responsive design.</li>
            <li><strong>Axios:</strong> For making HTTP requests to external APIs.</li>
        </ul>

        <h3>Backend & Services:</h3>
        <ul class="tech-list">
            <li><strong>Google Generative AI API:</strong> For generating AI-powered travel recommendations and itineraries.</li>
            <li><strong>Google Places API:</strong> For retrieving detailed information about places, hotels, and their photos.</li>
            <li><strong>Firebase Firestore:</strong> For storing and managing user trip data.</li>
            <li><strong>Firebase Authentication:</strong> For handling user authentication via Google OAuth.</li>
        </ul>

        <h3 id="started">Prerequisites</h3>
        <ul class="prerequisites-list">
            <li>Node.js & npm</li>
            <li>Firebase Project: Set up a Firebase project and configure Firestore and Authentication. Obtain your Firebase configuration keys.</li>
            <li>Google API Keys: Obtain API keys for Google Generative AI and Google Places API.</li>
        </ul>
    </div>
</body>
</html>
