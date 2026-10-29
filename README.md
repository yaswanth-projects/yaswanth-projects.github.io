
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="The personal website and portfolio of Yaswanth Reddy.">
  <title>Yaswanth Reddy | Personal Portfolio</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0; font-family: Arial, sans-serif;
      background: #0b1020; color: #f5f7ff;
      line-height: 1.7;
    }
    main { max-width: 850px; margin: auto; padding: 24px; }
    .hero {
      text-align: center; padding: 55px 18px;
      background: linear-gradient(140deg, #18294a, #17152d);
      border-radius: 24px; margin-top: 18px;
    }
    .avatar {
      width: 130px; height: 130px; border-radius: 50%;
      object-fit: cover; border: 3px solid #8b9cff;
    }
    h1 { font-size: clamp(30px, 7vw, 48px); margin-bottom: 4px; }
    h2 { color: #aab8ff; }
    .muted { color: #c3c9dc; }
    section {
      background: #141b2e; padding: 22px;
      border-radius: 18px; margin-top: 20px;
    }
    a { color: #aab8ff; }
    .button {
      display: inline-block; padding: 10px 18px;
      border-radius: 24px; background: #6578ed;
      color: white; text-decoration: none; margin: 5px;
    }
    footer { text-align: center; padding: 25px; color: #aeb6ca; }
  </style>
</head>
<body>
  <main>
    <header class="hero">
      <img class="avatar" src="profile.jpg" alt="Yaswanth Reddy">
      <h1>Yaswanth Reddy</h1>
      <p class="muted">Student · Creator · Aspiring Developer</p>
      <p>Welcome to my personal space on the internet.</p>
      <a class="button" href="#about">About Me</a>
      <a class="button" href="#contact">Connect</a>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>I'm a final-year B.Sc. Electronics student
      interested in technology, creativity and learning new skills.</p>
    </section>

    <section>
      <h2>My Interests</h2>
      <p>Photography · Video Editing · Technology · Projects</p>
    </section>

    <section>
      <h2>My Projects</h2>
      <p>Embedded Systems and electronics projects.</p>
      <p class="muted">More projects coming soon.</p>
    </section>

    <section>
      <h2>My Photos</h2>
      <p>Add your favourite photos here as your portfolio grows.</p>
      <img src="photo1.jpg" alt="My photo"
        style="width:100%;max-width:320px;border-radius:14px">
    </section>

    <section id="contact">
      <h2>Connect With Me</h2>
      <a class="button"
        href="https://www.instagram.com/YOUR_INSTAGRAM_USERNAME/">
        Instagram
      </a>
    </section>

    <footer>© 2026 Yaswanth Reddy · Personal Website</footer>
  </main>
</body>
</html>
