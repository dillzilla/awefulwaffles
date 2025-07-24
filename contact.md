---
layout: default
title: "Location, Hours & Contact | Visit Our Retro Diner | Awefull Waffles"
description: "Visit Awefull Waffles at 123 Retro Street! Open 7 days a week, 7AM-4PM. Call (555) 123-WAFL for reservations. Free parking, wheelchair accessible, family-friendly atmosphere."
keywords: "restaurant location, hours, phone number, reservations, directions, parking, wheelchair accessible, family restaurant, contact information"
---

<!-- Contact Hero Section -->
<section class="bg-retro-orange text-white py-16">
  <div class="container mx-auto px-4 text-center">
    <h1 class="text-5xl md:text-6xl font-display font-bold retro-shadow mb-6">
      Get In Touch!
    </h1>
    <p class="text-xl md:text-2xl max-w-3xl mx-auto">
      We'd love to hear from you! Come visit us, give us a call, or drop us a line. 
      We're always here to serve you with a smile! 🧇
    </p>
  </div>
</section>

<!-- Contact Information Section -->
<section class="py-16 bg-white">
  <div class="container mx-auto px-4">
    <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
      
      <!-- Location Info -->
      <div class="bg-retro-cream p-8 rounded-lg shadow-lg border-4 border-retro-orange text-center">
        <div class="text-6xl mb-4">📍</div>
        <h3 class="text-2xl font-bold text-retro-brown mb-4">Visit Us</h3>
        <div class="space-y-2 text-gray-700">
          <p class="font-semibold">{{ site.restaurant.address }}</p>
          <p class="text-sm">Easy parking available</p>
          <p class="text-sm">Wheelchair accessible</p>
          <p class="text-sm">Family-friendly atmosphere</p>
        </div>
        <a href="https://maps.google.com/?q={{ site.restaurant.address | url_encode }}" 
           target="_blank"
           class="inline-block mt-4 bg-retro-orange text-white px-6 py-3 rounded-full font-bold hover:bg-orange-600 transition-colors duration-300">
          🗺️ Get Directions
        </a>
      </div>

      <!-- Phone Info -->
      <div class="bg-retro-cream p-8 rounded-lg shadow-lg border-4 border-retro-orange text-center">
        <div class="text-6xl mb-4">📞</div>
        <h3 class="text-2xl font-bold text-retro-brown mb-4">Call Us</h3>
        <div class="space-y-2 text-gray-700">
          <p class="font-semibold text-xl">{{ site.restaurant.phone }}</p>
          <p class="text-sm">Order takeout & delivery</p>
          <p class="text-sm">Make reservations</p>
          <p class="text-sm">Ask about catering</p>
        </div>
        <a href="tel:{{ site.restaurant.phone }}" 
           class="inline-block mt-4 bg-retro-yellow text-retro-brown px-6 py-3 rounded-full font-bold hover:bg-yellow-300 transition-colors duration-300">
          📱 Call Now
        </a>
      </div>

      <!-- Email Info -->
      <div class="bg-retro-cream p-8 rounded-lg shadow-lg border-4 border-retro-orange text-center">
        <div class="text-6xl mb-4">✉️</div>
        <h3 class="text-2xl font-bold text-retro-brown mb-4">Email Us</h3>
        <div class="space-y-2 text-gray-700">
          <p class="font-semibold">{{ site.email }}</p>
          <p class="text-sm">General inquiries</p>
          <p class="text-sm">Catering requests</p>
          <p class="text-sm">Feedback & suggestions</p>
        </div>
        <a href="mailto:{{ site.email }}" 
           class="inline-block mt-4 bg-retro-red text-white px-6 py-3 rounded-full font-bold hover:bg-red-700 transition-colors duration-300">
          📧 Send Email
        </a>
      </div>
    </div>
  </div>
</section>

<!-- Hours of Operation -->
<section class="py-16 bg-retro-cream">
  <div class="container mx-auto px-4">
    <h2 class="text-4xl font-display font-bold text-retro-brown text-center mb-12 retro-shadow">
      Hours of Operation
    </h2>
    
    <div class="max-w-2xl mx-auto">
      <div class="bg-white p-8 rounded-lg shadow-lg border-4 border-retro-orange">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
          
          <!-- Weekdays -->
          <div class="text-center">
            <h3 class="text-2xl font-bold text-retro-brown mb-4">Weekdays</h3>
            <div class="space-y-3">
              <div class="flex justify-between">
                <span class="font-semibold">Monday</span>
                <span>{{ site.restaurant.hours.monday }}</span>
              </div>
              <div class="flex justify-between">
                <span class="font-semibold">Tuesday</span>
                <span>{{ site.restaurant.hours.tuesday }}</span>
              </div>
              <div class="flex justify-between">
                <span class="font-semibold">Wednesday</span>
                <span>{{ site.restaurant.hours.wednesday }}</span>
              </div>
              <div class="flex justify-between">
                <span class="font-semibold">Thursday</span>
                <span>{{ site.restaurant.hours.thursday }}</span>
              </div>
              <div class="flex justify-between">
                <span class="font-semibold">Friday</span>
                <span>{{ site.restaurant.hours.friday }}</span>
              </div>
            </div>
          </div>

          <!-- Weekends -->
          <div class="text-center">
            <h3 class="text-2xl font-bold text-retro-brown mb-4">Weekends</h3>
            <div class="space-y-3">
              <div class="flex justify-between">
                <span class="font-semibold">Saturday</span>
                <span>{{ site.restaurant.hours.saturday }}</span>
              </div>
              <div class="flex justify-between">
                <span class="font-semibold">Sunday</span>
                <span>{{ site.restaurant.hours.sunday }}</span>
              </div>
            </div>
            <div class="mt-6 p-4 bg-retro-cream rounded-lg">
              <p class="text-sm text-gray-600">
                <strong>Note:</strong> We're closed on major holidays. 
                Please call ahead for special holiday hours.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact Form Section -->
<section class="py-16 bg-white">
  <div class="container mx-auto px-4">
    <h2 class="text-4xl font-display font-bold text-retro-brown text-center mb-12 retro-shadow">
      Send Us a Message
    </h2>
    
    <div class="max-w-3xl mx-auto">
      <div class="bg-retro-cream p-8 rounded-lg shadow-lg border-4 border-retro-orange">
        
        <!-- Contact Form -->
        <form action="#" method="POST" class="space-y-6" id="contact-form">
          
          <!-- Name and Email Row -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <label for="name" class="block text-retro-brown font-bold mb-2">Your Name *</label>
              <input type="text" id="name" name="name" required 
                     class="w-full px-4 py-3 border-2 border-retro-orange rounded-lg focus:outline-none focus:ring-2 focus:ring-retro-yellow">
            </div>
            <div>
              <label for="email" class="block text-retro-brown font-bold mb-2">Email Address *</label>
              <input type="email" id="email" name="email" required 
                     class="w-full px-4 py-3 border-2 border-retro-orange rounded-lg focus:outline-none focus:ring-2 focus:ring-retro-yellow">
            </div>
          </div>

          <!-- Phone and Subject Row -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <label for="phone" class="block text-retro-brown font-bold mb-2">Phone Number</label>
              <input type="tel" id="phone" name="phone" 
                     class="w-full px-4 py-3 border-2 border-retro-orange rounded-lg focus:outline-none focus:ring-2 focus:ring-retro-yellow">
            </div>
            <div>
              <label for="subject" class="block text-retro-brown font-bold mb-2">Subject *</label>
              <select id="subject" name="subject" required 
                      class="w-full px-4 py-3 border-2 border-retro-orange rounded-lg focus:outline-none focus:ring-2 focus:ring-retro-yellow">
                <option value="">Select a subject...</option>
                <option value="reservation">Reservation Request</option>
                <option value="catering">Catering Inquiry</option>
                <option value="feedback">Feedback</option>
                <option value="complaint">Complaint</option>
                <option value="compliment">Compliment</option>
                <option value="other">Other</option>
              </select>
            </div>
          </div>

          <!-- Message -->
          <div>
            <label for="message" class="block text-retro-brown font-bold mb-2">Message *</label>
            <textarea id="message" name="message" rows="6" required 
                      placeholder="Tell us what's on your mind! We love hearing from our customers..."
                      class="w-full px-4 py-3 border-2 border-retro-orange rounded-lg focus:outline-none focus:ring-2 focus:ring-retro-yellow resize-vertical"></textarea>
          </div>

          <!-- Preferred Contact Method -->
          <div>
            <label class="block text-retro-brown font-bold mb-2">Preferred Response Method</label>
            <div class="flex flex-wrap gap-4">
              <label class="flex items-center">
                <input type="radio" name="contact_method" value="email" checked class="mr-2">
                <span>Email</span>
              </label>
              <label class="flex items-center">
                <input type="radio" name="contact_method" value="phone" class="mr-2">
                <span>Phone Call</span>
              </label>
              <label class="flex items-center">
                <input type="radio" name="contact_method" value="text" class="mr-2">
                <span>Text Message</span>
              </label>
            </div>
          </div>

          <!-- Submit Button -->
          <div class="text-center">
            <button type="submit" 
                    class="bg-retro-orange text-white px-8 py-4 rounded-full font-bold text-lg retro-button hover:bg-orange-600 transition-colors duration-300">
              🚀 Send Message
            </button>
          </div>

          <!-- Form Note -->
          <div class="text-center text-sm text-gray-600">
            <p>* Required fields</p>
            <p>We typically respond within 24 hours during business days.</p>
          </div>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- Map Section -->
<section class="py-16 bg-retro-cream">
  <div class="container mx-auto px-4">
    <h2 class="text-4xl font-display font-bold text-retro-brown text-center mb-12 retro-shadow">
      Find Us on the Map
    </h2>
    
    <!-- Map Placeholder -->
    <div class="max-w-4xl mx-auto">
      <div class="bg-white p-4 rounded-lg shadow-lg border-4 border-retro-orange">
        <div class="bg-gray-200 h-96 rounded-lg flex items-center justify-center relative overflow-hidden">
          <!-- Placeholder for map - replace with actual Google Maps embed or similar -->
          <div class="text-center">
            <div class="text-6xl mb-4">🗺️</div>
            <h3 class="text-2xl font-bold text-gray-600 mb-2">Interactive Map</h3>
            <p class="text-gray-500 mb-4">{{ site.restaurant.address }}</p>
            <a href="https://maps.google.com/?q={{ site.restaurant.address | url_encode }}" 
               target="_blank"
               class="inline-block bg-retro-orange text-white px-6 py-3 rounded-full font-bold hover:bg-orange-600 transition-colors duration-300">
              🧭 Open in Google Maps
            </a>
          </div>
          
          <!-- Decorative map-like elements -->
          <div class="absolute top-4 left-4 w-8 h-8 bg-retro-red rounded-full flex items-center justify-center text-white font-bold">
            📍
          </div>
          <div class="absolute bottom-4 right-4 text-xs text-gray-400">
            © Map Data Providers
          </div>
        </div>
      </div>
    </div>

    <!-- Location Details -->
    <div class="max-w-2xl mx-auto mt-8 text-center">
      <div class="bg-white p-6 rounded-lg shadow-lg border-l-4 border-retro-orange">
        <h3 class="text-xl font-bold text-retro-brown mb-4">Getting Here</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-sm text-gray-700">
          <div>
            <strong>🚗 By Car:</strong><br>
            Free parking available in our lot and on surrounding streets.
          </div>
          <div>
            <strong>🚌 Public Transit:</strong><br>
            Bus routes 12, 45, and 78 stop within 2 blocks of our location.
          </div>
          <div>
            <strong>🚶 Walking:</strong><br>
            Located in the heart of downtown, easy walking distance from hotels.
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Social Media & Follow Us -->
<section class="py-16 bg-retro-brown text-white">
  <div class="container mx-auto px-4 text-center">
    <h2 class="text-4xl font-display font-bold mb-8 retro-shadow">
      Follow Our Awefull Adventures
    </h2>
    <p class="text-xl mb-8 max-w-2xl mx-auto">
      Stay connected with us on social media for the latest updates, special offers, 
      and behind-the-scenes peeks at our delicious creations!
    </p>
    
    <!-- Social Media Links -->
    <div class="flex justify-center space-x-6 mb-8">
      <a href="https://facebook.com/awefullwaffles" 
         target="_blank"
         class="bg-retro-yellow text-retro-brown px-6 py-4 rounded-full font-bold hover:bg-yellow-300 transition-colors duration-300">
        📘 Facebook
      </a>
      <a href="https://instagram.com/awefullwaffles" 
         target="_blank"
         class="bg-retro-yellow text-retro-brown px-6 py-4 rounded-full font-bold hover:bg-yellow-300 transition-colors duration-300">
        📷 Instagram
      </a>
      <a href="https://twitter.com/awefullwaffles" 
         target="_blank"
         class="bg-retro-yellow text-retro-brown px-6 py-4 rounded-full font-bold hover:bg-yellow-300 transition-colors duration-300">
        🐦 Twitter
      </a>
    </div>

    <!-- Newsletter Signup -->
    <div class="max-w-md mx-auto">
      <h3 class="text-xl font-bold mb-4">Join Our Newsletter</h3>
      <div class="flex">
        <input type="email" 
               placeholder="Your email address"
               class="flex-1 px-4 py-3 rounded-l-full text-gray-800 focus:outline-none">
        <button class="bg-retro-orange px-6 py-3 rounded-r-full font-bold hover:bg-orange-600 transition-colors duration-300">
          Subscribe
        </button>
      </div>
      <p class="text-sm text-retro-cream mt-2">Get special offers and waffle news delivered to your inbox!</p>
    </div>
  </div>
</section>

<!-- JavaScript for form handling -->
<script>
// Simple form validation and submission handler
document.getElementById('contact-form').addEventListener('submit', function(e) {
  e.preventDefault();
  
  // Get form data
  const formData = new FormData(this);
  const name = formData.get('name');
  const email = formData.get('email');
  const message = formData.get('message');
  
  // Basic validation
  if (!name || !email || !message) {
    alert('Please fill in all required fields.');
    return;
  }
  
  // Simulate form submission
  alert('Thank you for your message! We\'ll get back to you soon. In the meantime, why not check out our menu?');
  
  // Reset form
  this.reset();
});

// Add smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    const target = document.querySelector(this.getAttribute('href'));
    if (target) {
      target.scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      });
    }
  });
});
</script>