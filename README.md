# Opis projektu

Projekt dotyczy analizy danych o nieruchomościach w Chicago, zebranych za pomocą techniki web scrapingu z serwisu Redfin. 
Projekt obejmuje następujące etapy: czyszczenie danych, analiza, modelowanie oraz wizualizacja wyników. 
W projekcie zastosowano modele regresji liniowej i lasu losowego do przewidywania cen nieruchomości.

### Struktura projektu

```/project-directory
    |- sample.ipynb          # Główny plik projektu w formacie Jupyter Notebook
    |- redfin_data_chrome.csv # Surowe dane pobrane poprzez web scraping
    |- redfin_cleaned_data.csv # Dane oczyszczone i przygotowane do analizy
    |- README.md             # Dokumentacja projektu
```

### Wymagania

- Python 3.8+

### Biblioteki:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- selenium

### Kroki uruchomienia

1. Zainstaluj wymagane biblioteki:

`pip install pandas numpy matplotlib seaborn scikit-learn streamlit selenium`

2. Uruchom projekt w Jupyter Notebooku:

`jupyter notebook sample.ipynb`
