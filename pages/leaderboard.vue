<template>
   <div class="container mx-auto p-6">
   <h1 class="text-3xl font-bold mb-6">
    Progress Page
   </h1>
   <!-- Overall Progress Section -->
   <section class="mb-8">
    <h2 class="text-2xl font-semibold mb-4">
     Overall Progress
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
     <div class="bg-white p-6 rounded-lg shadow-md">
      <h3 class="text-xl font-semibold mb-2">
       Time Spent
      </h3>
      <img alt="Graph showing time spent on the course over the past month" class="w-full h-40 object-cover" height="200" src="https://storage.googleapis.com/a1aa/image/sf3neR3O4mve3JBKCKdjfuuzLd0x0plemAjNwb37n4Zh7cvdC.jpg" width="300"/>
     </div>
     <div class="bg-white p-6 rounded-lg shadow-md">
      <h3 class="text-xl font-semibold mb-2">
       Modules Completed
      </h3>
      <img alt="Graph showing the number of modules completed" class="w-full h-40 object-cover" height="200" src="https://storage.googleapis.com/a1aa/image/S9BC0gmEU77vHZ1lGkeRZXfTmDa5Z719OxkJeIXspe10du3OB.jpg" width="300"/>
     </div>
     <div class="bg-white p-6 rounded-lg shadow-md">
      <h3 class="text-xl font-semibold mb-2">
       Course Progress
      </h3>
      <img alt="Graph showing overall course progress" class="w-full h-40 object-cover" height="200" src="https://storage.googleapis.com/a1aa/image/dC0qZ7kExy5sItdkkyYGI6qP0fQeUo0WsWU5tVXskATan7tTA.jpg" width="300"/>
     </div>
    </div>
   </section>
   <!-- Daily Streaks Section -->
   <section class="mb-8">
    <h2 class="text-2xl font-semibold mb-4">
     Daily Streaks
    </h2>
    <div class="bg-white p-6 rounded-lg shadow-md">
     <div class="flex justify-between items-center">
      <div>
       <h3 class="text-xl font-semibold">
        Current Streak
       </h3>
       <p class="text-4xl font-bold text-green-500">
        15 Days
       </p>
      </div>
      <div>
       <h3 class="text-xl font-semibold">
        Best Streak
       </h3>
       <p class="text-4xl font-bold text-blue-500">
        30 Days
       </p>
      </div>
     </div>
    </div>
   </section>
   <!-- Detailed Course Breakdown Section -->
   <section class="mb-8">
    <h2 class="text-2xl font-semibold mb-4">
     Detailed Course Breakdown
    </h2>
    <div class="bg-white p-6 rounded-lg shadow-md">
     <table class="w-full table-auto">
      <thead>
       <tr class="bg-gray-200">
        <th class="px-4 py-2">
         Lesson
        </th>
        <th class="px-4 py-2">
         Status
        </th>
        <th class="px-4 py-2">
         Improvement Needed
        </th>
       </tr>
      </thead>
      <tbody>
       <tr>
        <td class="border px-4 py-2">
         Lesson 1
        </td>
        <td class="border px-4 py-2 text-green-500">
         Completed
        </td>
        <td class="border px-4 py-2">
         No
        </td>
       </tr>
       <tr>
        <td class="border px-4 py-2">
         Lesson 2
        </td>
        <td class="border px-4 py-2 text-red-500">
         Incomplete
        </td>
        <td class="border px-4 py-2">
         Yes
        </td>
       </tr>
       <tr>
        <td class="border px-4 py-2">
         Lesson 3
        </td>
        <td class="border px-4 py-2 text-green-500">
         Completed
        </td>
        <td class="border px-4 py-2">
         No
        </td>
       </tr>
       <tr>
        <td class="border px-4 py-2">
         Lesson 4
        </td>
        <td class="border px-4 py-2 text-red-500">
         Incomplete
        </td>
        <td class="border px-4 py-2">
         Yes
        </td>
       </tr>
       <tr>
        <td class="border px-4 py-2">
         Lesson 5
        </td>
        <td class="border px-4 py-2 text-green-500">
         Completed
        </td>
        <td class="border px-4 py-2">
         No
        </td>
       </tr>
      </tbody>
     </table>
    </div>
   </section>
   <!-- Goal Setting Section -->
   <section>
    <h2 class="text-2xl font-semibold mb-4">
     Goal Setting
    </h2>
    <div class="bg-white p-6 rounded-lg shadow-md">
     <form>
      <div class="mb-4">
       <label class="block text-lg font-medium mb-2" for="weekly-goal">
        Weekly Goal (hours)
       </label>
       <input class="w-full p-2 border rounded-lg" id="weekly-goal" placeholder="Enter weekly goal" type="number"/>
      </div>
      <div class="mb-4">
       <label class="block text-lg font-medium mb-2" for="monthly-goal">
        Monthly Goal (new vocabulary)
       </label>
       <input class="w-full p-2 border rounded-lg" id="monthly-goal" placeholder="Enter monthly goal" type="number"/>
      </div>
      <button class="bg-blue-500 text-white px-4 py-2 rounded-lg" type="submit">
       Set Goals
      </button>
     </form>
    </div>
   </section>
  </div>
</template>