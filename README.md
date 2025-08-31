<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Syed Abdul Muiz - Developer</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

  /* Reset & basics */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #667eea, #764ba2);
    color: #fff;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px;
  }

  .container {
    background: rgba(255, 255, 255, 0.1);
    border-radius: 20px;
    padding: 40px;
    max-width: 700px;
    text-align: center;
    box-shadow: 0 8px 30px rgba(0,0,0,0.3);
  }

  h1 {
    font-size: 3.5rem;
    margin-bottom: 0.3em;
    text-transform: uppercase;
    letter-spacing: 4px;
    text-shadow: 2px 2px 8px rgba(0,0,0,0.4);
  }

  .subtitle {
    font-size: 1.3rem;
    font-weight: 600;
    margin-bottom: 1em;
    color: #ffdd59;
    letter-spacing: 2px;
    text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
  }

  .skills {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-bottom: 2em;
  }

  .skill {
    background: rgba(255, 255, 255, 0.15);
    padding: 12px 25px;
    border-radius: 50px;
    font-weight: 600;
    font-size: 1.1rem;
    color: #fff;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
    transition: background 0.3s ease;
    cursor: default;
  }
  .skill:hover {
    background: #ffdd59;
    color: #764ba2;
    box-shadow: 0 0 15px #ffdd59;
  }

  .description {
    font-size: 1.1rem;
    line-height: 1.6;
    margin-bottom: 2.5em;
    color: #e0e0e0;
    text-shadow: 1px 1px 5px rgba(0,0,0,0.2);
  }

  .footer {
    margin-top: 2em;
  }

  /* Audio Player Styling */
  audio {
    outline: none;
    border-radius: 12px;
    width: 100%;
    max-width: 400px;
    box-shadow: 0 4px 20px rgba(255, 221, 89, 0.6);
    cursor: pointer;
  }

  /* Animate fade in */
  .container {
    animation: fadeIn 1.5s ease forwards;
    opacity: 0;
  }

  @keyframes fadeIn {
    to {
      opacity: 1;
    }
  }
</style>
</head>
<body>

<div class="container">
  <h1>Syed Abdul Muiz</h1>
  <div class="subtitle">Coder | Developer | Problem Solver</div>

  <div class="skills">
    <div class="skill">Java</div>
    <div class="skill">C</div>
    <div class="skill">C++</div>
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
  </div>

  <p class="description">
    Passionate programmer specializing in Java, C, and C++ with a growing interest in web technologies like HTML, CSS, and JavaScript. 
    Always eager to learn, create, and contribute to meaningful projects.
  </p>

  <div class="footer">
    <audio controls>
      <source src="https://cdn.pixabay.com/download/audio/2023/03/24/audio_d3c39aa98f.mp3?filename=levitating-11652.mp3" type="audio/mpeg" />
      Your browser does not support the audio element.
    </audio>
  </div>
</div>

</body>
</html>
