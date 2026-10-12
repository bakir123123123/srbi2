# U sjenci platna i riječi — statički web portal

Kompletan lokalni web sajt sa šest HTML stranica, jednim CSS i jednim JS fajlom. Ne zahtijeva framework, instalaciju niti server za osnovni rad.

## Pokretanje

Raspakujte ZIP i otvorite `index.html` u pregledniku. Kroz navigaciju su dostupne stranice O projektu, Teme, Autori, Galerija i Izvori. Za objavljivanje postavite cijelu strukturu foldera na bilo koji statički hosting (Netlify, GitHub Pages, klasični hosting). Ne mijenjajte relativne putanje.

## Sadržaj i datumi

Izvor: `Materijal za web Nedic Milijana.docx` (49 stranica). Sadržaj paragrafa prenesen je u izvornom redosljedu, uključujući referencirane URL adrese i izvorne napomene. U folderu `data` nalaze se JSON indeks svih tekstualnih jedinica i slika te popis uredničkih sekcija. Prikazani datumi od 01.09.2026. do 08.10.2026. predstavljaju **planirane datume digitalnog objavljivanja**, a ne istorijski potvrđene datume. Izvorni datumi koji se spominju u sadržaju nijesu mijenjani.

## Napomene o fotografijama

Svih 53 slika iz DOCX-a sačuvano je kao lokalni optimizovani WebP fajl u `images/dokument`. Originalni logo Fonda nalazi se u `images/logo-fonda.png`, neizmijenjen. Galerija vodi na odgovarajuću tematsku cjelinu. Izgled ili autorstvo slika ne pripisuje se osobama kada to sam izvor ne potvrđuje. Pojedine slike i biografije možda zahtijevaju dodatnu uredničku provjeru prava na javno objavljivanje, tačnosti navoda i atribucije izvora. U dokumentu postoji nekoliko atribucija slika koje ne potvrđuju da prikazuju imenovanog autora.

## Stranice

- `index.html`: početna
- `o-projektu.html`: projektne oblasti i uvod
- `teme.html`: kultura, baština, međukulturni dijalog i mladi
- `biografije.html`: svih 15 biografskih cjelina uz pretragu
- `galerija.html`: svih 53 originalnih ilustracija, pregled uvećanih slika i pretraga
- `izvori.html`: završna bibliografija i napomena iz dokumenta

## Održavanje

Tekstovi su u HTML stranicama; sve izvorne jedinice dodatno su dostupne u `data/sadrzaj.json`. Stilovi: `css/style.css`; interakcije: `js/script.js`. Datum svake cjelina se nalazi pri dnu članka. Pretraživanje radi u pregledniku i ne koristi spoljašnje servise. Sajt **nema praćenje posjećenosti**, jer korisnik nije dostavio niti odobrio konkretan servis, identifikatore, privatnosnu politiku ili backend; timska odgovornost za praćenje u footeru jeste navedena, ali analitika nije predstavljena kao implementirana funkcija.
