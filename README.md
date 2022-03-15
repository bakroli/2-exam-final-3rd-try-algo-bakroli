# Add Digits
## Feladatleírás
Hozd létre az `AddDigits` osztályt, és annak az `addDigits(String input)` metódusát.

A metódus feladata, hogy a paraméterben kapott Stringben található összes számjegyet adja össze, és ennek az összegét
adja vissza. Ha a bemeneti String üres, vagy null, adjon vissza -1 -et.

Ha egy számjegy előtt a `-` jel szerepel, akkor a következő számjegy negatívnak számít.

### Példák

`""` -> `-1`

`"22"` -> `4`

`"1alma23"` -> `6`

`"1alm-8a23"` -> `-2`
