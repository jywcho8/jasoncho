/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', sans-serif;
  line-height: 1.6;
  background-color: #ffffff;
  color: #333;
}

/* Navigation Bar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background-color: #ffffff;
  
}

.navbar .logo img {
  height: 40px;
}

.navbar .nav-links a {
  margin-left: 20px;
  text-decoration: none;
  color: #333;
  font-weight: regular;
}

/* Hero Section */
.hero {
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 60px 20px;
  background-color: #fffff;
}

.hero-text {
  max-width: 500px;
  font-weight: bold;
}

.hero-text h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.hero-buttons button {
  font-size: 0.8rem;
  margin-right: 10px;
  padding: 10px 30px;
  border: 1.5px solid #333;
  background-color: white;
  cursor: pointer;
  font-weight: medium;
}

.hero-buttons button:hover {
  background-color: #333;
  color: #fff;
}

.hero-image img {
  width: 400px;
  border-radius: 10px;
}

/* Experience Section */
.experience {
  display: flex;
  justify-content: space-around;
  padding: 60px 20px;
  background-color: #F0F5F2;
}

.experience-item {
  max-width: 275px;
  text-align: left;
}

/* Projects Section */
.projects {
  padding: 60px 20px;
  text-align: center;
  background-color: #fffff;
}

.project-list {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}

.project {
  max-width: 300px;
  text-align: left;
}

.project button {
  margin-top: 10px;
  padding: 10px 20px;
  border: 1.5px solid #333;
  background-color: white;
  cursor: pointer;
  font-weight: bold;
}

.project button:hover {
  background-color: #333;
  color: #fff;
}

/* Blogs Section */
.blogs {
  padding: 60px 20px;
  text-align: center;
  background-color: #F0F5F2;
}

.blog-list {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin-top: 20px;
}

.blog {
  padding: 20px;
  border: 1px solid #ccc;
  text-align: center;
  background-color: #f8f9fa;
}

/* Contact Section */
.contact {
  padding: 60px 20px;
  text-align: center;
  background-color: #f8f9fa;
}

.contact button {
  margin-top: 20px;
  color: white;
  padding: 10px 50px;
  border: 1.5px solid #333;
  background-color: black;
  cursor: pointer;
  font-weight: regular;
}

.contact button:hover {
  background-color: white;
  color: black;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero, .experience, .project-list, .blog-list {
    flex-direction: column;
    align-items: center;
  }

  .blog-list {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .blog-list {
    grid-template-columns: 1fr;
  }
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jason Cho | Sports Analyst</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar">
    <div class="logo">
      <img src="logo%201.png" alt="Jason Cho Logo">
    </div>
    <div class="nav-links">
      <a href="#about">About Me</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h1>I'M JASON CHO,<br> A SPORTS ANALYST<br>WHO LOVES GOLF.</h1>
      <div class="hero-buttons">
        <button onclick="location.href='#about'">About Me</button>
        <button onclick="location.href='#contact'">Contact</button>
      </div>
    </div>
    <div class="hero-image">
      <img src="IMG_2793%203%201.png" alt="Golf Course">
    </div>
  </section>

  <!-- About/Experience Section -->
  <section class="experience" id="about">
    <div class="experience-item">
      <h3>Data Analytics for<br> Business Impact </h3>
      <p><br>Analyzed fan demographics across multiple golf tournaments, identified parents with young children as a key ticket buyer group. <br><br>Applied this insight to the Aramco Team Series by partnering with Gen.G to launch a family activation zone that drove early sell-outs and increased on-site engagement.</p>
    </div>
    <div class="experience-item">
      <h3>Hands-on Experience <br>in Sports Business</h3>
      <p><br>Led operations for international golf tournaments, city-scale charity events, and nationwide F&B operations, combining filed management expertise with a customer-centric approach.</p>
    </div>
    <div class="experience-item">
      <h3>Advanced Education in <br>Sports Analytics</h3>
      <p>Pursuing a Master's in Sports Administration (Sports Analytics) at Northwestern University.<br><br>Building expertise in data analysis, marketing strategy, and consumer insights using Python, R, and visualization tools.</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project">
        <h3>F1 World</h3>
        <p>A personal webpage that tracks and summarizes Formula 1 race results, driver standings, and key news throughout the 2025 season.</p>
        <button>Discover More</button>
      </div>
      <div class="project">
        <h3>tbd</h3>
        <p>golf golf golf golf haha golf golf golf golf haha golf golf golf golf haha golf golf golf golf haha golf</p>
        <button>Discover More</button>
      </div>
    </div>
  </section>

  <!-- Blog Section -->
  <section class="blogs">
    <h2>Blogs</h2>
    <div class="blog-list">
      <div class="blog">This is a template Figma file, turned into code using Anima.</div>
      <div class="blog">This is a template Figma file, turned into code using Anima.</div>
      <div class="blog">This is a template Figma file, turned into code using Anima.</div>
      <div class="blog">This is a template Figma file, turned into code using Anima.</div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <h2>Let's work together!</h2>
    <button>Contact</button>
  </section>
</body>
</html>
