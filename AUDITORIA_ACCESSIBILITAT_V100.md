# Accessibilitat i continuació de l’auditoria · V100

**Data:** 21 de novembre de 2026  
**Estat comunicat al web:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Canvis de V100

- Afegida separació visible i tàctil entre els enllaços de navegació de «Sobre el projecte».
- Actualitzada `accessibilitat.html` amb els resultats de la prova a zoom 500%.
- Enllaç a la pàgina d’accessibilitat des del mapa, la introducció i la cronologia.
- La pàgina indica explícitament que el projecte és personal i no és el portal oficial de l’Ajuntament ni dels centres.
- La declaració distingueix la norma harmonitzada per a webs del sector públic (EN 301 549 v3.2.1 en el marc de la Directiva (UE) 2016/2102) de WCAG 2.2 AA, usada com a objectiu complementari. No s’afirma conformitat legal universal.

## Abast acumulat de V97

La versió V97 va afegir landmarks i salts de contingut, estructura d’encapçalaments a les 224 fites, noms localitzats als controls del mapa, anuncis de resultats, preferència de moviment reduït, estats de focus i una alternativa textual a la cartografia.

## Comprovació manual al web publicat (V100)

- Selecció d’un centre mitjançant la llista HTML; el títol de la fitxa rep el focus.
- Activació per teclat del botó «Amplia la fotografia». El diàleg modal anuncia el tancament, manté el focus dins seu i permet arribar als enllaços de font i llicència.
- Escape tanca el diàleg i retorna el focus al botó que l’ha obert. La font i la llicència només es mostren en aquesta vista ampliada.
- A 500% de zoom en una finestra de 1363 píxels (uns 273 píxels CSS d’amplada), els controls, el text i la llista de centres s’apilen i es reflowen sense desplaçament horitzontal de pàgina; el mapa conserva la panoràmica pròpia de la cartografia.
- La revisió a 500% va revelar que els dos enllaços de «Sobre el projecte» quedaven massa junts; s’han separat i s’han convertit en controls d’almenys 44 píxels d’alçada.
- Comprovacions fetes amb Chrome d’escriptori el 21 de novembre de 2026; no substitueixen proves amb tecnologia assistiva ni cobreixen totes les funcions.

## Limitacions que continuen obertes

- No hi ha proves d’ús amb persones amb discapacitat ni una matriu completa de lectors de pantalla i navegadors.
- La revisió no és una avaluació completa de tots els criteris aplicables de EN 301 549/WCAG per a totes les combinacions de dispositiu i tecnologia assistiva.
- La cartografia i els enllaços a serveis externs depenen de tercers; la llista HTML ofereix una alternativa per als centres del mapa.
- La prova de reflow s’ha fet en Chrome d’escriptori, no en dispositius mòbils físics.
- No s’ha avaluat la conformitat legal del projecte, que depèn de la identitat del prestador i de la naturalesa del servei.

## Verificació de la publicació

La declaració V100 i la pàgina de presentació s’han publicat a GitHub Pages. S’ha comprovat la pàgina d’accessibilitat en directe després del desplegament.
