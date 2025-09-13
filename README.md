<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Baconboy08 - Reverse Engineering & Programming</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: white;
    }
    
    .profile-container {
      max-width: 900px;
      margin: 40px auto;
      padding: 30px;
      background-image: url('https://raw.githubusercontent.com/TheBaconboy08/TheBaconboy08/main/aurora-bg.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      border-radius: 20px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.6);
      position: relative;
      overflow: hidden;
      color: white;
      text-align: center;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7));
      z-index: 1;
    }

    .content {
      position: relative;
      z-index: 2;
      padding: 20px;
    }

    h1 {
      font-size: 2.8em;
      margin-top: 0;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.8);
    }

    p.subtitle {
      font-size: 1.4em;
      margin-bottom: 30px;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
    }

    .section {
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 12px;
      margin: 20px 0;
      text-align: left;
      border-left: 4px solid #4fc3f7;
    }

    .section h3 {
      margin-top: 0;
      color: #4fc3f7;
      font-size: 1.3em;
    }

    .section ul {
      list-style-type: none;
      padding-left: 0;
    }

    .section li {
      margin: 10px 0;
      padding-left: 20px;
      position: relative;
    }

    .section li:before {
      content: "•";
      color: #4fc3f7;
      position: absolute;
      left: 0;
    }

    .pronouns {
      font-size: 1.1em;
      background: rgba(0,0,0,0.6);
      padding: 12px;
      border-radius: 8px;
      display: inline-block;
      margin: 20px 0;
    }

    .views {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="profile-container">
    <div class="overlay"></div>
    <div class="content">
      <h1>Hello, I'm Baconboy08 👋</h1>
      <p class="subtitle">🔍 Reverse Engineering & Programming Enthusiast</p>

      <div class="section">
        <h3>🔭 Current Focus</h3>
        <ul>
          <li><strong>Reverse Engineering:</strong> Binary analysis, protocol dissecting</li>
          <li><strong>Programming:</strong> Low-level systems programming and security tools development</li>
        </ul>
      </div>

      <div class="section">
        <h3>🌱 Currently Learning</h3>
        <ul>
          <li>Advanced x86/x64 Assembly</li>
          <li>Windows Internals & API Hooking</li>
          <li>Firmware Analysis Techniques</li>
          <li>Modern C++ for Systems Programming</li>
        </ul>
      </div>

      <div class="pronouns">
        <strong>😄 Pronouns:</strong> He/Him
      </div>

      <div class="views">
        <img src="https://komarev.com/ghpvc/?username=TheBaconboy08&style=flat-square&color=4fc3f7" alt="Profile Views" />
      </div>
    </div>
  </div>
</body>
</html>
