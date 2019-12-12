## Zadanie 1

Plik ``excercise`` zawiera wynik y i dane wejściowe x1, x2 dla 40 punktów danych, z dalszymi 20 punktami z danymi wejściowymi, ale bez wyniku. 

- Wczytać plik do dataframe'a
- dopasować model regresji liniowej przewidujący y z x1, x2, używając pierwszych 40 punktów danych w pliku. 
- Podsumować wnioski i sprawdźić dopasowanie modelu.
- Wyświetl oszacowany model graficznie, 
- Wykonaj wykres residuów dla tego modelu. Czy wydaje się, że założenia zostały spełnione?
- Wykonaj prognozy dla pozostałych 20 punktów danych w pliku. Oceń pewność co do prognozach?

## Zadanie 2


Plik ``beauty`` zawiera dane z pracy Hamermesha i Parker (2005) na temat oceny piękna instruktorów i jakości uch nauczania dla kilku kursów na University of Texas. Oceny dydaktyczne przeprowadzono pod koniec semestru, a oceny urody dokonano później przez sześciu studentów, którzy nie uczestniczyli w zajęciach i nie byli świadomi ocen kursu.
-  Utwórz regresję przy użyciu piękna (zmienna btystdave), aby przewidzieć oceny kursu (courseevaluation), kontrolując różne inne dane wejściowe. Wyświetl dopasowany model graficznie i objaśnij znaczenie każdego ze współczynników wraz z pozostałym odchyleniem standardowym. Wykreślić residua względem dopasowanych wartości.
- Dopasuj niektóre inne modele, w tym piękno, a także inne zmienne wejściowe. Rozważ co najmniej jeden model z interakcjami. Dla każdego modelu określ, jakie są predyktory i jakie są dane wejściowe i wyjaśnij znaczenie każdego z jego współczynników.