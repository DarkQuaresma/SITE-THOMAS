Portfolio de Thomas
  Portfolio personnel one-page pour un graphiste, présentant son profil, ses articles de blog, ses travaux en vedette et un formulaire de contact. Le site est réalisé en HTML5 et CSS, sans JavaScript ni framework.

Fonctionnalités
  Barre de navigation avec liens vers le blog, le portfolio et le contact
  Présentation et bouton de téléchargement du CV
  Section d'articles récents
  Section de travaux en vedette (projets avec image, année et type)
  Section de contact : coordonnées, liens vers les réseaux sociaux et formulaire
  Pied de page avec icônes sociales
  Mise en page adaptée aux petits écrans (à partir de 768 px)

Structure des fichiers
  text
  portfolio/
  ├── index.html
  ├── style.css
  └── images/
      ├── logo.png
      ├── menu.png
      ├── Ellipse.png
      ├── dashboard.png
      ├── illustration.png
      ├── typography.png
      ├── insta.png
      ├── X.png
      ├── Facebook.png
      └── Linkedin.png
  Le dossier images/ doit être placé à la racine, à côté de index.html.

Prérequis
  Un navigateur web récent (Chrome, Firefox, Edge, Safari)
  Une connexion internet pour charger la police Heebo depuis Google Fonts

Police de caractères
  Le site utilise la police Heebo, de Google Fonts, pour l'ensemble des textes (titres, paragraphes, liens, formulaire).
  Source : Google Fonts
  Graisses disponibles : de 100 (Thin) à 900 (Black), selon la plage wght@100..900 chargée dans index.html
  Chargement : la police est importée dans la balise <head> de index.html. Une connexion internet est donc nécessaire pour l'afficher.
  Repli : si Heebo n'est pas disponible, le navigateur utilise la police sans empattement par défaut (sans-serif).
  Pour utiliser la police sans connexion, téléchargez Heebo depuis Google Fonts et déclarez-la avec @font-face dans style.css.
    Pour changer de police, modifiez le lien Google Fonts dans index.html et la règle font-family dans style.css.

Installation
  Téléchargez ou copiez les fichiers index.html et style.css.
  Créez le dossier images/ et ajoutez-y les images listées ci-dessus.
  Ouvrez index.html dans votre navigateur.
  Aucun serveur n'est nécessaire.

Personnalisation
  Textes : modifiez le contenu dans index.html (nom, description, articles, projets).
  Couleurs : modifiez les valeurs dans style.css, par exemple #FF6464 pour le bouton CV, #142850 pour les badges d'année et #EDF7FA pour le fond de la section blog.
  Coordonnées : remplacez l'adresse email beebs@gmail.com et les liens des réseaux sociaux, qui sont actuellement génériques.
  CV : le lien du bouton « Télécharger mon CV » pointe vers #cv. Remplacez-le par le chemin de votre fichier PDF, par exemple cv.pdf.
