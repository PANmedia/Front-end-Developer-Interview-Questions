#Pan Front-end Proficiency Test

Don’t panic! This is just to give us an idea of where your strengths are. We encourage you to ask questions; we won’t give you the answers but we want to make sure you understand the questions completely.     

When you’re done, we’ll go through your answers with you and you’ll have opportunities to discuss your answers with us in more detail.     

There is no time limit but your overall time will be taken into consideration.      


####General Questions:

* What's the coolest thing you've ever coded, what are you most proud of?
* What did you learn yesterday/this week?
* Briefly describe what "Semantic HTML" means.
* Briefly describe DRY development practices.
* Name 3 ways to decrease page load. (perceived or actual load time)


####Graphic Design & User Experience

* What does "User Experience Design" mean to you? 
* How would you explain the benefits of a user-centred design approach to a project manager or client who is unfamiliar with it?
* What are some visual design principles that you would try to follow when designing web pages?
* Explain the difference between lossy and lossless image compression
* Briefly outline your workflow for web-optimising the following image:

![Optimise](https://raw.github.com/PANmedia/Front-end-Developer-Interview-Questions/master/Lenna.png)


####HTML5

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

####Email

* Briefly outline the biggest differences between writing HTML/CSS for a web page and writing HTML/CSS for an Email template


####CSS Questions:

* Briefly describe:
  * What a "reset" CSS file does and how it's useful.
  * Floats and how they work.
  * CSS sprites, and how you would implement them on a page or site.
  * How you would implement a web design that uses non-standard fonts?
* Identify some CSS properties that are useful in modern browsers but aren't supported in some common feature-constrained browsers (eg: ie8)
* Have you ever used a grid system, and if so, what do you prefer and why?
* What does "Responsive" web design mean to you?
  * Have you used or implemented media queries or mobile specific layouts/CSS? If so, briefly outline about your approach?
* What are some of the "gotchas" for writing efficient CSS? (Bonus points - what are some common CSS techniques for increasing render performance?)
* Are you familiar with any of the following CSS preprocessors: SASS, Compass, Bourbon, Stylus, LESS? 
  * If so, describe what you like and dislike about the CSS preprocessors you have used. 
* Using CSS properties alone, recreate this button:

![Button](https://raw.github.com/PANmedia/Front-end-Developer-Interview-Questions/master/css-button.png)
