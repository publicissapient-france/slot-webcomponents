## HTML Import

Actuellement vous n'avez qu'un seul fichier `index.html`.

- faites en sorte d'isoler votre web component dans un autre fichier
- importez-le dans `index.html`



**Tip #1 :** pour acceder au document isolé utilisez `document.currentScript.ownerDocument`

**Tip #2 :** allez regarder du côté de [HTML Import](http://www.html5rocks.com/en/tutorials/webcomponents/imports/).

## Encapsulation du style ?

Ajouter dans `index.html` le code suivant : 

```
<style>
  img {
    background-color: red;
  }
</style>
```

Votre composant est impacté, le fond est rouge.

Comment faire pour que le style extérieur n'impacte pas votre composant ?

[Prev](html_template.md) [Next](shadow_dom.md)
