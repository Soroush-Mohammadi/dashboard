<template>
      <div class="container mx-auto p-6">
        <h1 class="text-3xl font-bold mb-6">Settings</h1>
        <div class="bg-white shadow-md rounded-lg p-6 mb-6">
            <h2 class="text-2xl font-semibold mb-4">Account Settings</h2>
            <form>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="username">Username</label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="username" type="text" placeholder="Username">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="email">Email</label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="email" type="email" placeholder="Email">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="password">Password</label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="password" type="password" placeholder="Password">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="confirm-password">Confirm Password</label>
                    <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="confirm-password" type="password" placeholder="Confirm Password">
                </div>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
                    Save Changes
                </button>
            </form>
        </div>

        <div class="bg-white shadow-md rounded-lg p-6 mb-6">
            <h2 class="text-2xl font-semibold mb-4">Language Preferences</h2>
            <form>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="primary-language">Primary Language</label>
                    <select class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="primary-language">
                        <option>English</option>
                        <option>Spanish</option>
                        <option>French</option>
                        <option>German</option>
                        <option>Chinese</option>
                    </select>
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="content-language">Content Language Preferences</label>
                    <select multiple class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="content-language">
                        <option>English</option>
                        <option>Spanish</option>
                        <option>French</option>
                        <option>German</option>
                        <option>Chinese</option>
                    </select>
                </div>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
                    Save Changes
                </button>
            </form>
        </div>

        <div class="bg-white shadow-md rounded-lg p-6 mb-6">
            <h2 class="text-2xl font-semibold mb-4">Notifications</h2>
            <form>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="course-reminders">Course Reminders</label>
                    <input type="checkbox" id="course-reminders" class="mr-2 leading-tight">
                    <span class="text-sm">Enable course reminders</span>
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="progress-updates">Progress Updates</label>
                    <input type="checkbox" id="progress-updates" class="mr-2 leading-tight">
                    <span class="text-sm">Enable progress updates</span>
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700 text-sm font-bold mb-2" for="community-activity">Community Activity</label>
                    <input type="checkbox" id="community-activity" class="mr-2 leading-tight">
                    <span class="text-sm">Enable community activity notifications</span>
                </div>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline" type="button">
                    Save Changes
                </button>
            </form>
        </div>

        <div class="bg-white shadow-md rounded-lg p-6">
            <h2 class="text-2xl font-semibold mb-4">Subscription & Billing</h2>
            <div class="mb-4">
                <h3 class="text-xl font-semibold mb-2">Current Plan</h3>
                <p class="text-gray-700">Premium Plan - $9.99/month</p>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline mt-2" type="button">
                    Change Plan
                </button>
            </div>
            <div class="mb-4">
                <h3 class="text-xl font-semibold mb-2">Billing History</h3>
                <ul class="list-disc pl-5 text-gray-700">
                    <li>January 2023 - $9.99</li>
                    <li>December 2022 - $9.99</li>
                    <li>November 2022 - $9.99</li>
                </ul>
            </div>
            <div class="mb-4">
                <h3 class="text-xl font-semibold mb-2">Payment Methods</h3>
                <p class="text-gray-700">Visa ending in 1234</p>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline mt-2" type="button">
                    Update Payment Method
                </button>
            </div>
        </div>
    </div>
</template>