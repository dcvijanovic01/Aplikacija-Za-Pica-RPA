Aplikacija za pića
1.1	Svrha aplikacije 
Kroz samostalni rad na kolegiju “Razvoj poslovnih aplikacija” razviti će se jednostavna aplikacija za pića koja podržava unos, uređivanje, brisanje, pretragu I popis pića u bazi. Aplikacija također treba omogućiti brisanje I prikaz detalja pojedinog pića. Svaki unos podataka kroz aplikaciju treba uključivati provjeru valjanostii za brisanje podataka je potrebna posebna potvrda korisnika.
1.2	Korisnici aplikacije
Aplikaciji treba moći pristupiti svi korisnici koji imaju internet I internet preglednik te žele pristupiti svim bitnih informacijama o raznim pićima na jednom centraliziranom mjestu.
1.3	Koristi (benefiti) od aplikacije
Stvoriti će se jedna centralna baza podataka o pićima dostupna svima. Korisnici kada budu htjeli potražiti informacije o pićima neće više morati pretraživati putem Googlea I koristiti više izvora za dobivanje informacija o nekom piću, jer će kroz aplikaciju moći dobiti sve potrebne informacije na jednom mjestu. Aplikacija će biti dostupna putem interneta zahvaljujući tome korisnik ima mogućnost korištenja aplikacije u bilo koje vrijeme.
2.	Zahtjevi
2.1	Funkcijski zahtjevi
Aplikacija mora omogućiti spremanje, uređivanje, pretraživanje, prikaz, traženje I brisanje pića u bazi podataka.
2.2	Sistemski, hardverski i mrežni zahtjevi
Budući da će aplikacija biti razvijena u ASP.NET Core MVC-u, ona treba biti smještena na Microsoft Web poslužitelj (eng. Server). Preporučuju se sljedeće hardverske specifikacije:
Minimum četverojezgreni processor radnog takta 2.2GHz
Minimum 32GB RAM memorije
Minimum 1TB diskovnog prostora
Operativni sustav Windows server (2019)

2.2.1. Web server
Preporučuje se korištenje Windows Azurea za hostanje aplikacije. Windows azuremože hostati bilo koju ASP.NET Core MVC aplikaciju, uključujući I našu predloženu aplikaciju u ovom dokumentu. Skaliranje je vrlo jednostavno jer je Microsoft odgovoran za dodavanje resursa na poslužitelju za vrijeme visokog prometa.
Troškovi su minimalni, oni ovise o količini podataka koji se prikazuju posjetiteljima te održavanje hardwarea nije uključeno u njih.

2.2.2. Baza podataka
Preporučuje se korištenje SQL SERVER baze podataka unutar WA, za temeljnu bazu podataka aplikacije. Što se tiče Web poslužitelja, ova preporuka osigurava visoku dostupnost hostinga za bazu podataka s dobrim omjerom vrijednosti za uloženi novac.To posebno ima smisla ako je i Web aplikacija hostana na Windows azureu.
2.3	Sigurnost
U kasnijem razvoju aplikacije razvit će se sigurna identifikacija I zaštićena autentifikacija gdje korisnička imena i lozinke ne smiju biti spremljena u obična tekstualna polja ili datoteke, a osobni podaci korisnika kao što su adresa, telefonski brojevi i brojevi kreditnih kartica neće biti dostupni anonimnim pristupom.
