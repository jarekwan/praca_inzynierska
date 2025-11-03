# Zastosowanie wybranych algorytmów uczenia maszynowego w zarządzaniu łańcuchem dostaw

Repozytorium zawiera kod oraz notebooki wykorzystane podczas realizacji pracy dyplomowej inżynierskiej dotyczącej zastosowania metod uczenia maszynowego do prognozowania 
oraz analizy danych czasowych w obszarze zarządzania łańcuchem dostaw.

Praca wykonywana na kierunku Elektronika i Telekomunikacja, specjalność Inżynieria Komputerowa.

## Cele projektu
- budowa modularnego systemu do przygotowania danych,
- generowanie cech czasowych ułatwiających modelom analizę sezonowości,
- testowanie wybranych algorytmów ML do prognozowania wartości,
- ocena jakości predykcji na danych testowych,
- możliwość porównania wielu modeli w jednakowych warunkach.

## Zakres funkcjonalny (skrót)
Projekt umożliwia:
- wczytywanie danych z pliku CSV, JSON oraz API,
- wybór i filtrowanie kolumn,
- wykrywanie typów danych (numeryczne, kategoryczne, daty),
- konwersję i obsługę kolumny daty, sortowanie, uzupełnianie luk,
- czyszczenie braków danych (usuwanie, wartości domyślne, średnie, ffill),
- tworzenie cech kalendarzowych (rok/miesiąc/dzień/dzień tygodnia),
- generowanie lagów i statystyk kroczących,
- kodowanie zmiennych kategorycznych,
- wybór zmiennej celu i cech,
- skalowanie danych numerycznych,
- podział danych w sposób chronologiczny (time-based split),
- trenowanie modeli ML i tradycyjnych,
- predykcję wartości na zbiorze testowym,
- ocenę jakości predykcji za pomocą metryk:
  - MAE
  - RMSE
  - MAPE
  - R²
- porównanie wyników wielu modeli.

## Modele wykorzystywane w projekcie
- SVR (Support Vector Regression)
- Random Forest Regressor
- K-Neighbors Regressor

Dodatkowo przewidziano obsługę modeli tradycyjnych (np. ARIMA, Holt-Winters).

## Notebooki w repozytorium
- `data_loader.ipynb`  
  Interaktywny moduł wczytywania danych z plików lub API, z obsługą uploadu.
- `model_selector.ipynb`  
  Wybór modelu ML i zapis konfiguracji do pliku `.pkl`.
- `lista_funkcji.txt`  
  Specyfikacja architektury modułów systemu.
- `requirements.txt`  
  Lista wymaganych bibliotek.

## Środowisko uruchomieniowe
Projekt jest uruchamiany w Google Colab i wykorzystuje Google Drive do przechowywania:
- datasetów,
- wytrenowanych modeli,
- konfiguracji.

Ścieżka zapisu:
