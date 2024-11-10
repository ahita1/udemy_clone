<template>
  <div class="bg-gray-100 min-h-screen">
    <!-- Header -->
    <header class="flex items-center justify-between px-6 py-2 bg-white shadow-md border-b">
      <!-- Left Section: Logo and Categories Dropdown -->
      <div class="flex items-center space-x-6">
        <!-- Logo -->
        <img src="@/assets/image.png" alt="Udemy Logo" class="w-24 h-auto" />
  
        <!-- Categories Dropdown -->
        <div class="relative group">
          <a href="#" class="text-gray-700 font-medium hover:text-black flex items-center">
            Categories
            <i class="fas fa-chevron-down ml-1 text-sm"></i>
          </a>
  
          <!-- Multi-level Dropdown Menu -->
          <div class="absolute left-0 mt-2 w-[800px] bg-white border border-gray-200 rounded-md shadow-lg hidden group-hover:flex z-10">
            <!-- Column 1: Browse Certifications -->
            <div class="p-4 border-r border-gray-200 w-1/3 group relative">
              <h4 class="font-semibold text-gray-800 mb-2">Browse Certifications</h4>
              <ul class="space-y-1 text-gray-700">
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Certification Preparation</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Development</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Business</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Finance & Accounting</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">IT & Software</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Office Productivity</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Personal Development</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Design</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Marketing</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Lifestyle</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Photography & Video</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Health & Fitness</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Music</a>
                </li>
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Teaching & Academics</a>
                </li>
              </ul>
            </div>
  
            <!-- Column 2: Popular Issuers -->
            <div class="p-4 border-r border-gray-200 w-1/3 group relative">
              <h4 class="font-semibold text-gray-800 mb-2">Popular Issuers</h4>
              <ul class="space-y-1 text-gray-700">
                <li class="relative group">
                  <a href="#" class="block hover:text-black">Amazon Web Services (AWS)</a>
                  <!-- Sub-menu for AWS Certifications -->
                  <div class="absolute left-full top-0 mt-0 ml-4 w-60 bg-white border border-gray-200 rounded-md shadow-lg hidden group-hover:block">
                    <ul class="p-4 space-y-1">
                      <li><a href="#" class="block hover:text-black">AWS Certified Solutions Architect - Associate</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Cloud Practitioner</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Developer - Associate</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified SysOps Administrator - Associate</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Solutions Architect - Professional</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified DevOps Engineer - Professional</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Security - Specialty</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Machine Learning - Specialty</a></li>
                      <li><a href="#" class="block hover:text-black">AWS Certified Advanced Networking - Specialty</a></li>
                    </ul>
                  </div>
                </li>
                <li><a href="#" class="block hover:text-black">Microsoft Certifications</a></li>
                <li><a href="#" class="block hover:text-black">Cisco Certifications</a></li>
                <li><a href="#" class="block hover:text-black">CompTIA Certifications</a></li>
                <li><a href="#" class="block hover:text-black">Project Management Institute (PMI)</a></li>
                <li><a href="#" class="block hover:text-black">Google Cloud Certifications</a></li>
                <li><a href="#" class="block hover:text-black">Six Sigma Certifications</a></li>
                <li><a href="#" class="block hover:text-black">Oracle Certifications</a></li>
              </ul>
              <h4 class="font-semibold text-gray-800 mt-4 mb-2">Popular Subjects</h4>
              <ul class="space-y-1 text-gray-700">
                <li><a href="#" class="block hover:text-black">Cloud Certification</a></li>
                <li><a href="#" class="block hover:text-black">Networking Certification</a></li>
                <li><a href="#" class="block hover:text-black">Cybersecurity Certification</a></li>
                <li><a href="#" class="block hover:text-black">Project Management Certification</a></li>
                <li><a href="#" class="block hover:text-black">DevOps Certification</a></li>
                <li><a href="#" class="block hover:text-black">Coding Certification</a></li>
                <li><a href="#" class="block hover:text-black">System Administration Certification</a></li>
                <li><a href="#" class="block hover:text-black">Artificial Intelligence Certification</a></li>
              </ul>
            </div>
  
            <!-- Column 3: Sample Subcategories (for future use) -->
            <div class="p-4 w-1/3">
              <!-- Optional: Add more categories or popular items here if needed -->
            </div>
          </div>
        </div>
      </div>
  
      <!-- Center Section: Search Bar -->
      <div class="flex-grow max-w-lg mx-4">
        <div class="relative">
          <input
            type="text"
            placeholder="Search for anything"
            class="w-full px-4 py-2 border border-gray-300 rounded-full focus:outline-none focus:ring focus:ring-purple-300"
          />
          <span class="absolute top-0 right-4 text-gray-500 flex items-center h-full">
            <i class="fas fa-search"></i>
          </span>
        </div>
      </div>
  
      <!-- Right Section: Links and Buttons -->
      <div class="flex items-center space-x-6">
        <a href="#" class="text-gray-700 font-medium hover:text-black">Udemy Business</a>
        <a href="#" class="text-gray-700 font-medium hover:text-black">Teach on Udemy</a>
        <a href="#" class="text-gray-700 hover:text-black"><i class="fas fa-shopping-cart"></i></a>
        <button class="text-gray-700 font-medium hover:text-black">Log in</button>
        <button class="px-4 py-2 bg-gray-900 text-white font-medium rounded-full hover:bg-gray-700">Sign up</button>
      </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto mt-8 px-4">
      <div class="lg:flex gap-8">
        <!-- Course Info -->
        <div class="flex-1">
          <nav class="text-sm text-gray-600">
            Design &gt; User Experience Design &gt; User Experience (UX) Design
          </nav>
          <h1 class="text-4xl font-bold my-4">UX & Web Design Master Course: Strategy, Design, Development</h1>
          <p class="text-lg mb-4">
            Learn how to apply User Experience (UX) principles to your website designs, code a variety of sites, and increase sales!
          </p>
          <div class="flex items-center space-x-2 mb-4">
            <span class="text-yellow-500 text-xl">★ 4.6</span>
            <span>(15,394 ratings)</span>
            <span>•</span>
            <span>106,300 students</span>
          </div>
          <div class="text-gray-500 mb-4">Created by <a href="#" class="text-blue-600">Joe Natoli</a></div>
          <div class="flex items-center space-x-4 text-gray-600 mb-8">
            <span>Last updated 3/2020</span>
            <span>English [Auto], French [Auto]</span>
          </div>
          <section class="bg-white rounded-lg p-6 shadow-lg mb-8">
            <h2 class="text-xl font-semibold mb-4">What you'll learn</h2>
            <ul class="space-y-2">
              <li>✓ A clear understanding of the principles and benefits of good UX and how to apply it to your website</li>
              <li>✓ The confidence to know what information should be included in your website, and how to design it to increase conversions</li>
              <li>✓ A strategy for making sure you know what people need from your website</li>
              <li>✓ The ability to code a variety of websites with HTML, CSS, WordPress, and other tools</li>
            </ul>
          </section>
          <section class="mb-8">
            <h2 class="text-xl font-semibold mb-4">Explore related topics</h2>
            <div class="flex flex-wrap gap-4">
              <span class="bg-gray-200 rounded-full py-2 px-4">User Experience (UX) Design</span>
              <span class="bg-gray-200 rounded-full py-2 px-4">Web Design</span>
              <span class="bg-gray-200 rounded-full py-2 px-4">User Experience Design</span>
              <span class="bg-gray-200 rounded-full py-2 px-4">Design</span>
            </div>
          </section>
        </div>

        <!-- Pricing Section -->
        <div class="lg:w-1/4 bg-white rounded-lg shadow-lg p-6 sticky top-16">
          <img src="@/assets/image.png" alt="Instructor" class="rounded-lg mb-4" />
          <div class="flex items-center justify-between mb-4">
            <span class="text-xl font-bold">$64.99</span>
            <button class="bg-purple-600 text-white py-2 px-4 rounded">Add to cart</button>
          </div>
          <p class="text-gray-600 mb-4">30-Day Money-Back Guarantee</p>
          <button class="bg-gray-800 text-white py-2 px-4 w-full rounded mb-2">Share</button>
          <button class="bg-gray-800 text-white py-2 px-4 w-full rounded mb-2">Gift this course</button>
          <div class="mt-4">
            <label for="coupon" class="block text-gray-600">Apply Coupon</label>
            <input type="text" id="coupon" class="border border-gray-300 rounded w-full py-2 px-3 mt-1" placeholder="Enter Coupon"/>
            <button class="bg-purple-600 text-white py-2 px-4 w-full mt-2 rounded">Apply</button>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'UdemyPageClone',
};
</script>

<style scoped>
.container {
  max-width: 1200px;
}
  /* Additional dropdown styling */
  .group:hover .group-hover\:block {
    display: block;
  }
  
  .group:hover .group-hover\:flex {
    display: flex;
  }
</style>
