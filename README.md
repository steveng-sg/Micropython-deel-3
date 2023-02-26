# Micropython-deel-3


### De Micropython API
* Open de MicroPython documentatie: Movement Zie [link](https://microbit-micropython.readthedocs.io/en/v1.1.1/tutorials/movement.html)

Bestudeer deze.

* Open de API voor de accelerometer. Zie [link](https://microbit-micropython.readthedocs.io/en/v1.1.1/accelerometer.html)

De volgende code is heel interessant:
``` python
microbit.accelerometer.get_values()
```
Deze functie retourneert een tuple (x,y,z)

### Tuples
Een tuple is een soort gegevensstructuur in Python die wordt gebruikt om meerdere waarden in één variabele op te slaan. Het is vergelijkbaar met een lijst, maar de belangrijkste verschillen zijn dat tuples tussen haakjes worden geplaatst in plaats van tussen vierkante haken en dat tuples onveranderlijk zijn, wat betekent dat hun waarden niet kunnen worden gewijzigd nadat ze zijn gemaakt. Een tuple kan bestaan uit verschillende datatypen, zoals strings, integers, floats en zelfs andere tuples. Bijvoorbeeld:

```python
my_tuple = ("appel", "banaan", "citroen")
```
In dit voorbeeld is my_tuple een tuple die drie strings bevat: "appel", "banaan" en "citroen". De waarden kunnen worden geopend door middel van indexering, net als bij een lijst, bijvoorbeeld:

```python
print(my_tuple[0]) # Output: "appel"
```

Tuples zijn nuttig omdat ze een veilige manier bieden om meerdere waarden te groeperen en te retourneren vanuit een functie, omdat hun waarden onveranderlijk zijn.

### Oefenen

* Maak oefening 1
* Maak oefening 2




