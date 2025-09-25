## 📄 README.md – Template Bootstrap + CSS Personnalisé

````markdown
# 🚀 Template Bootstrap + CSS Personnalisé  

Un template responsive moderne basé sur **Bootstrap 5** et **CSS personnalisé**, incluant un header sticky, une section hero, des services, un album photo, un formulaire de contact et un footer.  
Idéal pour une page de présentation d’école, entreprise, ou portfolio.  

---

## 🛠 Technologies utilisées  

- **HTML5** : Structure du site  
- **Bootstrap 5** : Grille responsive et composants  
- **CSS3 personnalisé** : Variables, animations, effets visuels  
- **Google Fonts (Poppins)** : Typographie moderne  
- **Font Awesome** : Icônes vectorielles  

---

## ⚡ Installation & Utilisation  

1. **Clonez le projet :**
   ```bash
   git clone https://github.com/votre-repo/template-bootstrap-css.git
   cd template-bootstrap-css
````

2. **Ouvrez le fichier dans votre navigateur :**

   ```bash
   open index.html
   ```

3. **Personnalisez les couleurs** via `style.css` si besoin.

---

## 📂 Structure du projet

```
template-bootstrap-css/
│
├── index.html          # Page principale
├── css/
│   └── style.css       # CSS personnalisé
├── assets/
│   ├── img/            # Images utilisées
│   └── icons/          # Icônes supplémentaires si besoin
└── README.md           # Documentation
```

---

## ✨ Fonctionnalités clés

* **Header sticky** : Reste en haut lors du défilement
* **Menu responsive** : Se transforme en hamburger sur mobile
* **Section Hero** : Grand titre + visuel accrocheur
* **Services** : Cartes modernes avec icônes
* **Album photo** : Grille responsive 4 colonnes
* **Contact** : Formulaire simple avec zone de texte
* **Footer minimaliste** : Fond sombre + texte clair
* **Animations CSS** : Cercles animés dans la section hero

---

## 🧩 Explication des classes et attributs Bootstrap

| Classe / Attribut                 | Rôle                                                                |
| --------------------------------- | ------------------------------------------------------------------- |
| `navbar-expand-lg`                | Navbar étendue sur écrans larges, réduite sur mobile                |
| `sticky-top`                      | Colle le header en haut lors du scroll                              |
| `navbar-brand`                    | Élément pour logo ou nom du site                                    |
| `data-bs-toggle="collapse"`       | Déclenche l’ouverture/fermeture du menu sur mobile                  |
| `collapse navbar-collapse`        | Zone du menu rétractable                                            |
| `row g-4`                         | Ligne Bootstrap avec espacement entre colonnes                      |
| `col-md-6`                        | Colonne prenant 50% largeur sur écran ≥768px, 100% sinon            |
| `fw-bold`                         | Texte en gras                                                       |
| `img-fluid`                       | Image responsive                                                    |
| `py-5`                            | Padding vertical taille 5                                           |
| `top-0 start-50 translate-middle` | Position absolue, centré en haut horizontalement (et verticalement) |

---

## 🎨 Personnalisation

* Les couleurs principales sont définies dans `style.css` :

  ```css
  html {
    --var-primary-color: #FDBB11;
    --var-secondary-color: #D57128;
    --var-text-color-dark: #000;
    --var-text-color-white: #fff;
  }
  ```

* Changez simplement les valeurs pour adapter la charte graphique à votre projet.

---

## 📸 Aperçu

![Demo Screenshot](assets/img/demo.png)

---

## 👏 Crédits

* [Bootstrap 5](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com/)
* [Google Fonts](https://fonts.google.com/)

---

## 📜 Licence

Libre d’utilisation pour projets personnels et commerciaux. Attribution recommandée.

```