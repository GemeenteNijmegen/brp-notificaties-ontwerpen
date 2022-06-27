# Event: persoon overleden

## Functioneel


**Overwegingen:**
Event wordt getriggerd op moment dat de persoonslijst in brp wordt bijgewerkt. Dit is wenselijk omdat de persoon nog in leven kan zijn in brp op het moment dat de zaak wordt ingeschoten.

## Kenmerken
| kenmerk | waarde                                                                  |
| ------- | ----------------------------------------------------------------------- |
| type    | "nl.gemeente.brp.persoon-overleden"                                     |
| dataref | Referentie naar haalcentraal: "/api​/v1.3​/ingeschrevenpersonen​/{bsn}" |
| subject | BSN                                                                     |
