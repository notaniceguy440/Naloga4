# ScrollingText – Android aplikacija

## Namen naloge
Namen naloge je bil nadgraditi aplikacijo ScrollingText tako, da omogoča pregledno prikazovanje daljšega besedila v drsnem pogledu z uporabo dveh stolpcev.

## Uporabljene tehnologije
- Android Studio
- XML
- Java / Kotlin
- Android UI Components

## Funkcionalnosti
- Prikaz daljšega besedila z uporabo `ScrollView`.
- Razporeditev vsebine v dva stolpca.
- Levi stolpec širine 100dp za podnaslov.
- Desni, širši stolpec za glavno besedilo članka.
- Uporaba `LinearLayout` z vodoravno orientacijo.
- Shranjevanje besedilnih vsebin v `strings.xml`.
- Gumb za oddajo komentarja.
- Prikaz sporočila `Comment submitted!` ob kliku na gumb z uporabo `Toast`.

## Uporabljeni gradniki
| Gradnik | Namen |
|---|---|
| `ScrollView` | Omogoča navpično drsenje besedila. |
| `LinearLayout` | Razporedi gradnike v dva stolpca. |
| `TextView` | Prikazuje podnaslov in glavno besedilo. |
| `Button` | Omogoča oddajo komentarja. |
| `Toast` | Prikaže potrditveno sporočilo. |

## Rezultat
Aplikacija omogoča pregledno prikazovanje daljšega članka v dveh stolpcih. Uporabnik lahko vsebino pomika navpično, ob kliku na gumb pa se prikaže potrditveno sporočilo.
