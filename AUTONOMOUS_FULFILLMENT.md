# Autonomiczny fulfillment

To repo jest przygotowane tak, żeby Hermes mógł działać bez proszenia Pauliny o każdy krok.

## Warunek wejścia

Nowe GitHub Issue z etykietą `order` i briefem.

## Co Hermes robi

1. Czyta brief.
2. Przygotowuje odpowiedź/deliverable w komentarzu albo pliku.
3. Oznacza, czego nie może zweryfikować, zwłaszcza płatności.
4. Nie dotyka prywatnych danych ani sekretów.

## Granica

Hermes nie widzi Revoluta i nie potwierdza pieniędzy. Może tylko dowozić pracę po sygnale z issue albo po potwierdzeniu Pauliny.
