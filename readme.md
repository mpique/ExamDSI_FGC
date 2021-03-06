# Examen Pràctic

## Enunciat
Bàsicament us dono un projecte ja fet en una arquitectura en tres capes i heu de migrar l'aplicació a una
**arquitectura hexagonal**

Es valorarà:
* L'organització del codi segueix l'estructura proposada per l'arquitectura hexagonal
* Es fan servir mòduls com a mecanisme per reforçar l'estructura (el compilador ens avisa quan ens saltem la direcció de 
les dependències)
* És fa servir el mapping més complert: especialment al cas d'ús que crea nous objectes

## L'aplicació
Pensada per gestionar els viatges més freqüents que fan els usuaris de la línia dels Ferrogarrils de la Generalitat de 
Catalunya que va de Lleida-Pirineus a La Pobla

Operacions disponibles (explicats a index.html):
* Llistat d'usuaris
* Llistat d'estacions
* Llistat dels viatges (Journey) favorits d'un usuari (FavoriteJourney)
* Crear un nou viatge favorit (FavoriteJourney)

Un **Journey** és un viatge entre una estació d'origen i una altra de destí.

Un **FavoriteJourney** composa un Journey i una llista que conté els moments en es fa el viatge: dia de la setmana i hora

Aquesta aplicació **NO TÉ seguretat** i NO cal que la poseu.

## Recomanacions
1. Descarregueu-vos (cloneu) repository a local
2. Executeu-lo i assegureu-vos que funciona i exploreu les funcionalitats
3. Mireu d'entendre el codi
3. Creeu un nou projecte amb l'estructura del mòduls
4. Copieu els fitxers del projecte original al nou
5. Feu les modificacions pertinents al codi
6. **Feu un push del nou projecte al GitHub**