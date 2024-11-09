<template>
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
  </template>
  
  <script lang="ts">
  export default {
    name: 'UdemyHeader',
  }
  </script>
  
  <style scoped>
  /* Additional dropdown styling */
  .group:hover .group-hover\:block {
    display: block;
  }
  
  .group:hover .group-hover\:flex {
    display: flex;
  }
  </style>
  