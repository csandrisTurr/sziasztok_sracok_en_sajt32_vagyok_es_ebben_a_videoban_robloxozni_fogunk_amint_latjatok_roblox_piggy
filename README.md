# Lottó projekt
- By: Császár (Kernel) András, Tarr (waves) Gábor, Juhász (Goser) Gábor
- Pages: [Link](https://csandristurr.github.io/ikt/)

- Képek: Tarr
- HTML: Juhász
- CSS: Császár

## Főoldal
- A főoldal egy bal oldalon elhelyezkedő navigációs sávból és a tartalomból áll.
- A navigációs linkek használata során a weblaphoz tartozó al-oldalakra kerülünk.
- Oldalváltásnál csak az oldal tartalma változik.

## Projekt felépítés
- A projekt felépítése rendezett, minden a maga helyén van.
```
├───ikt
│   │   index.html
│   │
│   └───assets
│       ├───css
│       │       1.css
│       │       alap.css
│       │
│       └───img
│               banner.png
│               hatter.jpg
│               kekw.png
│               lotto.jpg
│               naancs.png
│               pijos.png
│               rozaszin.png
│               züd.png
```
- A fájlrendszerben a központi fájl a root mappában lévá index.html
- Az összes css fájl az `assets/css/` mappában van
- Az összes felhasználandó kép az `assets/img/` mappában van

## Kódfelépítés
- A projektben minden oldal külön HTML fájl
- Az összes oldal felhasználja az `alap.css` fájlt és egy számozott css fájlt, ami a navigációs sávon lévő sorrend szerint dől el.
### HTML
- Adott alap:
  - Változatlan Navigációs szekció
  - Oldalanként változó Main szekció
### Lottószámok megoldása:
- Táblázattal vannak megoldva:
  - Ha lottószámot adunk meg, az adott cellában a `pgomb` és `pg-<szín>` classokat használjuk. Ezek az `alap.css` fájlban vannak megadva, hogy globálisan tudjuk őket használni.
