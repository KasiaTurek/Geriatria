Projekt dotyczy analizy sytuacji związanej z opieką geriatryczną w Polsce.
Do projektu użyłam danych znajdujących się na stronie Ministerstwa Zdrowia oraz Głównego Urzędu Statystycznego.

!!! UWAGA: z racji na ograniczenia zwiazane z maksymalną wielkością plików (LFS nie pomógł) prośba dla zainteresowanych o ściągnięcie brakujących dancyh do folderu Input ze strony:
https://basiw.mz.gov.pl/mapy-informacje/mapa-2022-2026/analizy/ambulatoryjna-opieka-specjalistyczna/

W zakładce "Wstęp" na samym dole jest guzik "POBIERZ DANE"
1) pakiet plików "Problemy zdrowotne - klasyfikacja ICD-10"
2) pakiet plików "Statystyki porad"

Wszystkie pliki w projekcie muszą być odzipowane.
### Struktura plików wygląda następująco:

> * project                                                                        <-- folder projektu
> * |____ Input                                                                    <-- folder, w którym znajdują się dane
> * |   |__ K3.G7.P2137 Ludność wg wieku i płci, 60+                               <-- folder z danymi źródłowymi
> |       |__ LUDN_2137_CREL_20240707161221.csv                                  <-- plik .csv
> |   |__ K22.G261.P1808 Szpitale z oddziałami geriatrycznymi 2018-2022          <-- folder z danymi źródłowymi
> |       |__ OCHR_1808_CREL_20240705143116.csv                                  <-- plik .csv
> |   |__ K22.G262.P2492 Szpitale i sanatoria uzdrowiskowe, wiek 65+, 2018-2022  <-- folder z danymi źródłowymi
> |       |__ OCHR_2492_CREL_20240705143736.csv                                  <-- plik .csv
> |   |__ problemy_zdrowotne_icd10                                               <-- folder z danymi źródłowymi
> |       |__ problemy_zdrowotne_icd10_2016.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2017.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2018.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2019.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2020.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2021.csv                                  <-- plik .csv
> |       |__ problemy_zdrowotne_icd10_2022.csv                                  <-- plik .csv
> |   |__ statystyki_porad                                                       <-- folder z danymi źródłowymi
> |       |__ statystyki_porad_2016.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2017.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2018.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2019.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2020.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2021.csv                                          <-- plik .csv
> |       |__ statystyki_porad_2022.csv                                          <-- plik .csv
> |   |__ wojewodztwa                                                            <-- folder z plikami do map
> |       |__ wojewodztwa.cpg                                                    <-- plik .cpg
> |       |__ wojewodztwa.dbf                                                    <-- plik .dbf
> |       |__ wojewodztwa.prj                                                    <-- plik .prj
> |       |__ wojewodztwa.qmd                                                    <-- plik .qmd
> |       |__ wojewodztwa.shp                                                    <-- plik .cpg
> |       |__ wojewodztwa.shx                                                    <-- plik .shp
> |   |__ swiad_woj.csv                                                          <-- plik .shx
> |
> |____ Output                                                                   <-- folder z wygenerowanymi mapami w fromacie .png
> |
> |____ projekt_testowy_MZ_K.Turek.ipynb                                         <-- plik .ipynb
> |
> |____ requirements                                                             <-- plik .txt
