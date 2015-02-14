## Shadow DOM

- au lieu d'ajouter le template directement dans le noeud `<boom-carrousel/>` faites-en sorte de créer un noeud fantôme
- inspecter le dom créé

![Shadow DOM](png/shadow.png "Shadow DOM")

### Encapsulation du CSS

Ajouter dans `index.html` le snippet suivant : 
```
<style>
  img {
    background-color: red;
  }
</style>
```

Pourquoi il n'y a pas d'impact sur votre component ?
Comment faire pour appliquer le [style](http://www.html5rocks.com/en/tutorials/webcomponents/shadowdom-201/) depuis l'extérieur du web component ?

- essayez temporarement de revenir à la version présedent de votre component (sans shadow root)

[Prev](html_import.md) [Next](behaviour.md)
