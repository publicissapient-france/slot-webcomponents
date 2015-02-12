## Communication

Bravo, si vous êtes arrivé jusqu'à cet exercice c'est que vous commencez à comprendre comment fonctionne les web components.

Plus qu'une seule chose, comment communiquer depuis le web component, vers la page et de la page vers le web component ?

![Communication](input.png "Communication")

### Custom element > page

Créez un champ `<input>`.

Faites en sorte que le champ `input` contienne le nom de l'image affichée.

### Page > custom element

#### API

Dans votre web component, créez une méthode `filterUnit(name)` qui prend en paramètre une chaine de caractère et affiche l'image de l'unité correspondante dans le carrousel.

Faites-en sorte qu'à chaque modification du contenu de l'`<input>` l'image du carrousel soit changée en conséquence.

#### Attributs

Ajouter un attribut `filter` à votre web component.

Faites-en sorte qu'à chaque modification de l'attribut l'image du carrousel soit changée en conséquence.
