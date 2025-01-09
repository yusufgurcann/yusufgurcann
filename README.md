<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yusuf's GitHub Profile</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f4f8;
      color: #333;
      text-align: center;
    }
    h1 {
      color: #4CAF50;
      font-size: 3rem;
      margin-top: 20px;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    }
    h3 {
      color: #666;
      font-size: 1.5rem;
    }
    h2 {
      color: #4CAF50;
      font-size: 2rem;
      margin-top: 30px;
    }
    .social-links img {
      margin: 10px;
      transition: transform 0.3s ease;
    }
    .social-links img:hover {
      transform: scale(1.1);
    }
    .tools img {
      margin: 10px;
      transition: transform 0.3s ease;
    }
    .tools img:hover {
      transform: rotate(15deg) scale(1.1);
    }
    .intro {
      font-size: 1.1rem;
      color: #555;
      line-height: 1.8;
      padding: 20px;
    }
    .container {
      max-width: 1200px;
      margin: auto;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hi 👋, I'm Yusuf</h1>
    <h3>Junior Developer | Passionate About Coding</h3>

    <div class="intro">
      <p>Welcome to my GitHub profile! I'm a passionate developer with a love for building mobile apps and web solutions. I'm currently working with Flutter and Firebase, and constantly learning new technologies!</p>
    </div>

    <h2>Connect with me:</h2>
    <div class="social-links">
      <a href="https://www.linkedin.com/in/yusuf-g%C3%BCrcan-563b4523a/" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="40" />
      </a>
      <a href="https://instagram.com/yusufgurcan_" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="40" width="40" />
      </a>
      <a href="https://x.com/yusufgurcann" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b7/X_logo.jpg" alt="X" height="40" width="40"/>
      </a>
    </div>

    <h2>Languages and Tools:</h2>
    <div class="tools">
      <a href="https://developer.apple.com/swift/" target="_blank">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="Swift" width="40" height="40"/>
      </a>
      <a href="https://kotlinlang.org" target="_blank">
        <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="Kotlin" width="40" height="40"/>
      </a>
      <a href="https://flutter.dev" target="_blank">
        <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter" width="40" height="40"/>
      </a>
      <a href="https://firebase.google.com/" target="_blank">
        <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" width="40" height="40"/>
      </a>
    </div>

    <h2>Design Tools:</h2>
    <div class="tools">
      <a href="https://www.figma.com/" target="_blank">
        <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40"/>
      </a>
    </div>
  </div>

  <script>
    const socialLinks = document.querySelectorAll(".social-links a");
    socialLinks.forEach(link => {
      link.addEventListener("mouseover", () => {
        link.querySelector("img").style.transform = "scale(1.2)";
      });
      link.addEventListener("mouseout", () => {
        link.querySelector("img").style.transform = "scale(1)";
      });
    });
  </script>

</body>
</html>
