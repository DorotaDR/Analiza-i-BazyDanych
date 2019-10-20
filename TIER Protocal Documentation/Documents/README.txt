READ ME 

1. ORGANIZACJA PLIK�W:
Pliki zorganizowane zosta�y w nast�puj�cy spos�b: 

�TIER Protocal Documentation� (folder g��wny)

 - �Documents� (pod-folder  �TIER Protocal Documentation�)

	- ReadMe.txt: Bie��cy dokument.

	- data-appendix.txt:  Dokumentacja u�ywanych plik�w danych w tym projkcie.

 - �OriginalData� (pod-folder  �TIER Protocal Documentation�)

	- dem_score.xlsx:  Oryginalne dane �r�d�owe.

	- �Metadata� (pod-folder �OriginalData�)

		- metadata_guide.txt : Informacje o �r�dle, zawarto�ci i formacie danych zapisanych w folderze �OriginalData�.

 
 - �CommandFiles� (pod-folder  �TIER Protocal Documentation�)

	- WorkWithData.ipynb: Notebook w kt�rym zosta�y przeprowadzone kolejne etapy analizy danych.  

 - �AnalysisData� (pod-folder  �TIER Protocal Documentation�)
	- dem_score_final.csv: Plik z danymi po ich analizie opisanej w pliku z foderu �CommandFiles�.


---------------------------------------------------------------------
Przeprocesowanie danych w pliku WorkWithData.ipynb z folderu �CommandFiles�.

- Wczytanie danych oryginalnych (znajduj�cych si� w folderze OriginalData\dem_score.xlsx) do formatu pandas
- Wykorzystanie funkcji melt w celu uporz�dkowania danych opisuj�cych lata i kraje. (id_vars =columns)
- Odpowiednie nazwanie kolumn nazwami zmiennych i naspisanie danych do dataFrame
- zapis finalnego pliku do AnalysisData\dem_score_final.csv