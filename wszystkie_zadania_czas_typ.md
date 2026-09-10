# 📊 Wszystkie zadania projektu – Czas i Typ

---

## BADANIA PRZEMYSŁOWE (Industrial Research)

### WP-BP.1 – Pilotaż i ustalenie procedur

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| BP.1.1 | Rekrutacja i enrolment | BP | M4–M5 | 40 uczestników; screening, zgoda, IRB/GDPR |
| BP.1.2 | Zbieranie danych pilotażowych | BP | M4–M5 | 4–6 tygodni: smartfon, opaska, samooceny i ocena specjalisty |
| BP.1.3 | Ocena jakości i kompletności danych | BP | M4–M5 | Rzetelność, braki, obciążenie i kalibracja |
| BP.1.4 | Ustalenie procedur | BP | M5 | Reguły jakości i braków dla kolejnych etapów |
| BP.1.5 | Parametry badania głównego | BP | M5 | Doprecyzowanie założeń roboczych |
| BP.1.6 | Raport pilotażu | BP | M5 | Rezultat: raport i procedury |

**Razem WP-BP.1:** M4–M5, **N=40 osób; obserwacja 4–6 tygodni**

---

### WP-BP.2 – Opracowanie modelu

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| BP.2.1 | Ekstrakcja i inżynieria cech (Features Engineering) | BP | M9–M12 | Sześć domen smartfonowych: głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja; dodatkowo dane z opaski |
| BP.2.2 | Opracowanie indywidualnego poziomu odniesienia | BP | M9–M12 | Algorytm, testowanie wariantów |
| BP.2.3 | Budowa modeli predykcyjnych (4 modele) | BP | M9–M12 | Baseline + populacyjny + indywidualny + hybrydowy |
| BP.2.4 | Dobór cech (Feature Selection) | BP | M9–M12 | Które domeny wnoszą wartość |
| BP.2.5 | Sparowane porównanie modeli smartfon vs smartfon + opaska | BP | M9–M11 | Czy dane opaski poprawiają wynik na tych samych osobach i okresach |
| BP.2.6 | Standaryzacja wyniku modelu | BP | M9–M12 | Łączenie WHO-5, WHODAS, EMA i PHQ-9 |
| BP.2.7 | Eksperymenty z metodami przetwarzania | BP | M9–M12 | Imputacja, normalizacja, okna czasowe |
| BP.2.8 | Zamrożenie modelu i dokumentacja | BP | M12 | Kod, definicje cech, reguły jakości i progi |

**Razem WP-BP.2:** akwizycja M6–M11, modelowanie M9–M12, **N=240 osób; obserwacja 16 tygodni**, **Rezultat: zamrożony model**

---

### WP-BP.3 – Niezależna walidacja modelu

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| BP.3.1 | Wdrożenie zamrożonego modelu (bez zmian!) | BP | M14–M20 (16 tyg.) | Kod, cechy, progi – wszystko zamrożone |
| BP.3.2 | Zbieranie danych niezależnych | BP | M14–M20 (16 tyg.) | 120 nowych osób, nowi terapeuci; wszyscy noszą opaskę |
| BP.3.3 | Ewaluacja jakości na danych walidacyjnych | BP | M20–M21 | MAE, korelacja, stabilność w podgrupach |
| BP.3.4 | Analiza błędów i wyjątków | BP | M20–M21 | Które osoby źle przewidywane i dlaczego |
| BP.3.5 | Raport walidacji niezależnej | BP | M21 | Trafność zamrożonego modelu i wartość opaski |

**Razem WP-BP.3:** M14–M21, **N=120 nowych osób; obserwacja 16 tygodni**, **TERAPEUTA ZAŚLEPIONY**

---

### WP-BP.4 – Badanie prognozowania (eksploracyjne)

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| BP.4.1 | Sformułowanie problemu prognozowania | BP | M9–M10 | Definiowanie pogorszenia i okna do 14 dni |
| BP.4.2 | Inżynieria cech czasowych | BP | M10–M12 | Trendy, zmienność i punkty przegięcia |
| BP.4.3 | Budowa modelu prognostycznego | BP | M11–M13 | Analiza eksploracyjna na danych rozwojowych |
| BP.4.4 | Metryki prognozowania | BP | M21–M23 | Czułość, PPV, fałszywe alarmy i czas wyprzedzenia |
| BP.4.5 | Raport możliwości prognozowania | BP | M24 | Status eksploracyjny; wynik nie warunkuje sukcesu projektu |

**Razem WP-BP.4:** opracowanie M9–M13, ocena M21–M24, **Status: eksploracyjny**

---

### WP-BP.5 – Literature Review i State-of-Art

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| BP.5.1 | Przegląd cyfrowego fenotypowania | BP | M0–M16 (18 mies.) | Smartfony + wearables w psychiatrii |
| BP.5.2 | Przegląd modelowania dobrostanu | BP | M0–M16 (18 mies.) | WHO-5, WHODAS, profili idiographic |
| BP.5.3 | Przegląd ochrony prywatności GDPR | BP | M0–M16 (18 mies.) | Best practices, minimalizacja danych |

**Razem WP-BP.5:** M0–M16 (równoległ. z całym projektem), **min. 20–25 artykułów**

---

## ⏱️ PODSUMOWANIE BADANIA PRZEMYSŁOWEGO

| WP | Czas | N osób | Status terapeuta | Cel |
|----|------|--------|------------------|-----|
| **BP.1** | M0–M4 | 40 | Nie widzi | Feasibility, procedury |
| **BP.2** | M6–M11 | 240 | Nie widzi | Opracowanie modelu → **ZAMRAŻANIE** |
| **BP.3** | M14–M20 | 120 (nowe) | **Zaślepiony** | Niezależna walidacja; 16 tygodni obserwacji |
| **BP.4** | M21–M24 | 120 (z BP.3) | Nie widzi | Prognozowanie (eksploracyjne) |
| **BP.5** | M0–M16 | – | – | Literature review |

**Razem:** M1–M24, **400 unikalnych osób**, **Rezultat: raport pilotażu, zamrożony model, raport walidacji i raport użyteczności**

---

---

## PRACE ROZWOJOWE (Development Activities)

### WP-PB.1 – Rozwój i integracja aplikacji mobilnej

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| PB.1.1 | Architektura systemu (backend + frontend) | PB | M0–M2 (6–8 tyg.) | Backend, Android/iOS, security |
| PB.1.2 | Moduł aktywności (accelerometr, kroki) | PB | M1–M3 (8 tyg.) | Ekstrakcja cech fizjologicznych |
| PB.1.3 | Moduł mobilności (GPS + cechy syntetyczne) | PB | M1–M3 (8 tyg.) | Bez dokładnych lokalizacji (GDPR) |
| PB.1.4 | Moduł użycia telefonu (ekran, odblokowania, aplikacje) | PB | M1–M3 (8 tyg.) | Bez treści, tylko metadane |
| PB.1.5 | Moduł komunikacji (SMS/rozmowy – bez treści) | PB | M1–M3 (8 tyg.) | Liczba i tempo |
| PB.1.6 | Moduł snu (ze smartfona lub opaski) | PB | M1–M3 (8 tyg.) | Integracja z OS lub wearable API |
| PB.1.7 | Moduł analizy głosu | PB | M2–M4 (6–8 tyg.) | Tempo mowy i zmienność; ekstrakcja cech bez zapisu nagrania |
| PB.1.8 | Integracja z opaskami wearable (Fitbit, Oura, Apple Watch) | PB | M2–M4 (10 tyg.) | API, synchronizacja, obsługa błędów |
| PB.1.9 | Moduł aktywnych samoocen (WHO-5, WHODAS, pytania) | PB | M2–M4 (8 tyg.) | Interface, notyfikacje, offline |
| PB.1.10 | Backend analityczny (placeholder do modelu) | PB | M3–M4 (4–6 tyg.) | Storage, logi audytu, HIPAA/GDPR |
| PB.1.11 | Unit testy, integracyjne testy | PB | M3–M5 (6–8 tyg.) | Coverage >80% |
| PB.1.12 | Testy użytkownika (usability) z 10–20 terapeutami | PB | M4–M5 (4–6 tyg.) | Feedback, iteracja UI |

**Razem WP-PB.1:** M0–M8 (równoległ. z BP.1 i BP.2), **Rezultat: MVP aplikacji** (TestFlight/Beta)

---

### WP-PB.2 – Integracja modelu w aplikacji

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| PB.2.1 | Port modelu do production-ready kodu | PB | M8–M10 (8–10 tyg.) | Python/R → JavaScript/Kotlin/Swift |
| PB.2.2 | Optymalizacja wydajności i edge cases | PB | M9–M10 (6–8 tyg.) | Latencja, pamięć, offline mode |
| PB.2.3 | Dashboard panelu dla psychoterapeuty | PB | M9–M11 (8–10 tyg.) | Wizualizacja trendu, zmian w domenach |
| PB.2.4 | Alert system (opcjonalny) | PB | M10–M11 (6–8 tyg.) | Notyfikacje o pogorszeniu |
| PB.2.5 | API documentation | PB | M11 (2–4 tyg.) | RESTful, OpenAPI spec |
| PB.2.6 | Architecture Decision Records (ADRs) | PB | M11 (2–4 tyg.) | Dokumentacja architektoniczna |
| PB.2.7 | Deployment guide + infrastruktura produkcyjna | PB | M11–M12 (4–6 tyg.) | Docker, CI/CD, monitorowanie |

**Razem WP-PB.2:** M8–M12 (4–5 miesięcy, sekwencyjnie po BP.2), **Rezultat: Panel gotowy do wdrożenia**

---

### WP-PB.3 – Badanie użyteczności i wdrożenie panelu

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| PB.3.1 | Training terapeutów (interpretacja wyniku, UI) | PB | M16–M17 (4 tyg.) | Przed wdrożeniem panelu |
| PB.3.2 | Dystrybucja do 30–40 terapeutów | PB | M17 (2 tyg.) | Wdrożenie w klinikach |
| PB.3.3 | Obsługa techniczna (helpdesk, wsparcie) | PB | M17–M24 (8 mies.) | Monitoring, bug fixes |
| PB.3.4 | Zbieranie danych na temat użyteczności | PB | M17–M24 (8 mies.) | Wywiady, SUS, ocena trafności |
| PB.3.5 | Analiza zmiany procesu terapeutycznego | PB | M20–M23 (4–6 mies.) | Czy terapeuta zmienia plan, komunikacja |
| PB.3.6 | Analiza adhes użytkownika (adherence pacjenta) | PB | M17–M24 (8 mies.) | Jak długo pacjent używa app, czemu odpadają |
| PB.3.7 | Feedback na iteracje UI/UX | PB | M17–M24 (8 mies.) | Ciągła poprawa interfejsu |
| PB.3.8 | Raport użyteczności i wdrożenia | PB | M24 (2–4 tyg.) | Rekomendacje, case studies |

**Razem WP-PB.3:** M16–M24 (8 miesięcy, sekwencyjnie po BP.3), **N=120 osób + 30–40 terapeutów**, **TERAPEUTA WIDZI PANEL**

---

### WP-PB.4 – Zarządzanie projektem, Compliance, Publikacja

| Lp. | Zadanie | Typ | Czas | Uwagi |
|-----|---------|-----|------|-------|
| PB.4.1 | Zatwierdzenie IRB/komisji etycznej | PB | M0–M2 (2–4 tyg.) | Przed startem pilotażu |
| PB.4.2 | GDPR/RODO compliance | PB | M0–M24 (całe 24 mies.) | Pseudonimizacja, szyfrowanie, procedury |
| PB.4.3 | Ubezpieczenie i procedury bezpieczeństwa | PB | M0–M2 (2–4 tyg.) | Screening ryzyka, interwencja |
| PB.4.4 | Zarządzanie danymi (storage, archiwizacja) | PB | M0–M24 (całe 24 mies.) | Bezpieczne przechowywanie, usuwanie |
| PB.4.5 | Raportowanie okresowe (miesieczne, kwartalne) | PB | M0–M24 (całe 24 mies.) | Monitorowanie postępu |
| PB.4.6 | Artykuł naukowy (draft) | PB | M12–M18 (6 mies.) | Po zebraniu danych walidacyjnych |
| PB.4.7 | Submission do czasopisma (J Med Internet Res lub NPJ) | PB | M18–M20 (2–4 tyg.) | Peer review |
| PB.4.8 | Open data repository (Zenodo, OSF) | PB | M20–M24 (4–6 mies.) | Po publikacji |
| PB.4.9 | Open source code na GitHub | PB | M20–M24 (4–6 mies.) | Model + dokumentacja |
| PB.4.10 | Konferencje i prezentacje | PB | M18–M24 (6 mies.) | Dissemination |
| PB.4.11 | Webinar dla psychoterapeutów | PB | M24 (1–2 tyg.) | Impact, adoption |

**Razem WP-PB.4:** M0–M24 (równoległ. z całym projektem), **Rezultat: Publikacja + kod + data + media**

---

## ⏱️ PODSUMOWANIE PRAC ROZWOJOWYCH

| WP | Czas | Co się pisze | Kiedy gotowe |
|----|------|-------------|--------------|
| **PB.1** | M0–M8 | Aplikacja mobilna MVP | Koniec M8 |
| **PB.2** | M8–M12 | Integracja modelu + panel | Koniec M12 |
| **PB.3** | M16–M24 | Testowanie + użyteczność | Koniec M24 |
| **PB.4** | M0–M24 | Zarządzanie + publikacja | Koniec M24 |

---

## 📊 MAPA CZASOWA – WSZYSTKO NA JEDNYM WIDOKU

```
Miesiąc:  0  1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24
         |--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|

BADANIA PRZEMYSŁOWE:
BP.1     ◆◆◆◆                                          Pilotaż (40 osób)
BP.2           ◆◆◆◆◆◆                                 Opracowanie (240 osób) + ZAMRAŻANIE
BP.3                    ◆◆◆◆◆◆                        Walidacja (120 osób) ZAŚLEPIENIE
BP.4                             ◆◆◆◆◆◆              Prognozowanie (eksploracyjny)
BP.5     ◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆                           Literature review (całe 16 mies)

PRACE ROZWOJOWE:
PB.1     ◆◆◆◆◆◆◆◆                                      App dev + API (8 mies)
PB.2                    ◆◆◆◆◆                         Integracja modelu (5 mies)
PB.3                                    ◆◆◆◆◆◆◆◆     Użyteczność + panel (8 mies)
PB.4     ◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆◆                 Compliance + publikacja (24 mies)

KLUCZOWE KAMIENIE MILOWE:
         ▼ IRB        ▼ Model      ▼ Walidacja      ▼ Panel          ▼ Publikacja
        M0–M2        M8            M12             M16–M24           M18–M20
```

---

## 📋 SZYBKI PRZEGLĄD CZASU

| Kategoria | Łączny czas | Liczba WP | Zadań razem |
|-----------|------------|-----------|------------|
| **Badania Przemysłowe** | 16 miesięcy (M0–M16) | 5 WP | ~30 zadań |
| **Prace Rozwojowe** | 24 miesiące (M0–M24) | 4 WP | ~35 zadań |
| **RAZEM** | **24 miesiące** | **9 WP** | **~65 zadań** |

---

## 💡 Czym się różnią: BADANIA vs PRACE ROZWOJOWE

| Aspekt | Badania Przemysłowe (BP) | Prace Rozwojowe (PB) |
|--------|--------------------------|----------------------|
| **Cel** | Odpowiedzieć na pytania, odkryć nową wiedzę | Zbudować produkt, który działa |
| **Output** | Artykuł naukowy, raporty, procedury | Kod, aplikacja, panel, dokumentacja |
| **Zespół** | Statystyk, badacz, naukowiec | Programiści, engineers, UX designer |
| **Niepewność** | Wysoka – nie wiemy co się okaże | Niska – wiemy jaki produkt chcemy |
| **BP.2 "zamrażanie"** | ✅ **OBOWIĄZKOWE** – bez tego brak wiarygodności | – |
| **Przykład zadania BP** | "Która z sześciu domen smartfonowych najlepiej przewiduje?" | – |
| **Przykład zadania PB** | – | "Zaprogramować dashboard panelu" |

---

**Gotowy do następnego kroku?** Chcesz wiedzieć, kto powinien robić które zadania?
