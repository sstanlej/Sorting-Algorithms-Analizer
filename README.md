Autor: Stanisław Liszewski

# Sorting Algorithms Analizer

Program konsolowy porównujący czasy działania 5 różnych algorytmów sortowania.
Program wczytuje dane wejściowe (słowa) z pliku tekstowego, sortuje je fragmentami o rosnącej wielkości i wizualizuje czas pracy każdego algorytmu.

Program testuje następujące metody sortowania:
- Bubble Sort (Sortowanie bąbelkowe) – złożoność O(n^2).
- Selection Sort (Sortowanie przez wybieranie) – złożoność O(n^2)
- Insertion Sort (Sortowanie przez wstawianie) – złożoność O(n^2)
- Quick Sort (Sortowanie szybkie) – złożoność średnia O(n * log n)
- Merge Sort (Sortowanie przez scalanie) – złożoność O(n * log n).

Program uruchamia się z linii komend, podając ścieżkę do pliku tekstowego z danymi:
> python main.py sciezka/do/pliku.txt
