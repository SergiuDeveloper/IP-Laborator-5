# IP-Laborator-5

## C4 Diagram Design

Deisgn-ul abstract al componentelor modulului pe nivele.
https://c4model.com/img/c4-overview.png

## Principii de realizare ale unei diagrame c4:
* Modulul curent va reprezenta cel mai probabil un context. Acesta va avea mai multe Containere (level 2), mecanisme abstracte ce realizeaza functionarea modulului.
* Fiecare Container (level 2) abstract e definit explicit in Componente (level 3)
* Fiecare Componenta va fi usor integrabila cu altele, nu vor exista God-Objects ( Componenta do-all, le face pe toate )

## Mod lucru
* Toate Containerele se stabilesc pe baza feature-urilor din backlog. Nu se definesc Containere inutile.
* Se stabilesc 1-2 Containere si se detaliaza cu 1-3 Componente pentru a fi date catre echipa UML (la inceput). Se vor completa aceste Containere primele.
* Se alege cate un Container si se detaliaza in intregime, in limitele timpului. Daca simtiti ca mai trebuie ceva adaugat, puteti amana si sa treceti la altul. Nu pierdeti timpul daca nu va vine o idee, alta echipa depinde de voi.
* Cand simtit ca un Container este gata, il dati pe acesta si pe Componentele acestuia catre echipa UML. (le puneti pe Git si anuntati).
