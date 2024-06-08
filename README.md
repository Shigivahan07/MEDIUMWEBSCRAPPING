<!DOCTYPE html>
<html>
<head>
  <title>Article Scraper</title>
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
      <pre><code>git clone https://github.com/yourusername/articlescraper.git</code></pre>
    </li>
    <li>Navigate to the project directory:
      <pre><code>cd articlescraper</code></pre>
    </li>
    <li>Install the dependencies:
      <pre><code>npm install</code></pre>
    </li>
  </ol>

  <h3>Running the Application</h3>
  <ol>
    <li>Start the development server:
      <pre><code>npm start</code></pre>
    </li>
    <li>Open your browser and go to:
      <pre><code>http://localhost:3000</code></pre>
    </li>
  </ol>

  <h2>Project Structure</h2>
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
        <li><code>styles/</code>
          <ul>
            <li><code>App.css</code> - Global styles for the application.</li>
            <li><code>form.css</code> - Styles for the search form.</li>
          </ul>
        </li>
        <li><code>App.js</code> - Main application component.</li>
        <li><code>index.js</code> - Entry point of the application.</li>
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

  <h2>License</h2>

  <p>Feel free to modify and enhance the application as per your requirements. Contributions are welcome!</p>
</body>
</html>
