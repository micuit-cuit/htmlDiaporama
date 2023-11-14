# htmlDiaporama
easy diaporama creator in html
# comment faire
Pour faire un diaporama, mettez les éléments dans une balise <int> avec un attribut display. 
L'attribut display doit contenir le numéro du slide de début et de fin (exemple : display="1-3").
La classe slideX (où X est le numéro du slide) permet de styler les éléments en fonction du slide.
Vous pouvez ajouter du CSS dans la balise <style> avec l'id diaporamaStyle.

Spécifiez le nombre de slides dans maxSlide et la première slide dans slide (exemple : let slide = 0; let maxSlide = 3;).
Ils doivent être strictement positifs, sans vérification de la valeur.

Le mode dev permet de rouvrir le diaporama sur le slide où vous étiez avant de le fermer.
Si vous avez un serveur, cela évite de devoir actualiser la page à chaque modification.

La limite théorique est de 2147483647 slides 😎
```html
<body>
    <content>
        <int>
            <!-- Vos éléments de diaporama ici -->
        </int>
    </content>
</body>
```
