
# TheSportsDB Tool

> Application graphique avancée pour gérer, rechercher et éditer des événements sportifs, équipes, joueurs et résultats sur [TheSportsDB.com](https://www.thesportsdb.com), avec navigateur intégré, recherche multicritère et bloc-notes.

**Dépôt officiel :** [https://github.com/Madumtv/thesportdbtool](https://github.com/Madumtv/thesportdbtool)

---

## ✨ Fonctionnalités

- **Connexion rapide** à TheSportsDB (identifiants mémorisés)
- **Navigateur intégré** (`QWebEngineView`) pour interagir avec le site et ses outils d’édition
- **Recherche multicritère** sur les événements (année, compétition, ville, mots-clés…)
- **Recherche rapide** par joueur, numéro de match, résultat, équipe, etc.
- **Saisie intelligente** (auto-synchronisation entre menus déroulants et champs texte)
- **Bloc-notes texte brut intégré**
- **Journal des actions/logs** pour garder trace de toutes vos opérations
- **Interface compacte et adaptable à tous les sports** référencés sur TheSportsDB

---

## 🖼️ Capture d’écran

> *(Ajoute ici un screenshot du programme pour un rendu optimal)*

---

## 🚀 Installation rapide

### 1. **Installer Python (si besoin)**
- [Télécharger Python pour Windows](https://www.python.org/downloads/windows/)  
- ⚠️ *Coche “Add Python to PATH” à l’installation*

### 2. **Cloner ou télécharger ce dépôt**
```sh
git clone https://github.com/Madumtv/thesportdbtool.git
cd thesportdbtool
```
*(ou télécharge et extrais le zip)*

### 3. **(Optionnel) Créer un environnement virtuel**
```sh
python -m venv .venv
.venv\Scriptsctivate
```

### 4. **Installer les dépendances**
```sh
pip install -r requirements.txt
```
ou :
```sh
pip install PyQt5 PyQtWebEngine requests
```

---

## 🖥️ Lancer l’application

```sh
python main.py
```

---

## 🏁 Compilation en exécutable Windows (.exe)

### 1. **Installer PyInstaller**
```sh
pip install pyinstaller
```
### 2. **Générer le .exe (mode rapide recommandé)**
```sh
python -m PyInstaller --windowed main.py
```
- Le `.exe` sera dans `dist\main\main.exe`  
- **Démarrage rapide** : lancer ce `.exe` dans le dossier

### 3. **(Optionnel) Générer un .exe unique**
```sh
python -m PyInstaller --onefile --windowed main.py
```
- Un seul `.exe` dans `dist\main.exe` (plus lent à démarrer)

---

## 📦 requirements.txt

```
PyQt5
PyQtWebEngine
requests
```

---

## ❓ Dépannage

- **ModuleNotFoundError** : Vérifie que tu utilises le bon Python/interpréteur.
- **pyinstaller non reconnu** :  
  Utilise
  ```sh
  python -m pip install pyinstaller
  python -m PyInstaller --windowed main.py
  ```
- **Lenteur .exe** : Privilégie le mode dossier (`--windowed` sans `--onefile`).
- **Distribution** : Zippe le dossier `dist/main/` pour le partager.

---

## 💡 Conseils

- Utilise un **SSD** pour de meilleures performances de lancement.
- Mets à jour les dépendances régulièrement :
  ```sh
  pip install --upgrade PyQt5 PyQtWebEngine pyinstaller
  ```
- Pour ajouter une icône à ton `.exe` :
  ```sh
  python -m PyInstaller --windowed --icon=icone.ico main.py
  ```

---

## 🤝 Contribuer

- Problèmes ? Suggestions ? [Ouvre une issue GitHub](https://github.com/Madumtv/thesportdbtool/issues) ou propose une Pull Request !

---

## 🔗 Liens utiles

- [TheSportsDB.com](https://www.thesportsdb.com)
- [PyQt5](https://pypi.org/project/PyQt5/)
- [PyQtWebEngine](https://pypi.org/project/PyQtWebEngine/)
- [PyInstaller](https://pyinstaller.org/)
- [Requests](https://pypi.org/project/requests/)
- [Dépôt officiel](https://github.com/Madumtv/thesportdbtool)

---

> **Développé par [Madumtv](https://github.com/Madumtv)**
