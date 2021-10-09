# Markdown course 
## Definition 
Markdown is a way to style text on the web. You control the display of the document; formaing words as
bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly,
Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

## comment faire un header h1 ou h2 ...?
on fait un header en tapant # et espace au debut de la ligne puis le nom du header 

le nombre de # correspondra à l'ordre du header.

## comment rendre un texte italic 
pour rendre un texte en italic on le précède par un \* et on lui suit par un \*  le texte en italic va s'afficher comme : 
*Itexte en italic*
### Remarque1: on ne doit pas faire des espaces apres les * car si non l'italic ne va pas etre appliqué sur le texte 


### Remarque2: on peut remplacer les * par des _ .
le resultat de l'italic est : _"texte en italic"_

## comment rendre un texte en gras 
 pour rendre un texte en gras on le précède par un \** et on lui suit par un \**  le texte en gras va s'afficher comme : 
**text en gras**
### Remarque1: on ne doit pas faire des espaces apres et avant les ** car si non le gras ne va pas etre appliqué sur le texte 


### Remarque2: on peut remplacer les * par des _ .
le resultat de l'italic est : __"texte en gras"__

## comment faire un texte barré ?
 on doit entourer le texte barré bar deux \~~ le text entouré avec ces derniers s'affichera comme suit:
~~texte barré~~
### Remarque 1
on ne doit pas faire des espaces avant et aprés les ~~
## Comment dessiner une ligne horizontale?
on peut tracer une ligne horizontale en tappant trois _ sans espace l'affichage sera comme suit: 
___

### Remarque1 : cette succession de _ doit etre situe dans une ligne séparé 

## comment annuler l'effet d'un caractere spéciale ?
 on doit le précéder par \ 
### Remarque 1
il ne faut pas faire des espaces !

## comment styliser une citation ?
 on doit débuter la ligne de la ciatation par un >  et l'affichage sera comme suit:
 >ceci est une citation 
## comment creer des liens? 
le code suivant est responsable a la création du lien 

`[lien vers fichier pdf]("https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf") `

[lien vers fichier pdf]("https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf")
## comment faire une liste non ordonnée 
a chaque élement on associe une ligne .chaque ligne doit commencer par * et espace .le résultat s'affichera comme suit :
* element 1
* element 2

### Remarque 1:
pour faire des sous elements on doit faire une tabulation et puis on met notre * .
le résultat s'affichera comme suit:
* element 1
    * sous élément 1
    * sous element 2
        * sous sous element

## comment faire une liste ordonnée 
a chaque élement on associe une ligne .chaque ligne doit commencer par 1. et espace. le résultat s'affichera comme suit :
1. element 1
1. element 2

### Remarque 1:
pour faire des sous elements on doit faire une tabulation et puis on met notre * .
le résultat s'affichera comme suit:
1. element 1
    1. sous élément 1
    1. sous element 2
        1. sous sous element

## Comment afficher un texte comme etant un code intégré dans le texte ?
on précède les codes à afficher par \` et on les ferme à la fin 
l'affichage sera comme suit:

`<p1> ceci est un paragraphe </p1>`

## Comment ajouter des images à notre contenu ?
le code suivant est responsable à l'apparition de l'image qui précède :

```
![texte qui s'apparait en cas de l'absence du lien ](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png) 
```


![texte qui s'apparait en cas de l'absence du lien ](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

## comment creer un bloc de code :
on doit entourer notre code par trois        \`  

l'affichage du code va etre comme suit :

```html
<p1>comment </p1>
```
```bash
npm install
```
```java
System.out.println("hello world !");
```
### Remarque 1 : 
on peut spécifier le langage dans les 3 premiers  \` on ecrit le nom du langage sans faire une espace.

## Comment faire des tableaux? 
Nom | Adresse Email
------------ | -------------
Ksibi | ksibijaouher@gmail.com
Ksibi | ksibijaouher@gmail.com
Ksibi | ksibijaouher@gmail.com

## Comment faire des listes de taches ? 
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), 
