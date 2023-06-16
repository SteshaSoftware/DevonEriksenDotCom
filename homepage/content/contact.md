---
title: "Contact"

menu: main
weight: 110
draft: false
---


{{< rawhtml >}}

<h1 class="text-xl text-gray-800 font-semibold mb-2">
  Simple contact form 
</h1>
<p class="mb-6 text-gray-600 w-2/3 leading-normal">
  This is a simple contact form that submits to FormBackend. Styling for this example is done using TailwindCSS, but that's something
  you control 100%.
</p>

<form action="https://formsubmit.co/devoneriksen@protonmail.com" method="POST">
  <div class="mb-3">
    <label for="name" class="font-bold uppercase text-gray-600 block tracking-wide text-sm mb-1">Name</label>
    <input type="text" id="name" name="name" class="bg-gray-300 rounded p-2 text-gray-600 focus:shadow-outline focus:outline-none" required>  
  </div>
  
  <div class="mb-3">
    <label for="email" class="font-bold uppercase text-gray-600 block tracking-wide text-sm mb-1">Email</label>
    <input type="email" id="email" name="email" class="bg-gray-200 rounded p-2 text-gray-600 focus:outline-none" required>
  </div>
  
  <div class="mb-3">
    <label for="message" class="font-bold uppercase text-gray-600 block tracking-wide text-sm mb-1">Message</label>
    <input type="text" id="message" name="message" class="bg-gray-300 rounded p-2 text-gray-600 focus:shadow-outline focus:outline-none" required>  
  </div>
  
  
  
<br>
  <div class="mb-3">
    <button type="submit" class="bg-blue-700 text-white px-4 py-2 rounded">
      Submit
    </button>
  </div>
</form>

{{< /rawhtml >}}
