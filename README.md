# Struktura

## Vendors
    Biblioteki podmiotów trzecich.

## Abstracts
    Tylko funkcje pomocnicze i nie-wyjściowe fragmenty (importy czcionek, miksy wielokrotnego użytku, zmienne globalne, kolory itp.)

## Base
    Style globalne są importowane tutaj. 
    Tutaj jest też grid.
    Można dodać niestandardowy plik resetowania, aby zastąpić normalizację.

## Layout
    Importowane są tutaj unikalne kombinacje komponentów i stylów bazowych.
    Każdy arkusz stylów zawiera wszystkie przesłonięcia stylu komponentu i tylko określone atrybuty układu.

## Components
    Importowane są tutaj elementy wielokrotnego użytku na poziomie mikro. 
    Każdy komponent robi jedną i tylko jedną rzecz. 
    Komponenty są wielokrotnego użytku w całym projekcie. 
    Komponenty są niezależne.

## Helpers
    Klasy pomocnicze.