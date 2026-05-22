## Zawartość repezytorium


- [requirements.txt](./requirements.txt) — lista niezbędnych bibliotek do uruchomienia projektu

## google drive


1. choose_source:https://colab.research.google.com/drive/1RsvYSZt4mYcYKe7DBJzypPiwNs3SK96o?usp=sharing

2. load_data:https://colab.research.google.com/drive/1Rl2VnYv1RJi2Erv6fj1vz8mLCVagRiB0?usp=sharing

3. select_columns:https://colab.research.google.com/drive/1hjoQUunzpALLPqvoUBKRSla2Y2-vdcEm?usp=sharing

4. detect_types:https://colab.research.google.com/drive/190cyoaw9aeY4cJ7x2w-KUSkm60S9UvJb?usp=sharing

5. set_date:https://colab.research.google.com/drive/1qhdOHdGQvIchXEick3mdlqnMJUBPUPVO?usp=sharing

6. clean_data:https://colab.research.google.com/drive/1Ecrpnrne4FPEPmICrDA2DdXFdhc95MAF?usp=sharing

7.date_features:https://colab.research.google.com/drive/1VpSqprZPl_R18vdG-eEc9Gb91vWN8Gs8?usp=sharing

8. create_lags:https://colab.research.google.com/drive/1dLdI0QJWslERqHVul7uZYEYWYQo9Hcf2?usp=sharing

9. rolling_stats:https://colab.research.google.com/drive/1I8PT51qslGNHspt-xJuMuaT2I7CxaN8x?usp=sharing

10. encode_categories:https://colab.research.google.com/drive/1i2ZEChLOAt6prt-Ae-60AEx65epysHXn?usp=sharing

11. set_target:https://colab.research.google.com/drive/1d3JLI01nycbGmBTpAZyYxN80_J97LQDY?usp=sharing

12. scale_data: https://colab.research.google.com/drive/1e6YOOn27CR8zDEfc-7eRJd8PxdwD26w2?usp=sharing

13. split_time: https://colab.research.google.com/drive/1mEqVNvyDMUiC63AKcYHiCQD_4WCFW_nl?usp=sharing

14. create_traditional_model_ui: https://colab.research.google.com/drive/1Lz6Azw4pHr6C4sH7EumHbGZ6pQ1y1qW2?usp=sharing

15. create_ml_model_ui: https://colab.research.google.com/drive/1pyDBwZ21bWl2tzxeRvt2J8nUC027tFFA?usp=sharing

16. train_ml: https://colab.research.google.com/drive/15J6-yMZTs5qPQVHNWCcg2Tpj9BkclLnO?usp=sharing

17. predict_ml:https://colab.research.google.com/drive/1TMiUoJLzdgqOZhhhsK2ZNzWoz8UI41TP?usp=sharing

18. train_traditional:https://colab.research.google.com/drive/1SrQ19tx3_-zRPnkTZR5134Zv_vPAzGHt?usp=sharing

19. predict_traditional: https://colab.research.google.com/drive/1w-dR2n50DbOWc4uHrNmTHO55JkRAr8rO?usp=sharing

20. evaluate_model: https://colab.research.google.com/drive/1gDEXQCjs9kCEmN2XUQc452JUG0S6R-P4?usp=sharing

21. compare_all: https://colab.research.google.com/drive/1YgPDIMfMqEnKKxC8oW2b36CPC1IwtVbo?usp=sharing

22. merge_predictions: https://drive.google.com/drive/folders/1Ga-4R4Nhohw9Uz1RCH6lbA8oVmlHOxKF?usp=sharing

Last: main:https://colab.research.google.com/drive/1CgRiU9IVoPEc48LNgI_T9GsWo9hduqA4?usp=sharing

SPHINX documentation:
https://jarekwan.github.io/praca_inzynierska/


# Zastosowanie wybranych algorytmów uczenia maszynowego w zarządzaniu łańcuchem dostaw

Repozytorium zawiera notebooki użyte w pracy inżynierskiej dotyczącej prognozowania danych czasowych w obszarze łańcucha dostaw.

## Zawartość

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

## Modele tradycyjne
- Naive Forecast
- Moving Average
- Simple Exponential Smoothing (SES)
- ARIMA

## Modele uczenia maszynowego
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest
- Support Vector Regression (SVR)
- XGBoost
- MLP (Multilayer Perceptron)

## Dodatkowe funkcjonalności
- prognozowanie statyczne
- prognozowanie kroczące
- grid search
- random search
- symulacja kontroli zapasów
- analiza RMSE / MAE / MAPE / R²

## Środowisko
Projekt uruchamiany w Google Colab z użyciem Google Drive (`/content/drive/MyDrive/ml_project`).

## Autor
Jarosław Wanczewski  
Nr albumu: 309470

## Promotor
dr inż. Marek Niewiński

