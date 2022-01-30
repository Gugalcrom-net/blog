---
title: "Cum să repari o lume coruptă de Minecraft"
tags: minecraft server
---

Mi s-a întâmplat și am găsit singur o soluție, de asta scriu aici. Dacă și ție ți s-a întâmplat, nu intra în panică. Metoda e foarte simplă. Mai jos vezi cum se face.

În primul rând, dacă lumea este pe un server, trebuie copiată pe calculatorul tău printr-o conexiune SSH sau FTP.

Apoi, trebuie să ai un backup mai vechi al lumii. Dacă nu există, mergi în Minecraft, dă clic pe lume și alege Recreează. Va crea o lume nouă cu același seed și aceleași setări.

Cu copia lumii făcută, deschide fișierul lumii. Este în `/home/user/.minecraft/saves` pe Linux. În Windows, deschide *Run* și tastează `C:\Users\user\AppData\Roaming\.minecraft`.

Din el, copiază dosarele:
* DIM1
* DIM-1
* region
* entities
* playerdata
în copia lumii. Se găsește în aceeași locație.

Acum, ar trebui să fie gata și lumea să poată fi jucată din nou. Dacă era pe un server, încarc-o din nou.
