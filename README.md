# Zagovori APPR 2014/15

Tukaj zbiramo delujoče različice vaših projektov, ki jih boste predstavili v zadnjem tednu 1. semestra.

V vsaki mapi so povezave na delujoče različice vaših projektov. Sami lahko delate naprej, morda daste na GitHub kakšno ne povsem delujočo vmesno različico. Če pa želite, da posodobim povezavo, odprite [issue](https://github.com/jaanos/APPR-2014-15-zagovori/issues) na tem repozitoriju, v katerem navedete šifro commita. Z različicami, na katere kaže ta repozitorij, bodo namreč generirana poročila, s katerimi boste predstavljali svoje projekte.

## Kako vem, na katero različico mojega projekta kaže povezava?

Vsak git commit ima svojo edinstveno šifro - zgostitev SHA256. V polni obliki gre za 256-bitno število, ki je navadno predstavljeno kot 64-mestno šestnajstiško število. Pogosto je to število skrajšano na prvih 10 ali 7 mest, ki navadno zadostujejo za identifikacijo commita.

Pri vsaki povezavi je tako izpisana 7-mestna šifra commita. Če jo kliknete, boste prišli na stanje repozitorija pri tem commitu. Zgoraj desno od datotek je pri _latest commit_ napisana tudi 10-mestna šifra tega commita. V isti vrstici imate tudi izpisano, koliko časa nazaj je bil ta commit opravljen. S klikom na _latest commit_ pridete na seznam sprememb v zadnjem commitu, zgoraj desno pa je izpisana tudi celotna 64-mestna šifra commita.

Na zadnjo različico vašega projekta greste tako, da pri izbiri zraven zelenega gumba izberete **master**. Sedaj bo na istih mestih izpisana šifra zadnjega commita. Če se ta ujema s prejšnjo, potem povezava kaže na zadnjo različico projekta. 

Če bi želeli posodobiti povezavo, na tem repozitoriju odprite issue in v njem navedite številko commita, ki bi jo radi vključili. Jaz si ga bom naložil, in če vse deluje, tudi posodobil povezavo. Vi lahko medtem nemoteno delate, brez skrbi, da bi kaj pokvarili. Šifro commita navedite v obliki
```
jaanos/APPR-2014-15@8742abbc785f62fa2535821fc9048c91b9ad85f5
```
Najprej torej navedite svoje uporabniško ime, nato za `/` ime svojega repozitorija, nazadnje pa za `@` še vsaj prvih sedem števk šifre commita. GitHub vam bo avtomatsko pretvoril tak niz v povezavo na vaš commit (to lahko preverite, če kliknete na _View_, da vidite, kako vaš issue izgleda).
