<!DOCTYPE html>
<html lang="kn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jnapaka Media</title>
  <!-- Tailwind CSS CDN for styling -->
  <link
    href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
    rel="stylesheet"
  />
  <!-- Kannada font from Google Fonts -->
  <link
    href="https://fonts.googleapis.com/css2?family=Noto+Sans+Kannada&display=swap"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Noto Sans Kannada', sans-serif;
    }
    /* Primary brand colors */
    .brand-blue {
      color: #1D4ED8;
    }
    .brand-orange {
      color: #F97316;
    }
    .bg-brand-blue {
      background-color: #1D4ED8;
    }
    .bg-brand-orange {
      background-color: #F97316;
    }
  </style>
</head>
<body class="bg-neutral-100 text-neutral-900">
  <!-- HEADER -->
  <header class="flex items-center justify-between px-8 py-6 bg-white shadow-md">
    <div class="flex items-center space-x-3">
      <!-- Logo: place logo.png in the same folder as this HTML -->
      <img src="logo.png" alt="Jnapaka Media Logo" class="w-12 h-12" />
      <h1 class="text-3xl font-extrabold brand-blue">Jnapaka Media</h1>
    </div>
    <nav class="space-x-6 text-base font-medium">
      <a href="#services" class="hover:underline brand-blue">Services</a>
      <a href="#portfolio" class="hover:underline brand-blue">Portfolio</a>
      <a href="#pricing" class="hover:underline brand-blue">Pricing</a>
      <a href="#contact" class="hover:underline brand-blue">Contact</a>
    </nav>
  </header>

  <!-- HERO SECTION -->
  <section class="text-center px-8 py-16">
    <h2 class="text-5xl font-bold mb-4 brand-blue">
      Empowering Kannada Businesses Online
    </h2>
    <p class="text-lg max-w-2xl mx-auto text-neutral-700">
      We specialize in digital marketing, website design, social media strategies, and local SEO for Kannada-speaking entrepreneurs and small businesses.
    </p>
    <a
      href="#contact"
      class="inline-block mt-8 px-6 py-3 bg-brand-orange text-white font-semibold rounded-lg shadow hover:bg-orange-600 transition"
      >Get Started</a
    >
  </section>

  <!-- SERVICES SECTION -->
  <section id="services" class="px-8 py-12 bg-white">
    <h3 class="text-3xl font-bold mb-8 text-center brand-blue">Our Services</h3>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
      <div class="bg-neutral-50 p-6 rounded-2xl shadow-sm">
        <h4 class="text-2xl font-semibold mb-2 brand-blue">Website Design</h4>
        <p class="text-neutral-700">
          Modern, mobile-friendly websites in Kannada and English.
        </p>
      </div>
      <div class="bg-neutral-50 p-6 rounded-2xl shadow-sm">
        <h4 class="text-2xl font-semibold mb-2 brand-blue">
          Social Media Marketing
        </h4>
        <p class="text-neutral-700">
          Content creation, post scheduling, and analytics.
        </p>
      </div>
      <div class="bg-neutral-50 p-6 rounded-2xl shadow-sm">
        <h4 class="text-2xl font-semibold mb-2 brand-blue">SEO & Local Search</h4>
        <p class="text-neutral-700">
          Get found on Google by Kannada-speaking customers.
        </p>
      </div>
      <div class="bg-neutral-50 p-6 rounded-2xl shadow-sm">
        <h4 class="text-2xl font-semibold mb-2 brand-blue">
          Branding & Logo Design
        </h4>
        <p class="text-neutral-700">
          Professional logos and identity kits.
        </p>
      </div>
    </div>
  </section>

  <!-- PORTFOLIO SECTION -->
  <section id="portfolio" class="px-8 py-12">
    <h3 class="text-3xl font-bold mb-8 text-center brand-blue">Our Portfolio</h3>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Replace src with your actual portfolio images -->
      <img
        src="https://via.placeholder.com/600x400?text=Project+1"
        alt="Project 1"
        class="w-full rounded-xl shadow-md"
      />
      <img
        src="https://via.placeholder.com/600x400?text=Project+2"
        alt="Project 2"
        class="w-full rounded-xl shadow-md"
      />
    </div>
  </section>

  <!-- PRICING SECTION -->
  <section id="pricing" class="px-8 py-12 bg-white">
    <h3 class="text-3xl font-bold mb-8 text-center brand-blue">Pricing</h3>
    <div class="max-w-xl mx-auto">
      <ul class="space-y-4 text-neutral-800">
        <li>
          <span class="font-semibold">Website Design (Basic):</span> ₹12,000
        </li>
        <li>
          <span class="font-semibold">Website Design (Advanced):</span> ₹20,000
        </li>
        <li>
          <span class="font-semibold">Social Media Management:</span> ₹8,000/month
        </li>
        <li>
          <span class="font-semibold">Logo & Branding:</span> ₹5,000
        </li>
        <li>
          <span class="font-semibold">SEO Package:</span> ₹7,500
        </li>
        <li>
          <span class="font-semibold"
            >Digital Marketing Plan:</span
          > ₹15,000/month
        </li>
      </ul>
      <p class="mt-6 text-center text-neutral-600">
        Discounts available for bundled services or long-term contracts.
      </p>
    </div>
  </section>

  <!-- CONTACT SECTION -->
  <section id="contact" class="px-8 py-12">
    <h3 class="text-3xl font-bold mb-6 text-center brand-blue">Contact Us</h3>
    <div class="max-w-lg mx-auto bg-neutral-50 p-8 rounded-2xl shadow-sm">
      <form action="#" method="POST" class="space-y-4">
        <input
          type="text"
          name="name"
          placeholder="ನಿಮ್ಮ ಹೆಸರು (Your Name)"
          required
          class="w-full p-3 border border-neutral-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-blue"
        />
        <input
          type="email"
          name="email"
          placeholder="ನಿಮ್ಮ ಇಮೇಲ್ (Your Email)"
          required
          class="w-full p-3 border border-neutral-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-blue"
        />
        <textarea
          name="message"
          rows="4"
          placeholder="ಸಂದೇಶ (Your Message)"
          required
          class="w-full p-3 border border-neutral-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-blue"
        ></textarea>
        <button
          type="submit"
          class="w-full py-3 bg-brand-orange text-white font-semibold rounded-lg hover:bg-orange-600 transition"
        >
          Send Message
        </button>
      </form>
      <div class="mt-6 text-neutral-700 space-y-1">
        <p>📞 Phone: +91-XXXXXXXXXX</p>
        <p>📧 Email: contact@jnapakamedia.in</p>
        <p>📍 Serving Karnataka – ಕನ್ನಡದಲ್ಲಿ ನಿಮ್ಮ ಡಿಜಿಟಲ್ ಸಂಭ್ರಮಕ್ಕಾಗಿ!</p>
      </div>
    </div>
  </section>

  <!-- WHATSAPP BUTTON -->
  <a
    href="https://wa.me/91XXXXXXXXXX"
    target="_blank"
    class="fixed bottom-6 right-6 bg-green-500 text-white p-4 rounded-full shadow-lg hover:bg-green-600 transition"
    aria-label="WhatsApp Chat"
  >
    <!-- WhatsApp Icon (SVG) -->
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="h-6 w-6"
      fill="currentColor"
      viewBox="0 0 24 24"
    >
      <path
        d="M20.52 3.48a11.95 11.95 0 00-16.9 0 11.95 11.95 0 000 16.9l-1.64 4.78a.75.75 0 00.96.96l4.78-1.64a11.95 11.95 0 0016.9-16.9zm-1.11 15.78a10.45 10.45 0 01-14.8 0 10.45 10.45 0 010-14.8 10.45 10.45 0 0114.8 0 10.45 10.45 0 010 14.8zM17.1 13.02c-.28-.14-1.64-.8-1.9-.89-.26-.08-.45-.12-.64.12s-.73.89-.9 1.07c-.17.18-.34.2-.63.07a7.12 7.12 0 01-2.1-1.3 8.13 8.13 0 01-1.5-1.84c-.16-.28 0-.43.13-.57.13-.13.28-.34.42-.51.14-.17.19-.3.28-.5.08-.17 0-.32-.02-.45-.02-.12-.64-1.54-.87-2.12-.23-.56-.47-.48-.64-.49h-.55c-.18 0-.45.07-.68.32s-.9.88-.9 2.15c0 1.27.92 2.5 1.05 2.68.12.17 1.8 2.74 4.36 3.84 2.56 1.11 2.56.74 3.02.69.45-.05 1.47-.6 1.68-1.18.2-.58.2-1.07.14-1.18-.07-.12-.25-.18-.53-.32z"
      />
    </svg>
  </a>

  <!-- FOOTER -->
  <footer class="bg-white py-6 mt-12">
    <div class="text-center text-neutral-600 text-sm">
      © <script>document.write(new Date().getFullYear())</script> Jnapaka Media. All rights reserved.
    </div>
  </footer>
</body>
</html>

Instructions:

1. Save this file as index.html.


2. Place your logo image (named logo.png) in the same folder as this HTML file.


3. Open index.html in any browser to view your standalone website.


4. Feel free to adjust the phone number (+91-XXXXXXXXXX) and email (contact@jnapakamedia.in) to your actual contact details.


5. The design uses:

Tailwind CSS (via CDN) for layout and styling.

Google’s Noto Sans Kannada for Kannada text support.

Brand colors: Blue (#1D4ED8) for headings/links and Orange (#F97316) for buttons and accents.



6. Links in the navigation (e.g., #services, #portfolio, etc.) smoothly scroll to each section on the same page.



You now have a complete, static HTML version of your Jnapaka Media website—logo included, with Kannada-friendly font, your brand colors, and text styling. Just upload this single HTML file (plus logo.png) to any static hosting (e.g. Netlify, GitHub Pages, Vercel) and you’re live!
<!-- Add this below the Pricing section in your website -->

<!-- Testimonials Section -->
<section id="testimonials" style="padding: 40px; background: #f5f5f5;">
  <h2 style="text-align: center; color: #0f172a;">What Our Clients Say</h2>
  <div style="display: flex; overflow-x: auto; gap: 20px; padding: 20px;">
    <div style="min-width: 300px; background: white; padding: 20px; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
      <p>“Jnapaka Media helped me grow my local store with Kannada SEO!”</p>
      <strong>- Ramesh, Bengaluru</strong>
    </div>
    <div style="min-width: 300px; background: white; padding: 20px; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
      <p>“Great design and quick support in Kannada and English.”</p>
      <strong>- Sneha, Hubli</strong>
    </div>
  </div>
</section>

<!-- Portfolio/Gallery -->
<section id="portfolio" style="padding: 40px;">
  <h2 style="text-align: center; color: #0f172a;">Our Work Gallery</h2>
  <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-top: 20px;">
    <img src="sample1.jpg" alt="Website Sample" style="width: 300px; border-radius: 10px;">
    <img src="sample2.jpg" alt="Logo Sample" style="width: 300px; border-radius: 10px;">
    <img src="sample3.jpg" alt="Social Media" style="width: 300px; border-radius: 10px;">
  </div>
</section>

<!-- Contact Form -->
<section id="inquiry" style="padding: 40px; background: #f8fafc;">
  <h2 style="text-align: center; color: #0f172a;">Send Us a Message</h2>
  <form action="mailto:contact@jnapakamedia.in" method="POST" enctype="text/plain" style="max-width: 500px; margin: auto; display: flex; flex-direction: column; gap: 15px;">
    <input type="text" name="name" placeholder="Your Name" required style="padding: 10px;">
    <input type="email" name="email" placeholder="Your Email" required style="padding: 10px;">
    <textarea name="message" placeholder="Your Message" rows="5" required style="padding: 10px;"></textarea>
    <button type="submit" style="padding: 10px; background-color: #fb923c; color: white; border: none;">Send</button>
  </form>
</section>
<!-- ✅ UPI Payment Button -->
<section id="payment" style="padding: 40px; background: #fff7ed; text-align: center;">
  <h2 style="font-size: 24px; color: #0f172a;">Make a Payment</h2>
  <p style="margin: 10px 0;">Scan the QR or click below to pay via UPI</p>
  <img src="https://upi-qr-code-generator.vercel.app/api/qr?upi=9019199604@fam&name=Jnapaka%20Media&amount=1500" alt="UPI QR Code" width="200" style="margin: 20px;">
  <br />
  <a href="upi://pay?pa=9019199604@fam&pn=Jnapaka%20Media&cu=INR" style="background: #10b981; color: white; padding: 10px 20px; border-radius: 8px; text-decoration: none;">Pay with UPI</a>
</section>

<!-- ✅ WhatsApp Bubble -->
<a href="https://wa.me/919019199604" target="_blank" style="position: fixed; bottom: 20px; left: 20px; z-index: 999;">
  <img src="https://img.icons8.com/color/48/000000/whatsapp--v1.png" alt="Chat on WhatsApp" width="50" height="50" />
</a>

<!-- ✅ Instagram Button (Floating) -->
<a href="https://instagram.com/your_instagram" target="_blank" style="position: fixed; bottom: 20px; left: 90px; z-index: 999;">
  <img src="https://img.icons8.com/fluency/48/instagram-new.png" alt="Instagram" width="50" height="50" />
</a>

<!-- ✅ Fake Customer Reviews Section -->
<section id="reviews" style="padding: 40px; background: #f1f5f9;">
  <h2 style="text-align: center; color: #0f172a;">What People Are Saying</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 20px;">
    <div style="background: white; padding: 20px; width: 280px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p>⭐️⭐️⭐️⭐️⭐️</p>
      <p>"Jnapaka Media made my brand look premium. I love their Kannada support!"</p>
      <strong>- Kavya, Mysuru</strong>
    </div>
    <div style="background: white; padding: 20px; width: 280px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p>⭐️⭐️⭐️⭐️⭐️</p>
      <p>"Affordable, fast service, and great logo design."</p>
      <strong>- Manju, Hassan</strong>
    </div>
    <div style="background: white; padding: 20px; width: 280px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p>⭐️⭐️⭐️⭐️</p>
      <p>"Digital marketing plan boosted my local sales by 40%!"</p>
      <strong>- Arjun, Tumakuru</strong>
    </div>
  </div>
</section>
<!-- Add this below your “Our Services” section -->

<!-- PAYMENT OPTIONS SECTION -->
<section id="payment-options" style="padding: 40px; background: #ffffff;">
  <h2 style="text-align: center; color: #0a2647; margin-bottom: 20px;">Secure Payment Options</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
    <!-- Website Design Payment Card -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 250px; text-align: center; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <h3 style="color: #0a2647; margin-bottom: 10px;">Website Design</h3>
      <p style="font-size: 1rem; margin-bottom: 15px;">₹12,000</p>
      <button onclick="window.location.href='upi://pay?pa=9019199604@fam&pn=JnapakaMedia&cu=INR&am=12000';"
              style="background: #ff6a00; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer;">
        Pay via UPI
      </button>
    </div>

    <!-- Social Media Marketing Payment Card -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 250px; text-align: center; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <h3 style="color: #0a2647; margin-bottom: 10px;">Social Media Marketing</h3>
      <p style="font-size: 1rem; margin-bottom: 15px;">₹8,000 / month</p>
      <button onclick="window.location.href='upi://pay?pa=9019199604@fam&pn=JnapakaMedia&cu=INR&am=8000';"
              style="background: #ff6a00; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer;">
        Pay via UPI
      </button>
    </div>

    <!-- Logo & Branding Payment Card -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 250px; text-align: center; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <h3 style="color: #0a2647; margin-bottom: 10px;">Logo & Branding</h3>
      <p style="font-size: 1rem; margin-bottom: 15px;">₹5,000</p>
      <button onclick="window.location.href='upi://pay?pa=9019199604@fam&pn=JnapakaMedia&cu=INR&am=5000';"
              style="background: #ff6a00; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer;">
        Pay via UPI
      </button>
    </div>

    <!-- SEO Services Payment Card -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 250px; text-align: center; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <h3 style="color: #0a2647; margin-bottom: 10px;">SEO Services</h3>
      <p style="font-size: 1rem; margin-bottom: 15px;">₹7,500</p>
      <button onclick="window.location.href='upi://pay?pa=9019199604@fam&pn=JnapakaMedia&cu=INR&am=7500';"
              style="background: #ff6a00; color: white; border: none; padding: 10px 15px; border-radius: 5px; cursor: pointer;">
        Pay via UPI
      </button>
    </div>
  </div>
</section>

<!-- WHATSAPP KEY FEATURES SECTION -->
<section id="whatsapp-features" style="padding: 40px; background: #f5f5f5;">
  <h2 style="text-align: center; color: #0a2647; margin-bottom: 20px;">Connect with Us on WhatsApp</h2>
  <div style="max-width: 800px; margin: 0 auto; line-height: 1.6; color: #333;">
    <ul style="list-style: none; padding: 0; font-size: 1rem;">
      <li style="margin-bottom: 15px;">
        <i class="fab fa-whatsapp" style="color: #25D366; margin-right: 10px;"></i>
        <strong>Instant Support:</strong> Chat with us directly for any queries or quick updates.
      </li>
      <li style="margin-bottom: 15px;">
        <i class="fab fa-whatsapp" style="color: #25D366; margin-right: 10px;"></i>
        <strong>Order Confirmation:</strong> Get real-time confirmation and status updates for your payments.
      </li>
      <li style="margin-bottom: 15px;">
        <i class="fab fa-whatsapp" style="color: #25D366; margin-right: 10px;"></i>
        <strong>Promotional Alerts:</strong> Receive exclusive offers, discounts, and tips in Kannada and English.
      </li>
      <li>
        <i class="fab fa-whatsapp" style="color: #25D366; margin-right: 10px;"></i>
        <strong>Customer Feedback:</strong> Share your thoughts after service completion and help us improve.
      </li>
    </ul>
    <div style="text-align: center; margin-top: 30px;">
      <a href="https://wa.me/919019199604" target="_blank"
         style="background: #25D366; color: white; padding: 12px 20px; border-radius: 6px; font-size: 1rem; text-decoration: none;">
        <i class="fab fa-whatsapp" style="margin-right: 8px;"></i>Chat on WhatsApp
      </a>
    </div>
  </div>
</section>

<!-- FAKE HAPPY CUSTOMER REVIEWS -->
<section id="fake-reviews" style="padding: 40px; background: #ffffff;">
  <h2 style="text-align: center; color: #0a2647; margin-bottom: 30px;">Our Happy Clients</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
    <!-- Review Card 1 -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 300px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p style="font-size: 1rem; color: #444; margin-bottom: 15px;">
        “Jnapaka Media’s team redesigned my restaurant website in Kannada—traffic doubled within a month!”
      </p>
      <strong style="color: #0a2647;">– Lakshmi, Mysuru</strong>
    </div>
    <!-- Review Card 2 -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 300px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p style="font-size: 1rem; color: #444; margin-bottom: 15px;">
        “Their WhatsApp support in Kannada was a lifesaver! Social media engagement went up 40%.”
      </p>
      <strong style="color: #0a2647;">– Ramesh, Hubballi</strong>
    </div>
    <!-- Review Card 3 -->
    <div style="background: #f1f5f9; padding: 20px; border-radius: 8px; width: 300px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
      <p style="font-size: 1rem; color: #444; margin-bottom: 15px;">
        “I paid via UPI instantly and got a confirmation message on WhatsApp—super convenient!”
      </p>
      <strong style="color: #0a2647;">– Priya, Shivamogga</strong>
    </div>
  </div>
</section>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
<section id="key-features" style="padding: 40px; background-color: #f0f9ff;">
  <h2 style="text-align: center; color: #0a2647; margin-bottom: 30px;">Why Choose Jnapaka Media?</h2>
  <div style="display: grid; grid-templa
