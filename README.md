# Portfolio<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yash Raghuwanshi | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .fade-in-up {
      animation: fadeInUp 0.8s ease-out forwards;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-900">

  <!-- Navbar -->
  <nav class="bg-gradient-to-r from-blue-700 to-purple-700 text-white p-4 shadow-md sticky top-0 z-50">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-extrabold tracking-wide animate-pulse">Yash Raghuwanshi</h1>
      <ul class="hidden md:flex gap-6 font-semibold">
        <li><a href="#about" class="hover:text-yellow-300 transition-transform hover:scale-110">About</a></li>
        <li><a href="#achievements" class="hover:text-yellow-300 transition-transform hover:scale-110">Achievements</a></li>
        <li><a href="#skills" class="hover:text-yellow-300 transition-transform hover:scale-110">Skills</a></li>
        <li><a href="#qna" class="hover:text-yellow-300 transition-transform hover:scale-110">QNA</a></li>
        <li><a href="#contact" class="hover:text-yellow-300 transition-transform hover:scale-110">Contact</a></li>
      </ul>
    </div>
  </nav>

  <div class="flex flex-col md:flex-row">

    <!-- Sidebar -->
    <aside class="md:w-1/5 bg-gradient-to-b from-blue-100 to-purple-100 p-4 shadow-md fade-in-up">
      <div class="text-center mb-6">
        <img src="https://via.placeholder.com/120" alt="Yash Raghuwanshi" class="rounded-full mx-auto mb-2 hover:scale-110 transition-transform duration-300" />
        <p class="font-bold text-xl">Yash Raghuwanshi</p>
        <p class="text-blue-700 italic text-sm">10th Grade | Sports Captain</p>
      </div>
      <ul class="space-y-2 font-medium">
        <li><a href="#subjects" class="block hover:text-blue-800 hover:scale-105 transition-transform">Subjects</a></li>
        <li><a href="#hobbies" class="block hover:text-blue-800 hover:scale-105 transition-transform">Hobbies</a></li>
        <li><a href="#qna" class="block hover:text-blue-800 hover:scale-105 transition-transform">QNA</a></li>
        <li><a href="#contact" class="block hover:text-blue-800 hover:scale-105 transition-transform">Contact</a></li>
      </ul>
    </aside>

    <!-- Main Content -->
    <main class="md:w-4/5 p-6 space-y-10">

      <!-- Section Template -->
      <section id="about" class="p-6 bg-blue-50 rounded-xl shadow-lg transform transition-all duration-700 opacity-0" data-animate>
        <h2 class="text-4xl font-bold text-blue-900 mb-4">About Me</h2>
        <p class="text-xl leading-relaxed">
          Hello! I'm <strong class="text-purple-700">Yash Raghuwanshi</strong>, a class 10 student and <span class="text-green-600 font-semibold">Sports Captain</span> of my school.
          <br><br>
          I'm a <span class="text-orange-600 font-bold">State-level Kho Kho player</span>, Table Tennis enthusiast 🏓, love gaming 🎮, and am known for my <strong class="text-teal-600">punctuality</strong>.
        </p>
      </section>

      <section id="achievements" class="p-6 bg-pink-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-pink-700 mb-4">Achievements</h2>
        <ul class="list-disc ml-6 space-y-2 text-lg">
          <li>🏆 State-level Kho Kho Player</li>
          <li>🥇 Multiple Kho Kho Gold Medals</li>
          <li>🥋 Gold in Karate (5th Grade)</li>
          <li>🏓 Table Tennis School Champion</li>
          <li>🏅 Won Quiz Competition (Olympics Theme)</li>
        </ul>
      </section>

      <section id="skills" class="p-6 bg-purple-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-purple-700 mb-4">Skills</h2>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-4 text-lg">
          <div class="bg-yellow-200 p-4 rounded-lg shadow hover:scale-110 transition">Leadership</div>
          <div class="bg-green-200 p-4 rounded-lg shadow hover:scale-110 transition">Punctuality</div>
          <div class="bg-blue-200 p-4 rounded-lg shadow hover:scale-110 transition">Sportsmanship</div>
          <div class="bg-pink-200 p-4 rounded-lg shadow hover:scale-110 transition">Quiz & GK</div>
          <div class="bg-indigo-200 p-4 rounded-lg shadow hover:scale-110 transition">Teamwork</div>
          <div class="bg-orange-200 p-4 rounded-lg shadow hover:scale-110 transition">Gaming Strategy</div>
        </div>
      </section>

      <section id="subjects" class="p-6 bg-green-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-green-800 mb-4">Favourite Subjects</h2>
        <div class="flex flex-wrap gap-4 text-lg">
          <span class="bg-yellow-300 px-3 py-1 rounded-full hover:scale-110 transition">Social Studies</span>
          <span class="bg-red-300 px-3 py-1 rounded-full hover:scale-110 transition">Hindi</span>
          <span class="bg-blue-300 px-3 py-1 rounded-full hover:scale-110 transition">English</span>
        </div>
      </section>

      <section id="hobbies" class="p-6 bg-yellow-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-yellow-800 mb-4">My Hobbies</h2>
        <ul class="list-disc ml-6 space-y-2 text-lg">
          <li>Playing Kho Kho, TT, Karate</li>
          <li>Online Gaming</li>
          <li>Quizzes & Knowledge Games</li>
          <li>Watching Sports Tournaments</li>
        </ul>
      </section>

      <section id="qna" class="p-6 bg-indigo-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-indigo-800 mb-4">QNA</h2>
        <details class="bg-white p-4 rounded-lg hover:scale-105 transition mb-3">
          <summary class="font-semibold cursor-pointer">How do you manage so many activities?</summary>
          <p class="mt-2">By planning my time well and staying consistent with my schedule.</p>
        </details>
        <details class="bg-white p-4 rounded-lg hover:scale-105 transition mb-3">
          <summary class="font-semibold cursor-pointer">Why do you love Kho Kho?</summary>
          <p class="mt-2">It's fast, energetic, and all about strategy and teamwork!</p>
        </details>
        <details class="bg-white p-4 rounded-lg hover:scale-105 transition">
          <summary class="font-semibold cursor-pointer">Are you good in studies too?</summary>
          <p class="mt-2">Yes! I really enjoy Social Studies, Hindi, and English.</p>
        </details>
      </section>

      <section id="contact" class="p-6 bg-teal-50 rounded-xl shadow opacity-0" data-animate>
        <h2 class="text-3xl font-bold text-teal-800 mb-4">Contact Me</h2>
        <form class="space-y-4 bg-white p-6 rounded-lg shadow hover:scale-[1.02] transition">
          <div>
            <label class="block font-semibold">Name</label>
            <input type="text" placeholder="Your Name" class="w-full p-2 border rounded" />
          </div>
          <div>
            <label class="block font-semibold">Email</label>
            <input type="email" placeholder="you@example.com" class="w-full p-2 border rounded" />
          </div>
          <div>
            <label class="block font-semibold">Message</label>
            <textarea rows="4" class="w-full p-2 border rounded" placeholder="Write your message here..."></textarea>
          </div>
          <button class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700 transition">Send</button>
        </form>
      </section>

    </main>
  </div>

  <!-- Footer -->
  <footer class="bg-gradient-to-r from-gray-700 to-gray-900 text-white text-center p-4 mt-8">
    <p>&copy; 2025 Yash Raghuwanshi. All rights reserved.</p>
  </footer>

  <!-- Scroll Animation Script -->
  <script>
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('fade-in-up');
          entry.target.classList.remove('opacity-0');
          observer.unobserve(entry.target);
        }
      });
    });

    document.querySelectorAll('[data-animate]').forEach(section => {
      observer.observe(section);
    });
  </script>

</body>
</html>
