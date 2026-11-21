# Auditoria d’accessibilitat · V104

**Data:** 21 de novembre de 2026  
**Estat publicat:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Objectiu d’aquesta passada

Comprovar el nom accessible del control per ampliar fotografies i el comportament del diàleg amb teclat.

## Troballa i correcció

El botó d’ampliació s’anunciava simplement com «Amplia la fotografia». El nom no distingia el contingut de la imatge. Ara incorpora la descripció alternativa, per exemple: «Amplia la fotografia: Façana de Maristes Valldemia».

## Verificació al web publicat

- En enfocar la foto de Maristes Valldemia, el navegador exposa el nom accessible amb l’acció i la descripció de la imatge.
- Retorn obre el diàleg. Aquest exposa la descripció de la imatge, els crèdits i els enllaços a la font i a la llicència.
- Escape tanca el diàleg i retorna el focus al botó d’ampliació amb el nom descriptiu.
- El canvi s’ha verificat al web publicat després del desplegament del commit `10105ede9dd4358e412ebc225dfda95fe3edb53c`.

## Abast i limitacions

Aquesta passada no és una auditoria completa de conformitat. Continuen pendents proves amb lectors de pantalla, tecnologies d’assistència i dispositius físics, així com una verificació exhaustiva de tots els criteris aplicables d’EN 301 549 i WCAG. L’estat global continua sent parcialment conforme.
