<template>
  <div class="bg-gray-100">
    <header class="bg-blue-600 text-white p-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold">Community Forum</h1>
        <nav>
          <ul class="flex space-x-4">
            <li><a href="#" class="hover:underline">Home</a></li>
            <li><a href="#" class="hover:underline">Discussion Boards</a></li>
            <li><a href="#" class="hover:underline">Language Exchange</a></li>
            <li><a href="#" class="hover:underline">Group Learning</a></li>
            <li><a href="#" class="hover:underline">Events</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <main class="container mx-auto mt-8">
      <!-- Discussion Boards Section -->
      <section class="mb-8">
        <h2 class="text-xl font-bold mb-4">Discussion Boards</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">General Questions</h3>
            <p class="text-gray-700">
              Ask any general questions about language learning.
            </p>
          </div>
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">Cultural Discussions</h3>
            <p class="text-gray-700">
              Discuss cultural aspects related to the language you are learning.
            </p>
          </div>
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">Study Tips</h3>
            <p class="text-gray-700">
              Share and discover effective study tips.
            </p>
          </div>
        </div>
      </section>

      <!-- Language Exchange Partners Section -->
      <section class="mb-8">
        <h2 class="text-xl font-bold mb-4">Language Exchange Partners</h2>
        <div class="bg-white p-4 rounded shadow">
          <h3 class="text-lg font-semibold mb-2">Find a Partner</h3>
          <p class="text-gray-700 mb-4">
            Connect with native speakers or other students to practice your
            language skills.
          </p>
          <button class="bg-blue-600 text-white px-4 py-2 rounded">
            Find a Partner
          </button>
        </div>
      </section>

      <!-- Group Learning Section -->
      <section class="mb-8">
        <h2 class="text-xl font-bold mb-4">Group Learning</h2>
        <div class="bg-white p-4 rounded shadow">
          <h3 class="text-lg font-semibold mb-2">Join a Group</h3>
          <p class="text-gray-700 mb-4">
            Join group study sessions or engage in group challenges to enhance
            your learning experience.
          </p>
          <button class="bg-blue-600 text-white px-4 py-2 rounded">
            Join a Group
          </button>
        </div>
      </section>

      <!-- Events/Webinars Section -->
      <section>
        <h2 class="text-xl font-bold mb-4">Events/Webinars</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">Live Q&A with Teachers</h3>
            <p class="text-gray-700 mb-4">
              Join our live Q&A sessions with experienced language teachers.
            </p>
            <button class="bg-blue-600 text-white px-4 py-2 rounded">
              View Schedule
            </button>
          </div>
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">
              Language Exchange Meetings
            </h3>
            <p class="text-gray-700 mb-4">
              Participate in scheduled language exchange meetings.
            </p>
            <button class="bg-blue-600 text-white px-4 py-2 rounded">
              View Schedule
            </button>
          </div>
          <div class="bg-white p-4 rounded shadow">
            <h3 class="text-lg font-semibold mb-2">Webinars</h3>
            <p class="text-gray-700 mb-4">
              Attend webinars on various language learning topics.
            </p>
            <button class="bg-blue-600 text-white px-4 py-2 rounded">
              View Schedule
            </button>
          </div>
        </div>
      </section>
    </main>

    <footer class="bg-blue-600 text-white p-4 mt-8">
      <div class="container mx-auto text-center">
        <p>&copy; 2023 Community Forum. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>
