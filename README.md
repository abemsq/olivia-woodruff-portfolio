# Static Website: Wine Festival Schedule

Simple static website showcasing Olivia Woodruff's portfolio.

![image](https://github.com/abemsq/olivia-woodruff-portfolio/blob/master/picture.png)

## HTML
```
<!DOCTYPE html>
<html>

<head>
  <title></title>
  <link href="style.css" type="text/css" rel="stylesheet">
</head>

<body>
  <div class="header">
    <img src="https://content.codecademy.com/courses/freelance-1/unit-2/travel.jpeg" />
    <h1>Olivia Woodruff</h1>
    <p class="about-me">I am a developer specializing in HTML and CSS. I like to run, bike, and make coffee using an Aeropress.</p>
  </div>

  <h2>Projects</h2>
  <p class="title">Web Development projects</p>
  <ul>
    <li>Coffee Bruër</li>
    <li>Taco Finder</li>
    <li>CSS Selector Finder</li>
    <li>HTML Formatter</li>
  </ul>

  <p class="title">Design projects</p>
  <ul>
    <li>Yum Yum Fudge Inc.</li>
    <li>University of Marimont Dance Marathon</li>
  </ul>
  <h2>Contact</h2>
  <p>Find me on Twitter, Dribbble, and GitHub.</p>

  <h6>&copy; Copyright. All Rights Reserved.</h6>
</body>

</html>
```

## CSS

```
.header {
    background-color: CornflowerBlue;
    text-align: center;
  }
  
  .about-me {
    font-size: 20px;
    opacity: 50%;
  }
  
  .title {
    font-weight: bold;
  }
  
  h1 {
    color: Azure;
  }
  
  body {
    font-family: Georgia;
    background-image: 
  url("https://content.codecademy.com/courses/learn-css-selectors-visual-rules/hypnotize_bg.png");
  }
```
