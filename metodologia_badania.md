# Metodologia badania

## Cel badania
Celem badania jest opracowanie i kliniczna walidacja systemu cyfrowych biomarkerów depresji opartego na danych pasywnie zbieranych ze smartfona, z opcjonalnym rozszerzeniem o opaskę wearable. Badanie ma odpowiedzieć na pytanie, czy same dane ze smartfona wystarczają do użytecznej predykcji, czy dodatkowe dane z opasek istotnie poprawiają jakość modelu.

## Główne pytania badawcze
1. Które sygnały pasywne ze smartfona i opaski najlepiej korelują z nasileniem objawów depresyjnych?
2. Czy model oparty wyłącznie na danych ze smartfona osiąga wystarczającą trafność kliniczną?
3. Czy dołączenie opaski poprawia trafność, stabilność lub czułość predykcji?
4. Czy psychologowie uznają wynik systemu za interpretowalny i przydatny klinicznie?

## Hipotezy badawcze
H1. Dane pasywnie zbierane ze smartfona pozwalają na użyteczną predykcję stanu psychicznego i stanowią wystarczający punkt wyjścia dla modelu klinicznego.

H2. Dodanie opaski wearable poprawia jakość predykcji w porównaniu z modelem opartym wyłącznie na smartfonie, szczególnie dla sygnałów związanych ze snem, aktywnością i fizjologią.

H3. Połączenie danych behawioralnych i fizjologicznych daje lepsze wyniki niż pojedyncze strumienie danych analizowane osobno.

H4. Wynik modelu może być interpretowalny klinicznie i wspierać decyzje psychologa bez zastępowania oceny specjalisty.

## Projekt badania
Badanie powinno mieć charakter prospektywny, obserwacyjny i wielomodalny. Proponowany schemat obejmuje:
- grupę uczestników z objawami depresyjnymi oraz grupę porównawczą,
- zbieranie danych ze smartfona w sposób pasywny,
- włączenie opaski u części uczestników lub w podbadaniu porównawczym,
- równoległą ocenę kliniczną za pomocą wystandaryzowanych narzędzi.

## Etapy badania
### Etap 1. Analiza potrzeb
- wywiady z psychologami klinicznymi,
- doprecyzowanie zastosowania klinicznego,
- identyfikacja wymagań funkcjonalnych, etycznych i organizacyjnych,
- ustalenie minimalnego zestawu danych i oczekiwanych raportów.

### Etap 2. Prototyp i akwizycja danych
- budowa prototypu aplikacji mobilnej,
- integracja danych z opaski wearable,
- zbieranie danych przez co najmniej 12 tygodni,
- rejestracja danych behawioralnych i fizjologicznych,
- równoległa ocena objawów przy pomocy narzędzi klinicznych.

### Etap 3. Modelowanie i walidacja
- ekstrakcja cech statycznych i dynamicznych,
- porównanie modeli: smartfon-only vs smartfon + wearable,
- trening modeli predykcyjnych z kontrolą zmiennych zakłócających,
- interpretacja cech i analiza ich znaczenia klinicznego.

### Etap 4. Ewaluacja kliniczna
- pilotaż z psychologami,
- ocena użyteczności, trafności i akceptowalności,
- analiza wpływu na decyzje terapeutyczne,
- zebranie informacji zwrotnej do iteracji produktu.

## Dane i zmienne
### Dane ze smartfona
- aktywność fizyczna,
- mobilność i GPS,
- użycie telefonu,
- komunikacja,
- dynamika pisania,
- analiza głosu,
- wzorce snu.

### Dane z opaski wearable
- tętno,
- HRV,
- aktywność i sen,
- dodatkowe wskaźniki fizjologiczne zależne od urządzenia.

### Zmienne kliniczne
- nasilenie depresji,
- objawy współwystępujące,
- wyniki kwestionariuszy klinicznych,
- ocena psychologa,
- wskaźniki użyteczności systemu.

## Metody analizy
- analiza opisowa i porównawcza cech,
- modele uczenia maszynowego dla danych wielomodalnych,
- porównanie wydajności modeli smartfon-only i smartfon + wearable,
- analiza interpretowalności modelu,
- ocena zgodności z pomiarem klinicznym.

## Co chcemy przeanalizować
Na podstawie onepagera i danych z ankiety chcemy sprawdzić przede wszystkim:
- czy wzorce snu są najmocniejszym i najbardziej stabilnym sygnałem związanym z nasileniem depresji,
- które cechy ze smartfona mają najwyższą wartość kliniczną w ocenie psychologów, zwłaszcza aktywność fizyczna, mobilność, użycie telefonu, komunikacja, dynamika pisania i analiza głosu,
- czy dane z opaski poprawiają predykcję względem samego smartfona, szczególnie dla snu, aktywności i sygnałów fizjologicznych,
- czy połączenie sygnałów behawioralnych i fizjologicznych daje lepszy wynik niż pojedyncze źródła danych,
- czy model pozostaje interpretowalny i zgodny z tym, jak psychologowie rozumieją objawy,
- czy użytkownicy kliniczni uznają wynik za praktyczny, czytelny i niewywołujący nadmiernego obciążenia,
- czy rozwiązanie można oprzeć wyłącznie na smartfonie, czy opaska daje na tyle duży przyrost jakości, że warto ją rekomendować jako element dodatkowy.

## Kryteria sukcesu
- wysoka zgodność predykcji z oceną kliniczną,
- poprawa metryk po dodaniu opaski,
- możliwość wygenerowania zrozumiałego wyniku dla psychologa,
- pozytywna ocena użyteczności w pilotażu,
- brak nadmiernego obciążenia uczestników.

## Innowacyjność
Innowacyjność badania polega na połączeniu trzech elementów:
- pasywnego pomiaru danych ze smartfona,
- porównania wariantu smartfon-only z wariantem wzbogaconym o opaskę,
- klinicznie interpretowalnego modelu, który ma wspierać psychologa, a nie jedynie generować wynik klasyfikacyjny.

Badanie może dostarczyć odpowiedzi nie tylko na pytanie, czy biomarkery cyfrowe są użyteczne, ale też jakie źródło danych daje najlepszy kompromis między jakością predykcji, kosztem wdrożenia i obciążeniem użytkownika.

## Znaczenie praktyczne
Jeśli model oparty wyłącznie na smartfonie okaże się wystarczający, rozwiązanie będzie prostsze, tańsze i łatwiejsze do wdrożenia. Jeśli opaska istotnie poprawi wyniki, badanie wskaże, w których sytuacjach warto ją włączyć jako element dodatkowy.