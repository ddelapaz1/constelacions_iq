# Constel·lacions I/Q

Laboratori interactiu de radiocomunicacions per explorar QPSK, 8PSK, 16QAM i 64QAM.

- Selecció de modulació i de símbol.
- Amplitud, fase i components I/Q.
- Mateixa potència mitjana normalitzada (1) en totes les modulacions.
- Soroll gaussià amb colors diferents per als símbols veïns.
- Zones de decisió i creus per a les mostres assignades a un altre símbol.
- Opció de mostrar només les mostres del símbol seleccionat.

El control de soroll expressa una intensitat relativa, no una SNR en decibels. Es fan servir 80 mostres simulades per símbol i la regla de decisió del punt ideal més proper. Les assignacions de bits són exemples amb codificació Gray.

## Ús

Obre `index.html` en un navegador. El fitxer conté tots els estils i la interactivitat i no necessita dependències externes.

## GitHub Pages

Publicació des de la branca principal, carpeta arrel. Per inserir el laboratori a Notion, afegeix un bloc `/embed` amb l’URL de GitHub Pages.
