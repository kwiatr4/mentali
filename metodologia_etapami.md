# MentaliCare — metodologia badania według etapów

**Jednolity opis badań i analiz | Wersja robocza 1.1 | 7 września 2026 r.**

**Cel projektu:** opracowanie i walidacja systemu, który na podstawie danych ze smartfona i opaski opisuje wielowymiarowy profil uczestnika: nasilenie objawów depresyjnych, dobrostan, codzienne funkcjonowanie oraz bieżące samooceny. Główną miarą objawów jest PHQ-9, a pozostałe wymiary są analizowane jako odrębne wyniki.

Dokument przedstawia jeden połączony protokół badania: pomiary, kontrolę jakości, opracowanie modelu, niezależną walidację i ocenę użyteczności. Każdy etap opisano według tych samych ośmiu punktów.

## Plan w jednym widoku

Badania uczestników rozpoczynają się od pilotażu noszenia opaski i zbierania danych ze smartfona. Konsultacje potrzeb ze specjalistami są pracą przygotowawczą, poprzedzającą pilotaż. Modelowanie i niezależną walidację opisano oddzielnie. Opaska oraz prognozowanie to podbadania prowadzone na tych samych kohortach.

| Karta | Zakres | Czas udziału / analizy | N planowane | Okno projektu |
|---|---|---|---|---|
| 1 | Pilotaż noszenia opaski, kalibracji i jakości danych | 4–6 tygodni/osobę; cały etap około 2 miesięcy | 40 badanych ze smartfonem i opaską | M4–M5 |
| 2 | Zbieranie danych rozwojowych | 16 tygodni/osobę; cały etap około 6 miesięcy | 240 nowych badanych | M6–M11 |
| 3A | Opracowanie modelu | Około 4 miesięcy analizy | Dane tych samych 240 osób | M9–M12 |
| 3B | Niezależna walidacja | 16 tygodni/osobę | 120 nowych uczestników | M14–M20 |
| 4 | Użyteczność panelu | Dodatkowe 8 tygodni/osobę; 24 tygodnie łącznie | Kontynuujący z kohorty 120 osób; ≥15 specjalistów, cel 30–40 | M21–M24 |
| P1 | Wartość dodatkowa opaski | W ramach obserwacji 16-tygodniowych | Dane 240 + 120 osób; wszyscy noszą opaskę | Pomiary M6–M20; analiza do M21 |
| P2 | Eksploracyjna analiza prognozowania pogorszenia | Dane z 16-tygodniowych obserwacji; horyzont do 14 dni | Dane 240 + 120 osób; dodatkowo liczba epizodów | Opracowanie M9–M13; ocena M21–M24 |

**Cały projekt: roboczo 24 miesiące.** M1–M4 obejmują przygotowanie prototypu i procedur oraz konsultacje z co najmniej 10 specjalistami. Konsultacje nie zastępują badania pilotażowego i nie wyznaczają jego N. M22–M24 obejmują również raportowanie i przygotowanie wyników do upowszechnienia. Miesiące są propozycją organizacyjną. Okna obejmują rekrutację; obserwacja ostatniej osoby musi zakończyć się przed zamknięciem odpowiedniej kohorty.

**N oznacza liczbę osób objętych badaniem i pomiarami.** Przed badaniem podaje się N planowane, a po zakończeniu osobno liczbę osób włączonych, przebadanych i uwzględnionych w analizie. Liczba urządzeń, rekordów, wywiadów ani członków zespołu nie jest N uczestników. Czas badania oznacza okres obserwacji uczestnika oraz czas realizacji całego etapu, nie długość pojedynczego wywiadu lub kwestionariusza.

**Łączna rekrutacja uczestników: 40 + 240 + 120 = 400 unikalnych osób.** Analiza modelu, opaska, prognozowanie i panel nie tworzą dodatkowych kohort. Uczestnik walidacji i panelu ma łącznie 24 tygodnie aktywnej obserwacji: 16 tygodni walidacji i 8 tygodni fazy użytkowej. Ewentualna przerwa między tymi częściami wydłuża czas kalendarzowy i jest raportowana osobno. Specjalistów liczy się oddzielnie, z uwzględnieniem ich udziału w kilku etapach.

Wszystkie N i progi są **założeniami do planowania**. Nie przeprowadzono jeszcze obliczenia wymaganej liczebności. Przy ubytku 20–25% przewiduje się 180–192 analizowalne osoby w kohorcie rozwojowej i 90–96 w walidacyjnej.

## Wspólne definicje i pomiary

Populacja: osoby w wieku 18–65 lat korzystające z ambulatoryjnej pomocy psychologicznej lub psychoterapii, o różnym nasileniu objawów depresyjnych. Wymagane są świadoma zgoda, możliwość realizacji pomiarów i kompatybilny smartfon. Objawy mierzone PHQ-9 nie są utożsamiane z niezależnie potwierdzonym rozpoznaniem depresji.

| Zmienna / symbol | Skrócona operacjonalizacja | Harmonogram w kohorcie 16-tygodniowej |
|---|---|---|
| Y — nasilenie objawów | Wynik PHQ-9 zgodnie z instrukcją; więcej punktów oznacza większe nasilenie objawów | Dzień 0 i tygodnie 2, 4, 6, 8, 10, 12, 14, 16 |
| ΔY — zmiana objawów | Bieżący PHQ-9 minus poprzedni PHQ-9; wartość dodatnia oznacza pogorszenie | Co 2 tygodnie |
| Dobrostan | WHO-5, osobny wynik; więcej punktów oznacza lepszy dobrostan | Równolegle z PHQ-9 |
| Funkcjonowanie | WHODAS 2.0, 12 pozycji, zgodnie z ustalonym sposobem punktacji | Dzień 0 i tygodnie 4, 8, 12, 16 |
| EMA — krótka samoocena | Nastrój, energia i funkcjonowanie; proponowane osobne skale 0–10 z opisanymi końcami | 3 razy w tygodniu |
| Kotwica zmiany | Ocena pacjenta od −3 do +3: −2/−3 wyraźne pogorszenie, +2/+3 poprawa | Od tygodnia 2, co 2 tygodnie |
| Ocena specjalisty | Stan wyjściowy i późniejsza ocena zmiany, bez wglądu w wynik cyfrowy w walidacji | Dzień 0 i tygodnie 4, 8, 12, 16 |
| Kontekst | Zdarzenia: zmiana leku, choroba, podróż, praca zmianowa, zmiana terapii lub telefonu | Po zdarzeniu, sprawdzenie co tydzień |

PHQ-9 i WHO-5 dotyczą poprzednich dwóch tygodni, a WHODAS poprzednich 30 dni. Zachowuje się te okna odniesienia. Dla punktu WHODAS w tygodniu 4 nie ma jeszcze pełnych 30 dni sensorów — tę niekompletność trzeba oznaczyć. [PHQ-9 — badanie walidacyjne](https://pmc.ncbi.nlm.nih.gov/articles/PMC1495268/), [WHO-5 — formularz WHO](https://cdn.who.int/media/docs/default-source/mental-health/five-well-being-index-%28who-5%29/who-5_english-original.pdf?sfvrsn=6f711f78_3), [WHODAS — podręcznik WHO](https://iris.who.int/bitstream/handle/10665/43974/9789241547598_eng.pdf)

| Zmienna cyfrowa X | Przykładowe mierzalne cechy | Czujnik / narzędzie pomiarowe |
|---|---|---|
| Głos | Tempo, długość pauz, zmienność cech akustycznych | Proponowana świadoma próbka 30–60 s, 3 razy w tygodniu |
| Aktywność i ruch | Przyspieszenie w trzech osiach, intensywność ruchu, okresy bezruchu, kroki | Akcelerometr telefonu i akcelerometr opaski; kroki z algorytmu urządzenia lub aplikacji |
| Mobilność | Promień przemieszczania, regularność tras i zmian lokalizacji | Dane GPS przekształcane w cechy przestrzenne |
| Używanie telefonu | Liczba sesji i odblokowań, czas używania, rozkład dobowy | Dostępne metadane systemowe |
| Dynamika pisania | Odstępy między interakcjami, pauzy, częstość korekt | Metadane bez wpisywanego tekstu |
| Sen i rytm dnia | Nocna nieaktywność telefonu, regularność jej początku i końca | Przybliżenia oparte na zachowaniu telefonu |
| Komunikacja | Liczba i dobowy rytm dostępnych zdarzeń komunikacyjnych | Metadane bez treści i identyfikowania rozmówców |
| Tętno / puls | Częstość pulsu i jej zmienność w ciągu dnia | Optyczny czujnik PPG opaski |
| Zmienność odstępów między uderzeniami | Np. RMSSD w ms, gdy dostępne są odstępy i wiarygodne reguły odrzucania artefaktów | PPG opaski; pomiar pulsowy opisywany jako PRV, z oceną możliwości wykorzystania jako przybliżenia HRV |
| EDA — aktywność elektrodermalna | Przewodnictwo skóry, poziom SCL w µS; liczba i amplituda reakcji SCR po ustaleniu algorytmu | Czujnik EDA i elektrody opaski obsługującej ten pomiar |
| Temperatura skóry | Poziom i zmiany temperatury przy skórze, w °C | Czujnik temperatury opaski, jeśli dostępny |
| Sen z opaski | Szacowany czas snu, pory snu i regularność | Algorytm opaski korzystający z dostępnych sensorów; osobno od przybliżenia snu z telefonu |

Sześć domen smartfonowych to: **głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja**. W obecnej wersji zakres pomiarów rozszerzono o akcelerometrię i wymienione sygnały opaski. Opaska musi obsługiwać dany czujnik i udostępniać dane o wystarczającej jakości. Dokumentacja urządzeń badawczych pokazuje dostęp do PPG, EDA, akcelerometru i temperatury, ale nie oznacza to dostępności tych pomiarów w dowolnej opasce. [Przykład dokumentacji surowych sygnałów](https://www.empatica.com/rawdata/), [Opis danych EDA](https://www.empatica.com/blog/decoding-wearable-sensor-signals-what-to-expect-from-your-e4-data)

rPPG, czyli zdalny pomiar pulsu kamerą telefonu, pozostaje opcjonalne. Próbki głosu i ewentualne rPPG są aktywnymi zadaniami, dlatego system jest w większości pasywny. EMA 0–10 i harmonogram próbek głosu są propozycjami wykonawczymi syntezy. Częstotliwość próbkowania, jednostki i kryteria jakości każdego czujnika zapisuje się po wyborze sprzętu i przed pilotażem.

**Modele porównawcze:** B0 = poprzedni PHQ-9; B1 = poprzedni PHQ-9 + ustalone dane demograficzne i kontekst; M1 = B1 + cechy populacyjne; M2 = B1 + odchylenia od osobistego profilu; M3 = B1 + oba typy cech. Dodatkowo oceniany jest wariant oparty wyłącznie na danych cyfrowych. B1 jest głównym punktem odniesienia dla wartości dodatkowej sensorów.

**Wskaźniki:** MAE = średni bezwzględny błąd w punktach PHQ-9, najpierw liczony na osobę; r = korelacja, z rozróżnieniem zmienności wewnątrz osób i między nimi; ICC = współczynnik rzetelności; SUS = wynik kwestionariusza użyteczności 0–100. Redukcja MAE [%] = 100 × (MAE modelu odniesienia − MAE modelu badanego) / MAE modelu odniesienia. Przy zerowym błędzie odniesienia raportuje się różnicę bezwzględną zamiast ilorazu.

## Etap 1 — pilotaż noszenia opaski, kalibracji i jakości danych

**Cel: sprawdzić, czy uczestnicy noszą opaskę, czy telefon i opaska zbierają użyteczne dane oraz czy można ustalić reguły pomiaru i indywidualny poziom odniesienia.**

### 1. Czas badania

**4–6 tygodni noszenia opaski i monitorowania telefonem na osobę; cały etap około 2 miesięcy, M4–M5.** W pierwszych 14 dniach wyznacza się wstępny profil zachowania i sprawdza ustawienia pomiaru. W kolejnych tygodniach ocenia się ciągłość noszenia, kompletność i stabilność działania. Prototyp i procedury muszą być gotowe przed włączeniem pierwszej osoby.

### 2. Zmienne

| Co badamy | Zmienne i cechy | Narzędzie / źródło danych |
|---|---|---|
| Noszenie opaski | Godziny noszenia, zdejmowanie, przerwy na ładowanie | Dostępna detekcja kontaktu ze skórą, status urządzenia i dzienniczek przerw |
| Ruch i aktywność | Przyspieszenie X/Y/Z, intensywność, bezruch, liczba kroków | Akcelerometr telefonu i opaski |
| EDA | Poziom przewodnictwa skóry i jego zmienność; reakcje po odrzuceniu artefaktów | Czujnik EDA opaski, jeśli obsługiwany |
| Puls i jego zmienność | Częstość pulsu, odstępy między uderzeniami i np. RMSSD | PPG opaski; analiza PRV, ocena przydatności do przybliżania HRV |
| Temperatura skóry | Poziom i zmiany temperatury | Czujnik temperatury opaski, jeśli dostępny |
| Pisanie | Tempo, odstępy, pauzy, korekty | Metadane interakcji z klawiaturą, bez tekstu |
| Mobilność i używanie telefonu | Przemieszczanie, sesje, czas ekranu, odblokowania i rytm komunikacji | GPS i dostępne metadane telefonu |
| Sen i rytm dnia | Regularność nocnej nieaktywności; osobno szacowany sen z opaski | Metadane telefonu i algorytm opaski |
| Głos | Tempo mowy i pauzy | Mikrofon telefonu, świadomie uruchamiana próbka |
| Objawy i funkcjonowanie | PHQ-9, dobrostan, funkcjonowanie i krótka samoocena | PHQ-9, WHO-5, WHODAS 2.0, EMA i kotwica zmiany |
| Jakość rejestracji | Braki, artefakty, zgodność czasu, przesłanie danych i awarie | Logi aplikacji, opaski i serwera |

PHQ-9 i WHO-5: dzień 0, tygodnie 2 i 4, a przy sześciu tygodniach także tydzień 6. WHODAS: dzień 0 i tydzień 4. EMA i próbka głosu: 3 razy w tygodniu. Akcelerometr, GPS i sensory opaski: rejestracja według protokołu urządzenia przez cały okres, z jawnym zapisem przerw i częstotliwości próbkowania.

### 3. N

**N planowane = 40 badanych osób.** Każda osoba w tej wersji pilotażu korzysta ze smartfona i otrzymuje opaskę. Dobór uwzględnia różne telefony i nasilenie objawów. Po zakończeniu raportuje się faktyczne N przebadanych i N analizowalnych. Udział wszystkich 40 osób w pomiarze z opaską jest propozycją wykonawczą tej wersji; kohorta pozostaje osobna od danych walidacyjnych.

### 4. Hipotezy

- **H-P1 — noszenie:** co najmniej 80% badanych realizuje co najmniej 80% zaplanowanego czasu noszenia opaski.
- **H-P2 — rejestracja:** telefon i opaska, oceniane oddzielnie, dostarczają co najmniej 80% ważnych dni pomiarowych u co najmniej 80% badanych.
- **H-P3 — kalibracja techniczna:** po konfiguracji system poprawnie rejestruje zaplanowane próby ruchu, pisania i głosu oraz synchronizuje czas pomiarów; co najmniej 80% badanych przechodzi cały ustalony zestaw prób.
- **H-P4 — kalibracja indywidualna:** u co najmniej 80% badanych można wyznaczyć wstępny profil z pierwszych 14 dni oraz ocenić jego stabilność w kolejnym okresie referencyjnie stabilnym.

Progi są założeniami pilotażowymi. Rozszerzenie reguły 80% na noszenie, próby techniczne i dostępność profilu jest doprecyzowaniem tej wersji; nie stanowi wyniku badania.

### 5. Metoda

Prospektywne badanie pilotażowe z równoległym zbieraniem sygnałów ze smartfona i opaski oraz samoocen uczestnika. Na początku wykonuje się konfigurację i ustalone próby: spoczynek, chód, zadanie pisania oraz próbkę głosu. Dziennik prób pozwala sprawdzić, czy zdarzenie zostało zapisane i czy znaczniki czasu się zgadzają. Próby techniczne powtarza się po usunięciu awarii i pod koniec pilotażu.

**Kalibracja techniczna** oznacza konfigurację, kontrolę synchronizacji, kontaktu czujnika i jakości zapisu, z tolerancjami ustalonymi przed pilotażem. Gdy ma być oceniana bezwzględna dokładność pulsu, EDA lub przyspieszenia, potrzebny jest odpowiedni pomiar lub wzorzec referencyjny; porównanie telefonu z opaską i sam fakt obecności sygnału tego nie dowodzą. **Kalibracja indywidualna** oznacza ustalenie profilu zachowania z pierwszych 14 dni, sprawdzenie jakości danych i stabilności na podstawie niezależnych samoocen.

Przez cały pilotaż oddzielnie analizuje się noszenie urządzenia, pracę sensorów, przesyłanie danych i wykonanie kwestionariuszy. Niski sygnał EDA lub brak ruchu sam w sobie nie oznacza zdjęcia opaski. Ustalone reguły jakości i braków oraz oszacowana zmienność pomiarów służą przygotowaniu badania głównego.

### 6. Wskaźniki

| Wskaźnik | Jak go liczymy | Proponowany cel |
|---|---|---|
| Realizacja noszenia opaski | Godziny potwierdzonego noszenia / zaplanowane godziny noszenia | ≥80% czasu u ≥80% włączonych osób |
| Ważne dni telefonu | Dni spełniające ustalone kryteria czujników i metadanych / wszystkie planowane dni | ≥80% dni u ≥80% osób |
| Ważne dni opaski | Dni spełniające kryteria noszenia i jakości wybranych sygnałów / wszystkie planowane dni | ≥80% dni u ≥80% osób |
| Jakość każdego sensora | Czas sygnału spełniającego kryteria jakości / planowany czas pomiaru; osobno akcelerometr, PPG, EDA i inne aktywne czujniki | Raport dla każdego sensora; minimalny użyteczny zakres ustalony przed oceną |
| Utrata w transmisji | Rekordy zapisane przez urządzenie, ale niedostarczone do bazy / zapisane rekordy, jeśli licznik źródłowy jest dostępny | Wykrycie i wyjaśnienie źródeł strat |
| Zaliczenie prób technicznych | Odsetek osób z poprawnym zapisem całego zdefiniowanego zestawu prób | ≥80% osób |
| Możliwość kalibracji indywidualnej | Osoby z wyznaczonym profilem i ocenioną stabilnością / wszystkie włączone osoby | ≥80% osób |
| Wykonanie samoocen | Wykonane / zaplanowane pomiary, osobno PHQ-9, WHO-5, WHODAS i EMA | Roboczo ≥80% pomiarów u ≥80% osób |

Zaplanowany czas noszenia ustala się przed startem, uwzględniając zgodne z instrukcją przerwy na ładowanie i higienę; rzeczywiste przerwy raportuje się osobno. Mianowników nie zmniejsza się po fakcie, aby poprawić wynik. Jeśli czasu noszenia nie da się wiarygodnie odtworzyć, oznacza się go jako nieustalony. Wynik pilotażu to decyzja o gotowości pomiarów, poprawkach sprzętu i aplikacji oraz regułach badania głównego.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Skrócona operacjonalizacja |
|---|---|
| Noszenie opaski | Minuty kontaktu ze skórą potwierdzone dostępnymi sygnałami i logami; osobno przerwy oraz nieustalony status |
| Ruch | Przyspieszenie X/Y/Z w jednostkach urządzenia, ujednolicone przed analizą; cechy ruchu z akcelerometru telefonu i opaski liczone osobno |
| EDA | SCL w µS i cechy reakcji po oznaczeniu artefaktów; brak czujnika oznacza brak pomiaru EDA |
| Pisanie | Odstępy między interakcjami w ms, pauzy i odsetek korekt, bez treści |
| Puls i zmienność | Puls na minutę i odstępy między pulsami; wskaźniki zmienności tylko w oknach spełniających kryteria jakości |
| Objawy depresyjne | PHQ-9 według instrukcji i zmiana względem poprzedniego pomiaru |
| Kalibracja indywidualna | Profil cech z pierwszych 14 dni; ocena stabilności z użyciem niezależnych samoocen |
| Poprawny zapis | Zgodność sygnału, czasu i kompletności z uprzednio określonym kryterium; osobno każdy czujnik |

### 8. Uzasadnienie założeń etapu

Etap łączy pomiar objawów PHQ-9, sześć domen smartfonowych (głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja), indywidualne profile, pilotaż N=40, obserwację 4–6 tygodni, sprawdzenie wykonalności, jakości, braków i poziomu odniesienia. Dodatkowo obejmuje opaskę u wszystkich 40 osób, pomiary akcelerometru i EDA, oddzielenie noszenia od jakości danych oraz zestaw prób kalibracyjnych.

## Etap 2 — zbieranie danych do opracowania modelu

**Cel: utworzyć zbiór danych ze smartfona i opaski sparowanych z niezależnymi pomiarami objawów.**

### 1. Czas badania

16 tygodni na osobę, M6–M11. Pierwsze 14 dni służy wyznaczeniu wstępnego profilu zachowania. Obserwacja ostatniej osoby musi zakończyć się przed ostatecznym wyborem modelu.

### 2. Zmienne

Wynik główny Y=PHQ-9; dodatkowo ΔY, WHO-5, WHODAS, EMA i kotwica zmiany. Predyktory: ruch z akcelerometru telefonu, tempo i pauzy pisania, GPS, używanie telefonu, komunikacja, głos i przybliżenie snu. W ramieniu opaski: akcelerometr, PPG i zmienność pulsu, EDA, temperatura skóry i szacowany sen, w zakresie potwierdzonym w pilotażu. Narzędzia i cechy podano we wspólnych tabelach. Rejestrowane są również osobisty poziom odniesienia i zdarzenia kontekstowe.

### 3. N

240 nowych uczestników; przy założonym ubytku 20–25% około 180–192 analizowalne osoby. Wszyscy uczestnicy korzystają ze smartfona i noszą opaskę. Model smartfonowy używa wyłącznie cech ze smartfona, a model rozszerzony dodatkowo cech z opaski.

### 4. Hipotezy

H-D1: zmiany cech cyfrowych wiążą się ze zmianami PHQ-9 w tej samej osobie. H-D2: kierunek i siła tych zależności różnią się między osobami. Ocena ma charakter rozwojowy; potwierdzenie następuje w etapie 3B.

### 5. Metoda

Prospektywna obserwacja z powtarzanymi pomiarami, według wspólnego harmonogramu. Terapeuta i uczestnik nie widzą interpretacji wyniku cyfrowego. Smartfon zbiera dane pasywne, uczestnik wykonuje próbki głosu i samooceny, a wszyscy uczestnicy noszą opaskę. Każdy rekord ma czas, identyfikator badawczy, źródło, wersję przetwarzania i jakość.

### 6. Wskaźniki

Rekrutacja 240 osób, retencja do tygodnia 12, liczba sparowanych pomiarów i dostępność domen. Cel techniczny: ≥80% ważnych dni u ≥80% wszystkich włączonych osób. Rezultat: opisany zbiór rozwojowy; zależności wykryte w nim nie są raportowane jako niezależna walidacja.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Para danych | Wynik PHQ-9 oraz cechy cyfrowe z poprzedzających go 14 dni |
| Profil osobisty | Podsumowanie pierwszych 14 dni, ze sprawdzeniem ich stabilności |
| Odchylenie od profilu | Różnica lub standaryzowane odchylenie bieżącej cechy od poziomu osobistego |
| Kontekst | Zdarzenie z datą, pozwalające powiązać je z okresem pomiaru |

### 8. Uzasadnienie założeń etapu

Etap obejmuje PHQ-9, wielowymiarowy profil uczestnika, obserwację przez 16 tygodni, kohortę 240 osób, sześć domen smartfonowych (głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja), dane z opaski, dodatkowe skale, brak dostępu do panelu i rejestrację zdarzeń kontekstowych.

## Etap 3A — opracowanie i wybór modelu

**Pierwsza część fazy 3. Cel: wybrać algorytm i zamrozić go przed niezależną walidacją.**

### 1. Czas badania

M9–M12, około 4 miesięcy pracy analitycznej. Wczesne analizy mogą nakładać się na końcówkę akwizycji. Model jest zamrażany dopiero po zamknięciu zbioru rozwojowego.

### 2. Zmienne

Zmienne wyjaśniane: PHQ-9 i osobno jego zmiana. Predyktory: dane cyfrowe i informacje dostępne w chwili oszacowania. Porównywane czynniki analityczne: personalizacja, liczba domen, cechy czasowe, rodzina modelu i sposób obsługi braków.

### 3. N

Te same 240 osób z etapu 2B, bez nowej rekrutacji. Rzeczywiste N analityczne zależy od z góry określonej jakości. Powtarzane rekordy nie są liczone jako niezależni uczestnicy.

### 4. Hipotezy

H-M1: model multimodalny ma mniejszy MAE niż B1 i najlepszy model jednodomenowy. H-M2: personalizacja poprawia pomiar względem modelu populacyjnego. H-M3: informacja czasowa poprawia wynik względem samych podsumowań statystycznych.

### 5. Metoda

Porównanie B0, B1, M1, M2 i M3 oraz wariantu wyłącznie cyfrowego. Modele regularyzowane i drzewa wzmacniane; model szeregów czasowych jako dodatkowy kandydat. Walidacja wewnętrzna rozdziela osoby, a dobór parametrów odbywa się wewnątrz części uczącej. Każdy podział osobno dopasowuje imputację, skalowanie i selekcję cech. Ocenia się wkład domen przez ich pomijanie lub zaburzanie.

### 6. Wskaźniki

MAE, względna redukcja MAE, korelacja wewnątrz osób, błąd zmian i pokrycie pomiarem. Cele rozwojowe: r≥0,70 i ≥10% redukcji MAE względem B1; ich potwierdzenie pozostaje zadaniem 3B. Rezultat: jedna wybrana wersja modelu oraz zamrożone cechy, profil osobisty, reguły jakości, braków i interpretacji.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Cechy statystyczne | Poziom, zmienność i regularność w oknach 7/14/28 dni, gdy historia jest dostępna |
| Cechy czasowe | Trend, tempo zmiany i uporządkowane w czasie sekwencje |
| Wartość personalizacji | Sparowana różnica MAE modelu z profilem i modelu populacyjnego |
| Wkład domeny | Zmiana jakości po pominięciu lub zaburzeniu jej informacji |

### 8. Uzasadnienie założeń etapu

Etap obejmuje fuzję domen, indywidualne profile, cel r≥0,70, modele porównawcze, rozdzielenie osób, zamrożenie algorytmu, porównanie cech statystycznych i czasowych oraz interpretację wkładu sygnałów.

## Etap 3B — niezależna walidacja

**Druga część fazy 3. Cel: sprawdzić jakość zamrożonego modelu na nowych osobach i u innych terapeutów.**

### 1. Czas badania

16 tygodni na uczestnika, M14–M20. Rekrutacja rusza po zamrożeniu modelu. Główne punkty oceny obejmują tygodnie 4, 6, 8, 10, 12, 14 i 16; pierwsze 14 dni wyznacza profil osobisty.

### 2. Zmienne

PHQ-9, oszacowanie modelu, błędy, zmiany obu wyników, kompletność i stabilność. Dodatkowo WHO-5, WHODAS i zaślepiona ocena specjalisty. Podgrupy: m.in. nasilenie objawów, etap terapii i platforma telefonu.

### 3. N

120 nowych uczestników u terapeutów nieuczestniczących w rozwoju modelu. Oczekiwane 90–96 analizowalnych osób przy ubytku 20–25%. Wszyscy uczestnicy noszą opaskę; model smartfonowy nie otrzymuje cech z opaski. Wyniki dotyczące małych podgrup pozostają opisowe.

### 4. Hipotezy

H-V1: model osiąga r≥0,70 z powtarzanymi pomiarami PHQ-9 wewnątrz osób. H-V2: MAE jest co najmniej o 10% mniejszy niż dla B1. H-V3: różnice kolejnych oszacowań odzwierciedlają rzeczywiste zmiany PHQ-9; błąd tej zmiany ocenia się osobno.

### 5. Metoda

Model działa bez ponownego strojenia. Dane wejściowe kończą się przed bieżącym kwestionariuszem; bieżący PHQ-9, WHO-5 i EMA nie trafiają do głównego modelu. Terapeuta i pacjent nie widzą interpretacji cyfrowej. Porównania wykorzystują te same osoby i okna. Przedziały ufności uwzględniają powtarzane pomiary i grupowanie u terapeutów, np. przez bootstrap hierarchiczny.

### 6. Wskaźniki

Główne cele: r≥0,70 oraz ≥10% redukcji MAE względem B1. Proponowana operacjonalizacja r dotyczy korelacji wewnątrz osób. Osobno raportuje się błąd bezwzględny, błąd zmiany i przedziały ufności. Cele techniczne: reguła 80%/80% oraz ICC≥0,70 dla określonych wskaźników w stabilnych okresach. Liczbowy próg akceptowalnego MAE zmiany wymaga ustalenia przed walidacją; nie jest tu dopisywany bez uzasadnienia.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Błąd poziomu | Wartość bezwzględna różnicy oszacowania i PHQ-9; średnia na osobę, następnie między osobami |
| Zmiana modelu | Δŷ=ŷ(t)−ŷ(t−14 dni), wobec ΔY=Y(t)−Y(t−14 dni); ocena w tygodniach 6, 8, 10, 12 |
| Stabilny okres | Okres spełniający wcześniej określone kryteria stabilności pomiarów referencyjnych |
| Dostępność wyniku | Odsetek planowanych okresów z wynikiem spełniającym kryteria jakości |

Odjęcie poprzedniego zmierzonego PHQ-9 od bieżącej prognozy daje taki sam błąd jak prognoza bieżącego poziomu; nie jest traktowane jako osobny dowód monitorowania zmian.

### 8. Uzasadnienie założeń etapu

Etap obejmuje PHQ-9, 16 tygodni obserwacji, 120 nowych osób, innych terapeutów, zaślepienie, zamrożenie modelu, porównanie z modelem odniesienia, korelację, MAE na osobę i osobną ocenę różnic kolejnych oszacowań.

## Etap 4 — użyteczność panelu dla specjalisty

**Cel: ocenić zrozumienie, wartość informacji i możliwość regularnego używania panelu.**

### 1. Czas badania

Dodatkowe 8 tygodni, M21–M24, po zakończeniu i ocenie niezależnej walidacji. Daje to 24 tygodnie aktywnej obserwacji uczestnika kohorty walidacyjno-użytkowej; przerwę organizacyjną liczy się osobno.

### 2. Zmienne

SUS, deklarowana wartość raportu, poprawność interpretacji, czas odczytu, chęć regularnego korzystania i wpływ informacji na rozmowę. Dostęp do panelu może być wprowadzany od razu lub z opóźnieniem. Objawy i funkcjonowanie są nadal mierzone pomocniczo.

### 3. N

Kontynuujący uczestnicy spośród 120 osób walidacyjnych, bez nowej kohorty. Co najmniej 15 specjalistów kończących ocenę; cel organizacyjny 30–40. Liczba raportów, liczba pacjentów i liczba specjalistów są podawane oddzielnie.

### 4. Hipotezy

H-U1: średni SUS wynosi co najmniej 68/100. H-U2: co najmniej 60% specjalistów potwierdza wartość dodatkową. H-U3: co najmniej 90% odpowiedzi w zadaniach interpretacyjnych jest poprawnych, a mediana czasu podstawowego odczytu nie przekracza 2 minut.

### 5. Metoda

Badanie użytkowe łączące kwestionariusze, zadania na raportach, pomiar czasu i wywiady. Jeśli liczba specjalistów pozwala, losuje się dostęp od pierwszego lub piątego tygodnia tej fazy. Porównanie pierwszych czterech tygodni dotyczy korzystania z informacji. Analiza uwzględnia pacjentów i raporty skupione u specjalisty. W przypadku niedostatecznej trafności modelu dopuszcza się ocenę interfejsu na scenariuszach, jawnie jako inny zakres wyniku.

### 6. Wskaźniki

SUS≥68/100, wartość dodatkowa u ≥60% specjalistów, poprawność interpretacji ≥90%, mediana odczytu ≤2 min i chęć stosowania u ≥60%. Wartość dodatkowa u 70% jest celem rozszerzonym. Dla odsetków raportuje się liczby i przedziały ufności, a także brak odpowiedzi. Ocena użytkowa nie potwierdza przyczynowego wpływu panelu na skuteczność terapii.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Użyteczność | Końcowy wynik SUS według instrukcji; próg średniego wyniku to doprecyzowanie syntezy |
| Wartość dodatkowa | Odsetek specjalistów potwierdzających nową lub porządkującą informację; jawny mianownik odpowiedzi |
| Rozumienie | Odsetek poprawnych odpowiedzi, liczony najpierw na specjalistę, następnie uśredniany |
| Czas odczytu | Pomiar czasu od otwarcia raportu do odpowiedzi na podstawowe zadanie |
| Wpływ na rozmowę | Zgłoszony temat podjęty dzięki raportowi; wynik opisowy |

### 8. Uzasadnienie założeń etapu

Etap obejmuje 8 tygodni panelu po 16-tygodniowej walidacji, minimum 15 specjalistów, ocenę SUS, wartości informacji, rozumienia wyniku i czasu odczytu. Raportuje się liczby pacjentów, raportów i specjalistów jako odrębne jednostki analizy.

## Podbadanie P1 — wartość dodatkowa opaski

**Przekrojowo przez fazy 2–3. Cel: ustalić, czy dane z opaski uzasadniają rozszerzenie wariantu smartfonowego.**

### 1. Czas badania

W ramach 16 tygodni etapu 2 i 16 tygodni etapu 3B; bez wydłużenia udziału. Modele opracowuje się do M12, a analizę walidacyjną zamyka po M20, orientacyjnie do M21.

### 2. Zmienne

Przydział opaski, jej dane fizjologiczne, PHQ-9, MAE modeli, kompletność, czas noszenia i obciążenie. Główny czynnik porównania: dodanie danych opaski przy zachowaniu tych samych pozostałych informacji wejściowych.

### 3. N

Wszyscy 360 uczestnicy badania głównego: 240 w kohorcie rozwojowej i 120 w walidacyjnej, korzystają ze smartfona i noszą opaskę. Tych N nie dolicza się do 400, ponieważ są ich częścią.

### 4. Hipotezy

H-W1: dodanie opaski zmniejsza MAE o co najmniej 10% względem modelu smartfonowego. H-W2: poprawie towarzyszy akceptowalne obciążenie i kompletność. Brak przewagi opaski pozostaje pełnoprawnym wynikiem badawczym.

### 5. Metoda

Na tych samych osobach i okresach porównuje się model smartfonowy z modelem „smartfon + opaska”. Wszystkie pozostałe informacje wejściowe pozostają takie same. Porównuje się także retencję, kompletność i obciążenie. Model multimodalny zostaje zamrożony przed niezależną walidacją.

### 6. Wskaźniki

Sparowana redukcja MAE≥10%, bezwzględna różnica błędu i przedziały ufności. Pomocniczo: ważne dni opaski, czas noszenia, rezygnacje i problemy z ładowaniem. Brak opaski lub danych fizjologicznych nie wyklucza uczestnika z głównej analizy smartfonowej.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Wariant modelu | 0 = smartfon; 1 = smartfon + opaska, oceniane na tych samych osobach i okresach |
| Przyrost jakości | Różnica MAE dwóch modeli na wspólnym zestawie osób i okresów |
| Czas noszenia | Czas prawidłowego rejestrowania, zgodnie z dostępnymi danymi urządzenia |
| Obciążenie | Częstość problemów i przerw związanych z noszeniem lub ładowaniem |

### 8. Uzasadnienie założeń etapu

Podbadanie obejmuje wartość dodatkową fizjologii z opaski oraz sparowane porównanie modeli „smartfon” i „smartfon + opaska” dla tych samych osób i okresów.

## Podbadanie P2 — prognozowanie pogorszenia

**Analiza eksploracyjna na danych faz 2–3. Cel: ocenić możliwość prognozowania przyszłych objawów i sygnałów poprzedzających pogorszenie.**

### 1. Czas badania

Horyzont prognozy: 14 dni. Wykorzystuje się obserwacje 12-tygodniowe bez dostępu do panelu. Opracowanie M9–M12, ocena M18–M22. Nie planuje się dodatkowej obserwacji ani nowej rekrutacji w tej karcie.

### 2. Zmienne

Przyszły PHQ-9, przyszłe pogorszenie, data początku niezależnie potwierdzonego zdarzenia, cechy dostępne do chwili prognozy, alarmy i ich czas. Dodatkowo liczba niezależnych epizodów i liczba osób z epizodami.

### 3. N

Dane 240 osób do opracowania i 120 do oceny, z uwzględnieniem braków i dostępnych par czasowych. Kluczowe N to również liczba niezależnych epizodów. Przy mniej niż 30 epizodach wynik pozostaje opisowy; 30 nie oznacza automatycznie wystarczającej mocy.

### 4. Hipotezy

H-F1: dane cyfrowe poprawiają przewidywanie PHQ-9 za 14 dni względem modelu opartego na wcześniejszych samoocenach. H-F2: określone wzorce pozwalają uzyskać sygnał co najmniej 14 dni przed niezależnie datowanym pogorszeniem. Hipotezy są oceniane oddzielnie; wykazanie H-F1 nie potwierdza H-F2.

### 5. Metoda

Modele korzystają wyłącznie z informacji dostępnej do czasu t, a wynik dotyczy okresu po t. Reguły braków, profilu i cech nie mogą korzystać z przyszłości. Model prognostyczny, definicja epizodu i alarmu muszą być ustalone na danych rozwojowych przed oceną kohorty 120 osób. Jeśli nie zostaną zamrożone na czas, analiza na tych 120 osobach zostaje opisana jako dalszy rozwój, bez deklarowania niezależnego potwierdzenia.

### 6. Wskaźniki

Dla przyszłego PHQ-9: MAE i przyrost względem modelu odniesienia. Dla zdarzeń: czułość, dodatnia wartość predykcyjna, kalibracja, liczba fałszywych alarmów na osobę w miesiącu i rozkład czasu wyprzedzenia. Cel badawczy wyprzedzenia wynosi ≥14 dni; dopuszczalną liczbę fałszywych alarmów należy ustalić przed oceną, bez dobierania jej do wyników.

### 7. Skrócona operacjonalizacja zmiennych

| Zmienna | Pomiar |
|---|---|
| Przyszłe nasilenie | PHQ-9 w t+14 dni, odnoszący się do okresu następującego po prognozie |
| Pogorszenie | Ustalony wzrost PHQ-9 i zgodna kotwica pacjenta; reguła i próg ustalone przed oceną |
| Niezależny epizod | Zdarzenie wydzielone według zamrożonych zasad; sąsiednie okna nie są automatycznie nowymi epizodami |
| Wyprzedzenie | Data potwierdzonego początku zdarzenia minus data pierwszego kwalifikującego alarmu |
| Nawrót depresji | Wymaga klinicznego potwierdzenia i datowania; sam wzrost PHQ-9 nie wystarcza |

### 8. Uzasadnienie założeń etapu

Podbadanie ma charakter eksploracyjny. Obejmuje prognozę przyszłego wyniku oraz analizę sygnałów czasowych poprzedzających pogorszenie, bez uzależniania sukcesu projektu od predykcji z wyprzedzeniem 14 dni.

## Zasady wspólne i elementy do doprecyzowania

Każda kohorta jest prowadzona według uzgodnionych procedur bezpieczeństwa i świadomej zgody. Obsługa samoocen wskazujących ryzyko ma określony personel, sposób kontaktu i czas reakcji; działa niezależnie od zaślepienia wyniku cyfrowego. Dane są pseudonimizowane, a treści wiadomości i wpisywany tekst nie są zbierane. Próbki głosu są celowo nagrywane na potrzeby badania, z ustalonym sposobem przetwarzania i retencji.

Przed finalizacją protokołu pozostają: obliczenie N, definicja ważnych dni i stabilnych okresów, próg błędu i istotnej zmiany PHQ-9, dokładny wariant ICC, reguły epizodów i alarmów, dostępność domen oraz urządzenie do podbadania. Są to jawnie wskazane parametry do ustalenia przed oceną potwierdzającą, a nie wyniki już uzyskane.

## Uwagi końcowe

Liczebność modelu rozwojowego i jego walidacji wymaga uzasadnienia odpowiedniego do złożoności modelu, struktury danych i wymaganej precyzji. [Planowanie próby rozwojowej — Riley i wsp.](https://www.bmj.com/content/368/bmj.m441.abstract), [Planowanie walidacji — Riley i wsp.](https://www.bmj.com/content/384/bmj-2023-074821)
