# Predykcja Raka Piersi (Breast Cancer Prediction)

Ten projekt to prosty model uczenia maszynowego służący do klasyfikacji nowotworów piersi na podstawie zbioru danych **Breast Cancer Wisconsin (Diagnostic) Data Set**. Celem jest predykcja, czy nowotwór jest złośliwy czy łagodny, z wykorzystaniem klasyfikatora maszynowego.

## 📊 Wykorzystane narzędzia

- Python
- scikit-learn
- pandas
- numpy
- matplotlib / seaborn
- Jupyter Notebook

## 📁 Zawartość repozytorium

- `Predykcja raka piersi.ipynb` – główny notebook z kodem
- `README.md` – ten plik, zawierający opis projektu

## 🔧 Jak uruchomić

1. Sklonuj repozytorium:
```
git clone https://github.com/twoj-nick/predykcja-raka-piersi.git
cd predykcja-raka-piersi
```

2. (Opcjonalnie) Stwórz i aktywuj środowisko virtualne:
```
python -m venv venv
source venv/bin/activate       # lub `venv\Scripts\activate` na Windows
```

3. Zainstaluj zależności:
```
pip install -r requirements.txt
```

4. Uruchom notebook:
```
jupyter notebook
```

## 📈 Wyniki

Model osiąga wysoką dokładność na zbiorze testowym i dobrze rozróżnia między nowotworem łagodnym a złośliwym. Do ewaluacji wykorzystano m.in. macierz pomyłek, dokładność i wykresy.

## 📚 Dane

Dane pochodzą z UCI Machine Learning Repository:  
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

## 🧠 Przyszłe usprawnienia

- Walidacja krzyżowa
- Testowanie różnych modeli klasyfikacyjnych
- Wykresy SHAP / interpretacja modelu
- GUI (np. Streamlit)

## 📜 Licencja

MIT License
