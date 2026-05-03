# 🔐 Projet : Ransomware éducatif en Python

## 📌 Description
Ce projet a été réalisé dans le cadre d’un module de cybersécurité.  
Il vise à comprendre le fonctionnement des ransomwares à des fins pédagogiques uniquement.

⚠️ **Important :**
Ce projet est strictement éducatif et doit être exécuté dans un environnement contrôlé.

---

## 🎯 Objectifs
- Comprendre le chiffrement symétrique
- Manipuler des fichiers avec Python
- Implémenter un système de chiffrement/déchiffrement
- Étudier les mécanismes des ransomwares

---

## 🛠️ Technologies utilisées
- Python 3
- Bibliothèque `cryptography` (Fernet)

---

## 📂 Structure du projet
```
ransomware/
│── rans.py        # Script de chiffrement
│── decrypt.py     # Script de déchiffrement
│── theKey.key     # Clé générée automatiquement
│── README.md
```

---

## ⚙️ Installation

### 1. Cloner le projet
```bash
git clone https://github.com/ton-username/ransomware-project.git
cd ransomware-project
```

### 2. Installer les dépendances
```bash
pip install cryptography
```

---

## ▶️ Utilisation

### 🔒 Chiffrement
```bash
python rans.py
```

### 🔓 Déchiffrement
```bash
python decrypt.py
```

---

## 🔐 Fonctionnement
- Génération d'une clé de chiffrement
- Chiffrement des fichiers du dossier
- Stockage de la clé dans `theKey.key`
- Déchiffrement avec authentification (phrase secrète)

---

## ⚠️ Avertissement
Ce projet est uniquement à but éducatif.  
Toute utilisation malveillante est illégale.

---

## 👨‍💻 Auteur
- Chaima Charif
- Cycle d’ingénieur SIT 1

---

## 📚 Conclusion
Ce projet permet de mieux comprendre les attaques ransomware et les techniques de protection associées.
