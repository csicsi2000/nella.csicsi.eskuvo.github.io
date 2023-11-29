---
title: Home page
layout: default
---
<div id="intro-example" class="p-5 text-center bg-image" style="background-image: url('images/kozos.jpg');background-size: contain;">
    <div class="mask" style="background-color: rgba(0, 0, 0, 0.3);">
      <div class="d-flex justify-content-center align-items-center h-100">
        <div class="text-white">
          <h1 class="mb-3" style="font-family: 'Angella White Personal use font', sans-serif; font-size: 5rem;">Nella + Csicsi</h1>
          <h4 class="mb-4" style="font-family: 'Cormorant Garamond', serif;">
            Ünnepelj velünk
          </h4>
          <h2 style="font-family: 'Slabo 27px', serif;">2024.07.29. | 17:00</h2>
          <a class="btn btn-outline-light btn-lg m-2" href="{{ site.baseurl }}/info.html"
            role="button" rel="nofollow">Információk</a>
        </div>
      </div>
    </div>
</div>
<div class="d-flex align-items-center justify-content-center mt-4">
<div id="flipdown" class="flipdown" style="width: unset"></div>
</div>
<script>
var flipColorMode = document.querySelector("html").getAttribute("data-bs-theme");
  console.log(flipColorMode)
  if(flipColorMode == "dark"){
    flipColorMode = "light"
  }else{
    flipColorMode = "dark"
  }
  new FlipDown(1722272400,{
    headings: ["Nap", "Óra", "Perc", "Másodperc"],
    theme: flipColorMode
  }).start();

</script>
