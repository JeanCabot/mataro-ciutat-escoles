# Auditoria d’accessibilitat · V101

**Data:** 21 de novembre de 2026  
**Estat publicat:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Objectiu d’aquesta passada

Continuar la prova de teclat del mapa i revisar el nom i l’activació dels marcadors interactius.

## Troballa i correcció

La seqüència de tabulació arribava als punts SVG del mapa. Els punts no tenien nom accessible, i Retorn no obria la fitxa. Això deixava controls sense una identificació o activació clara per a qui navega amb teclat o tecnologia assistiva.

La V101 etiqueta cada punt amb el nom del centre i l’adreça, declara el rol de botó, afegeix un indicador de focus visible i activa la fitxa amb Retorn o Espai. Els punts de seus addicionals i seus històriques indiquen també el tipus de seu. La llista HTML de centres continua disponible com a alternativa per trobar i obrir una fitxa.

## Verificació prevista després del desplegament

- Tabular fins a un marcador i comprovar que el focus és visible.
- Comprovar al navegador que el punt exposa rol de botó i un nom comprensible.
- Activar-lo amb Retorn i Espai i verificar que s’obre la fitxa correcta.
- Seleccionar un centre amb el botó de la llista per confirmar que l’alternativa continua funcionant.

## Abast i limitacions

Aquest canvi no tanca l’auditoria general. Continuen pendents les proves amb lectors de pantalla i persones amb discapacitat, més combinacions de navegadors i dispositius físics, i una revisió completa dels criteris aplicables de EN 301 549/WCAG. L’estat del web continua sent parcialment conforme.
