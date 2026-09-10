# MentaliCare — połączony protokół metodologiczny

## Założenie

Badanie łączy pomiar objawów depresyjnych, dobrostanu, codziennego funkcjonowania i bieżących samoocen z multimodalnymi danymi ze smartfona i opaski. Jego celem jest opracowanie interpretowalnego modelu monitorującego zmiany u konkretnej osoby oraz sprawdzenie, czy dane z opaski zwiększają wartość modelu opartego na smartfonie.

PHQ-9 jest główną miarą nasilenia objawów depresyjnych. WHO-5, WHODAS 2.0, EMA i ocena specjalisty są odrębnymi wymiarami profilu uczestnika oraz źródłami pomocniczej walidacji. Badanie nie zastępuje diagnozy klinicznej.

## Projekt badania

| Etap | N | Czas obserwacji | Rezultat |
|---|---:|---:|---|
| Pilotaż | 40 | 4–6 tygodni | Potwierdzenie wykonalności, jakości danych i reguł przetwarzania |
| Kohorta rozwojowa | 240 | 16 tygodni | Opracowanie modeli i ich zamrożenie |
| Niezależna walidacja | 120 nowych osób | 16 tygodni | Potwierdzenie trafności bez strojenia modelu |
| Faza użytkowa | Kontynuujący z walidacji | Dodatkowe 8 tygodni | Ocena użyteczności panelu |

Łączna rekrutacja wynosi 400 unikalnych uczestników. Każdy uczestnik korzysta ze smartfona i nosi opaskę. W badaniu głównym porównuje się model „smartfon” i model „smartfon + opaska” na tych samych osobach i okresach. Projekt jest roboczo rozpisany na 24 miesiące.

## Dane i minimalizacja danych

Sześć domen smartfonowych to: **głos, mobilność, używanie telefonu, dynamika pisania, sen i rytm dnia oraz komunikacja**. Zbierane są wyłącznie cechy potrzebne do analizy:

- głos: cechy akustyczne i prozodyczne, bez zapisu nagrań i transkrypcji;
- mobilność: cechy pochodne GPS, bez interpretacji znaczenia odwiedzanych miejsc;
- używanie telefonu: sesje, odblokowania i rytm dobowy;
- dynamika pisania: tempo, pauzy i korekty, bez tekstu;
- sen i rytm dnia: nocna nieaktywność i regularność;
- komunikacja: liczba oraz rytm zdarzeń, bez treści, nagrań i danych rozmówców.

Akcelerometry telefonu i opaski dostarczają danych o ruchu. W zależności od urządzenia opaska dostarcza też danych o śnie, tętnie, PRV/HRV, EDA i temperaturze skóry. EDA jest wykorzystywana tylko po potwierdzeniu dostępności i jakości tego sygnału.

## Hipotezy

1. Dane ze smartfona poprawiają oszacowanie PHQ-9 względem modelu odniesienia.
2. Połączenie sześciu domen smartfonowych poprawia wynik względem pojedynczej domeny.
3. Personalizacja względem indywidualnego profilu poprawia wynik względem modelu populacyjnego.
4. Cechy czasowe poprawiają wynik względem podsumowań statystycznych.
5. Dodanie opaski poprawia model „smartfon” w porównaniu sparowanym.
6. Panel jest zrozumiały i użyteczny dla specjalistów.
7. Prognozowanie pogorszenia pozostaje analizą eksploracyjną i nie warunkuje sukcesu projektu.

## Opracowanie i walidacja modelu

W kohorcie rozwojowej porównuje się model oparty na poprzednim PHQ-9, model odniesienia z danymi podstawowymi, model populacyjny, spersonalizowany i hybrydowy. Wszystkie decyzje dotyczące cech, braków danych, jakości, personalizacji i progów są podejmowane przed niezależną walidacją. Następnie model zostaje zamrożony.

W kohorcie walidacyjnej używa się nowych osób i innych terapeutów. Terapeuta i uczestnik nie widzą wyniku cyfrowego w części potwierdzającej trafność. Raport obejmuje MAE, korelację, ocenę zmian, kompletność techniczną, stabilność w podgrupach oraz wartość dodatkową opaski.

Interwencje i zdarzenia kontekstowe — w tym zmiany leków, choroby, podróże, praca zmianowa, zmiany terapii i urządzeń — są dokumentowane i uwzględniane przy interpretacji prognoz. W prognozowaniu wykorzystywane są wyłącznie dane dostępne przed ocenianym momentem.

## Status

Liczebności, progi, szczegółowy harmonogram i wybór opaski pozostają założeniami roboczymi do dalszego uzgodnienia. Pełny opis etapów znajduje się w [metodologia_etapami.md](metodologia_etapami.md).
