<script lang="ts">
 import qrCode from "$lib/assets/image-qr-code.png";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inconsolata:wght@300;400&family=Outfit&display=swap" rel="stylesheet">
</svelte:head>

<style>
 #fullscreen {
   background-color: hsl(212, 45%, 89%)
 }

 .outfit-copy {
   font-family: "Outfit", serif;
 }

 .subtitle {
   color: hsl(216, 15%, 48%);
 }
</style>


<div id="fullscreen" class="h-screen w-screen grid">
  <div class="mx-auto lg:w-1/6 content-center">
    <div class="bg-white rounded-xl shadow-xl" >
      <div class="lg:h-7/12">
        <div class="mx-auto pt-4">
          <img class="rounded-lg mx-auto w-72" alt="qr code for frontend mentors" src={qrCode} />
        </div>
      </div>
      <div class="text-center outfit-copy p-5 pb-10">
        <h2 class="font-bold"><b>Improve your front-end skills by building projects</b></h2>
        <p class="subtitle text-sm pt-3">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>
</div>
