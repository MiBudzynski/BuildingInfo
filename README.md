# BuildingInfo
# **Projekt z Inżynierii Oprogramowania**
**Dla administratorów budynków**, którzy pragną optymalizować koszty zarządzania budynkami  nasza aplikacja Building Info umożliwi pozyskanie informacji o parametrach budynku na poziomie pomieszczeń, kondygnacji oraz całych budynków. Aplikacja będzie dostępna poprzez GUI a także jako zdalne API dzięki czemu można ją zintegrować z istniejącymi narzędziami.

## **Struktura danych**
* Lokacja to budynek, poziom, lub pomieszczenie
* Budynek może składać się z poziomów a te z pomieszczeń
* Każda lokalizacja jest charakteryzowana przez:
    *  id – unikalny identyfikator
    *  name – opcjonalna nazwa lokalizacji
* Pomieszczenie dodatkowo jest charakteryzowane przez:
    * area = powierzchnia w m^2
    * cube = kubatura pomieszczenia w m^3
    * heating = poziom zużycia energii ogrzewania (float)
    * light – łączna moc oświetlenia
 
## Członkowie zespołu
* Agata Kashyna
* Michał Budzyński (Scrum Master)
* Aleksandra Bamberska
* Adam Biernacki

## Zarządzanie rejestrem projektu
Zarządzanie rejestrem projektu i rejestrem sprintu odbywa się na platformie Trello

[Zobacz rejestr projektu](https://trello.com/b/aaN2qBro)


