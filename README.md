# hotels-spa-tarragona
Aquesta pàgina web mostra els hotels amb spa a la província de Tarragona. 

## Motivació
La pàgina web ha estat creada per tal de facilitar als usuaris que desitgin passar unes vacacnces a la província de Tarragona i vulguin allotjar-se a algun hotel que disposi d'instal·lacions d'spa.

## Estructura de la web
La web compta de 5 pàgines: Home, Hotels, Locations, Tarragona, Contact. 
- Home és la pàgina inicial de la web, és on apareix la informació més bàsica sobre aquesta.
- Locations compta amb un mapa interactiu creat amb el pugin web2qgis i la llibreria Leaflet. Surt la distribució dels diferents hotels en forma de punts vermells. 
- A Hotels apareix un llistat amb tots els hotels de la província que disposen d'spa, així com la seva ubicació (si es fa click a l'adreça t'envia al Google Maps), i la pàgina web oficial de l'hotel corresponent (fent click a l'enllaç et redirigeix a la web oficial). 
- La pàgina de Tarragona dona breu informació sobre aquesta província, des d'un punt més enfocat cap al turista o visitant. 
- Contact és on apareix la informació de contacte de la website, així com uns formularis per rebre informació o notificacions d'ofertes (inscripció a la Newsletter)

La web ha estat creada amb l'ajuda d'una plantilla extreta de Bootstrap i la plataforma Colorlib.
La llicència és GNU General Public License v3.0.
També compta amb web responsive. 
 
## Cartografia qgis2web
En aquest apartat es mostrarà la cartografia elaborada mitjançant el software QGIS, fent servir el plugin qgis2web i la llibreria Leaflet. Els hotels amb distàncies pròximes entre ells apareixen en forma de cluster per tal de millorar l'experiència de l'usuari. Si es fa click en la icona verda d'aquest cluster que agrupa els diferents hotels, aquests surten distribuïts de forma individual en cadascuna de les seves ubicacions. 

## Dificultats i millores
He tingut dificultats sobretot per ficar la posició deistjada d'alguns elements com el mapa o fotografies, i també per ficar alguns espais.
La recerca dels hotels descrits ha estat senzilla, m'he recolzat de diferents cercadors web d'hotels populars utilitzant filtres d'instal·lacions spa, però possiblement m'he deixat algun.
