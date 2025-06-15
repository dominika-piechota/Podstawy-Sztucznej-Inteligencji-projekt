# 📍 Wyznaczanie tras przy pomocy algorytmu genetycznego

Projekt służy do wyznaczania optymalnej trasy między wybranymi punktami w mieście na podstawie danych z OpenStreetMap, wykorzystując:

- **algorytm Dijkstry** jako punkt odniesienia umożliwiający porównanie otrzymanego wyniku do najlepszego możliwego,
- **algorytm genetyczny** jako główny algorytm projektu, który szuka najkrótszej drogi łączącej wszystkie zaznaczone przez użytkownika punkty ma mapie
  
Wizualizacja i wybór punktów odbywa się interaktywnie na mapie za pomocą `ipyleaflet`.

Dodatkowo użytkownik może modyfikować parametry algorytmu genetycznego i obserwować wpływ tych zmian na dokładność otrzymywanych tras.

---

## 💻 Najważniejsze technologie i biblioteki

- **Python 3.10+**
- `networkx` – grafy i ścieżki
- `osmnx` – dane geograficzne z OpenStreetMap
- `ipyleaflet` – interaktywna mapa do wyboru punktów
- `ipywidgets` – dynamiczna interakcja z notebookiem
- `matplotlib` – wykresy dokładności
- `folium` – wizualizacje
- `random`, `itertools` – logika permutacji i losowości

---

##🚀 Uruchomienie
- Uruchom notatnik Jupyter lub Google Colab.
- Zaimportuj bibliotekę i uruchom kod z wyborem punktów.
- Zaznacz punkty na mapie (start, meta, punkty pośrednie).
- Uruchom algorytm genetyczny.
- Porównaj wyniki z trasą Dijkstry.

---

Projekt obsługuje mapę Krakowa w promieniu 10km od Rynku Głównego, jednak można to szybko zmienić i zaznaczyć inny obszar bądź lokalizację.
