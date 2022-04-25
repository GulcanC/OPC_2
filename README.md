
### :large_orange_diamond: Open Classrooms Projet 2

Dynamisez une page web avec des animations CSS

### :large_orange_diamond: Visitez la page du projet
🔗 https://gulcanc.github.io/OPC_2/

### :large_orange_diamond: A Propos du Projet
Au sein du Projet n°2 du parcours Développeur Web chez OpenClassrooms j'ai realizé un site web responsive en utilisant les langages CSS3, HTML5 et avec un préprocesseur CSS appelé Sass. 

**Sass** signifie Syntactically Awesome Style Sheet, une technologie qui améliore mon codebase et je simplifie la vie! 

D'ailleurs, j'ai utilisé **autoprixer** pour ce projet. **Autoprefixer** est un plugin qui vous évitera de -webkit-, -o- et -moz-. Il ajoute automatiquement des préfixes à votre CSS. Il vous suffit de lui fournir une feuille CSS et il passera par là pour ajouter les préfixes si nécessaire.

Par ai



* Pour les éléments parents:

  display:flex
  
  flex-direction: row | row-reverse | column | column-reverse
  
  flex-wrap: nowrap | wrap | wrap-reverse
  
  flex-flow: column wrap
  
  justify-content: flex-start | flex-end | center | space-between | space-around
  
  align-items: stretch | flex-start | flex-end | center | baseline 
  
* Pour les éléments enfants:

  flex: none |  <'flex-grow'> <'flex-shrink'>? || <'flex-basis'>
  
  flex:1
  
  flex:2

Pour ce projet, mon site web est le site web d’une petite entreprise proposant un outil de planification de vacances. Mon site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur  ambiance.

### :large_orange_diamond: Les Objectifs du Projet

💧 Découper et d’intégrer une maquette 

💧 Traduire la maquette en langage web, c’est-à-dire en HTML et en CSS

💧 Créer un site web qui consultera à la fois sur un portable, une tablette ou un ordinateur sans perdre en lisibilité et en vitesse de chargement

💧 La validitıon du code auprès du W3C [La validation pour HTML](https://validator.w3.org/) | [La validation pour CSS](https://jigsaw.w3.org/css-validator/)

💧 Pratiquer le technique flex box

💧 Pratiquer les sélecteurs CSS et les balises HTML

💧 Utiliser les cartes et les images d’arrière-plan dans le projet

💧 Utiliser FontAwsom icons

💧 Création d'une barre de navigation

💧 Utiliser la liste non ordonnée


### ☑️ Les Techniques Utilisés

Lorsqu'on travaille avec **les boîtes flexibles**, deux axes interviennent : l'axe principal (main axis en anglais) et l'axe secondaire (cross axis en anglais)

**Flexbox** est une méthode de mise en page selon un axe principal, permettant de disposer des éléments en ligne ou en colonne.

Pour créer un conteneur flexible, il faut que la valeur de la propriété display de cet élément soit flex ou inline-flex. Dès que c'est le cas, les éléments « enfants » directs deviennent des éléments flexibles (flex items).

Pour obtenir le « passage à la ligne », on ajoute la propriété **flex-wrap** avec la valeur **wrap**. Donc, si les éléments sont trop grands pour tenir sur une seule ligne, ils passeront sur une autre ligne.

Il est possible de synthétiser les propriétés **flex-direction** et **flex-wrap** avec la propriété raccourcie **flex-flow**.

La propriété raccourcie **flex** permet de définir les valeurs de la propriété dans cet ordre : **flex-grow**, **flex-shrink**, **flex-basis**

La propriété **align-items** permet d'aligner les éléments le long de l'axe secondaire. La valeur initiale de cette propriété est **stretch** que les éléments flexibles sont étirés sur l'axe perpendiculaire afin d'avoir la même taille que l'élément le plus grand dans cet axe. La valeur **flex-start** afin que les éléments soient alignés sur la ligne de début de l'axe secondaire, la valeur **flex-end** afin que les éléments soient alignés sur la ligne de fin de l'axe secondaire ou bien **center** pour les aligner au centre.

La propriété **justify-content** est utilisée afin d'aligner les éléments le long de l'axe principal dans la direction définie par flex-direction. La valeur initiale est **flex-start** qui place les éléments à partir de la ligne de début du conteneur sur l'axe principal. La valeur **flex-end** permet de les placer vers la fin et la valeur **center** permet de les centrer le long de l'axe principal. On peut également utiliser la valeur **space-between** afin de répartir l'espace disponible de façon égale entre chaque élément. Si on souhaite que l'espace soit également réparti autour des éléments, y compris au début et à la fin, on pourra utiliser la valeur **space-around**. Si on souhaite que l'espace soit également réparti et qu'il y ait un espace entier au début et à la fin, on utilisera la valeur **space-evenly**.
