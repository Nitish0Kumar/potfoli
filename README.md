<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nitish Kumar | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes glitter {
      0% { background-position: -200% 0; }
      100% { background-position: 200% 0; }
    }

    
    body {
      background-image: radial-gradient(circle, rgba(255,255,255,0.05) 1px, transparent 1px);
      background-size: 10px 10px;
      animation: sparkle 4s linear infinite;
    }

    @keyframes sparkle {
      0%, 100% { background-position: 0 0; }
      50% { background-position: 5px 5px; }
    }

    html {
      scroll-behavior: smooth;
    }

    /* Neon shadow for image and boxes */
    .neon-box {
      box-shadow: 0 0 10px #00f0ff, 0 0 20px #00f0ff, 0 0 30px #00f0ff;
    }

    /* Neon hover effect for links and buttons */
    .neon-hover:hover {
      text-shadow: 0 0 5px #00f0ff, 0 0 10px #00f0ff, 0 0 20px #00f0ff;
      color: #00f0ff !important;
      transition: all 0.3s ease-in-out;
    }
  </style>
</head>
<body class="glitter-bg bg-gradient-to-br from-gray-900 via-black to-gray-900 text-white font-sans">
  <!-- Navbar -->
  <header class="fixed top-0 w-full bg-black bg-opacity-80 z-50 shadow-md">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-cyan-400">Nitish Kumar</h1>
      <nav class="space-x-6">
        <a href="#home" class="text-white hover:text-cyan-400 neon-hover">Home</a>
        <a href="#about" class="text-white hover:text-cyan-400 neon-hover">About</a>
        <a href="#skills" class="text-white hover:text-cyan-400 neon-hover">Skills</a>
        <a href="#education" class="text-white hover:text-cyan-400 neon-hover">Education</a>
        <a href="#experience" class="text-white hover:text-cyan-400 neon-hover">Experience</a>
        <a href="#contact" class="text-white hover:text-cyan-400 neon-hover">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main id="home" class="container mx-auto flex flex-col md:flex-row items-center justify-between py-32 px-6">
    <div class="md:w-1/2">
      <h1 class="text-5xl font-bold text-gray-800">Hi There,</h1>
      <h2 class="text-5xl font-bold text-gray-800">I'm <span class="text-orange-500">Nitish Kumar</span></h2>
      <p class="text-2xl text-gray-600 mt-4">
        I Am Into <span class="text-red-500">Web Development</span>
      </p>
      <button id="scroll-btn" class="mt-8 px-6 py-2 bg-cyan-500 hover:bg-cyan-600 text-white rounded-xl neon-hover">
        About Me
      </button>
      <div class="flex space-x-4 mt-8">
        <a class="text-blue-600 text-2xl social-icon neon-hover" href="https://www.linkedin.com/in/nitish-kumar-67555a305">
          <i class="fab fa-linkedin"></i>
        </a>
        <a class="text-gray-800 text-2xl social-icon neon-hover" href="https://github.com/Nitish0Kumar">
          <i class="fab fa-github"></i>
        </a>
        <a class="text-blue-400 text-2xl social-icon neon-hover" href="https://x.com/nitishk61371811">
          <i class="fab fa-twitter"></i>
        </a>
        <a class="text-blue-600 text-2xl social-icon neon-hover" href="#">
          <i class="fab fa-telegram"></i>
        </a>
        <a class="text-pink-600 text-2xl social-icon neon-hover" href="https://www.instagram.com/nitish_d_luffy">
          <i class="fab fa-instagram"></i>
        </a>
        <a class="text-gray-800 text-2xl social-icon neon-hover" href="#">
          <i class="fab fa-dev"></i>
        </a>
      </div>
    </div>
    <div class="md:w-1/2 mt-10 md:mt-0">
      <img alt="profile picture" class="rounded-full object-cover mx-auto neon-box" height="300" src="IMG_6554 copy.jpeg" width="300"/>
    </div>
  </main>

  <!-- About Section -->
  <section id="about" class="py-20 px-6 md:px-16 bg-gray-900">
    <h2 class="text-4xl font-bold text-cyan-400 mb-6 text-center">About Me</h2>
    <div class="max-w-4xl mx-auto text-center space-y-6">
      <p class="text-gray-300 text-lg">
        I'm a 2nd-year B.Tech Computer Science student at Narula Institute of Technology. Passionate about full-stack development, Android apps, and creative UI/UX design.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-gray-800 p-6 rounded-xl shadow hover:bg-cyan-600 transition-all transform hover:scale-105 neon-box">
          <h3 class="text-2xl font-semibold mb-2">Skills</h3>
          <p class="text-gray-300">From front-end to back-end, I have honed a wide range of technical skills.</p>
        </div>
        <div class="bg-gray-800 p-6 rounded-xl shadow hover:bg-cyan-600 transition-all transform hover:scale-105 neon-box">
          <h3 class="text-2xl font-semibold mb-2">Projects</h3>
          <p class="text-gray-300">Explore some of the innovative projects I've worked on.</p>
        </div>
        <div class="bg-gray-800 p-6 rounded-xl shadow hover:bg-cyan-600 transition-all transform hover:scale-105 neon-box">
          <h3 class="text-2xl font-semibold mb-2">Goals</h3>
          <p class="text-gray-300">I’m always pushing my limits and learning new technologies.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="py-20 px-6 md:px-16 bg-black">
    <h2 class="text-4xl font-bold text-cyan-400 mb-10 text-center">Skills</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center text-white">
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">HTML</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">CSS / Tailwind</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">JavaScript</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">C / C++</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">Java</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">Jetpack Compose</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">Firebase</div>
      <div class="bg-gray-800 p-6 rounded-xl shadow hover:scale-105 transition neon-box">Git & GitHub</div>
    </div>
  </section>

  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Education Section</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />
    <style>
      .neon-box {
        transition: all 0.3s ease-in-out;
      }
  
      .neon-box:hover {
        box-shadow: 0 0 20px #0ff, 0 0 30px #0ff inset;
        transform: scale(1.02);
      }
  
      /* Smooth section entry animations */
      [data-aos] {
        opacity: 0;
        transition-property: opacity, transform;
      }
    </style>
  </head>
  <body class="bg-gray-900 text-white">
  
    <!-- Education Section -->
    <section id="education" class="py-20 px-6 md:px-16">
      <h2 class="text-4xl font-bold text-cyan-400 mb-12 text-center" data-aos="fade-up">Education</h2>
      
      <div class="max-w-4xl mx-auto space-y-10">
  
        <!-- B.Tech Card -->
        <div class="bg-gradient-to-br from-gray-800 to-gray-900 p-6 rounded-2xl shadow-lg neon-box" data-aos="fade-right">
          <div class="flex items-center gap-4 mb-3">
            <svg class="w-8 h-8 text-cyan-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
              <path d="M12 14l9-5-9-5-9 5 9 5zm0 0v6"></path>
            </svg>
            <h3 class="text-2xl font-semibold">B.Tech in Computer Science</h3>
          </div>
          <p class="text-gray-300">Narula Institute of Technology, Kolkata</p>
          <p class="text-gray-400 text-sm">2022 - 2026 (Currently in 2nd Year)</p>
          <ul class="mt-2 list-disc list-inside text-gray-400 text-sm">
            <li>Core Subjects: DSA, OS, DBMS, CN</li>
            <li>Projects: Travel App, Portfolio Website,wather monitring appp</li>
            <li>Clubs: Coding Club, Tech Fest Volunteer</li>
          </ul>
        </div>
  
        <!-- Class 12 Card -->
        <div class="bg-gradient-to-br from-gray-800 to-gray-900 p-6 rounded-2xl shadow-lg neon-box" data-aos="fade-left">
          <div class="flex items-center gap-4 mb-3">
            <svg class="w-8 h-8 text-yellow-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
              <path d="M5 13l4 4L19 7"></path>
            </svg>
            <h3 class="text-2xl font-semibold">Class 12 (CBSE)</h3>
          </div>
          <p class="text-gray-300">Kendriya Vidyalaya, Patna</p>
          <p class="text-gray-400 text-sm">Graduated: 2022</p>
          <ul class="mt-2 list-disc list-inside text-gray-400 text-sm">
            <li>Subjects: Physics, Chemistry, Math, CS</li>
            <li>Percentage: 91%</li>
            <li>Participated in Science Exhibitions</li>
          </ul>
        </div>
  
      </div>
    </section>
  
    <!-- AOS Script -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init({
        duration: 1000,
        once: true
      });
    </script>
  </body>
  </html>
  

  <!-- Experience Section -->
  <section id="experience" class="py-20 px-6 md:px-16 bg-black">
    <h2 class="text-4xl font-bold text-cyan-400 mb-10 text-center">Experience</h2>
    <div class="max-w-4xl mx-auto space-y-6">
      <div class="bg-gray-800 p-6 rounded-xl shadow neon-box">
        <h3 class="text-2xl font-semibold">Android Travel App (2025)</h3>
        <p class="text-gray-300">Built with Jetpack Compose and Firebase Authentication.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow neon-box">
        <h3 class="text-2xl font-semibold">Portfolio Website</h3>
        <p class="text-gray-300">Responsive and animated using HTML, Tailwind CSS, and JavaScript.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow neon-box">
        <h3 class="text-2xl font-semibold">Video Editing Workshop</h3>
        <p class="text-gray-300">Conducted a VN app-based editing workshop focused on real use cases.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-6 md:px-16 bg-gray-900">
    <h2 class="text-4xl font-bold text-cyan-400 mb-6 text-center">Contact</h2>
    <div class="max-w-lg mx-auto">
      <p class="text-center text-gray-300 mb-6">Feel free to reach out for collaborations or inquiries.</p>
      <form class="space-y-4">
        <input type="text" placeholder="Name" class="w-full px-4 py-2 rounded-xl bg-gray-800 text-white border border-transparent focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500" />
        <input type="email" placeholder="Email" class="w-full px-4 py-2 rounded-xl bg-gray-800 text-white border border-transparent focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500" />
        <textarea placeholder="Message" rows="4" class="w-full px-4 py-2 rounded-xl bg-gray-800 text-white border border-transparent focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500"></textarea>
        <button type="submit" class="w-full px-6 py-3 bg-cyan-500 text-white rounded-xl hover:bg-cyan-600 transition">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-6 bg-black text-center text-gray-300">
    <p>© 2025 Nitish Kumar. All rights reserved.</p>
  </footer>
</body>
</html>
