# ✈️ SkyDash - Dashboard Météo & Trafic Aérien

**SkyDash** est un tableau de bord interactif conçu pour les passionnés d'aviation et de météo. Il regroupe en une seule interface la météo locale, le suivi radar des vols au-dessus de toi et les données météo aéronautiques officielles (METAR & TAF).

---

## ✨ Fonctionnalités

- **🛰️ Suivi en direct du trafic aérien :** Carte Leaflet affichant les avions en survol autour de ta position grâce à l'API OpenSky Network.
- **⛅ Météo locale dynamique :** Géolocalisation automatique pour afficher la température, les conditions, le vent et la couverture nuageuse en temps réel via Open-Meteo.
- **🛩️ METAR & TAF Aéronautique :** Recherche par code OACI (ex: `CYHU`, `CYUL`, `CYQB`) avec décodage des conditions de vol (VFR, MVFR, IFR, LIFR).
- **🎨 Interface Cockpit / Dark Mode :** Design moderne en Glassmorphism optimisé pour desktop et mobile.

---

## 🛠️ Technologies utilisées

- **Frontend :** HTML5, CSS3, JavaScript ES6+
- **APIs Web :** 
  - [OpenSky Network API](https://opensky-network.org/) — Données de suivi des vols
  - [Open-Meteo API](https://open-meteo.com/) — Météo locale
  - [AVWX Aviation Weather API](https://avwx.rest/) — Rapports METAR / TAF
- **Cartographie :** [Leaflet.js](https://leafletjs.com/) & OpenStreetMap

---

## 🚀 Installation & Utilisation

Aucune installation complexe ni serveur requis ! Le projet s'exécute directement dans le navigateur.

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/RyzeOut1/skydash.git](https://github.com/RyzeOut1/skydash.git)
   cd skydash
