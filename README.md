# Ohmyfood

Il s'agit d'un site de référencement de restaurants, localisé par ville et/ou quartier.

Sur la page d'acceuil on y retrouve un formulaire de géolocalisation. Une notice du site, ainsi qu'une présentation des restaurants trouvés. Au chargement de la page on a un loader avec un spinner. Les boutons sont animés ainsi que l'icône favori qui se rempli au hover. Les cards restaurants sont cliquable et mènent à la page du restaurant choisi.

Sur les pages 1 à 4, il s'agit de la page du restaurants choisi. On y retrouve la photo, avec une carte du menu. Plusieurs animations sont disponible, au chargement de la page on a un défilement des cards, au hover de ces dernières un encart "check" apparait de droite vers la gauche.

Header : Similaire sur toutes les pages, à l'execption du bouton retour sur les pages restaurants qui permet de retourner sur la page d'acceuil.

Footer : Similaire sur toutes les pages, "contact" est cliquable et ouvre une fenêtre de messagerie avec le mail du site pré-rempli.


J'ai créé le site en html 5, la partie CSS a été conçu avec SASS, et un package.json avec une "dependencies" SASS est disponible pour permettre ca fonctionnalité sur les différents IDE.

Le code est partagé entre la partie html et css (scss)

HTML

5 pages

  index.html = page d'acceuil 
  page1.html = restaurant La palette du goût 
  page2.html = restaurant La note enchantée 
  page3.html = restaurant A la française 
  page4.html = Le délice des sens

CSS / SCSS

4 dossiers

Componants = composants d'une page

  cards = toutes les cartes
  footer = bas de page
  header = en-tête
  
Includes = éléments

  btn = bouton
  default = attribut par défaut
  icons = les icones
  titles = tous les titres
  txt = tous les textes
  
Keyframes = animations

Mixins = raccourcis valeur utilisé plusieurs fois

Pages = les différentes pages du site

  homepage = page d'acceuil
  load = la page du loader
  pages = les pages restaurants
