# Automotive-Data-Warehouse-Business-Intelligence.
Automotive sales data warehouse project using Microsoft Access, SQL and Tableau.

Opis projekta

Projekt obuhvaća izradu skladišta podataka i sustava poslovne inteligencije za analizu prodaje automobila.

Cilj projekta bio je transformirati izvorne podatke o prodaji automobila u strukturirano skladište podataka te izraditi interaktivne vizualizacije koje omogućuju analizu prodajnih rezultata i podršku donošenju poslovnih odluka.

Korištene tehnologije

Microsoft Access – izrada baze podataka, upravljanje podacima, SQL upiti i ETL procesi.

SQL – transformacija, čišćenje i učitavanje podataka.

Tableau – vizualizacija podataka, nadzorne ploče i analitički izvještaji.

Microsoft Excel – pregled i priprema podataka.

Skup podataka

U projektu je korišten skup podataka Car Sales Report, preuzet s platforme Kaggle.

Car Sales Report – Kaggle

Skup podataka obuhvaća informacije o prodaji automobila tijekom 2022. i 2023. godine, uključujući podatke o kupcima, karakteristikama vozila, prodavačima i prodajnim transakcijama.

Model skladišta podataka

Skladište podataka izrađeno je primjenom zvjezdaste sheme (Star Schema), koja se sastoji od središnje činjenične tablice i četiri dimenzijske tablice.

Činjenična tablica: Prodaja

Dimenzijske tablice:

Automobili

Kupci

Prodavači

Datumi

Ovakva struktura omogućuje analizu prodaje automobila prema različitim kriterijima.

ETL proces

ETL proces proveden je u alatu Microsoft Access i obuhvatio je tri glavne faze:

Ekstrakcija (Extract) – uvoz izvornog skupa podataka u Microsoft Access.

Transformacija (Transform) – prilagodba tipova podataka, izdvajanje vremenskih atributa (dan, mjesec i godina) te čišćenje nekonzistentnih vrijednosti.

Učitavanje (Load) – izrada i popunjavanje dimenzijskih tablica i središnje činjenične tablice.

Tableau nadzorna ploča i izvještaji

U alatu Tableau izrađena je interaktivna nadzorna ploča koja omogućuje pristup pet analitičkih izvještaja:

Trendovi prodaje automobila – analiza prihoda od prodaje prema vrsti motora i mjesecima.

Uspješnost prodavača po regijama – usporedba rezultata prodavača prema različitim regijama.

Analiza prihoda kupaca prema markama – analiza godišnjih prihoda kupaca prema markama kupljenih automobila.

Analiza automobila prema cijenama – prikaz raspodjele prodanih vozila prema cjenovnim razredima.

Prosječne cijene vozila po modelima – usporedba 20 modela s najvećom prosječnom cijenom.

Projektna dokumentacija

Projektna dokumentacija sadrži detaljan opis modela skladišta podataka, provedbe ETL procesa, korištenih SQL upita i izrađenih Tableau izvještaja.
