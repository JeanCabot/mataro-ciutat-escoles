# Accessibilitat i continuació de l’auditoria · V99

**Data:** 21 de novembre de 2026  
**Estat comunicat al web:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Canvis de V99

- Actualitzada `accessibilitat.html` per documentar la prova de teclat del visor de fotografies i les limitacions pendents de zoom i vista estreta.
- Enllaç a la pàgina d’accessibilitat des del mapa, la introducció i la cronologia.
- La pàgina indica explícitament que el projecte és personal i no és el portal oficial de l’Ajuntament ni dels centres.
- La declaració distingueix la norma harmonitzada per a webs del sector públic (EN 301 549 v3.2.1 en el marc de la Directiva (UE) 2016/2102) de WCAG 2.2 AA, usada com a objectiu complementari. No s’afirma conformitat legal universal.

## Abast acumulat de V97

La versió V97 va afegir landmarks i salts de contingut, estructura d’encapçalaments a les 224 fites, noms localitzats als controls del mapa, anuncis de resultats, preferència de moviment reduït, estats de focus i una alternativa textual a la cartografia.

## Comprovació manual al web publicat (V99)

- Selecció d’un centre mitjançant la llista HTML; el títol de la fitxa rep el focus.
- Activació per teclat del botó «Amplia la fotografia». El diàleg modal anuncia el tancament, manté el focus dins seu i permet arribar als enllaços de font i llicència.
- Escape tanca el diàleg i retorna el focus al botó que l’ha obert. La font i la llicència només es mostren en aquesta vista ampliada.
- Comprovacions fetes amb Chrome d’escriptori el 21 de novembre de 2026; no substitueixen proves amb tecnologia assistiva ni cobreixen totes les funcions.

## Limitacions que continuen obertes

- No hi ha proves d’ús amb persones amb discapacitat ni una matriu completa de lectors de pantalla i navegadors.
- La revisió no és una avaluació completa de tots els criteris aplicables de EN 301 549/WCAG per a totes les combinacions de dispositiu i tecnologia assistiva.
- La cartografia i els enllaços a serveis externs depenen de tercers; la llista HTML ofereix una alternativa per als centres del mapa.
- No s’ha verificat el reflow a 320 píxels CSS ni el zoom del navegador al 400%.
- No s’ha avaluat la conformitat legal del projecte, que depèn de la identitat del prestador i de la naturalesa del servei.

## Verificació de la publicació

La versió V98 de la declaració i els enllaços es va publicar a GitHub Pages. Aquesta V99 actualitza el mètode públic amb la prova manual del visor de fotografies. Abans de publicar-la, es comprovaran la coherència del contingut i els fitxers de desplegament.
