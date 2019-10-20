READ ME 

1. ORGANIZACJA PLIKÓW:
Pliki zorganizowane zosta³y w nastêpuj¹cy sposób: 

“TIER Protocal Documentation” (folder g³ówny)

 - “Documents” (pod-folder  “TIER Protocal Documentation”)

	- ReadMe.txt: Bie¿¹cy dokument.

	- data-appendix.txt:  Dokumentacja u¿ywanych plików danych w tym projkcie.

 - “OriginalData” (pod-folder  “TIER Protocal Documentation”)

	- dem_score.xlsx:  Oryginalne dane Ÿród³owe.

	- “Metadata” (pod-folder “OriginalData”)

		- metadata_guide.txt : Informacje o Ÿródle, zawartoœci i formacie danych zapisanych w folderze “OriginalData”.

 
 - “CommandFiles” (pod-folder  “TIER Protocal Documentation”)

	- WorkWithData.ipynb: Notebook w którym zosta³y przeprowadzone kolejne etapy analizy danych.  

 - “AnalysisData” (pod-folder  “TIER Protocal Documentation”)
	- dem_score_final.csv: Plik z danymi po ich analizie opisanej w pliku z foderu “CommandFiles”.


---------------------------------------------------------------------
Przeprocesowanie danych w pliku WorkWithData.ipynb z folderu “CommandFiles”.

- Wczytanie danych oryginalnych (znajduj¹cych siê w folderze OriginalData\dem_score.xlsx) do formatu pandas
- Wykorzystanie funkcji melt w celu uporz¹dkowania danych opisuj¹cych lata i kraje. (id_vars =columns)
- Odpowiednie nazwanie kolumn nazwami zmiennych i naspisanie danych do dataFrame
- zapis finalnego pliku do AnalysisData\dem_score_final.csv