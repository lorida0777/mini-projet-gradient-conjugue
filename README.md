# ⚙️ Projet Gradient Conjugué pour Matrices Creuses

## 📖 Description

Ce projet consiste à implémenter la méthode du **gradient conjugué** pour résoudre des systèmes linéaires avec des matrices creuses, symétriques et définies positives.  
L'objectif est aussi d'utiliser des préconditionneurs (Jacobi, SSOR) pour améliorer la convergence.  

Des comparaisons entre une version **NumPy** et une version **SciPy** sont réalisées, avec des visualisations graphiques de la convergence.

---

## 📂 Structure du dépôt
```
📁 mini-projet-gradient-conjugue
├── 📄 README.md
├── 📦 requirements.txt
├── 📂 scr/
│ ├── 📓 gradient_conjugue_numpy.ipynb
│ └── 📓 gradient_conjugue_scipy.ipynb
├── 📂 results/
│ ├── 📊 Comparaison_de_la_convergence_numpy.png
│ └── 📊 Comparaison_de_la_convergence_scipy.png
├── 📂 repports/
│ ├── 📄 repport.tex
│ ├── 📄 repport.pdf
│ ├── 🖼️ logo.jpg
│ ├── 📊 Comparaison_de_la_convergence_numpy.png
│ └── 📊 Comparaison_de_la_convergence_scipy.png
```
- 📄 **README.md** : ce fichier de présentation.  
- 📦 **requirements.txt** : dépendances Python nécessaires.  
- 📑 **repport.tex** & **repport.pdf** : rapport détaillé en LaTeX et PDF.  
- 🖼️ **logo.jpg** : logo du projet.  
- 📂 **scr/** : scripts sources et notebooks Jupyter.  
- 📊 **results/** : résultats générés par le programme.  
- 📈 **repports/** : images des comparaisons de convergence.

---

## 🚀 Installation

Pour installer les dépendances Python, exécute :

```bash
pip install -r requirements.txt
```
---

##▶️ Exécution
Pour lancer le projet, ouvrir et exécuter les notebooks suivants dans le dossier scr/ :

gradient_conjugue_numpy.ipynb

gradient_conjugue_scipy.ipynb

Les résultats et graphiques seront enregistrés dans results/ et repports/.

## 📝 Rapport
Le rapport complet est disponible en PDF : repport.pdf
Tu peux aussi consulter la source LaTeX dans repport.tex.

## 👤 Auteur
ANDRIATSIFERANA No Kanto Lorida
ZO Manampisoa Hermann

Merci pour votre attention ! 🙏
