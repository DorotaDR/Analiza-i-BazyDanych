# READ ME 

## 1. ORGANIZACJA PLIKÓW:
Pliki zorganizowane zostały w następujący sposób: 

“TIER Protocal Documentation” (folder główny)

 - “Documents” (pod-folder  “TIER Protocal Documentation”)

	- ReadMe.txt: Bieżący dokument.

	- data-appendix.txt:  Dokumentacja używanych plików danych w tym projkcie.

 - “OriginalData” (pod-folder  “TIER Protocal Documentation”)

	- dem_score.xlsx:  Oryginalne dane źródłowe.

	- “Metadata” (pod-folder “OriginalData”)

		- metadata_guide.txt : Informacje o źródle, zawartości i formacie danych zapisanych w folderze “OriginalData”.

 
 - “CommandFiles” (pod-folder  “TIER Protocal Documentation”)

	- WorkWithData.ipynb: Notebook w którym zostały przeprowadzone kolejne etapy analizy danych.  

 - “AnalysisData” (pod-folder  “TIER Protocal Documentation”)
	- dem_score_final.csv: Plik z danymi po ich analizie opisanej w pliku z foderu “CommandFiles”.


---------------------------------------------------------------------
## Przeprocesowanie danych w pliku WorkWithData.ipynb z folderu “CommandFiles”.

- Wczytanie danych oryginalnych (znajdujących się w folderze OriginalData\dem_score.xlsx) do formatu pandas
- Wykorzystanie funkcji melt w celu uporządkowania danych opisujących lata i kraje. (id_vars =columns)
- Odpowiednie nazwanie kolumn nazwami zmiennych i naspisanie danych do dataFrame
- zapis finalnego pliku do AnalysisData\dem_score_final.csv
