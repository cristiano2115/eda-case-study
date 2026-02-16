# Titanic EDA (Python, Pandas)

## Cel
Celem projektu jest wykonanie eksploracyjnej analizy danych (EDA): przegląd jakości danych, analiza rozkładów i zależności oraz zapis wersji „clean” danych do dalszej pracy.

## Dane
Źródło: Titanic dataset (CSV)  
Pliki:
- `data/raw/titanic.csv` — dane surowe  
- `data/processed/titanic_clean.csv` — dane po podstawowym czyszczeniu  
- `notebooks/eda.ipynb` — analiza krok po kroku

## Najważniejsze wnioski
- Przeżywalność mocno zależy od płci: kobiety mają wyraźnie wyższy odsetek przeżyć niż mężczyźni.
- Klasa pasażera ma duże znaczenie: najwyższa przeżywalność jest w 1. klasie, a najniższa w 3. klasie.
- Kolumna Age ma braki danych — uzupełniono je medianą; Cabin ma bardzo dużo braków, więc została usunięta w wersji „clean”.
- Fare ma rozkład prawoskośny — w analizie warto patrzeć na medianę/percentyle.

## Wykresy
![Age distribution](reports/figures/age_distribution.png)
![Survival by sex](reports/figures/survival_by_sex.png)
![Survival by class](reports/figures/survival_by_class.png)
