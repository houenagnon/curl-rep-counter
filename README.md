# 💪 Real-Time Biceps Curl Counter with MediaPipe & OpenCV

Ce projet utilise [MediaPipe](https://google.github.io/mediapipe/) et [OpenCV](https://opencv.org/) pour détecter les mouvements du bras en temps réel et compter automatiquement le nombre de **biceps curls** effectués pendant une séance de musculation.
## 📺 Tutoriel vidéo disponible sur YouTube

🎥 Regardez le tutoriel étape par étape ici :  
[![Regarder sur YouTube](https://img.shields.io/badge/📺%20Tutoriel%20YouTube-Regarder%20la%20vidéo-red?style=for-the-badge)](https://youtu.be/UPrW1I9YXAY)

## 🏋️ Objectif

Fournir un outil simple et efficace permettant aux sportifs de :

* Compter automatiquement leurs répétitions de biceps curls.
* Visualiser leur position et amplitude en temps réel via la webcam.
* Améliorer leur forme grâce à un feedback visuel.

---

## 📦 Fonctionnalités

* 📹 Détection en temps réel avec la webcam.
* 🤖 Suivi précis des articulations (épaule, coude, poignet).
* 🔢 Comptage intelligent des répétitions.
* 📈 Affichage en direct de l’angle du coude et du nombre de répétitions.

---

## 🔧 Dépendances

Assurez-vous d'avoir **Python 3.7+** installé, puis :

```bash
pip install mediapipe opencv-python numpy
```

---

## ▶️ Utilisation

Lancez simplement le script `biceps_counter.py` :

```bash
python biceps_counter.py
```

> Assurez-vous que votre webcam est connectée et activée.

---

## 🧠 Principe de fonctionnement

1. MediaPipe détecte les points clés du corps.
2. Le script calcule l’**angle du coude** à partir des coordonnées de l’épaule, du coude et du poignet.
3. Lorsqu’un cycle complet est détecté (bras tendu → bras plié → bras tendu), une répétition est comptée.

---

## 📁 Structure du projet

```bash
.
├── biceps_counter.py   # Script principal
├── README.md
```

---

## 📸 Aperçu

![demo](https://i.imgur.com/3j8BPdc.png)

---

## ✅ À faire

* [ ] Ajouter un mode d’entraînement avec timer.
* [ ] Exporter les statistiques en CSV.
* [ ] Ajouter une interface graphique (Tkinter ou PyQt).

---

## 🙌 Contribuer

Les contributions sont les bienvenues !
N’hésitez pas à ouvrir une **issue** ou une **pull request**.

---

## 📜 Licence

Ce projet est sous licence **MIT**.
