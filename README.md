# Da Vinci Kalender

[![Build Status](https://travis-ci.com/davinci-kalender/kalender.svg?branch=master)](https://travis-ci.com/davinci-kalender/kalender)

Een kalender voor Da Vinci.

## Kalender

Een _kalender_ is een samenvoeging van een globale _klas kalender_ en een _persoonlijke kalender_.

### Klas kalender

Een _klas kalender_, oftewel een rooster, wordt beheerd door een _roostermaker_ en/of _mentor_.
Elke _klas_ heeft 1 _klas kalender_.

## Rollen

### Leerling

Elke _leerling_ zit in een _klas_.
Elke _leerling_ heeft een _kalender_,
deze _kalender_ is het eind resultaat van het samenvoegen van een _klas kalender_ en _persoonlijke kalender_.

Elke _leerling_ kan _items_ toevoegen aan eigen _persoonlijke kalender_

Deze _klas kalender_ wordt beheerdt door een _docent/roostermaker_.

### Docent

Een _docent_ kan:

* zijn eigen _rooster_/_kalender_ zien
* het _rooster_ van een _leerling_ zien
* een _taak_ geven aan een _klas_
* een _taak_ geven aan een _leerling_
* een _taak_ geven aan een _groep_
* _studenten_ en _docenten_ toevoegen aan een _groep_
* een _groep_ verlaten

### Roostermaker

Een _roostermaker_ kan:

* _klas kalender_ zien
* _klas kalender_ aanmaken
* _klas kalender_ veranderen
* _klas kalender_ verwijderen

## Overige

### Groep

* Een _groep_ bestaat uit minsten 2 _studenten_ en/of _docenten_
* Een groep kan taken krijgen van _studenten_ en _docenten_

### Klassentaak:
* een klassentaak heeft een _einddatum(mag leeg zijn)_
* een klassentaak heeft een _uitvoeringsdatum(mag leeg zijn)_
* een klassentaak heeft een _naam_
* een klassentaak heeft een _beschrijving_
* een klassentaak heeft een _id_

### KlassentaakLeerling:
* verbind een leerling met een Klassentaak door middel van een _id_ van beide 
* Heeft een _klassentaak id_
* heeft een _leerling id_ 
* heeft een uitvoeringsdatum(mag leeg zijn)
* heeft een _status_ 

