## Zawartość repezytorium

- [data_loader.ipynb](./data_loader.ipynb) — notebook odpowiedzialny za wczytywanie danych (CSV/JSON/API)
- [model_selector.ipynb](./model_selector.ipynb) — notebook wyboru modelu ML oraz eksportu modeli do plików `.pkl`
-  [LISTA FUNKCJA EN.txt](./LISTA%20FUNKCJA%20EN.txt) — opis funkcji systemu (wersja EN)
- [requirements.txt](./requirements.txt) — lista niezbędnych bibliotek do uruchomienia projektu

## google drive
main:https://colab.research.google.com/drive/1CgRiU9IVoPEc48LNgI_T9GsWo9hduqA4?usp=sharing

choose_source:https://colab.research.google.com/drive/1RsvYSZt4mYcYKe7DBJzypPiwNs3SK96o?usp=sharing

load_data:https://colab.research.google.com/drive/1Rl2VnYv1RJi2Erv6fj1vz8mLCVagRiB0?usp=sharing

select_columns:https://colab.research.google.com/drive/1hjoQUunzpALLPqvoUBKRSla2Y2-vdcEm?usp=sharing

detect_types:https://colab.research.google.com/drive/190cyoaw9aeY4cJ7x2w-KUSkm60S9UvJb?usp=sharing

set_date:https://colab.research.google.com/drive/1qhdOHdGQvIchXEick3mdlqnMJUBPUPVO?usp=sharing

SPHINX documentation:
https://jarekwan.github.io/praca_inzynierska/


# Zastosowanie wybranych algorytmów uczenia maszynowego w zarządzaniu łańcuchem dostaw

Repozytorium zawiera notebooki użyte w pracy inżynierskiej dotyczącej prognozowania danych czasowych w obszarze łańcucha dostaw.

## Zawartość
- `data_loader.ipynb` — wczytywanie danych (CSV/JSON/API)
- `model_selector.ipynb` — wybór modelu ML i zapis do `.pkl`
- `lista_funkcji.txt` — opis funkcji systemu
- `requirements.txt` — wymagane biblioteki

## Funkcje systemu
- wybór kolumn i typu danych,
- obsługa kolumny daty,
- czyszczenie braków danych,
- generowanie cech kalendarzowych, lagów i statystyk kroczących,
- kodowanie kategorii,
- skalowanie danych numerycznych,
- podział czasowy train/test,
- trenowanie i predykcja modeli,
- porównanie wyników (MAE, RMSE, MAPE, R²).

## Modele ML
- SVR
- Random Forest
- K-Neighbors

## Środowisko
Projekt uruchamiany w Google Colab z użyciem Google Drive (`/content/drive/MyDrive/ml_project`).

## Autor
Jarosław Wanczewski  
Nr albumu: 309470

## Promotor
dr inż. Marek Niewiński

