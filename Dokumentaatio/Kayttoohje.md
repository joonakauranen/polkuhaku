## Käyttöohje
Vaikka graafisen käyttöliittymän tynkä löytyy, koodi toimii toistaiseksi printtaamalla terminaaliin. Yritys parantaa tilannetta on kova.

### Ohjelman hyväksymä syöte
- Ohjelma toimii niin, että graafisesta labyrintin esityksestä tehdään sanakirjamuotoinen esitys siitä, mistä koordinaatista voi siirtyä mihinkin koordinaattiin. Graafinen esitys on lista, jossa on merkkijonoja. Kukin listan jäsen vastaa yhtä riviä labyrintissa. Mallia voi katsoa testilabyrinmtti-tiedostosta
- Käytössä olevat merkit:
    - '#' = seinä
    - ' ' = lattia
    - 'A' = alku
    - 'B' = loppu
- Labyrintin reunat ovat seinää, joissa sijaitsevat myös alku ja loppu
- Alku ja loppu voivat sijaita vain seinillä, eivät nurkassa
- Labyrintissa voi kulkea sivuille, ylös ja alas mikäli sivuiltaan koskettavat lattian osat ovat molemmat lattiaa.
- Labyrintissa voi kulkea vinottain mikäli lattiaa ovat sekä määränpää että jompi kumpi ruuduista jotka ovat määränpään ja lähöruudun kanssa naapureita 

### Ohjelman käyttäminen
Tällä hetkellä ohjelma toimii vain suorittamalla index.py tiedoston. Esimerkiksi terminaalissa avaamalla ohjelman sisältävän kansion ja suorittamalla käskyn
```bash
python3 src/index.py
```