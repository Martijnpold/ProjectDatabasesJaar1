# ProjectDatabasesJaar1
Project Databases Stuffs

Processen:
> Verkoper – order vastleggen
    > De klant moet gekozen worden uit een lijstje. Het lijstje moet te sorteren zijn en je moet kunnen zoeken.
    > Als de klant gekozen is, kunnen bepaalde gegevens op het scherm al ingevuld worden.
    > Per orderregel moet een medicijn gekozen worden.
    > Als aantal van het medicijn is ingevuld, dan kan de totaalprijs voor die ene regel worden berekend en de totaalprijs van de order wordt    bijgewerkt (exclusief én inclusief de korting)
    > Als alles is ingevuld, wordt de order bewaard (Let op: jullie hoeven het SQL INSERT statement niet mee te nemen)

> Inkoper
    > medicijnen waarvan de voorraad te laag is, moeten ingekocht worden. Je moet ervan uitgaan dat een medicijn in principe bij meerdere leveranciers ingekocht kan worden en uiteraard wordt de goedkoopste besteld.

> Facturering
    > Orders die te factureren zijn (geleverd, maar nog niet gefactureerd) moeten gefactureerd worden

> Facturering
    > Wanbetalers nabellen: bedrijven die nalatig zijn bij het betalen van hun facturen moeten gebeld worden. 

> Magazijnmedewerker
    > Pak orders in die verstuurd moeten worden (en waarvoor de robots de medicijnen via één of meer bakken aan het verzamelen zijn). . 

Tabs:
> Home
    + Verwijzing naar de tabjes en de inhoud
> Klanten
    + Zoeken naar klanten
    + Toevoegen klanten
    + Verwijderen klanten
    + Aanpassen klanten
> Verkoop
    > Kiezen van klant (met search)
    > Order invullen, medicijn kiezen
    > Prijs per totaal productregel
    > Totaalprijs exclusief en inclusief korting
    > Save Order knop
> Inkoop
    + Lijst met tekort (aantal + minimum)
    + Klik op product voor leveranciers (Gesorteerd op prijs)
> Facturering
    > Orders met "Facturerings" status displayen
    > Op order klikken laat de medewerker aanvinken wat er verstuurd is en versturen.
> Facturering 2 (Eventueel op hetzelfde scherm)
    > Facturen laten zien die ouder dan [invulbaar] dagen oud zijn en "betaald" op 0 hebben staan.
> Magazijn
    > Laat lijstje van actieve orders zien
    > Klikken laat de robot zien die bezig is en vooruitgang en wat erbij hoort
    > Knop om status naar verstuurd te zetten