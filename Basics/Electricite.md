# Electricité

👉 [Electricité - C'est pas sorcier](https://youtu.be/efQW-ZmpyZs "Electricité - C'est pas sorcier")

👉 [Notions électriques fondamentales - FLOSS Manuals](https://fr.flossmanuals.net/arduino/les-bases-de-lelectronique/ "Notions électriques fondamentales - FLOSS Manuals")


## Les notes du Mooc

### Tension et intensité

À partir du circuit électrique le plus simple, jusqu'aux circuits les plus complexes, nous avons affaire à un courant électrique qui circule. Pour parler de la magnitude de ce courant électrique, on parle de l'**intensité**. Ce courant ou intensité est mesuré et exprimé en Ampères (A).

Pour faire circuler un courant électrique, il faut une "force motrice". En électricité, cette force est appelée **tension**. La tension est mesurée et exprimée en Volts (V).

Pour visualiser la différence entre **Intensité** et **Tension,** on peut faire un parallèle avec l'eau. L'intensité dans un circuit électrique est comme le débit de l'eau dans un tuyau. Et la tension électrique est comme la pression de l'eau. Pour un tuyau donné, plus on augmente la pression, plus le débit d'eau augmente. En électricité, c'est pareil : dans un circuit donné, plus on augmente la tension, plus l'intensité augmente.

### Résistance

Toujours avec notre tuyau d'arrosage, on peut visualiser une autre manifestation électrique : la **résistance**. La friction à l’intérieur du tuyau résiste au passage de l'eau. Plus le diamètre du tuyau est petit, plus la résistance est importante. Plus le tuyau est long, plus la résistance est forte. Et si, pour augmenter le débit, on augmente trop la pression – le tuyau se rompt.

La résistance électrique est très semblable.  La résistance est mesurée et exprimée en Ohms (Ω). Un simple fil électrique en cuivre montre une résistance au courant. Plus le diamètre du fil est petit, plus il y a de résistance. Plus le fil est long, plus il y a de résistance. Vous avez peut-être déjà expérimenté : si on essaie de passer trop de courant dans un petit fil électrique – le fil  fond (c'est le principe d'un fusible).

C'est la raison pour laquelle il faut en général protéger les LEDs avec des résistances.

Pour plus d'information sur les résistances, vous pouvez consulter cette excellente ressource [d'electrotrucs](https://www.youtube.com/channel/UCcnA6Abw23iIVzLbykJ64Dg)

### Loi d'Ohm

Bon, nous avons déjà trois phénomènes électriques à maîtriser : la **tension** (volts), **l'intensité** (ampères) et la **résistance** (ohms). Ces trois phénomènes sont intimement liés par une loi d'électricité dite loi d'Ohm. La loi s'exprime dans une formule très simple :

> **U = R × I**
> 
> avec :
> 
> -   **U** : Tension
> -   **I** : Intensité
> -   **R** : Résistance

La même loi peut être exprimée aussi en fonction de l'intensité et la résistance respectivement :

> **I = U⁄R** et  **R = U⁄I**

Pour terminer, sachez qu'il vous faudra protéger vos LED avec une résistance d'une valeur comprise entre 200Ω et 1kΩ. Nous verrons dès la semaine prochaine pourquoi !