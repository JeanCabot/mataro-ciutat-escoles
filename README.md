# Mataró, ciutat d’escoles

**Explora l’oferta educativa de Mataró en un mapa interactiu.** Hi trobaràs escoles, instituts, escoles bressol, acadèmies, centres de formació i altres espais on aprendre.

[Obre el mapa](https://jeancabot.github.io/mataro-ciutat-escoles/)

## Com fer-lo servir

- Cerca un centre o una activitat.
- Tria les categories que t’interessen amb els filtres.
- Selecciona un punt del mapa o un centre de la llista per consultar-ne la fitxa.
- Explora les dates i els llocs documentats amb la cronologia.

El mapa està pensat per a famílies, alumnat i qualsevol persona que vulgui conèixer l’oferta educativa de la ciutat. Les dades històriques s’incorporen progressivament.

## Proposa una correcció

Si detectes una dada que cal revisar o vols proposar un centre, [obre una incidència](https://github.com/JeanCabot/mataro-ciutat-escoles/issues) i, si pots, indica la font.

## Historial de canvis

- **21 de novembre de 2026:** afegit un identificador de versió a les imatges de la visita perquè els navegadors que havien desat l’error de càrrega tornin a demanar-les.

- **21 de novembre de 2026:** regenerades i verificades les tres il·lustracions de la visita guiada; ajustada la mida del globus i dels controls per a pantalles estretes i zoom ampliat. En obrir el web, la guia torna a aparèixer amb aquesta versió.

- **21 de novembre de 2026:** substituït el quadre de benvinguda per una visita guiada petita que es col·loca al costat de la cerca, els filtres i el mapa. Ressalta cada zona i mostra una il·lustració diferent de la parella a cada pas; es pot avançar, tornar, saltar o tancar.

- **21 de novembre de 2026:** corregida la publicació de la caricatura de benvinguda, que no es copiava al desplegament, i adaptat el diàleg perquè es mostri en una sola columna en finestres estretes.

- **21 de novembre de 2026:** la benvinguda ara guia en tres passos: cerca, filtres i consulta de fitxes. Inclou una caricatura manga chibi de les persones creadores, controls per avançar, tornar enrere o saltar, i conserva les opcions de tancament accessibles.

- **21 de novembre de 2026:** incorporat el logotip de l’Institut Escola Àngela Bransuela a partir de la imatge facilitada per la persona usuària.

- **21 de novembre de 2026:** afegida una benvinguda accessible a la landing, amb una caricatura de les persones creadores i indicacions breus per cercar, filtrar i obrir fitxes. Es pot tancar amb Escape, clic fora o el botó de tancament, i es pot triar que no torni a aparèixer.

- **21 de novembre de 2026:** afegits a les fitxes els logotips localitzats de l’Institut Miquel Biada, Meritxell, l’Institut Josep Puig i Cadafalch i el Consorci Sanitari del Maresme (per a URPIJ-UCA); fonts dels logotips documentades a `logos/fonts.json`.

- **21 de novembre de 2026:** recuperades al repositori les 72 fotografies i 48 logos que ja tenia documentats el projecte, perquè es carreguin a les fitxes; afegit també el registre de cobertura de les fotografies.

- **21 de novembre de 2026:** «Sobre el projecte» i «Accessibilitat» se situen a la mateixa fila que els filtres quan hi ha espai; en pantalles estretes continuen baixant de fila per facilitar-ne l’ús.

- **21 de novembre de 2026:** els filtres ja no mantenen la vora vermella ni el globus d’acció quan s’aparta el ratolí; els indicadors continuen disponibles en navegar amb el teclat.

- **21 de novembre de 2026:** afegit al costat del botó principal un botó per iniciar o tancar la cronologia. Comença amb el primer any documentat (1737), recorre els anys amb les dades disponibles i mostra el nombre de centres oberts en cada any. Els filtres públic i privat/concertat s’obren activats.

- **21 de novembre de 2026:** els filtres ara indiquen «Activa» o «Desactiva» segons l’estat actual. Els filtres de centres públics i privats/concertats continuen activats en obrir la pàgina.

- **21 de novembre de 2026:** simplificats els filtres del mapa: caselles ocultes, indicació «Clica» en passar-hi o enfocar-los, i selecció activa per a centres públics i privats/concertats.

- **21 de novembre de 2026:** prova del tema visual «Quadern de Platja & Dibuix», amb paleta sorra, blau marí, blau mar i coral, filtres accessibles i acabats orgànics coherents al mapa, la cronologia i les pàgines informatives. La versió anterior continua recuperable des de l’historial de Git.

- **21 de novembre de 2026:** filtres del mapa i de la cronologia alineats en una fila en pantalles amples; en pantalles estretes s’apilen per mantenir-los accessibles.

- **21 de novembre de 2026:** filtres de la cronologia en una sola fila en pantalles amples i en columnes en mòbil.

- **21 de novembre de 2026:** simplificació dels filtres del mapa; renovació de les pàgines informatives i de la cronologia amb el mateix estil visual, i afegida la cerca de fites, amb ajustos finals de lectura i navegació.

- **21 de novembre de 2026:** neteja dels paquets antics del repositori, simplificació d’aquesta guia i actualització del desplegament perquè faci servir una única font estable per als recursos del web.

Per mantenir el repositori lleuger, es conservaran com a màxim **cinc versions anteriors**. Evitarem pujar ZIPs grans quan els recursos actuals del web ja siguin suficients. Cada actualització publicada quedarà resumida en aquest historial; les versions antigues es podran recuperar des de l’historial de Git.

## Crèdits

El mapa utilitza [Leaflet](https://leafletjs.com/), [OpenStreetMap](https://www.openstreetmap.org/copyright) i dades de fonts públiques i dels centres. La procedència de les fotografies s’indica a les fitxes corresponents.
