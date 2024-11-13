<template>
  <div class="container mx-auto p-6">
   <h1 class="text-4xl font-bold text-center mb-8">
    Instructor Profiles
   </h1>
   <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
    <!-- Instructor 1 -->
    <div class="bg-white p-6 rounded-lg shadow-lg">
     <img alt="Portrait of Instructor 1, a middle-aged person with glasses and a friendly smile" class="w-full h-48 object-cover rounded-t-lg" height="300" src="https://storage.googleapis.com/a1aa/image/a6BaXpQuXdIHGtfXchTe95Q63ivetG9vM9ZONksLZeGKpu3OB.jpg" width="300"/>
     <div class="mt-4">
      <h2 class="text-2xl font-bold">
       John Doe
      </h2>
      <p class="text-gray-600">
       PhD in Computer Science, 10 years of teaching experience
      </p>
      <h3 class="text-xl font-semibold mt-4">
       Courses Offered:
      </h3>
      <ul class="list-disc list-inside">
       <li>
        Introduction to Programming
       </li>
       <li>
        Data Structures and Algorithms
       </li>
       <li>
        Machine Learning
       </li>
      </ul>
      <h3 class="text-xl font-semibold mt-4">
       Ratings and Reviews:
      </h3>
      <div class="flex items-center">
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-gray-400">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="ml-2 text-gray-600">
        (4.0)
       </span>
      </div>
      <p class="text-gray-600 mt-2">
       "John is an excellent instructor who makes complex topics easy to understand."
      </p>
      <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded">
       Contact/Inquire
      </button>
     </div>
    </div>
    <!-- Instructor 2 -->
    <div class="bg-white p-6 rounded-lg shadow-lg">
     <img alt="Portrait of Instructor 2, a young person with short hair and a confident expression" class="w-full h-48 object-cover rounded-t-lg" height="300" src="https://storage.googleapis.com/a1aa/image/AsRL7mpGKDKaD1bi1sXG7YjzSFvll7Ef6oF41AlQVjeYq7tTA.jpg" width="300"/>
     <div class="mt-4">
      <h2 class="text-2xl font-bold">
       Jane Smith
      </h2>
      <p class="text-gray-600">
       MSc in Mathematics, 5 years of teaching experience
      </p>
      <h3 class="text-xl font-semibold mt-4">
       Courses Offered:
      </h3>
      <ul class="list-disc list-inside">
       <li>
        Calculus I
       </li>
       <li>
        Linear Algebra
       </li>
       <li>
        Statistics
       </li>
      </ul>
      <h3 class="text-xl font-semibold mt-4">
       Ratings and Reviews:
      </h3>
      <div class="flex items-center">
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="ml-2 text-gray-600">
        (5.0)
       </span>
      </div>
      <p class="text-gray-600 mt-2">
       "Jane's passion for mathematics is contagious. She is a fantastic teacher."
      </p>
      <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded">
       Contact/Inquire
      </button>
     </div>
    </div>
    <!-- Instructor 3 -->
    <div class="bg-white p-6 rounded-lg shadow-lg">
     <img alt="Portrait of Instructor 3, an older person with a beard and a thoughtful expression" class="w-full h-48 object-cover rounded-t-lg" height="300" src="https://storage.googleapis.com/a1aa/image/yBPlefUZ3lhda0Vl6fP1Q5r0eNMSHSIj709KleaiubPkSdvdC.jpg" width="300"/>
     <div class="mt-4">
      <h2 class="text-2xl font-bold">
       Michael Brown
      </h2>
      <p class="text-gray-600">
       PhD in Physics, 15 years of teaching experience
      </p>
      <h3 class="text-xl font-semibold mt-4">
       Courses Offered:
      </h3>
      <ul class="list-disc list-inside">
       <li>
        Classical Mechanics
       </li>
       <li>
        Quantum Physics
       </li>
       <li>
        Thermodynamics
       </li>
      </ul>
      <h3 class="text-xl font-semibold mt-4">
       Ratings and Reviews:
      </h3>
      <div class="flex items-center">
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="ml-2 text-gray-600">
        (5.0)
       </span>
      </div>
      <p class="text-gray-600 mt-2">
       "Michael's deep understanding of physics is evident in his teaching. Highly recommended."
      </p>
      <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded">
       Contact/Inquire
      </button>
     </div>
    </div>
    <!-- Instructor 4 -->
    <div class="bg-white p-6 rounded-lg shadow-lg">
     <img alt="Portrait of Instructor 4, a middle-aged person with long hair and a warm smile" class="w-full h-48 object-cover rounded-t-lg" height="300" src="https://storage.googleapis.com/a1aa/image/9YY9eGbeDeA76pPoxLvp3t9qxpKHen7BU6fY3fp6L3ikl6e2JA.jpg" width="300"/>
     <div class="mt-4">
      <h2 class="text-2xl font-bold">
       Emily Davis
      </h2>
      <p class="text-gray-600">
       MFA in Fine Arts, 8 years of teaching experience
      </p>
      <h3 class="text-xl font-semibold mt-4">
       Courses Offered:
      </h3>
      <ul class="list-disc list-inside">
       <li>
        Introduction to Painting
       </li>
       <li>
        Advanced Sculpture
       </li>
       <li>
        Art History
       </li>
      </ul>
      <h3 class="text-xl font-semibold mt-4">
       Ratings and Reviews:
      </h3>
      <div class="flex items-center">
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-gray-400">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="ml-2 text-gray-600">
        (4.0)
       </span>
      </div>
      <p class="text-gray-600 mt-2">
       "Emily's creativity and passion for art are truly inspiring."
      </p>
      <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded">
       Contact/Inquire
      </button>
     </div>
    </div>
    <!-- Instructor 5 -->
    <div class="bg-white p-6 rounded-lg shadow-lg">
     <img alt="Portrait of Instructor 5, a young person with curly hair and a bright smile" class="w-full h-48 object-cover rounded-t-lg" height="300" src="https://storage.googleapis.com/a1aa/image/FuIeZMggsMwDHCSgWO9UV6fY9rhfDjI6mgpigPZ5XmSiU3bnA.jpg" width="300"/>
     <div class="mt-4">
      <h2 class="text-2xl font-bold">
       David Wilson
      </h2>
      <p class="text-gray-600">
       MBA, 6 years of teaching experience
      </p>
      <h3 class="text-xl font-semibold mt-4">
       Courses Offered:
      </h3>
      <ul class="list-disc list-inside">
       <li>
        Business Management
       </li>
       <li>
        Marketing Strategies
       </li>
       <li>
        Entrepreneurship
       </li>
      </ul>
      <h3 class="text-xl font-semibold mt-4">
       Ratings and Reviews:
      </h3>
      <div class="flex items-center">
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-yellow-500">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="text-gray-400">
        <i class="fas fa-star">
        </i>
       </span>
       <span class="ml-2 text-gray-600">
        (4.0)
       </span>
      </div>
      <p class="text-gray-600 mt-2">
       "David's insights into business are invaluable. Great instructor!"
      </p>
      <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded">
       Contact/Inquire
      </button>
     </div>
    </div>
   </div>
  </div>
</template>