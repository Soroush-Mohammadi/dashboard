<template>
    <div class="container mx-auto p-6">
        <h1 class="text-3xl font-bold mb-6">Lesson Module</h1>
        
        <!-- Lesson Content -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-4">Lesson Content</h2>
            <div class="space-y-4">
                <div>
                    <h3 class="text-xl font-semibold">Video</h3>
                    <video controls class="w-full h-64 bg-gray-200">
                        <source src="https://placehold.co/600x400" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                </div>
                <div>
                    <h3 class="text-xl font-semibold">Audio</h3>
                    <audio controls class="w-full">
                        <source src="https://placehold.co/600x400" type="audio/mpeg">
                        Your browser does not support the audio element.
                    </audio>
                </div>
                <div>
                    <h3 class="text-xl font-semibold">Text</h3>
                    <p class="bg-white p-4 rounded shadow">This is the text content of the lesson. It provides detailed explanations and examples.</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold">Interactive Content</h3>
                    <div class="bg-white p-4 rounded shadow">
                        <p>Interactive content goes here. This could be a quiz, a drag-and-drop activity, or other interactive elements.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Vocabulary List -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-4">Vocabulary List</h2>
            <ul class="bg-white p-4 rounded shadow space-y-2">
                <li class="flex justify-between">
                    <span>Word 1</span>
                    <span>Pronunciation</span>
                    <span>Definition</span>
                </li>
                <li class="flex justify-between">
                    <span>Word 2</span>
                    <span>Pronunciation</span>
                    <span>Definition</span>
                </li>
                <li class="flex justify-between">
                    <span>Word 3</span>
                    <span>Pronunciation</span>
                    <span>Definition</span>
                </li>
                <li class="flex justify-between">
                    <span>Word 4</span>
                    <span>Pronunciation</span>
                    <span>Definition</span>
                </li>
                <li class="flex justify-between">
                    <span>Word 5</span>
                    <span>Pronunciation</span>
                    <span>Definition</span>
                </li>
            </ul>
        </section>

        <!-- Grammar and Usage Tips -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-4">Grammar and Usage Tips</h2>
            <div class="bg-white p-4 rounded shadow">
                <p>Here are some grammar explanations related to the lesson. This section provides detailed information on grammar rules and usage tips.</p>
            </div>
        </section>

        <!-- Interactive Exercises -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-4">Interactive Exercises</h2>
            <div class="bg-white p-4 rounded shadow space-y-4">
                <div>
                    <h3 class="text-xl font-semibold">Multiple-Choice Questions</h3>
                    <div>
                        <p>Question 1: What is the correct answer?</p>
                        <ul class="list-disc pl-6">
                            <li>Option A</li>
                            <li>Option B</li>
                            <li>Option C</li>
                            <li>Option D</li>
                        </ul>
                    </div>
                    <div>
                        <p>Question 2: What is the correct answer?</p>
                        <ul class="list-disc pl-6">
                            <li>Option A</li>
                            <li>Option B</li>
                            <li>Option C</li>
                            <li>Option D</li>
                        </ul>
                    </div>
                </div>
                <div>
                    <h3 class="text-xl font-semibold">Fill-in-the-Blank</h3>
                    <div>
                        <p>Sentence 1: The quick brown ____ jumps over the lazy dog.</p>
                        <input type="text" class="border p-2 rounded w-full">
                    </div>
                    <div>
                        <p>Sentence 2: She sells sea ____ by the seashore.</p>
                        <input type="text" class="border p-2 rounded w-full">
                    </div>
                </div>
                <div>
                    <h3 class="text-xl font-semibold">Drag-and-Drop Tasks</h3>
                    <div class="bg-gray-200 p-4 rounded">
                        <p>Drag and drop the correct words into the blanks.</p>
                        <!-- Placeholder for drag-and-drop functionality -->
                    </div>
                </div>
            </div>
        </section>

        <!-- Audio Recording and Pronunciation Practice -->
        <section class="mb-8">
            <h2 class="text-2xl font-semibold mb-4">Audio Recording and Pronunciation Practice</h2>
            <div class="bg-white p-4 rounded shadow">
                <p>Record your voice and compare it with native speakers.</p>
                <button class="bg-blue-500 text-white px-4 py-2 rounded mt-2">Record</button>
                <button class="bg-green-500 text-white px-4 py-2 rounded mt-2">Play Native Speaker</button>
                <button class="bg-yellow-500 text-white px-4 py-2 rounded mt-2">Compare</button>
            </div>
        </section>
    </div>
</template>