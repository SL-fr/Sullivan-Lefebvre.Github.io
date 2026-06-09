---
title: Projets & TP
icon: fas fa-project-diagram
order: 3
layout: page
---

<style>
  .tp-category-title {
    text-align: center;
    font-size: 1.15rem;
    font-weight: 700;
    color: #fff;
    margin: 40px 0 5px;
    padding-top: 20px;
    border-top: 1px solid #333;
  }

  .tp-category-title:first-of-type {
    border-top: none;
    margin-top: 10px;
  }

  .tp-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 18px;
    max-width: 860px;
    margin: 0 auto 20px auto;
  }

  .tp-card {
    background: #ffffff;
    border-radius: 12px;
    padding: 20px 15px 15px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
  }

  .tp-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
  }

  .tp-card img {
    width: 80px;
    height: 80px;
    object-fit: contain;
    border-radius: 8px;
  }

  .tp-card-title {
    font-size: 0.88rem;
    font-weight: 600;
    color: #1a1a1a;
  }

  .tp-card-desc {
    font-size: 0.78rem;
    color: #555;
    line-height: 1.4;
  }

  .tp-badges {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 4px;
  }

  .badge {
    display: inline-block;
    padding: 3px 10px;
    border-radius: 20px;
    font-size: 0.72rem;
    font-weight: 600;
    text-decoration: none;
    transition: opacity 0.2s;
  }

  .badge:hover { opacity: 0.8; }

  .badge-pdf {
    background: #1a1a1a;
    color: #fff;
  }

  .badge-pt {
    background: #e8f4fd;
    color: #1565c0;
    border: 1px solid #90caf9;
  }
</style>

<!-- ───────────── TECHNIQUES ───────────── -->
<div class="tp-category-title">🖥️ Travaux pratiques et techniques – 1ère année</div>

<div class="tp-grid">

  <div class="tp-card">
    <img src="/assets/tp/dns.png" alt="DNS" onerror="this.style.display='none'">
    <div class="tp-card-title">TP DNS</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-dns.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/vlan.png" alt="VLAN" onerror="this.style.display='none'">
    <div class="tp-card-title">TP VLAN</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-vlan.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/vtp.png" alt="VTP" onerror="this.style.display='none'">
    <div class="tp-card-title">TP VTP</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-vtp.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/ssh.png" alt="SSH" onerror="this.style.display='none'">
    <div class="tp-card-title">TP SSH</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-ssh.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/glpi.png" alt="GLPI" onerror="this.style.display='none'">
    <div class="tp-card-title">Gestion des incidents / GLPI</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-glpi.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/routage-statique.png" alt="Routage statique" onerror="this.style.display='none'">
    <div class="tp-card-title">Routage statique</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-routage-statique.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/routage-dynamique.png" alt="Routage dynamique" onerror="this.style.display='none'">
    <div class="tp-card-title">Routage dynamique</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-routage-dynamique.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/inter-vlan.png" alt="Inter-VLAN" onerror="this.style.display='none'">
    <div class="tp-card-title">Routage inter-VLAN</div>
    <div class="tp-badges">
      <a href="/assets/pdf/tp-inter-vlan.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

</div>

<!-- ───────────── CYBERSÉCURITÉ ───────────── -->
<div class="tp-category-title">🛡️ Travaux pratiques de cybersécurité – 1ère année</div>

<div class="tp-grid">

  <div class="tp-card">
    <img src="/assets/tp/bonnes-pratiques.png" alt="Bonnes pratiques" onerror="this.style.display='none'">
    <div class="tp-card-title">Bonnes pratiques</div>
    <div class="tp-card-desc">Étude des règles essentielles de cybersécurité : mots de passe robustes, mises à jour, sauvegardes et comportements sûrs face aux cybermenaces.</div>
    <div class="tp-badges">
      <a href="/assets/pdf/cyber-bonnes-pratiques.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/byod.png" alt="BYOD" onerror="this.style.display='none'">
    <div class="tp-card-title">BYOD</div>
    <div class="tp-card-desc">Analyse des enjeux liés à l'utilisation d'appareils personnels en milieu professionnel : risques, politique de sécurité et conformité RGPD.</div>
    <div class="tp-badges">
      <a href="/assets/pdf/cyber-byod.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/charte.png" alt="Charte informatique" onerror="this.style.display='none'">
    <div class="tp-card-title">Charte informatique</div>
    <div class="tp-card-desc">Rédaction et analyse d'un document juridique définissant les règles d'utilisation des ressources numériques en entreprise, en conformité avec le RGPD.</div>
    <div class="tp-badges">
      <a href="/assets/pdf/cyber-charte.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/acces-privileges.png" alt="Gestion des accès" onerror="this.style.display='none'">
    <div class="tp-card-title">Gestion des accès et privilèges</div>
    <div class="tp-card-desc">Mise en place d'une politique IAM : contrôle des droits d'accès des utilisateurs, gestion des rôles et principe du moindre privilège pour sécuriser le système d'information.</div>
    <div class="tp-badges">
      <a href="/assets/pdf/cyber-acces-privileges.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

  <div class="tp-card">
    <img src="/assets/tp/segmentation.png" alt="Segmentation réseau" onerror="this.style.display='none'">
    <div class="tp-card-title">Segmentation réseau</div>
    <div class="tp-card-desc">Division du réseau en sous-réseaux isolés via des VLANs et pare-feux pour limiter la propagation des attaques et protéger les ressources critiques.</div>
    <div class="tp-badges">
      <a href="/assets/pdf/cyber-segmentation.pdf" class="badge badge-pdf">PDF</a>
    </div>
  </div>

</div>
