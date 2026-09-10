# Mapa prac B+R → Sekcje wniosku NCBR (SMART 3.26)

Dokument pokazuje, jak części z `podzial_prac_BR.md` mapują się na wymagane sekcje wniosku do NCBR.

---

## I. SEKCJE MERYTORYCZNE WNIOSKU

### 1. Cel projektu
**Powiązane WP:** WP-BP.1 do WP-BP.5 (badania) + WP-PB.3 (użyteczność)

**Co tam trafić:**
- Ogólne pytanie badawcze (7 pytań z protokołu)
- Zakres prac: pilotaż N=40 przez 4–6 tygodni, rozwój N=240 przez 16 tygodni, niezależna walidacja N=120 przez 16 tygodni oraz dodatkowe 8 tygodni oceny użyteczności
- Rezultat: zamrożony model + raport użyteczności
- Horyzont: 24 miesiące, 400 unikalnych uczestników

**Źródło:** `metodologia_badania.md` (sekcje I–V)

---

### 2. Problem badawczy / State of Art
**Powiązane WP:** WP-BP.5 (Literature Review)

**Co tam trafić:**
- Aktualny stan wiedzy: cyfrowe fenotypowanie, wearables, depresja
- 3–4 główne bariery (patrz: `wpis_do_wniosku_cel_innowacyjnosc.md`, sekcja 1.1)
- Luka w badaniach: brak studium porównujące smartfon-only vs smartfon+wearable w jednej logice
- Luka w zarządzaniu danymi: procedury zaślepienia, zamrażania modelu, indywidualny poziom odniesienia
- Przegląd (min. 15–25 artykułów): personalizacja, privacy, GDPR

**Zasoby:**
- Artykuły w folderze `artykuly_naukowe/`
- PubMed, ResearchGate, Google Scholar

**Źródło:** Nowy plik `literatura_state_of_art.md` (DO NAPISANIA)

---

### 3. Rodzaj prac B+R
**Powiązane WP:** WP-BP (wszystkie) + WP-PB (wszystkie)

**Co tam trafić:**
Zgodnie z wytycznymi Frascati 2015:
- ✅ **Badania przemysłowe:** WP-BP.1–BP.5 (eksploracja, odpowiadanie na pytania, nowa wiedza)
- ✅ **Prace rozwojowe:** WP-PB.1–PB.4 (budowa prototypu, integracja, testowanie, wdrażanie)

**Uzasadnienie w logice Frascati:**
- Badania: nowa wiedza (które cechy pracują, czy opaska pomaga, czy personalizacja lepsza)
- Rozwój: nowy produkt (aplikacja) + nowy proces (ciągłe monitorowanie bez interwencji terapeuty)
- Pięć cech B+R: ✅ nowatorskość, ✅ twórczość, ✅ niepewność, ✅ metodyczność, ✅ odtwarzalność

**Źródło:** `podzial_prac_BR.md` + `wpis_do_wniosku_cel_innowacyjnosc.md` (sekcja 1.1 Rodzaj prac)

---

### 4. Innowacyjność rezultatu B+R
**Powiązane WP:** WP-PB.1–PB.3 (głównie) + rezultaty WP-BP.2

**Sekcja 4.1 – Innowacja produktowa**

| Pytanie | Odpowiedź ze WP | Plik |
|---------|-----------------|------|
| **Jaki produkt?** | Aplikacja mobil. do cyfrowego fenotypowania dobrostanu (Android/iOS) z panelem dla psychoterapeuty | WP-PB.1–PB.3 |
| **Co nowego?** | 1) Zbieranie sześciu domen smartfonowych: głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja; 2) opaska u wszystkich uczestników; 3) sparowane porównanie smartfon vs smartfon + opaska; 4) wynik indywidualnie spersonalizowany i interpretowalny dla terapeuty | WP-BP.2 (rezultat), WP-PB.2 |
| **Wskaźnik 1** | Liczba zintegrowanych strumieni danych: 0 → 7 | WP-PB.1 (task 2) |
| **Wskaźnik 2** | Interpretowalny wynik (brak → tak) | WP-PB.2 (task 2) |
| **Wskaźnik 3** | Liczba analizowanych konfiguracji pomiaru: 1 → 2 (smartfon vs smartfon+wearable) | WP-BP.2 (task 3) |
| **Przewaga konkurencyjna?** | (DO NAPISANIA) Porównanie z 5–10 konkurentami | Nowy plik `analiza_konkurencji.md` |

**Sekcja 4.2 – Innowacja w procesie biznesowym**

| Pytanie | Odpowiedź ze WP | Plik |
|---------|-----------------|------|
| **Jaki proces zmienia?** | Monitorowanie pacjenta w terapii: z subiektywnych pytań do ciągłego, obiektywnego strumienia danych | WP-PB.3 |
| **Rezultat dla psychoterapeuty?** | Raport z panelu (zamiast manual. zebrania danych), wykrywanie zmian, śledzenie trendów | WP-PB.2 (task 2) |
| **Wskaźnik 1** | Czas przygotowania obrazu pacjenta: 30 min → 5 min (automatyzacja) | WP-PB.3 (task 2) |
| **Wskaźnik 2** | Złożoność danych: samoocena → sześć domen smartfonowych (głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja) oraz dane z opaski | WP-BP.2, WP-PB.1 |
| **Wpływ na zysk?** | (DO NAPISANIA) Oszczędność czasu terapeuty, lepszy wynik terapii (hipoteza) | Nowy plik `opłacalnosc_wdrazania.md` |

**Źródło:** `wpis_do_wniosku_cel_innowacyjnosc.md` (sekcja 1.2) + `podzial_prac_BR.md`

---

### 5. Metodyka badania
**Powiązane WP:** WP-BP.1–BP.4 + WP-PB.4 (compliance)

**Co tam trafić:**
- Design: prospektywny, obserwacyjny, wielomodalny
- Struktura etapów: N=40+240+120=400 unikalnych osób; faza użytkowa wykorzystuje uczestników walidacji
- Wszyscy uczestnicy noszą opaskę; porównanie smartfon vs smartfon+wearable jest sparowane na tych samych osobach i okresach
- Zaślepienie terapeuty w etapie walidacji (Key feature!)
- Zamrażanie modelu (procedure!)
- Indywidualny poziom odniesienia (personalizacja!)
- Standard referencyjny (WHO-5, WHODAS, samoocena)
- Procedury bezpieczeństwa (screening, interwencja)
- GDPR compliance (minimalizacja, szyfrowanie, pseudonimizacja)

**Miary główne:**
- Zgodność wyniku cyfrowego z wynikiem referencyjnym
- Wpływ opaski na jakość
- Wartość prognozowania (eksploracyjnie)

**Źródło:** `metodologia_badania.md` (wszystkie sekcje) + `podzial_prac_BR.md` (WP-BP.1–BP.4)

---

### 6. Zespół projektowy
**Powiązane WP:** Wszystkie WP (każdy wymaga ludzi o określonych umiejętności)

**Co tam trafić:**
- Kierownik projektu (Michał? Krzysztof?)
- Badacz główny (psychiatra/psycholog kliniczny)
- Data scientist / ML engineer (WP-BP.2)
- Programista mobilny (WP-PB.1–PB.2)
- Project manager (WP-PB.4)
- Statystyk (WP-BP.3–BP.4)
- Psycholog badawczy / QA (WP-PB.3)

**Dla każdego:**
- CV, doświadczenie, publikacje
- Rola w projekcie + % czasu
- Umiejętności: ML, mobile dev, psychiatria, GDPR, itp.

**Źródło:** Nowy plik `zespol_projektowy.md` (DO NAPISANIA) + CV zespołu

---

### 7. Zasoby i infrastruktura
**Powiązane WP:** WP-PB.1–PB.2 (dev) + WP-BP.1–BP.3 (badania)

**Co tam trafić:**
- **Infrastruktura IT:**
  - Serwery (AWS, Azure, on-premise?)
  - Baza danych (PostgreSQL, MongoDB?)
  - Narzędzia ML (Python + TensorFlow, scikit-learn?)
  - Narzędzia analityczne (R, Jupyter, Tableau?)
  
- **Sprzęt:**
  - Telefony testowe (iOS, Android)
  - Opaska wearable (Fitbit, Oura, Apple Watch – ile sztuk?)
  - Laptopy dla zespołu dev/badaczy
  
- **Licencje:**
  - GitHub, JetBrains, AWS credits
  
- **Lokalizacja:**
  - Laboratorium (adres, metraż)
  - Klinki/poradnie (dla rekrutacji pacjentów)

**Koszt szacunkowy:**
- Infrastruktura: ~10–15% budżetu
- Sprzęt: ~5–10%
- Narzędzia: ~5%

**Źródło:** Nowy plik `zasoby_infrastruktura.md` (DO NAPISANIA) + rozmowa z Kamilem

---

### 8. Harmonogram i kamienie milowe
**Powiązane WP:** Wszystkie (patrz tabela w `podzial_prac_BR.md`)

**Co tam trafić:**
- Mapa Gantta (24 miesiące)
- Kamienie milowe: koniec pilotażu, koniec 1A, koniec 1B, raport użyteczności
- Deliverables: raport pilotażu (M4), model zamrożony (M8), raport walidacji (M12), artykuł (M18), raport finalny (M24)
- Ryzyko: delay rekrutacji (mitygacja: multi-site recruitment)

**Źródło:** `podzial_prac_BR.md` (sekcja III – mapa czasowa)

---

### 9. Ryzyka i Plan zarządzania
**Powiązane WP:** Wszystkie WP + WP-PB.4 (compliance)

**Ryzyka techniczne:**
- Niska jakość danych z opasek (mitygacja: QC w pilotażu, WP-BP.1)
- Brakujące dane u pacjentów (mitygacja: redundancja, procedury w BP.1)
- Błędy implementacji aplikacji (mitygacja: testing, WP-PB.1)

**Ryzyka organizacyjne:**
- Niska rekrutacja pacjentów (mitygacja: multi-site, financial incentives)
- Rezygnacja terapeutów (mitygacja: training, support)
- Delay publikacji (mitygacja: pre-registration)

**Ryzyka regulacyjne:**
- Opóźnienie aprobaty IRB (mitygacja: early submission, WP-PB.4)
- Problemy GDPR (mitygacja: privacy by design, anonymization, WP-BP.1)

**Ryzyka finansowe:**
- Overspend (mitygacja: monitoring budżetu, contingency reserve)

**Źródło:** Nowy plik `analiza_ryzyk.md` (DO NAPISANIA)

---

### 10. Rezultaty i impakt
**Powiązane WP:** Wszystkie (szczególnie WP-BP.5 i WP-PB.3–PB.4)

**Rezultaty naukowe:**
- Publikacja w czasopiśmie peer-reviewed (J Med Internet Res, NPJ Digital Medicine)
- Open data repository (Zenodo, OSF)
- Open source code (GitHub)

**Rezultaty biznesowe:**
- Prototyp aplikacji (testowany z 30–40 terapeutami)
- Procedury i dokumentacja (możliwość replikacji)
- Potencjał do spin-off / komercjalizacji

**Impact:**
- Liczba cytowań
- Medias pokrycie
- Adopcja przez kliniczne

**Źródło:** `podzial_prac_BR.md` (sekcja IV – deliverables) + nowy plik `impact_plan.md` (DO NAPISANIA)

---

## II. TABELA MAPOWANIA WP → SEKCJE WNIOSKU

| WNIOSEK | WP zaangażowane | Plik źródłowy | Status |
|---------|-----------------|---------------|--------|
| **1. Cel projektu** | BP.1–BP.5, PB.3 | metodologia_badania.md | ✅ |
| **2. State of Art** | BP.5 | literatura_state_of_art.md | ⚠️ DO |
| **3. Rodzaj prac B+R** | BP+PB (wszystkie) | wpis_do_wniosku_cel_innowacyjnosc.md | ✅ |
| **4. Innowacyjność** | PB.1–PB.3, BP.2 | wpis_do_wniosku_cel_innowacyjnosc.md + analiza_konkurencji.md | ⚠️ CZ |
| **5. Metodyka** | BP.1–BP.4, PB.4 | metodologia_badania.md + podzial_prac_BR.md | ✅ |
| **6. Zespół** | Wszyscy | zespol_projektowy.md | ⚠️ DO |
| **7. Zasoby** | PB.1–PB.2 + BP | zasoby_infrastruktura.md | ⚠️ DO |
| **8. Harmonogram** | Wszyscy | podzial_prac_BR.md | ✅ |
| **9. Ryzyka** | Wszyscy | analiza_ryzyk.md | ⚠️ DO |
| **10. Impact** | BP.5 + PB.3–PB.4 | impact_plan.md | ⚠️ DO |

Legend: ✅ Gotowy | ⚠️ DO – do napisania | ⚠️ CZ – do uzupełnienia

---

## III. CHECKLIST DO WNIOSKU

### Faza 1: Przygotowanie treści (Tydzień 1–2)
- [ ] Naprawić `literatura_state_of_art.md` (min. 20 artykułów)
- [ ] Napisać `analiza_konkurencji.md` (5–10 konkurentów)
- [ ] Napisać `zespol_projektowy.md` (CV, role, %)
- [ ] Napisać `zasoby_infrastruktura.md` (szczegóły techniczne)
- [ ] Napisać `opłacalnosc_wdrazania.md` (rynek, scenario, revenue)
- [ ] Napisać `analiza_ryzyk.md` (12+ ryzyk + mitygacja)
- [ ] Napisać `impact_plan.md` (publikacje, dissemination)

### Faza 2: Integracja do wniosku Word (Tydzień 2–3)
- [ ] Skopiować zawartość z `.md` do `.docx` (formularz NCBR)
- [ ] Sprawdzić limity znaków dla każdej sekcji
- [ ] Dodać referencje do artykułów (bibliografię)
- [ ] Formatować tabelki, wykresy, rysunki
- [ ] Przeczytać pod kątem spójności

### Faza 3: Walidacja i dostosowanie (Tydzień 3)
- [ ] Sprawdzić zgodność z `Przewodnik kwalifikowalności wydatków`
- [ ] Sprawdzić zgodność z `Kryteria wyboru projektów`
- [ ] Przeczytać `Regulamin wyboru projektów`
- [ ] Konsultacje z NCBR (jeśli dostępne)

### Faza 4: Finalizacja (Tydzień 4)
- [ ] Ostateczna edycja lingwistyczna
- [ ] Podpisy i zatwierdzenia
- [ ] Upload do systemu NCBR

---

## IV. Pliki do stworzenia (DO LISTY)

| Plik | Odpowiedzialny | Deadline | Długość |
|------|-----------------|----------|---------|
| `literatura_state_of_art.md` | Michał | Tydzień 1 | ~2000 sł |
| `analiza_konkurencji.md` | Krzysztof | Tydzień 1 | ~1500 sł |
| `zespol_projektowy.md` | Krzysztof/Piotr K. | Tydzień 1 | ~1000 sł |
| `zasoby_infrastruktura.md` | Kamil/Krzysztof | Tydzień 1 | ~1000 sł |
| `opłacalnosc_wdrazania.md` | Kamil/Krzysztof | Tydzień 2 | ~1500 sł |
| `analiza_ryzyk.md` | Krzysztof | Tydzień 2 | ~1500 sł |
| `impact_plan.md` | Michał | Tydzień 2 | ~800 sł |

---

Podsumowanie: **7 nowych plików** niezbędnych do kompletnego wniosku NCBR.
