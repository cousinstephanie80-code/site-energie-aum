---
layout: default
title: À Propos | Energie de l'Aum
---

<div class="split-screen">
  
  <div class="split-text">
    <h1 class="editorial-title">L'Harmonie <br>Retrouvée</h1>
    
    <div class="editorial-content">
      <p>Bonjour, je suis <strong>Mélanie</strong>.</p>
      
      <p>Bienvenue dans mon univers. Mon cabinet, niché au cœur de <strong>Marseillan</strong>, a été pensé comme un refuge. Une parenthèse hors du temps, loin du tumulte, pour vous permettre de déposer vos charges et de renouer avec votre essence profonde.</p>
      
      <p>Maître Enseignante Reiki et praticienne passionnée, je ne "guéris" pas : j'éveille votre propre potentiel de guérison. Que ce soit par le toucher subtil du Reiki ou la puissance du LaHoChi, chaque séance est une invitation au voyage intérieur.</p>
      
      <p><em>"Le calme est la clé qui ouvre toutes les portes de la conscience."</em></p>
    </div>

    <div style="margin-top: 40px; display: flex; align-items: center; gap: 20px;">
      <img src="assets/images/portrait.jpg" style="width: 80px; height: 80px; border-radius: 50%; object-fit: cover; border: 2px solid #D4AF37;" alt="Mélanie">
      <img src="assets/images/logo.png" style="height: 50px; opacity: 0.7;" alt="Signature">
    </div>

    <div style="margin-top: 40px;">
      <a href="/soins.html" class="btn-outline" style="margin: 0;">Découvrir mes soins</a>
    </div>
  </div>

  <div class="split-image">
    <div class="slide-bg active" style="background-image: url('assets/images/slide1.jpg');"></div>
    <div class="slide-bg" style="background-image: url('assets/images/slide2.jpg');"></div>
    <div class="slide-bg" style="background-image: url('assets/images/slide3.jpg');"></div>
  </div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
  let slides = document.querySelectorAll('.slide-bg');
  let current = 0;
  
  setInterval(function() {
    slides[current].classList.remove('active');
    current = (current + 1) % slides.length;
    slides[current].classList.add('active');
  }, 5000); // Change toutes les 5 secondes
});
</script>