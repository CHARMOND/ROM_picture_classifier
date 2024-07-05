# Klasifikacija Fotografij Športnih Dogodkov
Tukaj je primer ReadMe datoteke za GitHub repozitorij za ta projekt:


## Opis Projekta
Ta projekt je del seminarske naloge pri predmetu Računalniška orodja v matematiki. Cilj projekta je razviti klasifikator za izbor fotografij športnih dogodkov, kot so teki in kolesarske dirke, z uporabo Wolfram Mathematica. Model bo treniran za razlikovanje med izbranimi in zavrnjenimi fotografijami ter bo validiran in testiran za oceno natančnosti.

## Struktura Projektnih Datotek
- `Seminarska2.nb`: Wolfram Mathematica notebook, ki vsebuje celotno kodo za uvoz, obdelavo, treniranje, validacijo in testiranje klasifikatorja.
- `Test_izbrane/`: Mapa, ki vsebuje izbrane fotografije za trening.
- `Test_vse/`: Mapa, ki vsebuje zavrnjene fotografije za trening.
- `Class_izbrane/`: Mapa, ki vsebuje izbrane fotografije za validacijo.
- `Class_neizbrane/`: Mapa, ki vsebuje zavrnjene fotografije za validacijo.
- `Validacija_izbrane/`: Mapa, ki vsebuje izbrane fotografije za testiranje.
- `Validacija_zavrnjene/`: Mapa, ki vsebuje zavrnjene fotografije za testiranje.
- `README.md`: Datoteka z opisom projekta in navodili za uporabo.

## Navodila za Namestitev
1. **Klonirajte repozitorij**:
   ```bash
   git clone https://github.com/tvoje_uporabniško_ime/klasifikacija-fotografij-športnih-dogodkov.git
   ```
2. **Odprite Wolfram Mathematica**.
3. **Odprite notebook `Seminarska2.nb`**.

## Navodila za Uporabo
1. **Nastavite delovno mapo**:
   Notebook je že nastavljen, da deluje z relativnimi potmi. Ko odprete notebook, bo delovna mapa samodejno nastavljena na lokacijo notebooka.

2. **Uvoz slikovnih podatkov**:
   Sledite ukazom v notebooku za uvoz slik iz map `Test_izbrane` in `Test_vse`. Slike bodo avtomatsko normalizirane na velikost 256x256 pik.

3. **Treniranje klasifikatorja**:
   Uporabite uvožene in obdelane slike za treniranje klasifikatorja z metodo RandomForest.

4. **Validacija modela**:
   Uvozite validacijske slike iz map `Class_izbrane` in `Class_neizbrane`. Izvajanje ukazov v notebooku bo omogočilo validacijo modela in oceno njegove natančnosti.

5. **Testiranje modela**:
   Uvozite testne slike iz map `Validacija_izbrane` in `Validacija_zavrnjene`. Izvajanje ukazov v notebooku bo omogočilo testiranje modela in generiranje končne natančnosti ter matrike zmede.

## Ocena Natančnosti
Po izvedbi vseh korakov boste dobili oceno natančnosti modela ter matriko zmede, ki prikazuje uspešnost modela pri razlikovanju med izbranimi in zavrnjenimi fotografijami.

## Zahteve
- Wolfram Mathematica 13.1 ali novejša različica
- Ustrezni slikovni podatki v mapah `Test_izbrane`, `Test_vse`, `Class_izbrane`, `Class_neizbrane`, `Validacija_izbrane`, `Validacija_zavrnjene`

## Povezava do Videoposnetka Predstavitve
[Povezava do videoposnetka](https://link-do-tvojega-videoposnetka)

## Avtor
- **Aljaž Čarman**
- **@CHARMOND** https://github.com/CHARMOND 

---

Z uporabo tega ReadMe dokumenta bodo uporabniki imeli jasna navodila za kloniranje repozitorija, namestitev potrebnih orodij, uvoz podatkov, treniranje modela in oceno njegove natančnosti.
