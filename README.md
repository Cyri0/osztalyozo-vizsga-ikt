# Villámkártyák - Frontend feladat

**<span style="color:red">Első lépésként forkoljátok le ezt a repository-t. A saját átforkolt változatotokon fogtok dolgozni. Ha kész a feladat, akkor küldjetek egy pull request-et, és akkor én is látni fogom a munkátokat.</span>**

A feladatotok a design mappában található képek alapján, és a public mappában található json felhasználásával elkészíteni a flashcards alkalmazás frontend részét. Egyelőre a json fájllal kell működnie a programnak. A json fájlt fetch vagy axios segítségével olvassátok be.
A kártyáknak készíts külön React komponenst!
A kártyák átfordításkor (tehát ha rákattintunk a kártyára amikor kérdés van rajta) animálva kell átfordulnia, amit az alábbi linken megnézhettek hogyan kell:

[W3Schools anyag](https://www.w3schools.com/howto/howto_css_flip_card.asp)

Ezután visszajelzést adhatunk, hogy tudtuk-e az adott kérdésre a választ vagy sem. Mindkét gomb lenyomásának eredménye azt kell hogy legyen, hogy átlépünk a következő lapra.

A kártya színe a kérdés nehézségétől függ (a nehézség pedig később attól fog függeni, hogy hányszor rontották el):

- pozitív szám esetén zöld (--green)
- 0 esetén fehér (white)
- negatív szám esetén piros (--red)

Ugyan ez vonatkozik az átfordítás után a fejlécben a színre (ahol megjelenik a nehézség pontszám is).

## Az oldalon használt színek

```css
--green: #66CB92;
--red: #FF9396;

--bg-color-1: #FC00FF;
--bg-color-2: #00DBDE;
```

## Font-awesome ikonok

```jsx
// Pipa
<i className="fa-regular fa-circle-check"></i>

// X
<i className="fa-regular fa-circle-xmark"></i>

// Plusz jel
<i className="fa-solid fa-plus"></i>
```

## Pontozás:
- Sikeres forkolás - 1 pont
- FlashCardType típus megírása - 1 pont
- megfelelő állapot lérehozása a FlashCard típus alapján - 1 pont
- json fájl beolvasása - 1 pont
- json fájl tartalmának eltárolása állapotban - 1 pont
- FlashCard komponens elkészítése (megfelelő szerkezettel a w3schools-os minta alapján) - 1 pont
- FlashCard animálásának CSS-e - 1 pont
- props-ok átadása - 1 pont
- kártya forgatása kattintásra - 1 pont
- kártyák léptetésének megoldása - 3 pont
- megfelelő háttérszín a pontok alapján - 2 pont
- progress bar számos része - 1 pont
- progress bar - 2 pont
- megfelelő GitHub commitolás (főbb feladatonként egy commit) - 2 pont
- pull request - 1 pont


| Pontszám | Százalék | Osztályzat |
|--------|---------|------------|
| 0–7    | 0–39%   | 1 – elégtelen |
| 8–10   | 40–54%  | 2 – elégséges |
| 11–13  | 55–69%  | 3 – közepes |
| 14–16  | 70–84%  | 4 – jó |
| 17–20  | 85–100% | 5 – jeles |
