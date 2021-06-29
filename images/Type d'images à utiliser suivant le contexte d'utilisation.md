---
titre: Type d'images à utiliser suivant le contexte d'utilisation
famille: 
statut: DOING
contributeur: renaud h
prioritaire: *
mise en œuvre: Facile
impact écologique: 
ressources économisées:
phase de conception: 
cible(s) visé(s):
---

## Sujet

Plusieurs format d'images sont possible sur le web. Le  SVG, le JPG/JPEG, le PNG, le GIF et le petit nouveau le WebP.

Pour faire simple et sans rentrer dans les détails trop technique, chacun à ses caractéristiques et son contexte d'utilisation ou contexte où il ne faut l'utiliser :

- Le **SVG** est un format vectoriel, il a comme caractéristique, vu qu'il est vectoriel (pour faire simple, l'images est composée des points de références et des courbes) de ne pas pixeliser lorsqu'on l'agrandit.
On s'en sert souvent pour faire des icônes, des petites illustrations type dessin. **Il est hyper léger**.
- Le **JPEG**, c'est un format d'image simple, qui peut se compresser. Il n'a pas vraiment de caractéristique spécifique. Il peut être lourd si l'image est très grande et pas compressée. Il faut l'adapter et faire qu'elle existe en plusieurs tailles qui seront servies suivant la tailles d'écran, la résolution et son contexte d'affichage (ne pas charger une image de 1500px de large si c'est pour l'afficher en vignette de 300px max !).
**Bien travaillé, il est relativement léger et doit être le format à utiliser pour afficher des photos, images de contenu ou à mettre en fond de section ou "image héros".**
- Le **GIF** est un très vieux format d'image qui a deux caractéristiques, celle de pouvoir être **une animation** et celle de pouvoir avoir un **fond transparent**. Cette seconde caractéristique n'en fait pas le meilleur format pour la transparence, car c'est binaire, le pixel est transparent ou opaque, ce qui fait que sur un fond inadapté, on voit les pixels crénelés. **Aujourd'hui, on lui préfère le PNG qui gère une vraie transparence**.
Son autre caractéristique, c'est d'être animé, comme une mini-vidéo, on en voit partout grâce aux memes portés par la plateforme GIPHI. Mais comme c'est un très vieux format, il n'est pas du tout optimisé coté poids et demande beaucoup de ressource à la machine pour l'afficher. **Il est préférable d'utiliser des vidéos avec des codecs adaptés au web.**
- Le **PNG** à la caractéristique de pouvoir avoir de la transparence comme le GIF, mais lui gère vraiment la transparence, ce qui permet d'utiliser des ombres et d'être indépendant du fond par dessus le quel se trouve l'image. C'est à utiliser comme pictos de petites tailles, car très lourd. **Son utilisation est à bannir comme image de contenu, de fond de section ou comme "image héros" !**
- Pour finir, le petit dernier né, le WebP. C'est un format pensé pour le web, qui ne gère pas la transparence et qui a un rendu de qualité malgré un fichier de petit poids. Son seul inconvénient est de ne pas être encore pris en compte par tous les navigateurs, il faut donc mettre une solution de "fall back" qui proposera suivant le navigateur soit l'image au format WebP, soit le format d'origine.

Le JPG, le PNG et le GIF, sont contrairement au SVG des formats BITMAP, donc des images composées de pixels. Ce qui veut dire qu'une image agrandit, agrandit aussi la taille des ses pixels, ce qui sur certains matériel, ayant une résolution d'écran très précis, ça se verra.

> **Donc il n'y a pas de bon format, il y a par contre un bon format par usage !**

C'est pour ça que les graphiste fournissent plusieurs formats / tailles d'images et pas toutes dans tous dans tous les formats lors de leurs livraisons.

## Exemple

## Sources