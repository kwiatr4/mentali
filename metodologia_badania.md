# Metodologia badania

## Cel badania
Celem badania jest opracowanie i walidacja systemu wspierającego psychoterapeutów w ocenie dobrostanu psychicznego, opartego na danych pasywnie zbieranych ze smartfona, z opcjonalnym rozszerzeniem o opaskę wearable. Badanie ma odpowiedzieć na pytanie, czy same dane ze smartfona wystarczają do użytecznej oceny dobrostanu, czy dodatkowe dane z opasek istotnie poprawiają jakość modelu.

## Główne pytania badawcze
1. Które sygnały pasywne ze smartfona i opaski najlepiej korelują z nasileniem objawów depresyjnych?
2. Czy model oparty wyłącznie na danych ze smartfona osiąga wystarczającą trafność praktyczną?
3. Czy dołączenie opaski poprawia trafność, stabilność lub czułość predykcji?
4. Czy psychoterapeuci uznają wynik systemu za interpretowalny i przydatny praktycznie?

## Hipotezy badawcze
H1. Dane pasywnie zbierane ze smartfona pozwalają na użyteczną ocenę dobrostanu i stanowią wystarczający punkt wyjścia dla modelu praktycznego.

H2. Dodanie opaski wearable poprawia jakość oceny dobrostanu w porównaniu z modelem opartym wyłącznie na smartfonie, szczególnie dla sygnałów związanych ze snem, aktywnością i fizjologią.

H3. Połączenie danych behawioralnych i fizjologicznych daje lepsze wyniki niż pojedyncze strumienie danych analizowane osobno.

H4. Wynik modelu może być interpretowalny praktycznie i wspierać decyzje psychoterapeuty bez zastępowania oceny specjalisty.

## Projekt badania
Badanie powinno mieć charakter prospektywny, obserwacyjny i wielomodalny. Proponowany schemat obejmuje:
- grupę uczestników z objawami depresyjnymi oraz grupę porównawczą,
- zbieranie danych ze smartfona w sposób pasywny,
- włączenie opaski u części uczestników lub w podbadaniu porównawczym,
- równoległą ocenę dobrostanu za pomocą wystandaryzowanych narzędzi.

## Etapy badania
### Etap 1. Analiza potrzeb
- wywiady z psychoterapeutami,
- doprecyzowanie zastosowania praktycznego,
- identyfikacja wymagań funkcjonalnych, etycznych i organizacyjnych,
- ustalenie minimalnego zestawu danych i oczekiwanych raportów.

### Etap 2. Prototyp i akwizycja danych
- budowa prototypu aplikacji mobilnej,
- integracja danych z opaski wearable,
- zbieranie danych przez co najmniej 12 tygodni,
- rejestracja danych behawioralnych i fizjologicznych,
- równoległa ocena dobrostanu przy pomocy narzędzi praktycznych.

### Etap 3. Modelowanie i walidacja
- ekstrakcja cech statycznych i dynamicznych,
- porównanie modeli: smartfon-only vs smartfon + wearable,
- trening modeli predykcyjnych z kontrolą zmiennych zakłócających,
- interpretacja cech i analiza ich znaczenia praktycznego.

### Etap 4. Ewaluacja praktyczna
- pilotaż z psychoterapeutami,
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
- wskaźniki dobrostanu,
- objawy współwystępujące,
- wyniki kwestionariuszy dobrostanu,
- ocena psychoterapeuty,
- wskaźniki użyteczności systemu.

## Metody analizy
- analiza opisowa i porównawcza cech,
- modele uczenia maszynowego dla danych wielomodalnych,
- porównanie wydajności modeli smartfon-only i smartfon + wearable,
- analiza interpretowalności modelu,
- ocena zgodności z pomiarem dobrostanu.

## Co chcemy przeanalizować
Na podstawie onepagera i danych z ankiety chcemy sprawdzić przede wszystkim:
- czy wzorce snu są najmocniejszym i najbardziej stabilnym sygnałem związanym z nasileniem depresji,
- które cechy ze smartfona mają najwyższą wartość praktyczną w ocenie psychoterapeutów, zwłaszcza aktywność fizyczna, mobilność, użycie telefonu, komunikacja, dynamika pisania i analiza głosu,
- czy dane z opaski poprawiają predykcję względem samego smartfona, szczególnie dla snu, aktywności i sygnałów fizjologicznych,
- czy połączenie sygnałów behawioralnych i fizjologicznych daje lepszy wynik niż pojedyncze źródła danych,
- czy model pozostaje interpretowalny i zgodny z tym, jak psychoterapeuci rozumieją dobrostan,
- czy użytkownicy praktyczni uznają wynik za praktyczny, czytelny i niewywołujący nadmiernego obciążenia,
- czy rozwiązanie można oprzeć wyłącznie na smartfonie, czy opaska daje na tyle duży przyrost jakości, że warto ją rekomendować jako element dodatkowy.

## Kryteria sukcesu
- wysoka zgodność predykcji z oceną dobrostanu,
- poprawa metryk po dodaniu opaski,
- możliwość wygenerowania zrozumiałego wyniku dla psychoterapeuty,
- pozytywna ocena użyteczności w pilotażu,
- brak nadmiernego obciążenia uczestników.

## Innowacyjność
Innowacyjność badania polega na połączeniu trzech elementów:
- pasywnego pomiaru danych ze smartfona,
- porównania wariantu smartfon-only z wariantem wzbogaconym o opaskę,
- praktycznie interpretowalnego modelu, który ma wspierać psychoterapeutę, a nie jedynie generować wynik klasyfikacyjny.

Badanie może dostarczyć odpowiedzi nie tylko na pytanie, czy biomarkery cyfrowe są użyteczne, ale też jakie źródło danych daje najlepszy kompromis między jakością predykcji, kosztem wdrożenia i obciążeniem użytkownika.

## Znaczenie praktyczne
Jeśli model oparty wyłącznie na smartfonie okaże się wystarczający, rozwiązanie będzie prostsze, tańsze i łatwiejsze do wdrożenia. Jeśli opaska istotnie poprawi wyniki, badanie wskaże, w których sytuacjach warto ją włączyć jako element dodatkowy.