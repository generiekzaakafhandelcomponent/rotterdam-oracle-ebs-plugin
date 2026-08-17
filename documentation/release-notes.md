# Release notes

Overzicht van wijzigingen per versie van de Rotterdam Oracle EBS-plugin.

## 2.0.5

Valtimo bijgewerkt naar versie 13.41.0.

## 2.0.4
Voorinvullen van journaalpost-regels werkt nu correct en veroorzaakt geen dubbele waarden of fouten meer.

## 2.0.3
Gesynchroniseerd met de laatste v13-versie uit de monorepo, met opgeschoonde imports en bijgewerkte afhankelijkheden.

## 1.4.3
Ondersteuning toegevoegd voor `bronspecifiekewaarden` bij de actie journaalpost-opvoeren.

## 1.4.1
Vertaalsleutel gecorrigeerd en aanvullende eigenschappen toegevoegd aan de loglijn.

## 1.4.0
`grootboek`-eigenschap toegevoegd aan de actie journaalpost-opvoeren.

## 1.3.0
Eigenschap `factuurKenmerk` toegevoegd aan de actie verkoopfactuur-opvoeren.

## 1.2.0
Mogelijkheid toegevoegd om een factuuradres mee te geven bij het opvoeren van een verkoopfactuur.

## 1.1.0
Sleutels worden nu nullable behandeld en `bronsleutel` is optioneel in de proceskoppeling.

## 1.0.10
Loglevel verhoogd voor betere diagnose.

## 1.0.9
`bronsleutel` optioneel gemaakt in de proceskoppeling.

## 1.0.7 - 1.0.8
Kleine versiebumps om frontend en backend gelijk te trekken.

## 1.0.6
Extra eigenschappen toegevoegd aan de actie verkoopfactuur-opvoeren en spellingsfout in README hersteld.

## 1.0.5
Dubbel veld uit het formulier verwijderd en frontend- en backendversies gelijkgetrokken.

## 1.0.3
Dropdowns vervangen door invoervelden zodat waarden via een value resolver kunnen worden meegegeven, en regels kunnen nu dynamisch worden opgegeven.

## 1.0.2
Resultaat van opvoeren-acties wordt opgeslagen in procesvariabelen zodat de uitkomst elders gebruikt kan worden.

## 1.0.0
Eerste publieke release: financiele transacties zoals journaalposten en verkoopfacturen versturen naar Oracle EBS van de gemeente Rotterdam.
