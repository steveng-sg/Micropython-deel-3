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
Hoe doe je dit?
1. Zorg dat je de repository gecloned hebt.
2. Open de juiste oefening in de mu-editor.
3. Schrijf de code/ pas de code aan zoals gevraagd.
4. Upload de code naar de microbit.
5. Test de code met de microbit
6. Maak eventueel aanpassingen aan de code om de werking te verbeteren.
7. Sla je werk op en deel het met de leerkracht via Github Classroom.

* Oefening 1

Bestudeer goed de waarden van oefening 1. Bij welke waarde helt de microbit veel? Bij welke waarde (interval) is de microbit +/-waterpas? Je hebt deze kennis nodig voor de volgende oefening.

* Oefening 2

In deze oefening ga je een waterpas maken op de microbit. Je gebruikt enkel de middelste rij LEDs. Bij een waterpas gaat het luchtbolletje altijd omhoog.
Als de microbit naar links helt, zal het bolletje op het scherm naar links rollen en als de microbit naar rechts helt, zal het bolletje naar rechts rollen. Is de microbit waterpas, dan zal enkel de centrale led opgelicht zijn.


* Oefening 3
Maak de waterpas in 3D. Houd je deze schuin naar links/achter dan is het bolletje rechts beneden opgelicht.





