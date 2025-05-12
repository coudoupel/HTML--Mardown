# Conversion HTML → Markdown avec Python

## 1.  Objectif du projet

L’objectif de ce projet est de développer un outil simple et automatisé permettant de convertir un fichier HTML en fichier Markdown.  



## 2. 🔧 Choix technologiques

### a. Langage : Python
- **Pourquoi Python ?**
  - Haut niveau, lisible, rapide à développer.
  - Excellente bibliothèque standard pour le traitement de fichiers.
  - Large écosystème de bibliothèques de conversion et de parsing HTML.

### b. Librairie : `html2text`
- Convertit automatiquement des fichiers HTML vers Markdown.
- Open source et largement utilisée.

## 3. Structure du projet

html_to_markdown/  
├── html_to_markdown.py ← Script principal  
├── page.html ← Exemple de fichier HTML source  
├── page.md← Fichier Markdown généré (output)  
└── README.md← Instructions et explications

## 4. Procédure
Installer la librairie :

```bash
pip install html2text
```

Si nécessaire, mettez à jour python : 
```bash
python.exe -m pip install --upgrade pip
```

Exécuter le script avec le fichier html associé :
```bash
python html_to_markdown.py  page.html
```

## 5. Conclusion

Ce projet fournit un outil fiable et léger pour convertir des fichiers HTML en Markdown.  
Le choix de Python et `html2text` m'a permis une implémentation rapide.
Il peut être utilisé dans des workflows de publication, migration de contenus, ou tout contexte où le Markdown est préférable au HTML brut.
