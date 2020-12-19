<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>

    <meta charset="utf-8">
    <!--Create a link for the default.css file-->
    <link rel="stylesheet" href="default.css">

    <link id="theme-style" rel="stylesheet" href="">

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Russo+One&display=swap" rel="stylesheet">

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&family=Russo+One&display=swap" rel="stylesheet">

    <title>Ankit Bisht</title>
  </head>
  <body>

    <!--Create a section for the h1 tag-->
    <section class="s1">
      <div class="main-container">

        <!--Create a wrapper around h1 to form a grid and work on centering it-->
        <div class="greeting-wrapper">
          <h1>Hi, I'm Ankit Bisht </h1>
        </div>

        <!--Create wrapper for the nav, left-column, right-cloumn -->
        <div class="intro-wrapper">
          <div class="nav-wrapper">
            <div class="dots-wrapper">
              <!--create three div for the three dots, set diff id for each dot-->
              <div class="browser-dots" id="dot-1"></div>
              <div class="browser-dots" id="dot-2"></div>
              <div class="browser-dots" id="dot-3"></div>
            </div>
            <ul id="navigation">
              <li>

                <a href="#">Contact</a>
              </li>
            </ul>
          </div>
          <div class="left-column">
            <img id="profile_pic" src="images/ankit.jpg" alt="">
            <h5 style="text-align:center; line-height: 0;">Personalize Theme</h5>
            <div id="theme-options-wrapper">
              <div data-mode="light" id="light-mode" class="theme-dot"></div>
              <div data-mode="blue" id="blue-mode" class="theme-dot"></div>
              <div data-mode="green" id="green-mode" class="theme-dot"></div>
              <div data-mode="purple" id="purple-mode" class="theme-dot"></div>

            </div>
            <p id="settings-note">*Theme setting will be saved for<br> your next visit.</p>
          </div>
          <div class="right-column">
            <div id="preview-shadow">
            <div id="preview">
              <div id="corner-tl" class="corner"></div>
              <div id="corner-tr" class="corner"></div>

              <h3>What I Do</h3>
              <p>Work with Java and Python to create
                Web/Machine Learning applications .</p>
                <div id="corner-br" class="corner"></div>
                <div id="corner-bl" class="corner"></div>
            </div>
          </div>
          </div>
        </div>

        <!--<p>This is a sentence</p>
        <a href="#">Link</a>-->
      </div>
    </section>

    <section class="s2">
      <div class="main-container">
        <div class="about-wrapper">
          <div class="about-me">
            <h4>More About Me</h4>
            <p>I like to work on new projects mainly focused on
            Machine Learning and Web Development.
            </p>
            <p>Coding and Debugging are my favorite part. I can
              speak a bit of Japanese and am interested in Japanese culture .
            </p>

          <hr>
          <h4>TOP EXPERTISE</h4>
          <p>Fullstack developer with primary focus on React and
            Flask:<a target="_blank" href="resume ankit python.pdf">Download Resume</a>
          </p>

          <div id="skills">
            <ul>
              <li>Python</li>
              <li>Flask</li>
              <li>JavaScript</li>
              <li>React</li>
              <li>SQL</li>
            </ul>

            <ul>
              <li>OpenCV</li>
              <li>Tensorflow</li>
              <li>GCP</li>
              <li>Heroku</li>
              <li>HTML/CSS</li>
            </ul>
          </div>
          </div>

          <div class="social-links">
            <img id="social_image" src="images/linkiden.png" alt="FollowMe">
            <h3>Find me on Linkiden</h3>
            <a target="_blank" href="https:www.linkedin.com/in/ankit-bisht-4442b4186/">Linkiden:@ankitbisht</a>
          </div>

        </div>
      </div>
    </section>

    <section class="s1">
      <div class="main-container">
        <h3 style="text-align: center;">Some of my past projects</h3>

          <div class="post-wrapper">

          <div>
            <div class="post">
              <img class="thumbnail" src="images/blog.jpg" alt="post_image">
              <div class="post-preview">
                <h6 class="post-title">Blogspot</h6>
                <p class="post-intro">Created blog website using flask.
                   Check out my daily updates on my blog. </p>
                <a href="post.html">Read More</a>
              </div>
            </div>
        </div>

          <div>
            <div class="post">
              <img class="thumbnail" src="images/fb.jpg" alt="post_image">
              <div class="post-preview">
                <h6 class="post-title">FB-Clone</h6>
                <p class="post-intro">Facebook clone with React.
                Try it out and feedback is much appreciated.</p>

                <a href="#">Read More</a>
              </div>
            </div>
          </div>

          <div>
            <div class="post">
              <img class="thumbnail" src="images/nlp.png" alt="post_image">
              <div class="post-preview">
                <h6 class="post-title">Sentiment Analysis</h6>
                <p class="post-intro">Sentiment analysis of Imbd movie reviews to judge
                if review is positive or negative.</p>

                <a target="_blank" href="https://github.com/41AnkitBisht/imgroot.git">Read More</a>
              </div>
            </div>
        </div>

        </div>
      </div>
    </section>

    <section class="s2">
      <div class="main-container">
        <h3 style="text-align:center;" >Get In Touch</h3>
        <form id="contact-form">
          <label>Name</label>
          <input type="text" name="name" class="input-field">

          <label>Subject</label>
          <input type="text" name="subject" class="input-field">

          <label>Email</label>
          <input type="text" name="text" class="input-field">

          <label>Message</label>
          <textarea name="message" class="input-field" rows="8" cols="80"></textarea>

          <input id="submit-btn" type="submit" value="Send">
        </form>
      </div>
    </section>

    <script type="text/javascript" src="script.js"></script>

  </body>
</html>
