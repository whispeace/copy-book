<template>
  <!--
// v0 by Vercel.
// https://v0.dev/t/7TDa0BvleE8
-->
  <div class="flex h-full">
    <div class="flex flex-col w-64 p-4 border-r bg-gray-100 dark:bg-gray-900">
      <div class="flex justify-between items-center mb-4">
        <h2 class="text-lg font-semibold">
          Name App
        </h2><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class=" h-3 w-3"><path d="m12 19-7-7 7-7" /><path d="M19 12H5" /></svg>
      </div><div class="mb-6">
        <h3 class="text-lg font-medium mb-2">
          Tags
        </h3><div class="flex flex-wrap gap-2">
          <a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            #Tag 1
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            #Tag 2
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            #Tag 3
          </a>
        </div>
      </div><div class="mb-6">
        <h3 class="text-lg font-medium mb-2">
          Categories
        </h3><div class="flex flex-wrap gap-2">
          <a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Category 1
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Category 2
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Category 3
          </a>
        </div>
      </div><div>
        <h3 class="text-lg font-medium mb-2">
          Moods
        </h3><div class="flex flex-wrap gap-2">
          <a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Happy
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Sad
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Excited
          </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
            Calm
          </a>
        </div>
      </div>
    </div><div class="flex-grow p-4 bg-gray-100 dark:bg-gray-900">
      <h1 class="text-lg font-semibold text-gray-800 dark:text-gray-100 mb-2">
        All
      </h1><h2 class="text-md font-medium text-gray-600 dark:text-gray-400 mb-6">
        #Tag 1, #Tag 2
      </h2><div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <a class="block relative group p-4 border rounded-lg shadow-sm bg-gray-100 dark:bg-gray-800" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class=" h-4 w-4 text-gray-500 dark:text-gray-400 absolute top-1 right-1 opacity-0 group-hover:opacity-100"><rect width="8" height="4" x="8" y="2" rx="1" ry="1" /><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2" /></svg><p class="mb-4 text-gray-800 dark:text-gray-100 pr-8">
          This is a slightly longer phrase for the first card. It is meant to be more descriptive and unique.
        </p><div class="flex flex-wrap gap-2"><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
          #Tag 1
        </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
          #Tag 2
        </a></div></a><a class="block relative group p-4 border rounded-lg shadow-sm bg-gray-100 dark:bg-gray-800" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class=" h-4 w-4 text-gray-500 dark:text-gray-400 absolute top-1 right-1 opacity-0 group-hover:opacity-100"><rect width="8" height="4" x="8" y="2" rx="1" ry="1" /><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2" /></svg><p class="mb-4 text-gray-800 dark:text-gray-100 pr-8">
          Here's another distinct phrase for the second card. It differs from the first and is also extended.
        </p><div class="flex flex-wrap gap-2"><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
          #Tag 2
        </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
          #Tag 3
        </a></div></a><a class="block relative group p-4 border rounded-lg shadow-sm bg-gray-100 dark:bg-gray-800" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class=" h-4 w-4 text-gray-500 dark:text-gray-400 absolute top-1 right-1 opacity-0 group-hover:opacity-100"><rect width="8" height="4" x="8" y="2" rx="1" ry="1" /><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2" /></svg><p class="mb-4 text-gray-800 dark:text-gray-100 pr-8">
          Lastly, this is the third phrase. It's unique and longer than the previous phrases on the card.
        </p><div class="flex flex-wrap gap-2"><a class="text-xs font-medium text-gray-700 hover:underline" href="#">
          #Tag 1
        </a><a class="text-xs font-medium text-gray-700 hover:underline" href="#" /></div></a>
      </div>
    </div>
  </div>
</template>
