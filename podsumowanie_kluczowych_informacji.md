# Podsumowanie kluczowych informacji

## O czym jest projekt
Projekt dotyczy aplikacji mobilnej do pasywnego zbierania danych ze smartfona i budowy cyfrowych biomarkerów dobrostanu. Celem jest wsparcie psychoterapeutów w ocenie dobrostanu, monitorowaniu zmian w funkcjonowaniu i planowaniu pracy terapeutycznej.

## Najważniejsze sygnały
- Wzorce snu
- Aktywność fizyczna
- Mobilność / GPS
- Użycie smartfona
- Komunikacja
- Dynamika pisania
- Analiza głosu
- Tętno i HRV jako komponent opcjonalny

## Planowane badanie
Badanie ma mieć cztery etapy:
1. Analiza potrzeb z udziałem psychoterapeutów, w tym wywiady i doprecyzowanie wymagań funkcjonalnych oraz etycznych.
2. Budowa prototypu aplikacji i zbieranie danych multimodalnych w obserwacji trwającej co najmniej 12 tygodni, z równoległą walidacją praktyczną. W badaniu włączymy także opaski, aby sprawdzić, czy dane zbierane wyłącznie ze smartfonów są wystarczające, czy do uzyskania lepszej jakości oceny dobrostanu trzeba dodatkowo uwzględnić opaski.
3. Opracowanie modeli ML łączących wiele strumieni danych i generujących interpretowalny wynik dla psychoterapeuty.
4. Pilotaż praktyczny z psychoterapeutami, ocena użyteczności, trafności i wpływu na decyzje terapeutyczne.

Jedna z kluczowych hipotez badania brzmi: dane z samych smartfonów mogą być wystarczające do użytecznej predykcji, ale wariant z opaskami może poprawić trafność, stabilność lub czułość modelu.

## Wnioski z ankiety
Ankieta pokazuje wyraźne poparcie dla sygnałów związanych ze snem. W 5 odpowiedziach wzorce snu pojawiły się we wszystkich wskazaniach top 3. Wysoko oceniono też aktywność fizyczną, mobilność, samoopis, formalną ocenę dobrostanu oraz HRV i poziom kortyzolu / melatoniny.

Z odpowiedzi jakościowych wynika kilka powtarzalnych tez:
- najlepiej oceniane są parametry obiektywne i mierzalne,
- sen i rytm okołodobowy są uznawane za szczególnie czułe wskaźniki,
- warto łączyć dane behawioralne z samoopisem użytkownika,
- należy ograniczać ryzyka związane z prywatnością, kontekstem użycia i fałszywą interpretacją danych.

## Najważniejszy kierunek
Najmocniejszy sygnał z ankiety to koncentracja na śnie jako głównym biomarkerze wspierającym resztę danych. Dobrze widziane jest rozwiązanie, które pozostaje pasywne, obiektywne i wspierające psychoterapeutę w ocenie dobrostanu, a nie zastępujące ocenę specjalisty.

Badanie Liu et al. z wearable'ami może być też wzorem odniesienia do tego, jak zoperacjonalizować dane: od surowych sygnałów, przez cechy statyczne i dynamiczne, po model predykcyjny oraz walidację praktyczną.