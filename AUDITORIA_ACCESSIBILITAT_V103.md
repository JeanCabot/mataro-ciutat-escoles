# Auditoria d’accessibilitat · V103

**Data:** 21 de novembre de 2026  
**Estat publicat:** parcialment conforme segons autoavaluació tècnica; no és una certificació.

## Objectiu d’aquesta passada

Revisar si es pot arribar amb teclat a la llista de centres sense haver de recórrer abans tots els marcadors interactius del mapa.

## Troballa i correcció

Després dels filtres, el focus entrava al mapa i recorria cada marcador abans d’arribar als controls del mapa i a la llista textual. A la vista inicial hi ha desenes de marcadors, cosa que feia llarg el recorregut per a qui només volia consultar els centres en format de llista.

S’ha afegit després dels filtres l’enllaç «Ves a la llista de centres». L’enllaç porta el focus a l’encapçalament de la llista, amb un indicador visible; Tab continua cap al primer centre. Els marcadors del mapa continuen disponibles per teclat.

## Verificació al web publicat

- L’enllaç apareix al final dels filtres i es pot activar amb Retorn.
- En activar-lo, el focus arriba a l’encapçalament «Centres del mapa» i el focus és visible.
- Amb Tab, el focus passa al primer centre de la llista («Balmes»); amb Retorn, s’obre la fitxa i el focus passa a «Fitxa seleccionada: Balmes».
- La verificació s’ha fet al web publicat després del desplegament del commit `d619698f95b39b358f7418abf0e8bb126e561dd1`.

## Abast i limitacions

Aquesta passada no és una auditoria completa de conformitat. Continuen pendents proves amb lectors de pantalla, tecnologies d’assistència i dispositius físics, així com una verificació exhaustiva de tots els criteris aplicables d’EN 301 549 i WCAG. L’estat global continua sent parcialment conforme.
