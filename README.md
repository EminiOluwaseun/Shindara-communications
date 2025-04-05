<!DOCTYPE html>
<html>
<head>
  <title>Shindara Communications</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="font-roboto bg-gray-100">
  <!-- Navbar -->
  <nav class="bg-blue-600 p-4">
    <div class="container mx-auto flex justify-between items-center">
      <a class="text-white text-2xl font-bold" href="#">
        Shindara Communications
      </a>

      <!-- Mobile Menu Button -->
      <button id="menu-btn" class="text-white md:hidden">
        <i class="fas fa-bars text-2xl"></i>
      </button>

      <!-- Nav Links -->
      <ul id="nav-links" class="hidden md:flex space-x-4">
        <li><a class="text-white hover:text-gray-300" href="#">Home</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">Products</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">About Us</a></li>
        <li><a class="text-white hover:text-gray-300" href="#">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-white py-20">
    <div class="container mx-auto flex flex-col md:flex-row items-center">
      <div class="md:w-1/2">
        <h1 class="text-4xl font-bold mb-4">Welcome to Shindara Communications</h1>
        <p class="text-gray-700 mb-4">
          Your one-stop shop for phone accessories, home appliances, teddy bears, and toys.
        </p>
        <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Shop Now</a>
      </div>
      <div class="md:w-1/2 mt-8 md:mt-0">
        <img src="https://storage.googleapis.com/a1aa/image/gkig0w6Hn5yo4cVVfixr-6HiAsypkHRoFEquXqPjtws.jpg" alt="A variety of phone accessories, home appliances, teddy bears, and toys displayed attractively" width="600" height="400"/>
      </div>
    </div>
  </section>

  <!-- Products Section -->
  <section class="py-20">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">Our Products</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Product Cards (same structure as before) -->
        <div class="bg-white p-4 rounded shadow">
          <img class="mb-4" src="https://storage.googleapis.com/a1aa/image/jdTHEz7NVrAw0JuXZY88wVXEjXuT_bOrzmvtbPCfm1U.jpg" alt="Phone accessories" width="300" height="300"/>
          <h3 class="text-xl font-bold mb-2">Phone Accessories</h3>
          <p class="text-gray-700 mb-4">High-quality accessories for all your phone needs.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Shop Now</a>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <img class="mb-4" src="https://storage.googleapis.com/a1aa/image/5vJXha3EsJluyTHV0H1YyTeBI7WI21Tg7GQrmYzF2Ug.jpg" alt="Home appliances" width="300" height="300"/>
          <h3 class="text-xl font-bold mb-2">Home Appliances</h3>
          <p class="text-gray-700 mb-4">Top-notch appliances to make your home life easier.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Shop Now</a>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <img class="mb-4" src="https://storage.googleapis.com/a1aa/image/BQNia_xEnoxxaubWHskpR5OzAi53bXm8g-LeFbJKq54.jpg" alt="Teddy bears" width="300" height="300"/>
          <h3 class="text-xl font-bold mb-2">Teddy Bears</h3>
          <p class="text-gray-700 mb-4">Soft and cuddly teddy bears for all ages.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Shop Now</a>
        </div>
        <div class="bg-white p-4 rounded shadow">
          <img class="mb-4" src="https://storage.googleapis.com/a1aa/image/z2meMcqxBWMdJ9LcewufRWYuE7gAFlnxLdmijaLA76U.jpg" alt="Toys" width="300" height="300"/>
          <h3 class="text-xl font-bold mb-2">Toys</h3>
          <p class="text-gray-700 mb-4">Fun and educational toys for children of all ages.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Shop Now</a>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section class="bg-white py-20">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">About Us</h2>
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2">
          <img src="https://storage.googleapis.com/a1aa/image/UxCVMFdwS6fbGd0-9NNe51JkV-2B8xBPjRXNw_PHhXM.jpg" alt="Team of Shindara Communications" width="600" height="400"/>
        </div>
        <div class="md:w-1/2 md:pl-10">
          <p class="text-gray-700 mb-4">
            Shindara Communications is dedicated to providing high-quality products and exceptional customer service. We offer a wide range of phone accessories, home appliances, teddy bears, and toys to meet all your needs.
          </p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded" href="#">Learn More</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="py-20">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-10">Contact Us</h2>
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2">
          <img src="https://storage.googleapis.com/a1aa/image/7A4c2qRFidH7fquIYb1S040hQZ4Lyud3VPD1fyun4PU.jpg" alt="Contact illustration" width="600" height="400"/>
        </div>
        <div class="md:w-1/2 md:pl-10">
          <form id="contact-form" class="bg-white p-6 rounded shadow">
            <div class="mb-4">
              <label for="name" class="block text-gray-700">Name</label>
              <input type="text" id="name" class="w-full px-4 py-2 border rounded" placeholder="Your Name" />
            </div>
            <div class="mb-4">
              <label for="email" class="block text-gray-700">Email</label>
              <input type="email" id="email" class="w-full px-4 py-2 border rounded" placeholder="Your Email" />
            </div>
            <div class="mb-4">
              <label for="message" class="block text-gray-700">Message</label>
              <textarea id="message" class="w-full px-4 py-2 border rounded" placeholder="Your Message"></textarea>
            </div>
            <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded">Send Message</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 py-4">
    <div class="container mx-auto text-center text-white">
      <p>© 2023 Shindara Communications. All rights reserved.</p>
    </div>
  </footer>

  <!-- Scripts -->
  <script>
    // Mobile menu toggle
    const menuBtn = document.getElementById("menu-btn");
    const navLinks = document.getElementById("nav-links");

    menuBtn.addEventListener("click", () => {
      navLinks.classList.toggle("hidden");
      navLinks.classList.toggle("flex");
      navLinks.classList.toggle("flex-col");
      navLinks.classList.toggle("absolute");
      navLinks.classList.toggle("top-16");
      navLinks.classList.toggle("right-4");
      navLinks.classList.toggle("bg-blue-600");
      navLinks.classList.toggle("p-4");
      navLinks.classList.toggle("rounded");
      navLinks.classList.toggle("space-y-2");
    });

    // Form validation
    document.getElementById("contact-form").addEventListener("submit", function (e) {
      e.preventDefault();
      const name = document.getElementById("name").value.trim();
      const email = document.getElementById("email").value.trim();
      const message = document.getElementById("message").value.trim();

      if (!name || !email || !message) {
        alert("Please fill in all fields.");
        return;
      }

      alert("Thanks for reaching out! We'll get back to you soon.");
      this.reset();
    });
  </script>
</body>
</html>
<style>
  html {
    scroll-behavior: smooth;
  }
</style>
<a class="text-white hover:text-gray-300 font-semibold" href="#">Home</a>
<!-- Add hamburger menu button -->
<button class="text-white md:hidden">
  <i class="fas fa-bars"></i>
</button>
<script>
  document.querySelector("form").addEventListener("submit", function (e) {
    e.preventDefault();
    alert("Thanks for reaching out! We'll get back to you soon.");
  });
</script>
