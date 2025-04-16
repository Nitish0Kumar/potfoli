<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Kumar | Portfolio</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Font Awesome CDN -->
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
    integrity="sha512-dOQk6vSrmYWeEkldN8z81mldGgf5Vkl2tkPlFSuEPR3gKVk59L9Y8I+ISiN7P/qXRa6TYPv9HDB0zsu6tL2Ldw=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />

  <!-- Custom Styles -->
  <style> 


    body {
      background-image: url('newBack.png');
      background-size: contain;
      perspective: 1000px;
    }

    @keyframes bgMove {
      0%, 100% {
        background-position: top left;
      }
      50% {
        background-position: bottom right;
      }
    }

    .neon-hover:hover {
      color: #00f0ff;
      text-shadow: 0 0 5px #00f0ff, 0 0 10px #00f0ff, 0 0 20px #00f0ff;
      transition: all 0.3s ease-in-out;
    }

    .neon-box {
      box-shadow: 0 0 10px #00f0ff, 0 0 20px #00f0ff, 0 0 30px #00f0ff;
    }

   
  </style>
</head>
<body class="text-white">

  <!-- Navbar -->
  <header class="fixed top-0 left-0 w-full bg-black bg-opacity-80 z-50 shadow-lg">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-cyan-400">Nitish Kumar</h1>
      <nav class="space-x-6 text-lg">
        <a href="#home" class="neon-hover">Home</a>
        <a href="#about" class="neon-hover">About</a>
        <a href="#skills" class="neon-hover">Skills</a>
        <a href="#education" class="neon-hover">Education</a>
        <a href="#experience" class="neon-hover">Experience</a>
        <a href="#contact" class="neon-hover">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="min-h-screen flex flex-col md:flex-row items-center justify-between pt-32 px-8 container mx-auto">
    <!-- Text -->
    <div class="md:w-1/2 text-center md:text-left">
      <h1 class="text-5xl font-bold text-gray-100">Hi There,</h1>
      <h2 class="text-5xl font-bold mt-2">I'm <span class="text-orange-500">Nitish Kumar</span></h2>
      <p class="text-2xl text-gray-400 mt-4">I Am Into <span class="text-red-500">Web Development</span></p>
      <a href="#about">
        <button class="mt-8 px-6 py-2 bg-cyan-500 hover:bg-cyan-600 text-white rounded-xl neon-hover">
          About Me
        </button>
      </a>
      <!-- Social Media Icons -->
      <div class="flex justify-center md:justify-start space-x-6 mt-8 text-2xl">
        <a href="https://www.linkedin.com/in/nitish-kumar-67555a305" class="text-blue-500 neon-hover" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/Nitish0Kumar" class="text-white neon-hover" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://x.com/nitishk61371811" class="text-blue-400 neon-hover" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="#" class="text-cyan-400 neon-hover" target="_blank"><i class="fab fa-telegram"></i></a>
        <a href="https://www.instagram.com/nitish_d_luffy" class="text-pink-600 neon-hover" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="#" class="text-gray-400 neon-hover" target="_blank"><i class="fab fa-dev"></i></a>
      </div>
    </div>

    <!-- Profile Image -->
    <div class="md:w-1/2 mt-10 md:mt-0">
      <img src="IMG_6554 copy.jpeg" alt="Nitish Kumar" class="rounded-full w-72 h-72 object-cover mx-auto neon-box" />
    </div>
  </section>
</body>
</html>

<!--About section --> 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About | Nitish Kumar</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .neon {
      text-shadow: 0 0 10px #0ff, 0 0 20px #0ff, 0 0 40px #0ff;
    }

    .fade-in {
      animation: fadeIn 1.5s ease-in-out forwards;
      opacity: 0;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
      
    }

    .glow-btn {
      box-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .glow-btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #0ff, 0 0 40px #0ff;
    }
  </style>
</head>
<body class="bg-gray-950 text-white font-sans">



  <!-- About Section -->
  <section class="min-h-screen flex flex-col justify-center items-center px-6 pt-24 text-center fade-in">
    <img src="IMG_6554 copy.jpeg" alt="Nitish Kumar" class="w-48 h-48 rounded-full border-4 border-cyan-400 shadow-xl mb-6" />
    
    <h2 class="text-4xl md:text-5xl font-bold neon mb-4">About Me</h2>

    <p class="max-w-2xl text-lg text-gray-400 mb-6">
      I'm Nitish Kumar, a Computer Science student with a passion for building modern websites and mobile apps that are both visually stunning and highly functional. I love working with new technologies and constantly exploring ways to push creative boundaries. Whether it’s design, frontend magic, or backend logic — I enjoy bringing ideas to life!
    </p>

    <a href="Nitish_Kumar_CV.pdf" download class="bg-cyan-500 glow-btn text-white px-6 py-3 rounded-full font-semibold transition-all">
      🚀 Download CV
    </a>
  </section>


</body>
</html>

<!--Skill Section-->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Skills | Nitish Kumar</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    .neon {
      text-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .fade-in {
      animation: fadeIn 1.5s ease-in-out forwards;
      opacity: 0;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    .glow-box {
      border: 2px solid #0ff;
      box-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
      color: solid whitesmoke ;
    }

    /* SVG lines animation */
    .animated-line {
      stroke-dasharray: 200;
      stroke-dashoffset: 200;
      animation: draw 2s ease-out forwards;
    }

    @keyframes draw {
      to {
        stroke-dashoffset: 0;
      }
    }
  </style>
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

<body class="bg-gray-950 text-white font-sans">


  <!-- Skills Section -->
  <section class="min-h-screen pt-32 px-6 fade-in">
    <h2 class="text-4xl md:text-5xl font-bold text-center neon mb-12">Skills</h2>

    <!-- SVG Connector Lines -->
    <svg width="100%" height="120" class="mb-10 hidden md:block">
      <line x1="25%" y1="20" x2="15%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>
      <line x1="25%" y1="20" x2="25%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>
      <line x1="25%" y1="20" x2="35%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>

      <line x1="75%" y1="20" x2="65%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>
      <line x1="75%" y1="20" x2="75%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>
      <line x1="75%" y1="20" x2="85%" y2="100" stroke="#0ff" stroke-width="2" class="animated-line"/>
    </svg>

    <!-- Skill Categories -->
    <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto">

      <!-- Frontend -->
       
      <div class="glow-box p-6 rounded-xl text-center">
        <h3 class="text-2xl font-semibold text-cyan-400 mb-4 neon">Frontend</h3>
        <div class="flex justify-center gap-6 text-4xl text-white">
          <i class="fab fa-html5 hover:text-orange-500 transition"></i>
          <i class="fab fa-css3-alt hover:text-blue-500 transition"></i>
          <i class="fas fa-bolt hover:text-cyan-400 transition"></i> <!-- Tailwind -->
          <i class="fab fa-js hover:text-yellow-400 transition"></i>
        </div>
        <p class="text-sm mt-3 text-gray-400">HTML, CSS, Tailwind, JavaScript</p>
      </div>

      <!-- Backend -->
      <div class="glow-box p-6 rounded-xl text-center">
        <h3 class="text-2xl font-semibold text-cyan-400 mb-4 neon">Backend</h3>
        <div class="flex justify-center gap-6 text-4xl text-white">
          <i class="fab fa-node-js hover:text-green-400 transition"></i>
          <i class="fas fa-database hover:text-indigo-400 transition"></i>
          <i class="fas fa-fire hover:text-red-500 transition"></i> <!-- Firebase -->
        </div>
        <p class="text-sm mt-3 text-gray-400">Node.js, Firebase, SQL</p>
      </div>

      <!-- Tools -->
      <div class="glow-box p-6 rounded-xl text-center">
        <h3 class="text-2xl font-semibold text-cyan-400 mb-4 neon">Tools & Platforms</h3>
        <div class="flex justify-center gap-6 text-4xl text-white">
          <i class="fab fa-android hover:text-green-500 transition"></i>
          <i class="fab fa-github hover:text-gray-300 transition"></i>
          <i class="fas fa-terminal hover:text-pink-400 transition"></i>
        </div>
        <p class="text-sm mt-3 text-gray-400">Android, GitHub, CLI</p>
      </div>

    </div>
  </section>

</body>
</html>

 <!-- Education Section -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Education | Nitish Kumar</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    .neon {
      text-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .timeline-dot {
      box-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
      background-color: #0ff;
    }

    .fade-slide {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlideUp 1s ease-out forwards;
    }

    @keyframes fadeSlideUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body class="bg-gray-950 text-white font-sans">



  <!-- Education Section -->
  <section class="pt-32 px-6 max-w-4xl mx-auto">
    <h2 class="text-4xl md:text-5xl font-bold text-center neon mb-12">Education</h2>

    <div class="relative border-l-2 border-cyan-400 ml-6">

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">B.Tech in Computer Science & Engineering</h3>
        <p class="text-sm text-gray-400">Narula Institute of Technology • 2022 – 2026 (Ongoing)</p>
        <p class="mt-2 text-gray-300">Currently pursuing my B.Tech with a focus on full-stack development, app design, and AI/ML fundamentals.</p>
      </div>

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide" style="animation-delay: 0.3s">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">Higher Secondary (Class 12)</h3>
        <p class="text-sm text-gray-400">CBSE • 2020 – 2022</p>
        <p class="mt-2 text-gray-300">Completed my Class 12 with Science stream, gaining a strong foundation in Physics, Chemistry, and Mathematics.</p>
      </div>

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide" style="animation-delay: 0.6s">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">Secondary Education (Class 10)</h3>
        <p class="text-sm text-gray-400">CBSE • 2018 – 2020</p>
        <p class="mt-2 text-gray-300">Built strong logical and problem-solving skills. Developed a passion for computers and began experimenting with web design.</p>
      </div>

    </div>
  </section>

</body>
</html>

 <!-- Experience Section -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Experience | Nitish Kumar</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    .neon {
      text-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .timeline-dot {
      box-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
      background-color: #0ff;
    }

    .fade-slide {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlideUp 1s ease-out forwards;
    }

    @keyframes fadeSlideUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body class="bg-gray-950 text-white font-sans">


  <!-- Experience Section -->
  <section class="pt-32 px-6 max-w-4xl mx-auto">
    <h2 class="text-4xl md:text-5xl font-bold text-center neon mb-12">Experience</h2>

    <div class="relative border-l-2 border-cyan-400 ml-6">

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">Frontend Developer Intern</h3>
        <p class="text-sm text-gray-400">XYZ Tech Solutions • Jan 2025 – Mar 2025</p>
        <p class="mt-2 text-gray-300">Worked on modern UI designs using React & TailwindCSS, built responsive dashboards, and enhanced user interactivity.</p>
      </div>

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide" style="animation-delay: 0.3s">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">Android App Developer</h3>
        <p class="text-sm text-gray-400">Freelance • Aug 2024 – Nov 2024</p>
        <p class="mt-2 text-gray-300">Created mobile apps using Jetpack Compose & Firebase, including user authentication, maps, and clean UI components.</p>
      </div>

      <!-- Timeline Item -->
      <div class="mb-12 pl-6 fade-slide" style="animation-delay: 0.6s">
        <div class="absolute left-0 w-4 h-4 rounded-full timeline-dot -ml-2 mt-1"></div>
        <h3 class="text-xl font-bold text-cyan-400 neon">Web Designer (College Projects)</h3>
        <p class="text-sm text-gray-400">Narula Institute of Technology • 2023 – Present</p>
        <p class="mt-2 text-gray-300">Designed creative, responsive project websites with animations, custom JS effects, and clean dark-mode themes.</p>
      </div>

    </div>
  </section>

</body>
</html>

<!--contect me -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact | Nitish Kumar</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    .neon {
      text-shadow: 0 0 10px #0ff, 0 0 20px #0ff;
    }

    .form-input {
      background-color: transparent;
      border: 1px solid #0ff;
      color: white;
      padding: 0.75rem;
      border-radius: 0.5rem;
      outline: none;
      transition: border-color 0.3s ease;
    }

    .form-input:focus {
      border-color: #00ffff;
      box-shadow: 0 0 10px #0ff;
    }

    .send-btn {
      background-color: #0ff;
      color: #000;
      font-weight: bold;
      padding: 0.75rem 2rem;
      border-radius: 0.5rem;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .send-btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #0ff;
    }

    .fade-slide {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeSlideUp 1s ease-out forwards;
    }

    @keyframes fadeSlideUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body class="bg-gray-950 text-white font-sans">


  <!-- Contact Section -->
  <section class="pt-32 px-6 max-w-4xl mx-auto text-center">
    <h2 class="text-4xl md:text-5xl font-bold neon mb-6">Get in Touch</h2>
    <p class="text-gray-400 mb-12">Have a project or just want to say hi? Drop me a message!</p>

    <form action="https://formspree.io/f/your-form-id" method="POST" class="space-y-6 fade-slide">
      <input type="text" name="name" placeholder="Your Name" class="form-input w-full" required />
      <input type="email" name="email" placeholder="Your Email" class="form-input w-full" required />
      <textarea name="message" placeholder="Your Message" rows="5" class="form-input w-full" required></textarea>
      <button type="submit" class="send-btn">Send Message 🚀</button>
    </form>

    <!-- Social Links -->
    <div class="flex justify-center gap-6 mt-12 text-cyan-400 text-2xl fade-slide" style="animation-delay: 0.3s">
      <a href="https://github.com/yourusername" target="_blank" class="hover:text-white transition"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/yourusername" target="_blank" class="hover:text-white transition"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:your@email.com" class="hover:text-white transition"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-6 mt-16 bg-gray-900 text-gray-400">
    © 2025 Nitish Kumar. All rights reserved.
  </footer>

</body>

</html>
