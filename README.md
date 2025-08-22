# Notebooks - Projet Pneumonie

## ⚠️ Problème d'affichage
Certains notebooks peuvent afficher une erreur de rendu sur GitHub :  
`Invalid Notebook: the 'state' key is missing from 'metadata.widgets'`  

➡️ Cela est uniquement dû à un problème lié aux **widgets** utilisés.  
Les notebooks restent parfaitement fonctionnels et peuvent être **téléchargés puis ouverts dans Google Colab ou Jupyter** sans aucun problème.

---

## 📂 Contenu du dépôt

### 1. `Generate10.ipynb`
- Génère **10 images** issues du fine-tuning basé sur mon modèle posté sur **Hugging Face**.

### 2. `ProjetPneumo.ipynb`
- Récupère les données stockées dans un **bucket GCP**.  
- Crée un **classifieur** pour détecter la pneumonie.  
- Réalise une **analyse de performance** du modèle.

### 3. `analyse.ipynb`
- Calcule deux métriques importantes pour la comparaison d’images :
  - **SSIM (Structural Similarity Index Measure)**
  - **PSNR (Peak Signal-to-Noise Ratio)**

### 4. `PneumoVfinale.ipynb`
- Contient le code du **fine-tuning** du modèle.  
- Effectue le **push du modèle final sur Hugging Face**.

---

## 🚀 Utilisation
1. Téléchargez le notebook de votre choix.  
2. Importez-le dans **Google Colab** ou ouvrez-le avec **Jupyter Notebook**.  
3. Exécutez les cellules normalement.

---

## 📌 Remarque
- Le problème d’affichage sur GitHub **n’affecte en rien l’exécution**.  
- Les notebooks peuvent être utilisés tels quels pour reproduire les expériences.
