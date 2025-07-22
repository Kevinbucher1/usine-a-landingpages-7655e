---
title: Test meta gazelec
date: 2025-07-22T18:17:00.000+02:00
permalink: meta-gazelec
layout: layouts/base.njk
templateEngineOverride: njk
page_css: >-
  <script src="https://cdn.tailwindcss.com"></script>

  <link rel="preconnect" href="https://fonts.googleapis.com"> <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            'primary': '#141A46',
            'secondary': '#8BD8BD',
            'accent': '#EC8B5E',
            'light-bg': '#F1F7F9',
          },
          fontFamily: {
            'sans': ['Poppins', 'sans-serif'],
          }
        }
      }
    }
  </script>

  <script async src="https://www.googletagmanager.com/gtag/js?id=AW-16465363779"></script> <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'AW-16465363779');
  </script>

  <script> !function(f,b,e,v,n,t,s) {if(f.fbq)return;n=f.fbq=function(){n.callMethod? n.callMethod.apply(n,arguments):n.queue.push(arguments)}; if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0'; n.queue=[];t=b.createElement(e);t.async=!0; t.src=v;s=b.getElementsByTagName(e)[0]; s.parentNode.insertBefore(t,s)}(window,document,'script', 'https://connect.facebook.net/en_US/fbevents.js'); fbq('init', '963557524306737'); fbq('track', 'PageView'); </script> <noscript> <img height="1" width="1" src="https://www.facebook.com/tr?id=963557524306737&ev=PageView&noscript=1"/> </noscript>

  <script type="text/javascript"> var _iub = _iub || []; _iub.csConfiguration = {"askConsentAtCookiePolicyUpdate":true,"floatingPreferencesButtonDisplay":"bottom-right","lang":"fr","perPurposeConsent":true,"siteId":3550954,"whitelabel":false,"cookiePolicyId":41345322,"i18n":{"fr":{"banner":{"title":"Vos données sont protégées.","dynamic":{"body":"Nous ainsi que des tiers sélectionnés utilisons des cookies ou des technologies similaires pour des finalités techniques et, avec votre consentement, pour les finalités « fonctionnalité », « expérience », « mesure » et « marketing » (publicités personnalisées)."}}}},"banner":{"acceptButtonCaptionColor":"#FFFFFF","acceptButtonColor":"#334757","acceptButtonDisplay":true,"backgroundColor":"#F4FBFF","closeButtonDisplay":false,"customizeButtonCaptionColor":"#14213D","customizeButtonColor":"#DCE2E6","customizeButtonDisplay":true,"explicitWithdrawal":true,"listPurposes":true,"position":"bottom","rejectButtonCaptionColor":"#FFFFFF","rejectButtonColor":"#334757","rejectButtonDisplay":true,"theme":"winter-neutral","textColor":"#45423F"}}; </script> <script type="text/javascript" src="https://cs.iubenda.com/autoblocking/3550954.js"></script> <script type="text/javascript" src="//cdn.iubenda.com/cs/iubenda_cs.js" charset="UTF-8" async></script>
eleventyNavigation:
  page_css: >-
    <script src="https://cdn.tailwindcss.com"></script>


    <style>
      /* Ce test vérifie si les styles sont bien injectés. */
      /* Si le fond de la page devient jaune clair, cela signifie que cette partie fonctionne. */
      body {
        background-color: #FFFFAA;
      }
    </style>
  order: 0
  key: "1"
---
<div class="bg-blue-700 text-white font-sans p-10 m-10 rounded-lg">
  <h1 class="text-4xl font-bold mb-4">Test Tailwind</h1>
  <p class="text-lg">
    Si ce bloc a un fond bleu, du texte blanc, des coins arrondis et des marges,
    alors le script de Tailwind fonctionne correctement.
  </p>
</div>
