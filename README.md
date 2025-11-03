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

