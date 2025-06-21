<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me - Amine</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Orbitron', sans-serif;
      background: url('https://images.unsplash.com/photo-1508672019048-805c876b67e2?auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      margin: 0;
      padding: 0;
      animation: fadeInBody 2s ease;
    }
    @keyframes fadeInBody {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .container {
      max-width: 700px;
      margin: 50px auto;
      background: rgba(0, 0, 0, 0.75);
      padding: 30px;
      box-shadow: 0 0 25px rgba(0,0,0,0.7);
      border-radius: 14px;
      animation: fadeInUp 1.2s ease-in-out;
      backdrop-filter: blur(10px);
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    h1 {
      text-align: center;
      color: #00ffff;
      margin-bottom: 30px;
      text-shadow: 0 0 10px #00ffff;
    }
    ul {
      list-style: none;
      padding: 0;
      line-height: 1.8;
    }
    li {
      padding: 10px 0;
      border-bottom: 1px solid rgba(255,255,255,0.1);
      transition: all 0.3s ease;
      display: flex;
      align-items: center;
    }
    li:hover {
      background-color: rgba(255,255,255,0.05);
      padding-left: 12px;
    }
    .label {
      font-weight: bold;
      color: #90caf9;
      width: 160px;
    }
    .icon {
      margin-right: 10px;
      font-size: 1.2em;
      color: #00ffff;
    }
    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #00ffff;
      display: block;
      margin: 0 auto 20px;
      box-shadow: 0 0 15px #00ffff;
    }
    .download {
      display: block;
      text-align: center;
      margin-top: 30px;
    }
    .download a {
      text-decoration: none;
      color: #fff;
      background-color: #00ffff;
      padding: 10px 20px;
      border-radius: 30px;
      font-weight: bold;
      transition: background 0.3s ease;
      box-shadow: 0 0 15px #00ffff;
    }
    .download a:hover {
      background-color: #00cccc;
    }
  </style>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <div class="container">
    <img class="avatar" src="https://i.pinimg.com/736x/87/f9/61/87f9613122c59fdf5faeb1d6f1c0c9ab.jpg" alt="Avatar" />
    <h1>About Me</h1>
    <ul>
      <li><span class="icon"><i class="fas fa-user"></i></span><span class="label">Name:</span> Amine</li>
      <li><span class="icon"><i class="fas fa-birthday-cake"></i></span><span class="label">Age:</span> 18 y.o.</li>
      <li><span class="icon"><i class="fas fa-flag"></i></span><span class="label">Country:</span> Algeria</li>
      <li><span class="icon"><i class="fas fa-book"></i></span><span class="label">Major:</span> 1st yr ST (Sci & Tech)</li>
      <li><span class="icon"><i class="fas fa-bolt"></i></span><span class="label">Future Field:</span> Electrical Eng.</li>
      <li><span class="icon"><i class="fas fa-ruler-vertical"></i></span><span class="label">Height:</span> 183 cm</li>
      <li><span class="icon"><i class="fas fa-weight"></i></span><span class="label">Weight:</span> 86 kg</li>
      <li><span class="icon"><i class="fas fa-tools"></i></span><span class="label">Skills:</span> Black belt Karate, Coding (beg.), Time Mgmt, Ambition</li>
      <li><span class="icon"><i class="fas fa-heart"></i></span><span class="label">Hobbies:</span> Anime, Movies, Tech</li>
      <li><span class="icon"><i class="fas fa-language"></i></span><span class="label">Languages:</span> Arabic, French, English</li>
    </ul>
    <div class="download">
      <a href="#">📄 Download CV</a>
    </div>
  </div>
</body>
</html>
