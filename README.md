# 🛰️ OpenGeoAI – Analyse d’images satellites assistée par IA

> Détection intelligente d’objets (routes, bâtiments, incendies…) sur des images satellites, avec visualisation sur carte interactive.

---

## 📌 Présentation

**OpenGeoAI** est une application web open-source permettant de :

- 📥 Uploader une image satellite
- 🧠 Lancer une détection d’objets simulée (routes, bâtiments, feux, etc.)
- 🗺️ Afficher les résultats sur une carte interactive via Folium

Un excellent point de départ pour un système de vision par ordinateur géospatial avec possibilité d’ajouter un modèle réel (YOLOv5, SAM, etc.).

---

## ⚙️ Stack technique

- [Python 3](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Folium](https://python-visualization.github.io/folium/)
- [PIL (Pillow)](https://python-pillow.org/)
- (À venir : [PyTorch](https://pytorch.org/) pour intégrer un vrai modèle de détection)

---

## 📸 Fonctionnalités

- ✅ Upload d’image satellite (PNG, JPG, JPEG)
- ✅ Détection d’objets simulée (routes, bâtiments, incendies)
- ✅ Carte interactive centrée sur des coordonnées personnalisables
- ✅ Interface simple et rapide avec Streamlit
- 🔄 Logique prête à être connectée à un vrai modèle IA
