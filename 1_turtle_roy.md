## Intro

- Turtle Roy: [http://turtle-roy.herokuapp.com/](http://turtle-roy.herokuapp.com/)
- Ohjeita (englanniksi) Githubissa: [https://github.com/raimohanska/turtle-roy](https://github.com/raimohanska/turtle-roy))
- [Suomenkieliset komennot](https://github.com/ykarikos/koodikoulu/blob/master/suomenkieliset_komennot.md) esiladattuna Turtle Royhyn: [http://turtle-roy.herokuapp.com/?turtle=XDPNCMH7VQ](http://turtle-roy.herokuapp.com/?turtle=XDPNCMH7VQ)

## Koodataan!

- Hiukan Turtle-grafiikkaa

```
ty
et 100
v 90
et 100
o 90
et 20
```

- Sekvenssi, eli tehdään asioita peräkkäin

```
s [et 100, v 90]
```

- Toisto, eli tehdään sama juttu monta kertaa (kokeile muuttaa parametrejä -\> jännän äärellä)

```
t 4 (s [et 100, v 90])
```

- Funktiot, eli opetetaan tietokoneelle juttuja

```
let askel = s [et 100, v 90] 
let neliö = t 4 askel
neliö
```

- Parametrisoidut funktiot, eli tehdään samalla koodilla eri kokoisia juttuja

```
let ympyrä säde = repeat 45 (s [et säde, v 8]) 
ympyrä 2 
ympyrä 4
```

- Rekursiiviset funktiot, eli itseään kutsuvat funktiot

```
let kiemura x = if x == 0 then et 0 else s [et x/10, o 10, kiemura (x - 1)]
kiemura 100
```

## Vinkkejä

- `ty` tyhjentää ruudun ja palauttaa konnan keskelle
- ` ↑ ` (nuoli ylös)
 - pääset tekemään edellisen jutun uudestaan
 - voit myös muokata komentoriviä liikkumalla sivunuolilla ja lisäämällä ja poistamalla tekstiä
- `ctrl-e` menee rivin loppuun
- `ctrl-a` menee rivin alkuun
- "show editor" -linkistä pääsee muokkaamaan koko ohjelmaa. "run" suorittaa sen alusta.
- Työn tallennus
 - `login "petteri"`
 - `save "häkkyrä"`
- Työn lataus
 - `login "petteri"`
 - `ls`
 - `open "häkkyrä"`
