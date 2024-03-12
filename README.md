# AI-Data-Science-Portfolio

## Navigation Bar

- [Statistics](#)
- [Linear Algebra](#)
- [Machine Learning](#)
- [Deep Learning](#)
- Search Bar: `<input type="text" placeholder="Search...">`

## Hero Section

- Video Background: `<video autoplay loop muted> <source src="placeholder-video.mp4" type="video/mp4"> </video>`
- Dynamic Tagline:
  - "Learn at your own pace"
  - "Discover new passions"
  - "Expand your horizons"
- Get Started Button: `<button>Get Started</button>`

## Featured Courses

### Course Card

- Image: `<img src="placeholder-image.jpg" alt="Course Image">`
- Title: `<h3>Course Title</h3>`
- Author: `<p>Author Name</p>`
- Description: `<p>Course description goes here...</p>`

## Learning Paths

- Description: Take a short quiz to determine your data science interests.
- Start Quiz Button: `<button id="start-quiz">Start Quiz</button>`

## Success Stories

### Testimonial

- Text: `<p>Testimonial text goes here...</p>`
- Client Name: `<p>- Client Name</p>`

## Footer

- Blog: [Blog](#)
- FAQ: [FAQ](#)
- Privacy Policy: [Privacy Policy](#)
- Contact Us Button: `<button id="contact-us">Contact Us</button>`

## JavaScript

```javascript
const tagline = document.getElementById('tagline');
const taglines = ['Learn at your own pace', 'Discover new passions', 'Expand your horizons'];
let currentIndex = 0;

function rotateTagline() {
  currentIndex = (currentIndex + 1) % taglines.length;
  tagline.textContent = taglines[currentIndex];
}

setInterval(rotateTagline, 3000);

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

nav {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav li {
  margin-right: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

#hero {
  height: 100vh;
  position: relative;
  overflow: hidden;
}

#hero video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

#hero .content {
  position: relative;
  z-index: 1;
  text-align: center;
  color: #fff;
  padding: 20px;
}

section {
  padding: 50px;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}
