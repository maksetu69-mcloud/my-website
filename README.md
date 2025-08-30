# my-website
My first HTML site 
<html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Social News</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>SocialNews</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Trending</a>
      <a href="#">Politics</a>
      <a href="#">Tech</a>
      <a href="#">Login</a>
    </nav>
  </header>

  
    <section class="news-grid">
      <article class="news-card">
        <img src="https://via.placeholder.com/300x180" alt="News Image" />
        <h2>Breaking: Major Event in Politics</h2>
        <p>Summary of the news goes here. Short and catchy description.</p>
        <div class="tags">
          <span>#Politics</span>
          <span>#Breaking</span>
        </div>
      </article>

      <article class="news-card">
        <img src="https://via.placeholder.com/300x180" alt="News Image" />
        <h2>Tech Giants Launch New AI</h2>
        <p>New innovation is taking over the world with this release...</p>
        <div class="tags">
          <span>#Tech</span>
<span>#AI</span>
        </div>
      </article>

      <!-- More articles... -->
    </section>
  </main>

  <footer>
    <p>&copy; 2025 SocialNews. All rights reserved.</p>
  </footer>
</body>
</html>
