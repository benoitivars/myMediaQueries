# Media Queries

En avant pour de nouvelels aventures !

## La base

Tout d'abord, créer l'index, le fichier style, mettre le boiler html et le reset du CSS

## Un peu de théorie

### Le méta dans le ```<head>```html

Pour faire du media query, il faut d'abord s'intéresser au html, et à cette ligne en particulier :

```<meta name="viewport" content="width=device-width, initial-scale=1.0">```html

Grosso modo, ce meta du head permet de dire au navigateur d'adapter :

* La largeur de la page à celle de l'écran ```width=device-width```html
* à l'échelle 100% ```initial-scale=1.0```html

### La synthaxe dans le code CSS

La synthaxe :

´´´@media media type and (condition: breakpoint) {

}```css

On a ici deux choses qui rentrent en ligne de compte :

* ```@media media type```css qui nous permettra de spécifier le type device
* une condition de "breakpoint"

Enfin, entre les brakets, on mettra le style qui s'adaptera à ces conditions

### Exemple

```@media screen and (min-width: 481px ma-width )```