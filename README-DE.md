# Erstelle Apps mit JavaScript Klassen

Verwende dein Wissen von JavaScript-Klassen, um die hier aufgeführten Anwendungen zu erstellen: Baue die passenden Methoden, instanziiere die Klassen als Objekt, und rufe die entsprechenden Methoden für die Objekte auf, damit Ihre Anwendung funktioniert.

## 1. Gebrauchtes Auto App

- Car
	- constructor(make,color,year)
	- Properties
	    - make --> (Marke)
	    - color --> (Farbe)
	    - year --> (Jahr)
	- Methoden
	    - display()
- Cars
	- constructor()
	- Properties
	    - cars *(array)*
	- Methoden
	    - addCar(car)
	    - listCars()

## 2. Coding Schule App

- Tutorial
	- Properties
		- title --> (Titel)
		- chapters --> (Kappiteln)
		- price --> (Preis)
		- users - *(array)*
	- Methoden
		- addUser(user)
		- listUsers()
- user
	- properties
		- id
		- firstName
		- lastName
	- display()


## 3. Transportation-Sharing App

- Vehicle (Fahrzeug)
	- latitude --> (Breitengrad)
	- longitude --> (Längengrad)
	- currentlyRented --> (derzeit vermietet)
- Bike --> (Fahrrad)
	- color
	- size (child, adult)
	- wheels (2,3)
- Scooter 
	- batteryMinutesLeft --> (Akku Minuten übrig)
- Vehicles --> (Fahrzeuge)
	- listBikes([child/adult/all])
	- listCurrentlyFree() --> (Liste Derzeit frei) 
 
### Challenge :muscle:
- zusätzliche Methoden für Fahrzeuge
	- displayOnMap()
		- text?
		- canvas?
		- Google Maps API?
	- getClosestVehicle(lat,long)

