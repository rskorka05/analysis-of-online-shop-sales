Analiza danych sprzedażowych - wizualizacje, statystyki, podsumowania wg kategorii, metod płatności, województw i klientów


Projekt w Pythonie wykonany został w Jupyter Notebook, którego celem jest analiza danych sprzedażowych.  
Został przygotowany w ramach nauki analizy danych i wizualizacji w Pandas oraz Matplotlib.

Cele projektu
1. Wstępne przygotowanie i oczyszczenie danych:
   - sprawdzenie braków danych,
   - konwersja dat,
   - sortowanie po czasie.
2. Stworzenie nowych zmiennych:
   - kolumna "Całkowity_przychód",
   - sumaryczne przychody wg kategorii, metod płatności, województw i klientów.
3. Analiza i wizualizacja:
   - wykresy liniowe (przychód w czasie, sezonowość),
   - wykresy kołowe (udział metod płatności),
   - wykresy słupkowe (przychody wg kategorii, województw).
4. Interpretacja wyników:
   - sprawdzenie sezonowości sprzedaży,
   - identyfikacja najlepiej i najsłabiej sprzedających się kategorii,
   - analiza popularności metod płatności.

Struktura projektu
- "analiza_sprzedazy.ipynb" – główny notebook z kodem i analizą,
- "sales.csv" - dane sklepowe
- "README.md" – opis projektu.

Technologie:
- Python
- Pandas, Numpy
- Matplotlib
- Jupyter Notebook

Przykładowe wyniki:

Udział metod płatności – wykres kołowy  

<img width="613" height="498" alt="image" src="https://github.com/user-attachments/assets/59da984c-8784-45a3-87a5-d1837eb2f6c1" />


Przychody w czasie – wykres liniowy

<img width="847" height="518" alt="image" src="https://github.com/user-attachments/assets/40b43c42-c122-4e94-8b56-b33489c7a314" />


Przychody wg województw – wykres słupkowy  

<img width="1096" height="523" alt="image" src="https://github.com/user-attachments/assets/a81cb310-9f00-4701-834a-af2efa9a62c3" />
