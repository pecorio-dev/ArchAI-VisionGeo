## 🧠🏛️ ArchAI-VisionGeo

### 🔍 Analyse intelligente de plans architecturaux grâce à l’IA

**ArchAI-VisionGeo** est un projet **public** d’analyse automatisée de plans architecturaux, combinant :

* 🖼️ **Vision par ordinateur** (CNN)
* 📄 **Traitement du langage** (NLP)
* 🌐 **Analyse géospatiale** (GeoPandas)

Développé avec **PyTorch** et **Streamlit**, optimisé GPU, modulaire, et idéal pour **architectes**, **urbanistes**, et **chercheurs**.

⚠️ **Ce texte a été généré en partie par une IA** 🤖. Le projet est **toujours instable**, en cours de test et d’amélioration : soyez patient·e ! 🙏

---

### 👥 Collaboration & Suivi
Pour **toute demande** ou suggestion, laissez un commentaire dans l’onglet **« Feedback »** du Sheet, ou contactez-moi :
✉️ [stream2free.pecorio@gmail.com](mailto:stream2free.pecorio@gmail.com)

---

### 🧰 Fonctionnalités clés

| Fonctionnalité          | Description                                                                 |
| ----------------------- | --------------------------------------------------------------------------- |
| 🔍 Analyse visuelle     | Reconnaissance de styles (moderne, classique…) via CNN (\~1.5 M paramètres) |
| 📝 Extraction textuelle | OCR (Tesseract) + NLP (CamemBERT) pour lire les annotations                 |
| 🗜️ Géolocalisation     | Enrichissement GeoJSON avec GeoPandas                                       |
| 💻 Interface Web        | Application Streamlit interactive                                           |
| ⚡ Optimisation GPU      | Support CUDA 12.1, précision mixte, batch évolutif                          |

---

### 🚀 Installation & Lancement

1. **Cloner le projet** (public) :

   ```bash
   ```

git clone [https://github.com/Pecorio/ArchAI-VisionGeo.git](https://github.com/Pecorio/ArchAI-VisionGeo.git)

````
2. **Créer et activer l’environnement** :  
   ```bash
python -m venv .venv  
source .venv/bin/activate  # Linux/Mac
.\.venv\Scripts\activate    # Windows
````

3. **Installer les dépendances** :

   ```bash
   ```

pip install torch torchvision torchaudio --index-url [https://download.pytorch.org/whl/cu121](https://download.pytorch.org/whl/cu121)
pip install streamlit geopandas rasterio pytesseract sentencepiece pillow numpy pandas --upgrade

````
4. **Installer Tesseract OCR** (si besoin)  
   - Télécharger depuis UB Mannheim  
   - Ajouter `Tesseract-OCR` au `PATH`  
   - Vérifier : `tesseract --version`
5. **Lancer l’application** :  
   ```bash
streamlit run main.py --server.fileWatcherType none
````

---

### 💻 Utilisation

1. Ouvrez votre navigateur à : **[http://localhost:8501](http://localhost:8501)**
2. Sections principales :

   * 📂 **Télécharger Données**
   * 🧠 **Analyse Style & Texte**
   * 🤖 **Chatbot NLP**

**Exemple** :

* Chargez un plan PNG & un GeoJSON →

  * Style prédit (ex. *Moderne*)
  * Texte extrait automatiquement
  * Données géospatiales enrichies 🌍

---

### ⚒️ Statut du projet

🚧 **En développement public** : bugs possibles, évolutions fréquentes.

---


### 📬 Support & Contribution

✨ **Montrez votre intérêt** :

* ⭐ Star & Fork sur GitHub
* 👥 Partagez le projet

Pour questions ou collaborations, toujours :
✉️ [stream2free.pecorio@gmail.com](mailto:stream2free.pecorio@gmail.com)

---

**Merci pour votre soutien et votre patience !**
Pecorio, 17 ans, jeune développeur IA & architecture.
