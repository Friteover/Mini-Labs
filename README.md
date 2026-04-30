# 🔬 Mini Labs

> 10 simulations physiques, chimiques et biologiques entièrement dans le navigateur — aucune dépendance, pur HTML/CSS/JS vanilla.

![Version](https://img.shields.io/badge/version-2.0-blue) ![Licence](https://img.shields.io/badge/licence-MIT-green) ![Taille](https://img.shields.io/badge/taille-fichier%20unique-orange)

---

## ✨ Aperçu

Un laboratoire virtuel interactif couvrant 10 domaines scientifiques fondamentaux. Chaque simulation est pilotée par des curseurs en temps réel, affiche les formules associées et met à jour les métriques instantanément.

---

## 🧪 Simulations disponibles

### Physique
| Simulation | Loi modélisée | Paramètres |
|---|---|---|
| **Pendule simple** | T = 2π√(L/g) | Longueur, angle, amortissement |
| **Tir parabolique** | x = v₀cos(θ)t, y = v₀sin(θ)t − ½gt² | Vitesse initiale, angle |
| **Superposition d'ondes** | y = Σ Aᵢ·sin(2πfᵢt + φᵢ) | Amplitude, fréquence, phase |
| **Orbites de Kepler** | T² ∝ a³/M, F = GMm/r² | Masse, distance, excentricité |
| **Oscillateur masse-ressort** | F = −kx, T = 2π√(m/k) | Raideur, masse, amortissement |
| **Double pendule (chaos)** | Équations de Lagrange | Longueurs, angles initiaux |

### Chimie & Biologie
| Simulation | Loi modélisée | Paramètres |
|---|---|---|
| **Gaz parfait** | PV = nRT | Température, volume, N particules |
| **Cinétique chimique** | d[A]/dt = −k₁[A] + k₂[B] | Concentrations, constantes de vitesse |
| **Double hélice ADN** | Modèle Watson-Crick | Paires de bases, mutations |

### Électronique
| Simulation | Loi modélisée | Paramètres |
|---|---|---|
| **Circuit RC** | Vc(t) = V₀(1 − e^(−t/τ)) | Résistance, capacité, tension |

---

## 🚀 Démarrage rapide

```bash
git clone https://github.com/Friteover/Mini-Labs
cd Mini-Labs
# Ouvrir index.html dans un navigateur — aucune installation requise
open index.html
```

Ou directement via GitHub Pages :
```
https://friteover.github.io/Mini-Labs/
```

---

## 🛠️ Stack technique

- **HTML5 Canvas** — rendu des animations en temps réel
- **Vanilla JS** — zéro framework, zéro dépendance
- **CSS Variables** — thème clair/sombre automatique
- **requestAnimationFrame** — boucle de simulation fluide (60 fps)

---

## 📐 Architecture

```
index.html          ← fichier unique auto-contenu
├── <style>         ← variables CSS + mise en page
├── <canvas>        ← rendu par simulation (×10)
└── <script>        ← moteurs physiques indépendants
    ├── Pendule     ← intégration d'Euler
    ├── Projectile  ← cinématique 2D
    ├── Ondes       ← superposition sinusoïdale
    ├── Orbites     ← mécanique céleste (Kepler)
    ├── Ressort     ← oscillateur amorti
    ├── Gaz         ← simulation de particules (brownien)
    ├── Réaction    ← cinétique chimique ODE
    ├── ADN         ← visualisation hélice 3D→2D
    ├── Circuit RC  ← charge/décharge exponentielle
    └── Chaos       ← double pendule (Runge-Kutta)
```

---

## 🎯 Fonctionnalités clés

- **Temps réel** — tous les paramètres sont ajustables pendant la simulation
- **Mode sombre/clair** — s'adapte automatiquement à la préférence système
- **Formules affichées** — chaque simulation montre les équations utilisées
- **Métriques live** — valeurs calculées mises à jour à chaque frame
- **Effet papillon** — le double pendule permet de cloner un pendule avec une infime différence pour visualiser la divergence chaotique

---

## 📚 Concepts scientifiques couverts

`Mécanique classique` `Cinématique` `Oscillations` `Mécanique céleste` `Thermodynamique` `Physique statistique` `Cinétique chimique` `Biologie moléculaire` `Électronique analogique` `Théorie du chaos`

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! Idées pour de nouvelles simulations :

- [ ] Diffraction et interférence lumineuse
- [ ] Simulation d'évolution (algorithme génétique)
- [ ] Électrostatique (champ de Coulomb)
- [ ] Dynamique des fluides (Navier-Stokes simplifié)
- [ ] Relativité restreinte (dilatation du temps)

---

## 📄 Licence

MIT — libre d'utilisation pour l'éducation et les projets personnels.

---

<p align="center">Crée Par Friteover</p>
