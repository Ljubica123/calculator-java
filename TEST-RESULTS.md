# TEST-RESULTS – Calculator Java

Vrsta testiranja: Black Box (sistemsko / prihvatno testiranje)

-------------------------------------
POZITIVNI TESTOVI
-------------------------------------

Test 1
Ulaz: 2+2
Očekivano: 4
Dobijeno: 4
Status: PROŠAO

Test 2
Ulaz: 10-3
Očekivano: 7
Dobijeno: 7
Status: PROŠAO

Test 3
Ulaz: 2+3*4
Očekivano: 14
Dobijeno: 14
Status: PROŠAO

Test 4
Ulaz: 10+5*4+3
Očekivano: 33
Dobijeno: 33
Status: PROŠAO

-------------------------------------
NEGATIVNI TESTOVI
-------------------------------------

Test 1
Ulaz: 5/0
Očekivano: Greška
Dobijeno: Program se ruši / baca grešku
Status: PALO

Test 2
Ulaz: abc
Očekivano: Greška
Dobijeno: Program odbija unos
Status: PROŠAO

Test 3
Ulaz: 5++
Očekivano: Greška
Dobijeno: Program se ruši / baca grešku
Status: PALO

Test 4
Ulaz: 5+
Očekivano: Greška
Dobijeno: Program se ruši / baca grešku
Status: PALO

-------------------------------------
ZAPAŽANJA
-------------------------------------

- Kalkulator radi osnovne operacije (+, -, *, /) i poštuje prioritet množenja i deljenja
- Ako se unesu slova ili znakovi koji nisu brojevi ili operatori, program može da padne
- Deljenje nulom uzrokuje pad programa
- Ne podržava razmake u izrazu
- Nema poruka korisniku kada se desi greška

-------------------------------------
PREPORUKE
-------------------------------------

- Dodati proveru ispravnosti unosa pre računanja
- Rukovati greškama kao što su deljenje nulom ili nevažeći znakovi
- Prikazivati poruku korisniku kada unos nije dobar
- Dodati jednostavne unit testove (kao onaj za Calculate metodu)
