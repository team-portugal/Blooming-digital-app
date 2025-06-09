---
layout: default
---

<link rel="icon" type="image/png" href="assets/images/favicon.png">


# 🌱 Blooming Digital  
## Enriching Lives, Opening Minds – *Liveable Earth*
---

<div style="position: relative; text-align: center; color: white;">

  <!-- Background Image -->
  <img src="assets/images/pasiagem.jpg" alt="Nature landscape" style="width: 100%; max-height: 500px; object-fit: cover; filter: brightness(60%);">

  <!-- Logo Overlay -->
  <img src="assets/images/logo_erasmus_1.jpg" alt="Erasmus+ Logo" style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);
       width: 300px; max-width: 80%; opacity: 0; animation: fadeIn 3s forwards 1s;">

  <!-- Optional Slogan -->
  <div style="position: absolute; bottom: 20px; width: 100%; font-size: 1.5rem; font-weight: bold;">
    Blooming Digital: Enriching Lives, Opening Minds
  </div>
</div>

<style>
@keyframes fadeIn {
  to {
    opacity: 1;
  }
}
</style>

---


Welcome to our Erasmus+ project website!  
This space is dedicated to showcasing the collaborative work of students and teachers across Europe, exploring sustainability, creativity, and digital tools.

---


## 🌍 What is Blooming Digital?

**Blooming Digital: Enriching Lives, Opening Minds** is a collaborative Erasmus+ project uniting students and teachers across Europe to explore the intersection of sustainability, culture, and digital innovation.

Over the course of several months, schools from **Portugal, Ireland, Romania, and Türkiye** worked together on creative and educational activities centered around the theme of a **Liveable Earth**. The project empowers students to think critically about environmental issues while developing essential digital and intercultural skills.

**Blooming’** calls to mind nature and the environment; The theme for all the digital artefacts to be created throughout the project is **‘sustainability’**.

From interactive workshops and podcasts to student-designed booklets, Blooming Digital celebrates diversity, creativity, and the power of international collaboration in education.

<div style="text-align: center; margin-top: 60px;">

  <!-- School Logos Row -->
  <div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap; margin-bottom: 20px;">
    <div style="width: 100px; height: 80px; display: flex; align-items: center; justify-content: center;">
      <img src="assets/images/logo_pt.jpg" alt="Portugal School" style="max-height: 80px; max-width: 100%; object-fit: contain;">
    </div>
    <div style="width: 100px; height: 80px; display: flex; align-items: center; justify-content: center;">
      <img src="assets/images/logo_ir.png" alt="Ireland School" style="max-height: 80px; max-width: 100%; object-fit: contain;">
    </div>
    <div style="width: 100px; height: 80px; display: flex; align-items: center; justify-content: center;">
      <img src="assets/images/logo_ro.png" alt="Romania School" style="max-height: 80px; max-width: 100%; object-fit: contain;">
    </div>
    <div style="width: 100px; height: 80px; display: flex; align-items: center; justify-content: center;">
      <img src="assets/images/logo_tr.png" alt="Türkiye School" style="max-height: 80px; max-width: 100%; object-fit: contain;">
    </div>
  </div>

  <!-- Country Flags Row -->
  <div style="display: flex; justify-content: center; gap: 40px; flex-wrap: wrap;">
    <img src="assets/images/pt.svg" alt="Portugal Flag" width="100">
    <img src="assets/images/ie-flag.png" alt="Ireland Flag" width="100">
    <img src="assets/images/ro.svg" alt="Romania Flag" width="100">
    <img src="assets/images/tr.svg" alt="Türkiye Flag" width="100">
  </div>

</div>



## 🎓 Look at the amazing work of our students!

<div style="width: 100%; max-width: 800px; margin: 0 auto; position: relative; text-align: center;">

  <input type="radio" name="slider" id="slide1" checked style="display: none;">
  <input type="radio" name="slider" id="slide2" style="display: none;">
  <input type="radio" name="slider" id="slide3" style="display: none;">
  <input type="radio" name="slider" id="slide4" style="display: none;">

  <div style="display: flex; overflow: hidden; position: relative; height: 450px;">
    <div style="display: flex; width: 400%; transition: transform 0.5s ease;
                transform: translateX(calc(
                  -100% * (var(--slide, 0))
                ));">

      <!-- Slide 1: Spotify -->
      <div style="flex: 1 0 100%; padding: 20px;">
        <iframe style="border-radius:12px" 
          src="https://open.spotify.com/embed/show/0VX7Q2XRQ1vbJ6FQwVwPUs?utm_source=generator" 
          width="100%" height="152" frameborder="0" allowfullscreen="" 
          allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy">
        </iframe>
        <p><strong>🎧 Listen to our Podcast!</strong></p>
      </div>


    <!-- Slide 2: PDF Booklet with preview -->
    <div style="flex: 1 0 100%; padding: 20px;">
    <a href="assets/LiveableEarth_A4_Dec24.pdf" download>
        <img src="assets/images/booklet_preview.png" alt="Booklet Preview" style="max-width: 100%; max-height: 300px; border: 1px solid #ccc;">
    </a>
    <p><strong>📘 Click to download the student booklet</strong></p>
    </div>


      <!-- Slide 3: Certificate -->
      <div style="flex: 1 0 100%; padding: 20px;">
        <img src="assets/images/certificate.jpg" alt="Certificate" style="max-width: 100%; max-height: 300px;">
        <p><strong>🏅 Certificate of Participation</strong></p>
      </div>

      <!-- Slide 4: Group Photo -->
      <div style="flex: 1 0 100%; padding: 20px;">
        <img src="assets/images/group_photo_pt.jpg" alt="Group Photo" style="max-width: 100%; max-height: 300px;">
        <p><strong>📸 Students collaborating in action</strong></p>
      </div>
    </div>
  </div>

  <!-- Navigation Dots -->
  <div style="margin-top: 10px;">
    <label for="slide1" style="cursor: pointer; margin: 0 5px;">⬤</label>
    <label for="slide2" style="cursor: pointer; margin: 0 5px;">⬤</label>
    <label for="slide3" style="cursor: pointer; margin: 0 5px;">⬤</label>
    <label for="slide4" style="cursor: pointer; margin: 0 5px;">⬤</label>
  </div>
</div>

<style>
:has(#slide1:checked) {
  --slide: 0;
}
:has(#slide2:checked) {
  --slide: 1;
}
:has(#slide3:checked) {
  --slide: 2;
}
:has(#slide4:checked) {
  --slide: 3;
}
</style>

<hr style="margin-top: 80px;">

<div style="display: flex; align-items: center; background-color: #f1f1f1; padding: 20px; flex-wrap: wrap;">

  <img src="assets/images/EU_eramus_message_flag.jpeg" alt="EU Flag" style="height: 110px; margin-right: 20px;">

  <p style="flex: 1; text-align: center; font-weight: bold; font-size: 1.1rem; margin: 0;">
    Funded by the Erasmus+ Programme of the European Union
  </p>

</div>



<style>
.page-header {
  display: none !important;
}
</style>