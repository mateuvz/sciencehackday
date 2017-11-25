Kako uporabljat Jekyll?
https://jekyllrb.com/

- To je namenjeno statičniam spletnim stranem, kjer se vsebina ne spreminja aktivno sproti.
- Git je javen in omogoča 10gb in domeno, vendar je koda javna. Če hočmo zasebnost, treba plačat.

Osnovna spletna stran je zgenerirana s programom jekyll, dobimo približno tisto kar mam na githubu.

- Posts - v zgornjem delu naštimamo naslov in datum objave - lahko tudi za prihodnost, vendar treba pol enkrat osvežit stran, da se zgnereira nova.

- Podstrani (na zavihkih): Vrstni red uredi po abecednem redu, kako lahko to spremenimo?: 
-- permalink: zabava.html // /zabava/ (razlika enkrat kot html standardno, drugič kot mapa)
-- Objave so vedno na seznamu na index strani, ki ima layout: home; če index strani spremenimo layout: default in damo neki drugi strani layout:home, bo seznam objav tam.

* Slike -> ![](link-do-slike)   (klicaj je tam kot "dej tukej pokaž kar je linkano", sicer bi bla to povezava do linka z vsebino [...])
  * Ce sliko objavljamo v "mapah" straneh, ne html, potem je treba pred sliko dat polno pot (sleš) (/DSC_0001.jpg), ker sicer išče sliko po tej "mapi"
