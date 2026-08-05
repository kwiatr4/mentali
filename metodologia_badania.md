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

## Planowana liczebność próby
Minimalną liczebność próby oszacowano w programie G*Power dla porównania dwóch niezależnych grup przy założeniu średniego efektu (d = 0,5), poziomu istotności α = 0,05, mocy testu 0,95, testu dwustronnego oraz równego podziału uczestników między grupy. W takim układzie wymagana liczebność wynosi 210 osób łącznie, czyli 105 osób w każdej grupie.

W praktyce rekrutację należy zaplanować z uwzględnieniem możliwych braków danych i rezygnacji uczestników w trakcie obserwacji, tak aby końcowa liczebność analityczna nie spadła poniżej tego poziomu.

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

## Proces przetwarzania danych i wykorzystanie ML
Surowe dane pasywnie zbierane ze smartfona i opaski będą najpierw czyszczone, synchronizowane i agregowane w oknach czasowych, a następnie przekształcane w cechy statyczne i dynamiczne opisujące funkcjonowanie uczestnika. W praktyce oznacza to wyprowadzenie wskaźników takich jak sen, aktywność, mobilność, użycie telefonu, komunikacja, dynamika pisania, analiza głosu oraz parametry fizjologiczne z opaski.

Na tak przygotowanych danych zostaną porównane dwa warianty modelu: smartfon-only oraz smartfon + wearable. Uczenie maszynowe będzie wykorzystywane nie jako cel sam w sobie, lecz jako narzędzie do wykrywania wzorców związanych z dobrostanem oraz do sprawdzenia, czy dodatkowe dane z opaski poprawiają trafność, stabilność i czułość predykcji.

Istotnym elementem analizy będzie interpretowalność: ocena, które sygnały mają największy wpływ na wynik modelu, oraz czy rezultat można przedstawić psychoterapeucie w sposób praktyczny i zrozumiały. Taki schemat jest zgodny z logiką badania opisaną w artykule Liu et al. 2026, który pokazuje przejście od surowych danych z urządzeń do cech, modeli predykcyjnych i walidacji praktycznej.

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

Z dokumentu Frascati warto też przenieść konkretne wskaźniki oceny:
- SUS co najmniej 68/100,
- korelacja z oceną kliniczną na poziomie co najmniej r = 0,70,
- deklarowana wartość dodana przez co najmniej 60% psychoterapeutów,
- możliwość uchwycenia sygnałów ostrzegawczych z wyprzedzeniem około 14 dni.

## Innowacyjność
Innowacyjność badania polega na połączeniu trzech elementów:
- pasywnego pomiaru danych ze smartfona,
- porównania wariantu smartfon-only z wariantem wzbogaconym o opaskę,
- praktycznie interpretowalnego modelu, który ma wspierać psychoterapeutę, a nie jedynie generować wynik klasyfikacyjny.

Analiza z dokumentu od dr. Slęzaka doprecyzowuje, że projekt warto opisywać w logice Frascati 2015 jako połączenie badań przemysłowych i prac rozwojowych. W tym ujęciu innowacja ma charakter produktowy i procesowy, a jej rdzeniem nie jest samo wdrożenie aplikacji, tylko metodyczne usunięcie niepewności badawczej.

W praktyce oznacza to nacisk na:
- multimodalne łączenie danych ze smartfona i opaski wearable,
- sprawdzenie wariantu smartfon-only względem smartfon + wearable,
- budowę interpretowalnego wyniku dla psychoterapeuty,
- testowanie indywidualnych profili behawioralnych zamiast prostych progów populacyjnych,
- możliwość odtworzenia wyników przez inne zespoły na podstawie protokołu, modelu i zbioru danych.

Badanie może dostarczyć odpowiedzi nie tylko na pytanie, czy biomarkery cyfrowe są użyteczne, ale też jakie źródło danych daje najlepszy kompromis między jakością predykcji, kosztem wdrożenia i obciążeniem użytkownika.

## Znaczenie praktyczne
Jeśli model oparty wyłącznie na smartfonie okaże się wystarczający, rozwiązanie będzie prostsze, tańsze i łatwiejsze do wdrożenia. Jeśli opaska istotnie poprawi wyniki, badanie wskaże, w których sytuacjach warto ją włączyć jako element dodatkowy.