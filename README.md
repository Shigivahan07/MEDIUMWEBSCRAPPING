<!DOCTYPE html>
<html>
<head>
</head>
<body>
  <h1>Article Scraper</h1>
  <p>This project is a simple React application that allows users to search for articles by a specific tag. It scrapes articles from a backend service and displays the results in a neat and responsive layout.</p>

  <h2>Features</h2>
  <ul>
    <li>Search for articles by tag</li>
    <li>Display a list of articles with title, author, date, and link</li>
    <li>Handle loading and error states</li>
    <li>Responsive design using Bootstrap and custom CSS</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li>Node.js</li>
    <li>Express</li>
    <li>Puppeteer</li>
    <li>React</li>
    <li>Bootstrap</li>
    <li>Custom CSS</li>
  </ul>

  <h2>Getting Started</h2>
  <p>These instructions will help you set up and run the project on your local machine for development and testing purposes.</p>

  <h3>Prerequisites</h3>
  <ul>
    <li>Node.js and npm installed on your machine</li>
  </ul>

  <h3>Installation</h3>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/Shigivahan07/mediumwebscrapping.git</code></pre>
    </li>
    <li>Install the dependencies:
      <pre><code>npm install</code></pre>
    </li>
  </ol>

  <h3>Running the Application</h3>
    <ol>
    <li>Start the backend server:
      <pre><code>node server.js</code></pre>
    </li>
    <li>Start the frontend development server:
      <pre><code>npm start</code></pre>
    </li>
    <li>Open your browser and go to:
      <pre><code>http://localhost:3000</code></pre>
    </li>
  </ol>

<h2>Project Structure</h2>
    <h3>Backend</h3>
  <ul>
    <li><code>scraper.js</code> - Script to scrape articles.</li>
    <li><code>server.js</code> - Express server to handle API requests.</li>
  </ul>

  <h3>Frontend</h3>
  <ul>
    <li><code>src/</code>
      <ul>
        <li><code>components/</code>
          <ul>
            <li><code>Article.js</code> - Component to display individual article details.</li>
            <li><code>ArticleList.js</code> - Component to display a list of articles.</li>
          </ul>
        </li>
        <li><code>hooks/</code>
          <ul>
            <li><code>useFetchArticles.js</code> - Custom hook to fetch articles from the backend.</li>
          </ul>
        </li>
        <li><code>pages/</code>
          <ul>
            <li><code>HomePage.js</code> - Main page component.</li>
          </ul>
        </li>
        <li><code>services/</code>
          <ul>
            <li><code>api.js</code> - Service to handle API requests.</li>
          </ul>
        </li>
        <li><code>styles/</code>
          <ul>
            <li><code>App.css</code> - Global styles for the application.</li>
            <li><code>Article.css</code> - Styles for article components.</li>
            <li><code>form.css</code> - Styles for the search form.</li>
            <li><code>input.css</code> - Styles for the input fields.</li>
          </ul>
        </li>
        <li><code>App.js</code> - Main application component.</li>
        <li><code>index.js</code> - Entry point of the application.</li>
        <li><code>index.css</code> - Global CSS for the application.</li>
      </ul>
    </li>
  </ul>

  <h2>Custom Hooks</h2>
  <ul>
    <li><code>useFetchArticles.js</code> - Custom hook to handle fetching articles based on a given tag. This hook manages the state of the articles, loading, and errors.</li>
  </ul>

  <h2>Styling</h2>
  <p>Bootstrap is used for responsive design and some basic styling. Custom CSS is used for additional styling and form control animations.</p>

  <h2>Usage</h2>
  <ol>
    <li>Enter a topic in the search input field.</li>
    <li>Click the "Scrape Articles" button.</li>
    <li>The application will display a loading message while fetching articles.</li>
    <li>If no articles are found, it will display "No articles found".</li>
    <li>If articles are found, they will be displayed in a list.</li>
  </ol>
  </pre>

</body>
</html>
