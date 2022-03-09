# H&M Personalized Fashion Recommendations, a Kaggle competition
*Provide product recommendations for users based on their previous purchases.*

Kaggle competition, available at https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations

## Uvod

Natečaj podjetja H&M sprašuje ali lahko na podlagi podatkov o preteklih nakupih strank in metapodatkov o izdelkih, pripravimo primerna priporočila izdelkov za stranko v bodoče. Torej razviti bi bilo potrebno priporočilni sistem za dane podatke. V nalogi bi poskušal postaviti neko osnovo za reševanje tega specifičnega problema.

## Podatki

Dani podatki so sestavljeni iz treh datotek tabelaričnih podatkov, ter zbirke slikovnega gradiva. V nalogi bi se posvetil zgolj tabelaričnemu delu, in sicer:

* **articles.csv** - Datoteka vsebuje podatke o artiklih. Tukaj so zajeti ključni atributi (barva, znamka, kategorija izdelak, itd) v katerih bi poskušali iskati vzorce v nakupih specifične stranke.
* **customers.csv** - Datoteka vsebuje podatke o uporabnikih.
* **transactions_train.csv** - Datoteka vsebuje podatke o nakupih, kateri uporabnik je kupil kateri artikel.

*sample_submission.csv - primer zaželjene končne datoteke*

Za začetek bi podatke porezal tako, da bi izoliral nekaj uporabnikov in upošteval le transakcije teh parih uporabnikov. Nato bi poskušal poiskati ali obstajajo kakšni vzorci v nakupih izbranih uporabnik, recimo ali je uprabnik pritegnjen kupovati določeno barvo, določeno znamko, itd.

## Cilji

Minimalen cilj je poiskati čimveč uporabnih vzorcev v podatkih. Glavni cilj je razviti učinkovit priporočilni sistem.
