---
title: test4
permalink: test4
layout: layouts/base.njk
page_css: |
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: "#141A46",
            secondary: "#8BD8BD",
            accent: "#EC8B5E"
          }
        }
      }
    }
  </script>
---
<div class="bg-primary text-white p-8 rounded-lg shadow-lg">
  <h1 class="text-2xl font-bold mb-4">Test Tailwind</h1>
  <p class="mb-2">Ceci est un test de rendu Tailwind en production.</p>
  <button class="bg-secondary text-primary px-4 py-2 rounded hover:bg-accent transition">
    Clique-moi
  </button>
</div>
