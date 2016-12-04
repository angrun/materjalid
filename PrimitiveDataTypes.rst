Primitiivsed andmetüübid
========

Andmetüübid Javas jagunevad kahte suuremasse klassi: primitiivsed andmetüübid ja objektid. Primitiivsete andmetüüpide korral kehtib reegel, et muutujal on konkreetne väärtus. Andmetüüp määrab ära, milliseid väärtuseid see võib sisaldada ning milliseid toiminguid sellega läbi võib viia. Javas on 8 erinevat primitiivset andmetüüpi.

Primitiivsed andmetüübid on väikese algustähega ja objektid suure algustähega, see tuleneb selle tüübi võimalustest. Objektidel on meetodid (näiteks *.equals()*), primitiivsetel andmetüüpidel need puuduvad.

-------

* **byte** – 8-bitiline (1-baidine) täisarv. Selle võimalikud väärtused on -128 kuni 127 (kaasa arvatud). Vaikeväärtus on 0. 
* **short** – 16-bitiline (2-baidine) täisarv. Selle võimalikud väärtused on -32,768 kuni 32,767 (kaasa arvatud). Vaikeväärtus on 0.
* **int** – 32-bitiline (4-baidine) täisarv. Selle võimalikud väärtused on -2,147,483,648 kuni 2,147,483,647 (kaasa arvatud). Vaikeväärtus on 0.
* **long** – 64-bitiline (8-baidine) pikk täisarv. Selle võimalikud väärtused on -9,223,372,036,854,775,808 kuni 9,223,372,036,854,775,807 (kaasa arvatud). Vaikeväärtus on 0L.
* **float** – 32-bitiline (4-baidine) 7 tüvenumbri täpsusega ujukomaarv. Vaikeväärtus on 0.0f. Seda andmetüüpi ei tohiks kasutada täpsete väärtustega arvutamisel, näiteks raha puhul, kuna võivad tekkida ümardamise vead. Sellisel juhul oleks soovitatav kasutada *java.math.BigDecimal* klassi.
* **double** – 64-bitiline (8-baidine) 16 tüvenumbri täpsusega ujukomaarv. Vaikeväärtus on 0.0d.
* **boolean** – kahe võimaliku väärtusega andmetüüp, mille väärtuseks on kas true või false. Vaikeväärtus on false.
* **char** – 16-bitiline Unicode karakter, miiniumväärtus on '\\u0000' (või 0) ja maksimumväärtus on '\\uffff' (või 65,535). Vaikeväärtus on '\\u0000'.

Sõned ei ole Java mõttes primitiivid, vaid (klassi String) objektid. Nende jaoks kehtivad mõned lihtsustavad erandid. Näiteks saab sõnesid luua (ilma isendiloome operaatorit *new* kasutamata), pannes vastava teksti jutumärkide(" ") vahele. Erinevalt Pythonist tähistavad ühekordsed (' ') jutumärgid Javas üksikuid tähemärke.


----

Dokumentatsioon: https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html