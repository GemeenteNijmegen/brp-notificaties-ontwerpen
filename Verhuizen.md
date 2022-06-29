# Event: verhuizen


## Functioneel
Een verhuizing van een persoon kan op meerdere manieren worden getriggered. 
Bijvoorbeeld:
- ingeschrevene
- technische wijziging i.v.m. BAG

Op de vraag wat te doen met verschillende soorten mutaties anders dan ingeschrevene (Bijv. BAG) is het wenselijk een extra veld op te nemen met het mutatie subtype. Hierin kan volgens de "Omschrijving van de aangifte adreshouding" ([Zie pagina 314 van het Logisch ontwerp GBA 3.14](https://www.rvig.nl/binaries/rvig/documenten/publicaties/2022/01/02/logisch-ontwerp-gba-3.14/LO+GBA+3.14.pdf)) worden aangegeven waarom de mutatie voor komt. Dit stelt event afnemers in staat te filteren op het soort mutatie die het verhuizing event triggered.  

## Kenmerken
De kenmerken van een event bericht worden vastgelegd aan de hand de kenmerken

| kenmerk | waarde                                                                  |
| ------- | ----------------------------------------------------------------------- |
| type    | "nl.gemeente.brp.verhuizing"                                            |
| dataref | Referentie naar haalcentraal: "/api​/v1.3​/ingeschrevenpersonen​/{bsn}" |
| subject | BSN                                                                     |
