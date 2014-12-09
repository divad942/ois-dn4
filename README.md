ois-dn4
=======

Izdelajte spletno aplikacijo, ki na inovativen način prikaže podatke o vitalnih znakih pacienta. Za motivacijo pri iskanju ideje si poglejte demo aplikacije na EhrScape platformi, na voljo pa je tudi njihova izvorna koda. Predlog rešitve naj bo vaš, kjer si morate zamisliti scenarij uporabe, končnega uporabnika (pacient) in namen uporabe (npr. preventiva, obveščenost ipd.). Aplikacija naj ne zapisuje podatkov v lastno podatkovno bazo, ampak zgolj bere podatke iz naslednjih podatkovnih virov:

podatki o vitalnih znakih iz platforme EhrScape s pomočjo Electronic Health Record API,
vsaj 1 zunanji podatkovni vir  (npr. WHO, Statistični urad RS, Twitter, Facebook, Zdravniška zbornica, Zdravniki.org, idr.),
Za potrebe testiranje razvijte tudi generator testnih podatkov, ki vam bo napolnil podatke, uporabljene v vašem prototipu. Na voljo je tudi enostaven primer, kako lahko generirate takšne podatke (izvorni repozitorij za fork in navodila za uporabo EhrScape na primerih).

Rešitev naj bo spletna aplikacija, ki v celoti deluje na strani odjemalca in s pomočjo API klicev pridobiva podatke iz zunanjih virov (EhrScape in ostali). Pri integraciji z drugim virom lahko pogojno v svoj repozitorij prenesete tudi podatke v datoteki (npr. kakšen seznam v obliki datoteke, ki ga vaša aplikacija uporablja). Delovanje na strani odjemalca pomeni, da v primeru, če si izvorno kodo vaše aplikacije prenesemo na svoj lokalni računalnik in zgolj poženemo v spletnem brskalniku, mora le-ta delovati.

Vse oddane naloge bodo pregledane s pomočjo orodja MOSS za ugotavljanje plagiarizma na podlagi podobnosti oddane kode (med demo primerom, testnimi primeri na platformi EhrScape in posameznimi oddajami vseh študentov) in časa oddaje oz. uveljavitve na GitHub repozitoriju. V primeru suma prepisovanja velja, da je originalni avtor rešitve tisti, ki jo je oddal prej.

Funkcionalne zahteve aplikacije
Pri implementaciji upoštevajte naslednje zahteve in omejitve:

predlagajte inovativno aplikacijo, ki deluje nad podatki o vitalnih znakih pacienta (telesna višina, teža, temperatura, sistolični in diastolični krvni tlak ter nasičenost krvi s kisikom) in vsaj 1 zunanjim virom podatkov,
identificirajte 3 zanimive scenarije uporabe vaše aplikacije (pripravite testne podatke pacientov, npr. otrok, ki se poškoduje in njegovi vitalni znaki nakazujejo poškodbo ali starejša oseba, ki je hospitalizirana zaradi pljučnice ipd.),
uporabnik naj ima možnost izbora ene izmed 3 oseb iz padajočega menuja (podobno kot pri demo aplikaciji),
na voljo naj bo izvorna koda generatorja podatkov, ki ste ga uporabiliza generiranje podatkov teh 3 oseb,
na uporabniškem vmesniku naj bo povezava, ki omogoča zagon generatorja podatkov,
uporabite vsaj 1 master/detail načrtovalski vzorec,
uporabite vsaj 1 AQL poizvedbo,
pri izgradnji uporabniškega vmesnika uporabite vsaj 1 ogrodje za razvoj spletnih aplikacij (npr. Bootstrap, AngularJS, Semantic UI, Almost Flat UI, Foundation, Zimit Framework, Ink, HTML KickStart, Pure, HTML5 Boilerplate, YUI idr.),
rešitev naj deluje vsaj na 2 različnih spletnih brskalnikih (npr. Chrome, Firefox, Safari, Internet Explorer itd.),
rešitev naj deluje tudi na mobilnem telefonu oz. tablici,
pri vizualizaciji uporabite vsaj eno tehniko, ki je na voljo v knjižnici D3js (primeri),
