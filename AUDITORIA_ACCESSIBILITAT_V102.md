# Auditoria d’accessibilitat · V102

**Data:** 21 de novembre de 2026  
**Estat publicat:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Objectiu d’aquesta passada

Comprovar amb teclat els controls de zoom del mapa i els controls principals de la cronologia.

## Verificacions

- Els controls d’apropament i allunyament del mapa s’exposen amb noms accessibles: «Apropa el mapa» i «Allunya el mapa».
- El control d’apropament es pot enfocar i activar amb Retorn. En rebre el focus, mostra un contorn visible d’alt contrast.
- A la cronologia, el selector de centre i el control lliscant d’any es poden canviar amb les fletxes del teclat.
- En canviar l’any o el centre seleccionat, s’actualitza el recompte dins d’una regió amb `role="status"` i `aria-live="polite"`.
- La prova no ha detectat cap barrera nova en aquests controls.

## Abast i limitacions

Aquesta passada no és una auditoria completa de conformitat. Continuen pendents proves amb lectors de pantalla, tecnologies d’assistència i dispositius físics, així com una verificació exhaustiva de tots els criteris aplicables d’EN 301 549 i WCAG. L’estat global continua sent parcialment conforme.
