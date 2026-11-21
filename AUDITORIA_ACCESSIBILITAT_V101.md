# Auditoria d’accessibilitat · V101

**Data:** 21 de novembre de 2026  
**Estat publicat:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Objectiu d’aquesta passada

Continuar la prova de teclat del mapa i revisar el nom i l’activació dels marcadors interactius.

## Troballa i correcció

La seqüència de tabulació arribava als punts SVG del mapa. Els punts no tenien nom accessible, i Retorn no obria la fitxa. Això deixava controls sense una identificació o activació clara per a qui navega amb teclat o tecnologia assistiva.

La V101 etiqueta cada punt amb el nom del centre i l’adreça, declara el rol de botó, afegeix un indicador de focus visible i activa la fitxa amb Retorn o Espai. Els punts de seus addicionals i seus històriques indiquen també el tipus de seu. La llista HTML de centres continua disponible com a alternativa per trobar i obrir una fitxa.

## Verificació al web publicat

- Després del desplegament, a la vista inicial hi havia 47 marcadors interactius: tots exposaven `role="button"` i un nom accessible; cap dels marcadors SVG interactius observats quedava sense nom.
- En tabular fins a «Balmes», el focus visible es distingia del punt. El marcador exposava el nom «Balmes, Plaça dels Bous, 1».
- Retorn i Espai van obrir la fitxa de Balmes i el focus va passar a l’encapçalament «Fitxa seleccionada».
- En activar successivament «Altres centres», «Acadèmies de reforç» i «Lleure i casals», els marcadors creats per cada filtre també tenien noms accessibles (163, 56 i 81 punts visibles, respectivament; zero sense nom en cada comprovació). Els filtres es van deixar desactivats en acabar.
- La llista HTML de centres continua exposant els elements com a botons amb nom, adreça i estudis, i ofereix una alternativa per obrir les fitxes.
- Verificació manual amb Chrome d’escriptori després de publicar el commit `df007807e8c76f1ff78e32422fd27476b91bcd64`.

## Abast i limitacions

Aquest canvi no tanca l’auditoria general. Continuen pendents les proves amb lectors de pantalla i persones amb discapacitat, més combinacions de navegadors i dispositius físics, i una revisió completa dels criteris aplicables de EN 301 549/WCAG. L’estat del web continua sent parcialment conforme.
