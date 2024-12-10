# Analiza parametrów baterii  
Projekt realizowany w ramach przedmiotu **Zaawansowana eksploracja danych** na kierunku **Informatyka** (specjalizacja: Inżynieria Oprogramowania).  

## Opis projektu  
Celem projektu jest analiza parametrów technicznych baterii na podstawie zbioru danych *batteries* udostępnionego przez prowadzącego.  
Analiza obejmuje:  
- Wstępne przetwarzanie danych  
- Eksplorację danych i wizualizację  
- Identyfikację wzorców i zależności  
- Interaktywną prezentację wyników z wykorzystaniem Shiny  

## Struktura projektu  
- `projektR.Rmd`  
  Plik źródłowy w R Markdown zawierający kod analizy i aplikacji Shiny.  
- `projektR.html`  
  Plik statyczny HTML prezentujący wyniki analizy (bez funkcjonalności interaktywnych).  
- `data/`  
  Katalog z danymi wejściowymi (*mp_batteries.csv*).  

## Wymagania  
Do uruchomienia projektu wymagane jest środowisko **RStudio** z następującymi pakietami R:  
- `DT`  
- `ggplot2`  
- `dplyr`  
- `tidyr`  
- `kableExtra`  
- `shiny`  
- `corrplot`  
- `caret`  
- `randomForest`  
- `plotly`  

**Uwaga**: Plik `projektR.html` można otworzyć w przeglądarce, aby obejrzeć wyniki analizy w formie statycznej, jednak interaktywność zapewniana przez Shiny będzie niedostępna.
Link do otwarcia formy statycznej pliku: [projektR.html](https://example.com).
