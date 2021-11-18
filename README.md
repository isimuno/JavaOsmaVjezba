# JavaOsmaVjezba

8.Osma laboratorijska vježba
8.1. TEMA VJEŽBE
Svrha laboratorijske vježbe je implementacija grafičkog sučelja
temeljena na JavaFX tehnologiji s naglaskom na ekranima za dodavanje
novu zapisa u datoteke.
8.2. ZADATAK ZA PRIPREMU
Proširiti rješenje sedme laboratorijske vježbe na način da se kopira
rješenje te preimenuje u naziv koji sadrži indeks „8“, umjesto „7“. Osim
same mape s projektom, potrebno je promijeniti i naziv projekta unutar
IntelliJ-a korištenjem opcije „Refactor->Rename“. Program je potrebno
proširiti na sljedeći način:
1. FXML datoteku koja predstavlja početni ekran proširiti na način da se
u svaki od izbornika postavi dodatna opcija „Novi zapis“, uz već
postojeću opciju „Pretraga“.
2. Kreirati datoteku „izbornik.fxml“ koja se sadržavati konfiguraciju
„MenuBar“ izbornika unutar npr. „AnchorPane“ organizatora
rasporeda komponenti. Tu datoteku je korištenjem sljedeće naredbe
potrebno dodati na sve ostale ekrane:
<fx:include fx:id="izbornik" source="izbornik.fxml" />
Izbornik mora biti povezan s klasom „PocetniEkranController“ koji
sadrži metode za otvaranje svih ostalih ekrana koji se dohvaćaju
putem izbornika.
3. Kreirati novi FXML datoteku pod nazivom
„dodavanjeNoveZupanije.fxml“ koji može izgledati kao ekran na
sljedećoj slici. Na ekranu na slici dodati „izbornik.fxml“ kako bi se
mogla obavljati navigacija na sve ostale ekrane.
Slika 1. Dizajn ekrana za dodavanje nove županije
4. Kreirati klasu „DodavanjeNoveZupanijeController“ koja će sadržavati
varijable grafičkih komponenata prikazanih na slici 1 te metodu za
dodavanje nove županije u datoteku.
5. Kreirati ekrane za dodavanje svih ostalih entiteta u aplikaciji:
simptoma, bolesti, virusa i osoba. Također kreirati „Controller“ klase
za sve navedene ekrane pomoću kojih se dodaju novi podaci u
aplikaciju.
6. Na svim mjestima gdje je to prikladno postaviti dijalog koji
obavještava korisnika o uspješno ili neuspješno izvršenoj akciji.
Primjer izvođenja programa za spremanje novih županija je prikazan na
sljedećem videu: https://www.youtube.com/watch?v=XNwiKS2mYWU.
