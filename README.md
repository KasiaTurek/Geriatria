Projekt dotyczy analizy sytuacji związanej z opieką geriatryczną w Polsce.
Do projektu użyłam danych znajdujących się na stronie Ministerstwa Zdrowia oraz Głównego Urzędu Statystycznego.

!!! UWAGA: z racji na ograniczenia zwiazane z maksymalną wielkością plików (LFS nie pomógł) prośba dla zainteresowanych o ściągnięcie brakujących dancyh do folderu Input ze strony:
https://basiw.mz.gov.pl/mapy-informacje/mapa-2022-2026/analizy/ambulatoryjna-opieka-specjalistyczna/

W zakładce "Wstęp" na samym dole jest guzik "POBIERZ DANE"
1) pakiet plików "Problemy zdrowotne - klasyfikacja ICD-10"
2) pakiet plików "Statystyki porad"

Wszystkie pliki w projekcie muszą być odzipowane.
### Struktura plików wygląda następująco:

> project                                                                        <-- folder projektu
> 1. Input                                                                    <-- folder, w którym znajdują się dane
> 1.1. K3.G7.P2137 Ludność wg wieku i płci, 60+                               <-- folder z danymi źródłowymi
> * LUDN_2137_CREL_20240707161221.csv                                  <-- plik .csv
> 1.2. K22.G261.P1808 Szpitale z oddziałami geriatrycznymi 2018-2022          <-- folder z danymi źródłowymi
> * OCHR_1808_CREL_20240705143116.csv                                  <-- plik .csv
> 1.3. K22.G262.P2492 Szpitale i sanatoria uzdrowiskowe, wiek 65+, 2018-2022  <-- folder z danymi źródłowymi
> * OCHR_2492_CREL_20240705143736.csv                                  <-- plik .csv
> 1.4. problemy_zdrowotne_icd10                                               <-- folder z danymi źródłowymi
> * problemy_zdrowotne_icd10_2016.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2017.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2018.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2019.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2020.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2021.csv                                  <-- plik .csv
> * problemy_zdrowotne_icd10_2022.csv                                  <-- plik .csv
> 1.5. statystyki_porad                                                       <-- folder z danymi źródłowymi
> * statystyki_porad_2016.csv                                          <-- plik .csv
> * statystyki_porad_2017.csv                                          <-- plik .csv
> * statystyki_porad_2018.csv                                          <-- plik .csv
> * statystyki_porad_2019.csv                                          <-- plik .csv
> * statystyki_porad_2020.csv                                          <-- plik .csv
> * statystyki_porad_2021.csv                                          <-- plik .csv
> * statystyki_porad_2022.csv                                          <-- plik .csv
> 1.6. wojewodztwa                                                            <-- folder z plikami do map
> * wojewodztwa.cpg                                                    <-- plik .cpg
> * wojewodztwa.dbf                                                    <-- plik .dbf
> * wojewodztwa.prj                                                    <-- plik .prj
> * wojewodztwa.qmd                                                    <-- plik .qmd
> * wojewodztwa.shp                                                    <-- plik .cpg
> * wojewodztwa.shx                                                    <-- plik .shp
> 1.7. swiad_woj.csv                                                          <-- plik .shx
> 2. Output                                                                   <-- folder z wygenerowanymi mapami w fromacie .png
> 3. projekt_testowy_MZ_K.Turek.ipynb                                         <-- plik .ipynb
> 4. requirements                                                             <-- plik .txt
