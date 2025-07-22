---
title: test3
date: 2025-07-22T19:46:00.000+02:00
permalink: test1
eleventyNavigation:
  order: 0
  showFooter: true
  key: "1"
  page_css: >
    script src="https://cdn.tailwindcss.com"></script>


    <style>

    /* Ce test vérifie si les styles sont bien injectés. */

    /* Si le fond de la page devient jaune clair, cela signifie que cette partie fonctionne. */

    body {

    background-color: #FFFFAA;

    }

    </style>
---
<div class="bg-blue-700 text-white font-sans p-10 m-10 rounded-lg">
  <h1 class="text-4xl font-bold mb-4">Test Tailwind</h1>
  <p class="text-lg">
    Si ce bloc a un fond bleu, du texte blanc, des coins arrondis et des marges,
    alors le script de Tailwind fonctionne correctement.
  </p>
</div>
