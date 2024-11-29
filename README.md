<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carlo's GitHub Profile</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Flex:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto Flex', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    h1 {
      text-align: center;
      color: #1a73e8;
      margin-top: 20px;
    }
    .content {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .accordion {
      border: 1px solid #ddd;
      border-radius: 8px;
      margin-bottom: 10px;
      overflow: hidden;
    }
    .accordion-header {
      background-color: #1a73e8;
      color: #fff;
      cursor: pointer;
      padding: 15px;
      text-align: left;
      font-weight: bold;
      font-size: 16px;
      transition: background-color 0.3s;
    }
    .accordion-header:hover {
      background-color: #1459b3;
    }
    .accordion-content {
      display: none;
      padding: 15px;
      background-color: #f9f9f9;
      border-top: 1px solid #ddd;
    }
    .accordion-content p {
      margin: 0;
    }
    .icons img {
      margin: 5px;
      vertical-align: middle;
    }
    a {
      color: #1a73e8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>Welcome to My GitHub Profile</h1>

    <!-- Information Section -->
    <div class="accordion">
      <div class="accordion-header">Information</div>
      <div class="accordion-content">
        <p>
          Hi, my name is Carlo. I'm 22 years old and I'm from Italy. 
          <img src="https://cdn-icons-png.flaticon.com/512/5582/5582641.png" alt="Italy Flag" width="30">
        </p>
        <p>
          I'm a Computer Science student at the University of Catania. 
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Catania-Stemma.svg/1200px-Catania-Stemma.svg.png" alt="Catania Logo" width="30">
        </p>
        <p>
          I'm passionate about programming and always looking for new challenges. 
          <img src="https://cdn-icons-png.flaticon.com/512/4838/4838645.png" alt="Challenge Icon" width="30">
        </p>
        <p>
          Currently, I'm working on a project called <strong>Ilarity Network</strong>. 
          <a href="https://github.com/IlarityMC" target="_blank">Visit the Repository</a>
          <img src="https://media.discordapp.net/attachments/990325355485229107/1090036318647631992/image.png" alt="Minecraft Icon" width="30">
        </p>
      </div>
    </div>

    <!-- Statistics Section -->
    <div class="accordion">
      <div class="accordion-header">Statistics</div>
      <div class="accordion-content">
        <div class="statistics">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=mathsanalysis" alt="GitHub Streak" style="display: block; margin: 10px auto;">
          <img src="https://github-readme-stats.vercel.app/api?username=mathsanalysis&count_private=true&show_icons=true&theme=prussian" alt="GitHub Stats" style="display: block; margin: 10px auto;">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mathsanalysis&hide_progress=false" alt="Top Languages" style="display: block; margin: 10px auto;">
        </div>
      </div>
    </div>

    <!-- Skills Section -->
    <div class="accordion">
      <div class="accordion-header">Skills</div>
      <div class="accordion-content">
        <p><strong>Main Language:</strong></p>
        <div class="icons">
          <a href="https://www.java.com" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="40">
          </a>
        </div>
        <p><strong>Additional Knowledge:</strong></p>
        <div class="icons">
          <a href="https://developer.android.com" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android" width="40">
          </a>
          <a href="https://www.arduino.cc/" target="_blank">
            <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="40">
          </a>
          <a href="https://www.gnu.org/software/bash/" target="_blank">
            <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash" width="40">
          </a>
          <a href="https://www.cprogramming.com/" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40">
          </a>
          <a href="https://www.w3schools.com/cpp/" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40">
          </a>
        </div>
      </div>
    </div>
  </div>

  <script>
    const accordions = document.querySelectorAll('.accordion-header');
    accordions.forEach(header => {
      header.addEventListener('click', () => {
        const content = header.nextElementSibling;
        content.style.display = content.style.display === 'block' ? 'none' : 'block';
      });
    });
  </script>
</body>
</html>
