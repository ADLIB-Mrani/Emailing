# 📝 Instructions CodePen - Projet 1

## 🚀 Démarrage en 3 Étapes

### Étape 1 : Ouvrir CodePen
Allez sur : **https://codepen.io/pen/**

Vous verrez 3 panneaux vides :
- HTML (à gauche)
- CSS (au milieu)
- JS (à droite)

---

### Étape 2 : Copier-Coller le Code

#### 📄 Code HTML
1. Ouvrez le fichier **`codepen-html.html`**
2. Sélectionnez TOUT le contenu (Ctrl+A)
3. Copiez (Ctrl+C)
4. Collez dans le panneau **HTML** de CodePen

#### 🎨 Code CSS
1. Ouvrez le fichier **`codepen-css.css`**
2. Sélectionnez TOUT le contenu (Ctrl+A)
3. Copiez (Ctrl+C)
4. Collez dans le panneau **CSS** de CodePen

#### ⚡ Code JavaScript
1. Ouvrez le fichier **`codepen-js.js`**
2. Sélectionnez TOUT le contenu (Ctrl+A)
3. Copiez (Ctrl+C)
4. Collez dans le panneau **JS** de CodePen

---

### Étape 3 : Voir le Résultat ! 🎉

Le site apparaît **automatiquement** dans la zone de prévisualisation en bas !

---

## 💾 Sauvegarder Votre Travail

### Option 1 : Sans Compte (Temporaire)
- Votre travail est sauvegardé automatiquement dans votre navigateur
- ⚠️ Se perd si vous videz le cache

### Option 2 : Avec Compte (Recommandé - Gratuit)
1. Cliquez sur "Sign Up" en haut à droite
2. Créez un compte gratuit
3. Cliquez sur "Save" ou "Fork"
4. Vous obtenez une URL permanente !
   - Exemple : `https://codepen.io/votre-nom/pen/aBcDeF`

---

## 🎨 Personnaliser Votre Site

### Changer le Nom de l'Agence
Dans le panneau HTML, cherchez :
```html
<h1>EmailPro</h1>
```
Remplacez par votre nom :
```html
<h1>Mon Agence</h1>
```

### Changer la Couleur Principale
Dans le panneau CSS, cherchez :
```css
--primary-color: #2563eb;
```
Changez la couleur (exemples) :
```css
--primary-color: #10b981;  /* Vert */
--primary-color: #8b5cf6;  /* Violet */
--primary-color: #f59e0b;  /* Orange */
```

### Changer les Statistiques
Dans le panneau JS, cherchez :
```javascript
const STATS_TARGETS = {
    clients: 500,
    emails: 10000000,
    satisfaction: 95
};
```
Modifiez les nombres selon vos besoins.

---

## 📱 Tester sur Mobile

Dans CodePen :
1. Cliquez sur "Change View"
2. Sélectionnez "Editor on right" ou "Editor on left"
3. La zone de prévisualisation s'agrandit
4. Redimensionnez votre navigateur pour simuler un mobile

---

## 🔗 Partager Votre Site

### URL à Partager
Après avoir sauvegardé :
- Copiez l'URL de votre Pen
- Exemple : `https://codepen.io/username/pen/xxxxx`
- Partagez cette URL avec qui vous voulez !

### Mode Plein Écran
Ajoutez `/full` à la fin de l'URL :
- Avant : `codepen.io/username/pen/xxxxx`
- Après : `codepen.io/username/pen/xxxxx/full`
- Le site s'affiche sans l'éditeur CodePen !

---

## 🛠️ Fonctionnalités CodePen Utiles

### Auto-Save
- CodePen sauvegarde automatiquement toutes les 2 secondes
- Un petit point vert indique que c'est sauvegardé

### Console
- Cliquez sur "Console" en bas
- Voir les messages JavaScript et les erreurs

### Format Code
- Sélectionnez le code
- Clic droit → "Format Code"
- Le code devient plus lisible

### Rechercher
- `Ctrl + F` (ou `Cmd + F` sur Mac)
- Rechercher dans le code

---

## ⚠️ Problèmes Courants

### Le site ne s'affiche pas
✅ **Solution :**
1. Vérifiez que les 3 panneaux (HTML, CSS, JS) ont du code
2. Ouvrez la console (F12) pour voir les erreurs
3. Rafraîchissez la page (Ctrl+R)

### Les couleurs sont bizarres
✅ **Solution :**
1. Vérifiez que le CSS est dans le bon panneau
2. Cherchez `--primary-color:` dans le CSS

### Le formulaire ne marche pas
✅ **Solution :**
1. C'est normal ! Le formulaire simule l'envoi
2. Regardez dans la console : vous verrez les données
3. Pour un vrai formulaire, il faut un backend

### J'ai perdu mon travail
✅ **Solution :**
- Si vous n'étiez pas connecté, c'est malheureusement perdu
- Créez un compte pour éviter ce problème
- Utilisez "Fork" pour créer une copie sauvegardée

---

## 🎓 Aller Plus Loin

### Ajouter des Images
Dans le HTML :
```html
<img src="URL_DE_L_IMAGE" alt="Description">
```

Vous pouvez utiliser :
- Unsplash : https://source.unsplash.com/800x600/?business
- Placeholder : https://via.placeholder.com/800x600

### Ajouter des Icônes
Dans le panneau CSS, ajoutez dans Settings → CSS :
- Font Awesome : https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css

Puis dans le HTML :
```html
<i class="fa fa-envelope"></i>
```

### Animations Supplémentaires
Cherchez "CSS animations" dans la documentation CodePen.

---

## 🆘 Besoin d'Aide ?

### Ressources CodePen
- Documentation : https://blog.codepen.io/documentation/
- Tutoriels : https://codepen.io/topics/
- Communauté : Recherchez "email template" sur CodePen

### Autres Tutoriels
- HTML : https://www.w3schools.com/html/
- CSS : https://www.w3schools.com/css/
- JavaScript : https://www.w3schools.com/js/

---

## ✅ Checklist Finale

Avant de partager votre site :

- [ ] Le site s'affiche correctement
- [ ] Vous avez changé "EmailPro" par votre nom
- [ ] Les couleurs vous plaisent
- [ ] Le texte est correct (pas de fautes)
- [ ] Le site est responsive (testé sur mobile)
- [ ] Vous avez sauvegardé votre Pen
- [ ] Vous avez testé l'URL de partage

---

## 🎉 Félicitations !

Vous avez maintenant un site web d'agence d'emailing fonctionnel, accessible depuis n'importe où, sans avoir rien installé !

---

**Temps total estimé :** 5-10 minutes
**Difficulté :** Très facile
**Coût :** 0€

**Bon codage ! 🚀**
