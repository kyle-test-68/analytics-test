<!--
Copyright 2018 Google Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
<!DOCTYPE html>
<html lang="en">
<head>

  <!-- Set the viewport -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Set character encoding -->
  <meta charset="utf-8">
  <!-- Include manifest -->
  <link rel="manifest" href="manifest.json">
  <!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-N58JMQ5');</script>
<!-- End Google Tag Manager -->
  <!-- link CSS -->
  <link rel="stylesheet" href="styles/main.css">
  <!-- Set title -->
  <title>Analytics Lab</title>
</head>

<body>
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-N58JMQ5"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

  <header>
    <h1>Google Analytics lab</h1>
  </header>

  <section class="note">
    <p>This page must be accessed using 
      <strong>HTTPS</strong> or via <strong>localhost</strong>.
    </p>
  </section>

  <section>
    <div class="img-container">
      <img src="images/cat.jpg" alt="An adorable cat.">
    </div>
    <div class="buttons-container">
      <button id="favorite">Favorite</button>
      <button id="subscribe">Subscribe</button>
      <button id="unsubscribe">Unsubscribe</button>
    </div>
  </section>

  <footer>
    <a href="pages/other.html" id="other">Other page</a>
  </footer>

  <!-- TODO Add tracking snippet -->

  <script src="js/main.js"></script>
  <!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-158693411-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-158693411-1');
</script>


</body>
</html>
