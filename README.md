# Automotive-Data-Warehouse-Business-Intelligence.
Automotive sales data warehouse project using Microsoft Access, SQL and Tableau.
---

## 1. Opis projekta

Projekt obuhvaća izradu **skladišta podataka (Data Warehouse)** i sustava **poslovne inteligencije (Business Intelligence)** za analizu prodaje automobila.

Cilj projekta bio je transformirati izvorne podatke o prodaji automobila u strukturirano skladište podataka te izraditi interaktivne vizualizacije koje omogućuju analizu prodajnih rezultata i podršku donošenju poslovnih odluka.

## 2. Korištene tehnologije

| Tehnologija | Primjena |
|---|---|
| **Microsoft Access** | Izrada baze podataka, upravljanje podacima i ETL procesi |
| **SQL** | Transformacija, čišćenje i učitavanje podataka |
| **Tableau** | Vizualizacija podataka, nadzorne ploče i analitički izvještaji |
| **Microsoft Excel** | Pregled i priprema podataka |

## 3. Skup podataka

U projektu je korišten skup podataka **Car Sales Report**, preuzet s platforme Kaggle.

<https://www.kaggle.com/datasets/missionjee/car-sales-report>

Skup podataka obuhvaća informacije o prodaji automobila tijekom 2022. i 2023. godine, uključujući podatke o:

- kupcima
- karakteristikama automobila
- prodavačima
- prodajnim transakcijama

## 4. Model skladišta podataka

Skladište podataka izrađeno je primjenom **zvjezdaste sheme (Star Schema)**, koja se sastoji od jedne središnje činjenične tablice i četiri dimenzijske tablice.

**Činjenična tablica:**
- Prodaja

**Dimenzijske tablice:**
- Automobili
- Kupci
- Prodavači
- Datumi

Ovakva struktura omogućuje analizu prodaje automobila prema različitim kriterijima.

## 5. ETL proces

ETL proces proveden je u alatu Microsoft Access i obuhvatio je tri glavne faze:

1. **Ekstrakcija (Extract)** – uvoz izvornog skupa podataka u Microsoft Access.
2. **Transformacija (Transform)** – prilagodba tipova podataka, izdvajanje vremenskih atributa (dan, mjesec i godina) te čišćenje nekonzistentnih vrijednosti.
3. **Učitavanje (Load)** – izrada i popunjavanje dimenzijskih tablica i središnje činjenične tablice.

## 6. Tableau – nadzorna ploča i izvještaji

U alatu Tableau izrađena je interaktivna nadzorna ploča koja omogućuje pristup pet analitičkih izvještaja:

| Izvještaj | Opis |
|---|---|
| **1. Trendovi prodaje automobila** | Analiza prihoda od prodaje prema vrsti motora i mjesecima |
| **2. Uspješnost prodavača po regijama** | Usporedba rezultata prodavača prema različitim regijama |
| **3. Analiza prihoda kupaca prema markama** | Analiza godišnjih prihoda kupaca prema markama kupljenih automobila |
| **4. Analiza automobila prema cijenama** | Prikaz raspodjele prodanih vozila prema cjenovnim razredima |
| **5. Prosječne cijene vozila po modelima** | Usporedba 20 modela s najvećom prosječnom cijenom |

## 7. Projektna dokumentacija

Projektna dokumentacija sadrži detaljan opis:

- modela skladišta podataka
- provedbe ETL procesa
- korištenih SQL upita
- izrade dimenzijskih i činjenične tablice
- Tableau nadzorne ploče i analitičkih izvještaja

---

**Projekt je izrađen u sklopu kolegija Skladište podataka i poslovna inteligencija na Fakultetu organizacije i informatike.**

Projektna dokumentacija sadrži detaljan opis modela skladišta podataka, provedbe ETL procesa, korištenih SQL upita i izrađenih Tableau izvještaja.
