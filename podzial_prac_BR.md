# Podział prac badawczych i rozwojowych (B+R)

Projekt obejmuje dwie równoległy komponenty: **badania przemysłowe** (research component) i **prace rozwojowe** (development component), realizowane synchronicznie i sekwencyjnie.

---

## I. BADANIA PRZEMYSŁOWE (Industrial Research)

### Cel
Eksploracja, odkrywanie nowej wiedzy, odpowiedź na pytania badawcze, usunięcie niepewności technologicznej.

---

### WP-BP.1 – Pilotaż i ustalenie procedur (Etap 0)
**Czas:** Miesiące 1–4 (16 tygodni)  
**Liczebność:** 40 uczestników  
**Terapeuta widzi panel:** Nie

#### Zadania:
1. **Rekrutacja i enrolment** (10 terapeutów × 4 pacjentów)
   - Screening, informacja, zgoda
   - Procedury IRB i GDPR
   - Dystrybuacja aplikacji i opasek

2. **Zbieranie danych pilotażowych**
   - Dane cyfrowe ze smartfona i opaski u wszystkich uczestników
   - Samooceny (WHO-5, WHODAS 2.0, króciutkie samooceny)
   - Oceny terapeuty
   - Zdarzenia kontekstowe

3. **Walidacja narzędzi pomiarowych**
   - Rzetelność WHO-5 i WHODAS 2.0 w próbie
   - Rozkład i brakujące dane
   - Jakość sygnałów z aplikacji i opaski
   - Obciążenie uczestników i terapeutów

4. **Ustalenie procedur**
   - Reguła wyznaczania "ważnego dnia" (na każdej domenie)
   - Procedury bezpieczeństwa (screen gotośni, interwencja)
   - Kryteria analizowalności (kiedy pacjent przerywa, kiedy dane nie liczone)
   - Procedury braku danych

5. **Symulacja mocy i parametry końcowe**
   - Na podstawie rozkładu efektów w pilotażu
   - Oszacowanie liczebności etapu 1B
   - Ustalenie progów zmian klinicznych

6. **Rezultaty pilotażu**
   - Raport wykonalności
   - Protokół procedur (zamrażany)
   - Zbór danych pilotażowych (odłożony, nie wchodzi do modelu)

---

### WP-BP.2 – Opracowanie modelu (Etap 1A – Część Badawcza)
**Czas:** Miesiące 6–11 (16 tygodni obserwacji uczestnika, równolegle z WP-PB.1)  
**Liczebność:** 240 uczestników  
**Terapeuta widzi panel:** Nie

#### Zadania:
1. **Ekstrakcja i inżynieria cech (Features Engineering)**
   - Z każdej domeny cyfrowej: agregacja, standaryzacja, transformacje
   - Sen: całkowity czas, ciągłość, latencja
   - Aktywność: liczba kroków, dystans, zmienność dobowa
   - Telefon: czas ekranu, liczba odblokowań, przełączanie aplikacji
   - Komunikacja: liczba SMS/rozmów, tempo odpowiadania
   - Dynamika pisania: tempo, tempo zmian, pauzy
   - Głos (jeśli dostępne): tempo mowy, zmienność
   - Fizjologia (wariant B): HR, HRV, aktywność nocna, temperatura

2. **Opracowanie indywidualnego poziomu odniesienia**
   - Algorytm wyliczania poziomu z pierwszych 14 dni
   - Testowanie wariantów (stały vs dynamiczny vs z historią)
   - Walidacja stabilności w okresach referencyjnie stabilnych

3. **Budowa modeli predykcyjnych** – Porównanie ≥4 podejść:
   - **Model A:** Samoocena historyczna (baseline) – wcześniejszy wynik samooceny
   - **Model B:** Populacyjny – cechy cyfrowe dla całej próby (bez personalizacji)
   - **Model C:** Indywidualny – odchylenia od osobistego poziomu odniesienia
   - **Model D:** Hybrydowy – informacja populacyjna + indywidualna

4. **Dobór cech (Feature Selection)**
   - Która z sześciu domen smartfonowych (głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja) wnosi największą wartość?
   - Analiza zmienności między osobami vs wewnątrz osoby
   - Wybór podejścia: populacyjne progi vs indywidualne profili
   - Przepełnienie (overfitting) – cross-validation na danych treningowych

5. **Łączenie danych smartfon vs opaska**
   - Dla wariantu B: jaka kombinacja liniowa/nieliniowa cech?
   - Czy opaska rzeczywiście poprawia predykcję?
   - Analiza wkładu każdej domeny

6. **Standaryzacja wyniku modelu**
   - Jak łączyć samooceny (WHO-5, WHODAS, krótkie pytania)?
   - Struktura zależności między miarami (analiza czynnikowa)
   - Model zmiennej ukrytej (latent variable model) vs reguła z góry określona

7. **Eksperymenty z metodami przetwarzania**
   - Imputacja brakujących danych (forward fill, interpolacja, MICE?)
   - Normalizacja i standaryzacja cech
   - Okna czasowe (7, 14, 28 dni?) – co jest optymalne?

8. **Rezultaty etapu 1A**
   - **Kod modelu** – zamrażany algorytm do wykorzystania w 1B
   - **Definicje cech** – dokładny opis każdej cechy cyfrowej
   - **Progi decyzyjne** – jakie wartości sygnalizują zmianę
   - **Procedura wyliczania poziomu odniesienia** – zamrażana
   - **Raporty badawcze** – które cechy są najsilniejsze, które domeny zawodzą

---

### WP-BP.3 – Niezależna walidacja modelu (Etap 1B – Część Badawcza)
**Czas:** Miesiące 14–20 (16 tygodni obserwacji uczestnika, sekwencyjnie po WP-BP.2)  
**Liczebność:** 120 nowych uczestników (nie było w zbiorze treningowym!)  
**Terapeuta widzi panel:** **NIE** przez całe 16 tygodni (zaślepienie)

#### Zadania:
1. **Wdrożenie zamrożonego modelu**
   - Kod z WP-BP.2 bez zmian
   - Definicje cech bez zmian
   - Progi bez zmian
   - Procedury braku danych bez zmian

2. **Zbieranie danych niezależnych**
   - Identyczna procedura co etap 1A
   - Ale nowe osoby, nowi terapeuci

3. **Ewaluacja jakości na danych walidacyjnych**
   - **Główne wyniki:**
     - Zgodność wyniku cyfrowego z wynikiem referencyjnym (korelacja, MAE)
     - Średni błąd bezwzględny (MAE) i błąd względny
     - Czy model osiąga minimalny próg wydajności?
   - **Stabilność w podgrupach:**
     - Mężczyźni vs kobiety
     - Początek vs trwająca terapia
     - Wariant smartfon vs wariant smartfon+wearable
   - **Powtarzalność w okresach stabilnych**
     - Czy wynik jest spójny, gdy terapeuta obserwuje stabilizację?

4. **Analiza błędów i wyjątków**
   - Które osoby model źle przewiduje? Dlaczego?
   - Czy błędy wiążą się z określonymi zdarzeniami kontekstowymi?
   - Czy trzeba dodać zmienne moderujące?

5. **Raport walidacji niezależnej**
   - Czy model przechodzi kryteria sukcesu?
   - Czy opaska poprawia wyniki? Jak dużo?
   - Jakie są ograniczenia modelu?
   - Czy personalizacja była warta inwestycji?

---

### WP-BP.4 – Badanie prognozowania (Eksploracyjny – Etap 1B część druga)
**Czas:** Miesiące 12–16 (równolegle z końcem 1B)  
**Liczebność:** 120 osób z etapu 1B (dane walidacyjne)  
**Terapeuta widzi panel:** Nie (dane z okresu zaślepienia)

#### Zadania:
1. **Sformułowanie problemu prognozowania**
   - Zdarzenie do przewidywania: przyszłe istotne pogorszenie (7 lub 14 dni naprzód)
   - Definiowanie pogorszenia: standard referencyjny (WHO-5, WHODAS)
   - Wyłącze tylko okresy zaślepienia (terapeuta nie widział panelu)

2. **Inżynieria cech czasowych**
   - Wzorce dynamiczne: trend, zmienność, punkt przegięcia
   - Analiza w oknach 7, 14, 28 dni
   - Czułość systemu na przesunięcia czasowe

3. **Budowa modelu prognostycznego**
   - Jeśli N pogorszeń ≥ 30: modele klasyfikacji (logistyka, las losowy)
   - Jeśli N pogorszeń < 30: analiza opisowa

4. **Metryki prognozowania**
   - Czułość, swoistość, wartość predykcyjna dodatnia/ujemna
   - Liczba fałszywych alarmów na pacjenta/miesiąc
   - Czas wyprzedzenia (lead time)
   - Kalibracja

5. **Rezultaty (status: eksploracyjny)**
   - Raport możliwości prognozowania
   - Potencjalne zastosowania
   - **Wniosek:** czy wymagana dalsze walidacja prospektywna

---

### WP-BP.5 – Analiza Literature Review i State-of-Art
**Czas:** Równolegle z całym projektem (Miesiące 0–16)

#### Zadania:
1. **Przegląd cyfrowego fenotypowania**
   - Badania na smartfonach i wearables w psychiatrii
   - Które cechy cyfrowe mają najboliszszą rzetelność?
   - Jakie są ograniczenia metodologiczne?

2. **Przegląd modelowania dobrostanu**
   - WHO-5, WHODAS – walidacja w różnych populacjach
   - Indywidualne profile behawioralne (idiographic vs nomothetic)
   - Badania nad personalizacją

3. **Przegląd ochrony prywatności i GDPR**
   - Jakie są best practices w zbieraniu danych cyfrowych?
   - Minimalizacja, pseudonimizacja, szyfrowanie

---

## II. PRACE ROZWOJOWE (Development Activities)

### Cel
Budowa, integracja, testowanie, wdrażanie – rzeczywiście użyteczny produkt.

---

### WP-PB.1 – Rozwój i integracja aplikacji mobilnej
**Czas:** Miesiące 0–8 (równolegle z WP-BP.1 i WP-BP.2)

#### Zadania:
1. **Architektura systemu**
   - Backend (serwer, baza danych, API)
   - Frontend (aplikacja mobilna Android/iOS)
   - Bezpieczeństwo: szyfrowanie, autentykacja, autoryzacja

2. **Zbieranie danych cyfrowych (passive sensing)**
   - Moduł aktywności (accelerometr, kroki)
   - Moduł mobilności (GPS + cechy syntetyczne)
   - Moduł użycia telefonu (time on screen, uklady, aplikacje – bez treści)
   - Moduł komunikacji (liczba SMS/rozmów – bez treści)
   - Moduł snu (ze smartfona lub opaski)
   - Moduł analizy głosu: ekstrakcja cech bez zapisu nagrania

3. **Integracja z opaskami wearable**
   - API do Fitbita, Oury, Apple Watch itp.
   - Synchronizacja HR, HRV, aktywności, snu
   - Obsługa błędów synchronizacji

4. **Moduł aktywnych samoocen**
   - Interface do wpisywania WHO-5, WHODAS, pytań króciutkich
   - Notyfikacje, reminiscencje
   - Obsługa offline

5. **Backend analityczny (placeholder)**
   - API do uruchomienia modelu (będzie gotowy po etapie 1A)
   - Storage danych, logi audytu
   - HIPAA/GDPR compliance

6. **Testowanie i iteracja**
   - Unit testy, integracyjne testy
   - Testy użytkownika (usability testing) z 10–20 terapeutami
   - Raport z iteracji

---

### WP-PB.2 – Integracja modelu w aplikacji (post-etap 1A)
**Czas:** Miesiące 8–12 (po zamrożeniu modelu z WP-BP.2)

#### Zadania:
1. **Port modelu do production-ready kodu**
   - Z Pythona/R do JavaScript/Kotlin/Swift (lub C++)
   - Optymalizacja wydajności
   - Testing edge cases

2. **Implementacja wyświetlania wyniku dla psychoterapeuty**
   - Dashboard panelu
   - Wizualizacja trendu dobrostanu
   - Identyfikacja zmian w poszczególnych domenach
   - Alert system (opcjonalnie)

3. **Dokumentacja techniczna**
   - API documentation
   - Architecture decision records (ADRs)
   - Deployment guide

---

### WP-PB.3 – Badanie użyteczności i wdrożenie panelu (Etap User/Use-case)
**Czas:** Miesiące 21–24 (8 tygodni, sekwencyjnie po etapie 1B)  
**Liczebność:** 120 osób z etapu 1B + 30–40 terapeutów  
**Terapeuta widzi panel:** **TAK** (od tygodnia 17 lub 21)

#### Zadania:
1. **Wdrożenie panelu w praktyce klinicznej**
   - Dystrybucja do terapeutów
   - Training na temat interpretacji wyniku
   - Obsługa techniczna (helpdesk)

2. **Zbieranie danych na temat użyteczności**
   - Wywiad z terapeutami: czy wynik jest zrozumiały?
   - Czy wynik zmienia proces terapeutyczny?
   - Czy pacjenci akceptują aplikację?
   - SUS (System Usability Scale)
   - Raport godzin wdrażania/pacjenta

3. **Użyteczność dla pacjenta (User Experience)**
   - Ilu pacjentów zgłasza problemy techniczne?
   - Jak wiele danych brakuje/zaburzonych?
   - Jak długo pacjent używa aplikację (adherence)?
   - Feedback na iterację UI

4. **Analiza wpływu na proces terapii**
   - Czy terapeuta zmienia plan terapii na podstawie panelu?
   - Czy panel wspiera komunikację pacjent-terapeuta?
   - Czy pacjent czuje się lepiej monitorowany?
   - Raport case studies

5. **Rezultat: Raport wdrożeniowy**
   - Rekomendacje dla przyszłych implementacji
   - Co się udało, co nie
   - Kryteria gotowości do fazy komercyjnej

---

### WP-PB.4 – Zarządzanie projektem i Compliance
**Czas:** Miesiące 0–24 (przez całą realizację)

#### Zadania:
1. **Regulatory & Ethics**
   - Zatwierdzenie IRB/komisji etycznej
   - RODO/GDPR compliance
   - Ubezpieczenie badaczy i uczestników
   - Procedury bezpieczeństwa (screening ryzyka, interwencja)

2. **Zarządzanie danymi**
   - Pseudonimizacja
   - Szyfrowanie
   - Bezpieczne archiwizowanie
   - Procedury usuwania (po upływie terminu)

3. **Dokumentacja i raportowanie**
   - Protokół badania (wersja ostateczna)
   - Raporty okresowe (miesieczne, kwartalne)
   - Raport końcowy

4. **Publiczna nauka i impact**
   - Artykuł naukowy w czasopiśmie peer-reviewed
   - Konferencje (prezentacje)
   - Open data/code repository
   - Webinar dla psychoterapeutów

---

## III. Mapa czasowa i zależności

```
Miesiąc:     0    4    8    12   16   20   24
             |    |    |    |    |    |    |

WP-BP.1      |◆◆◆◆|    |    |    |    |    |  Pilotaż
WP-PB.1      |◆◆◆◆◆◆◆◆|    |    |    |    |  App dev
WP-BP.2      |    |◆◆◆◆|    |    |    |    |  Opracowanie
WP-PB.2      |    |    |◆◆◆◆|    |    |    |  Integracja modelu
WP-BP.3      |    |    |◆◆◆◆|    |    |    |  Walidacja niezal.
WP-BP.4      |    |    |    |◆◆|    |    |  Prognozowanie
WP-PB.3      |    |    |    |    |◆◆◆◆|    |  Użyteczność
WP-BP.5      |◆◆◆◆◆◆◆◆◆◆◆◆◆◆|    |    |  Literature review
WP-PB.4      |◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆|    |  Compliance & mgmt
```

---

## IV. Rezultaty i deliverables

| Typ | WP | Rezultat | Format | Kiedy |
|-----|----|-----------| -------|--------|
| **Badania** | BP.1 | Raport pilotażu + procedury | PDF + GitHub | M4 |
| **Badania** | BP.2 | Model zamrożony + artykuł | Python code + PDF | M8 |
| **Badania** | BP.3 | Raport walidacji | PDF | M12 |
| **Badania** | BP.4 | Raport prognozowania | PDF | M16 |
| **Badania** | BP.5 | Literature review | PDF + citations | M16 |
| **Rozwój** | PB.1 | Aplikacja mobilna MVP | GitHub repo + TestFlight | M8 |
| **Rozwój** | PB.2 | Zintegrowany panel | GitHub repo | M12 |
| **Rozwój** | PB.3 | Raport użyteczności | PDF | M20 |
| **Rozwój** | PB.4 | Dokumentacja compliance | GitHub wiki | M24 |
| **Artykuł** | BP.2+BP.3 | Publikacja naukowa | J Med Internet Res | M18+ |

---

## V. Budżet – przybliżony podział

| Kategoria | Badania % | Rozwój % | Razem |
|-----------|-----------|----------|--------|
| **Personel badawczy** | 60% | – | 60% |
| **Personel dev** | – | 70% | 70% |
| **Infrastruktura (serwer, baza)** | – | 15% | 15% |
| **Sprzęt (opaska, telefony testowe)** | 20% | 5% | 25% |
| **Narzędzia (ML, analytics) **| 10% | 10% | 20% |
| **Rekrutacja i obciążenie kosztami** | 10% | – | 10% |
| **Publikacja i dissemination** | – | – | 5% |

---

## Podsumowanie

**Badania Przemysłowe (WP-BP):**  
Eksploracja, odkrywanie reguł, odpowiedź na pytania „Które cechy pracują? Czy opaska pomaga? Czy można prognozować?"

**Prace Rozwojowe (WP-PB):**  
Budowa aplikacji, integracja modelu, testowanie w praktyce, przygotowanie do wdrożenia komercyjnego.

Oba komponenty są **równoległy i uzupełniające się** – badania kierują rozwojem, a rozwój umożliwia badania.
