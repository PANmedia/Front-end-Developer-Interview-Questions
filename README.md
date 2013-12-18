#Pan Front-end Interview Questions

## <a name='toc'>Table of Contents</a>

  1. [General Questions](#general)
  1. [Graphic Design & UX](#graphic)
  1. [HTML Questions](#html)
  1. [Email Questions](#email)
  1. [CSS Questions](#css)


####[[⬆]](#toc) <a name='general'>General Questions:</a>

* What's the coolest thing you've ever coded, what are you most proud of?
* What did you learn yesterday/this week?
* Briefly describe what "Semantic HTML" means.
* Briefly describe DRY development practices.
* Name 3 ways to decrease page load. (perceived or actual load time)


####[[⬆]](#toc) <a name='graphic'>Graphic Design & User Experience/a>

* What does "User Experience Design" mean to you? 
* How would you explain the *benefits* of a user-centred design approach to a project manager/client who is unfamiliar with it?
* What are some visual design principles that you would try to follow when designing web pages?
* Explain the difference between lossy and lossless image compression
* Briefly outline your workflow for web-optimising the following image:

![Optimise](https://raw.github.com/PANmedia/Front-end-Developer-Interview-Questions/master/Lenna.png)


####[[⬆]](#toc) <a name='html'>HTML5</a>

The following HTML5 is not quite valid. Circle the issues that make it invalid.

```html
<head>
  <meta charset="utf-8" />
  <title>Home</title>
</head>

<body>
  <ul>
    <li><a href="/" id="home-selected">Home</a>
    <li><a href="/product" id="product-info">Product Info</a>
    <li><a href="/about" id="about-us">About Us</a>

    <img src="/images/its-a-big-logo.png">
  </li>

  <form action="/stockist" class="new_stockist" id="new_stockist">
    <label for="stockist_name">Full Name</label>
    <input id="stockist_name" name="stockist[name]"
      size="30" type="name">

    <label for="stockist_phone">Phone</label>
    <input id="stockist_phone" name="stockist[phone]"
      size="30" type="phone">

    <label for="stockist_email">Email Address</label>
    <input id="stockist_email" name="stockist[email]"
      size="30" type="email">
  </form>

  <p>According to <i>PANmedia</i>, <blockquote>The importance of
  <div class="fat-looking">adhering to web standards</div>
  cannot be stressed enough</blockquote></div></p>
</body>
```

####[[⬆]](#toc) <a name='email'>Email</a>

* Briefly outline the biggest differences between writing HTML/CSS for a web page and writing HTML/CSS for an Email template


####[[⬆]](#toc) <a name='css'>CSS Questions:</a>

* Briefly describe:
  * What a "reset" CSS file does and how it's useful.
  * Floats and how they work.
  * CSS sprites, and how you would implement them on a page or site.
  * How you would implement a web design that uses non-standard fonts?
* Identify some css properties that are useful in modern browsers that aren't supported in some common feature-constrained browsers (eg ie8)
* Have you ever used a grid system, and if so, what do you prefer and why?
* What does "Responsive" web design mean to you?
  * Have you used or implemented media queries or mobile specific layouts/CSS? If so, what is your preferred approach?
* What are some of the "gotchas" for writing efficient CSS? (Bonus points - what are some common CSS techniques for increasing render performance?)
* Are you familiar with any of the following CSS preprocessors: SASS, Compass, Bourbon, Stylus, LESS? 
  * If so, describe what you like and dislike about the CSS preprocessors you have used. 
* Using CSS properties alone, recreate this button:

![Button](https://raw.github.com/PANmedia/Front-end-Developer-Interview-Questions/master/css-button.png)
