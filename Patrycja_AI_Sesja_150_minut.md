# PATRYCJA.AI
## Spotkanie 2: od analizy stanowiska do projektowania usprawnień

**Scenariusz warsztatu: 150 minut (2,5 godziny)**  
**Dla:** Patrycji, praktykantki w Termoinstal, absolwentki psychologii i studentki „AI w biznesie”  
**Forma:** dwie praktyczne misje z ChatGPT i osobistym mentorem AI  
**Prowadzący:** dr Marcin Albiniak

> **Idea spotkania:** Nie uczymy się przycisków ChatGPT. Uczymy się rozumieć pracę człowieka, formułować problemy biznesowe i zamieniać je w prototypy narzędzi. Decyzje merytoryczne podejmuje Patrycja, a AI pomaga je sprawdzić i zrealizować.

## Plan spotkania

| Czas | Zadanie | Rezultat |
|---|---|---|
| **0–90 min** | **Misja 1. Job & Competency Explorer**: symulowany wywiad, mapa stanowiska i pierwszy prototyp | Mapa obowiązków i kompetencji + działająca aplikacja HTML |
| **90–150 min** | **Misja 2. Process Redesign Lab**: od rozpoznania procesu kalkulacji i ofertowania do modelu „przed i po” | Mapa procesu + drugi prototyp + krótkie rekomendacje |

### Przygotowanie przed startem (2–3 min)

- Otwórz prywatny projekt ChatGPT Patrycji i przywołaj mentora po wybranym imieniu. Jeżeli profil lub instrukcja mentora nie są dostępne, dołącz zatwierdzony profil i użyj zapisanej instrukcji.
- Jeśli masz raport kadrowy Patrycji, możesz odnieść się do **jego wniosków**, ale nie kopiuj do AI poufnych danych kadrowych ani danych osób trzecich.
- Prototypy budujemy na **danych fikcyjnych**. Nie podłączamy się do systemów firmowych, nie wykonujemy importów ani nie generujemy realnych ofert.

---

# MISJA 1 (90 min)
## Job & Competency Explorer: analiza stanowiska → interaktywne narzędzie

**Cel:** wykorzystać psychologię pracy do zrozumienia obowiązków, kompetencji, punktów przeciążenia i szans na usprawnienia.

### Przebieg

| Minuty | Krok | Co robi Patrycja |
|---|---|---|
| **0–10** | Aktywacja mentora | Przywołuje go po imieniu i wskazuje swój cel |
| **10–30** | Wywiad symulacyjny | Sama pyta fikcyjną pracownicę działu kadr |
| **30–50** | Analiza | Porządkuje obowiązki, kompetencje, powtarzalność i obciążenie poznawcze |
| **50–80** | Prototyp | Zatwierdza interfejs i tworzy działający plik HTML |
| **80–90** | Krytyka | Broni użyteczności narzędzia i ustala 3 ulepszenia |

### Prompt nr 1: wklej do ChatGPT

> **PATRYCJA.AI | MISJA 1: JOB & COMPETENCY EXPLORER**  
> Przywołuję mojego mentora AI. Jeżeli masz dostęp do zatwierdzonego profilu i instrukcji mentora w tym projekcie, wykorzystaj je. Jeśli nie, poproś o brakujące materiały.  
> Mam licencjat z psychologii, studiuję AI w biznesie i uczę się analizować stanowiska pracy w Termoinstal. Chcę samodzielnie odkrywać problemy, a nie dostawać gotowe odpowiedzi.  
> **Faza A: symulowany wywiad.** Wciel się w fikcyjną pracownicę działu kadr średniej firmy instalacyjnej. Odpowiadaj realistycznie, ale nie ujawniaj wszystkich trudności od razu. To ja zadaję pytania. Kiedy napiszę „koniec wywiadu”, przeanalizuj, o co nie zapytałam, w szczególności o kompetencje, decyzje, powtarzalność, błędy i obciążenie poznawcze.  
> **Faza B: model stanowiska.** Wspólnie przygotujmy mapę zadań i kompetencji, listę czynności powtarzalnych, źródła przerw w pracy i potencjalne usprawnienia. Rozróżniaj fakty, założenia i elementy symulacji. Nie oceniaj osobowości ani wartości pracownika.  
> **Faza C: działający prototyp.** Zaproponuj prostą aplikację „Job & Competency Explorer”: wybór stanowiska, lista zadań, mapa kompetencji, oznaczanie czynności powtarzalnych, dodawanie obserwacji i wizualne podsumowanie. Najpierw pokaż szkic funkcji i poproś o moją akceptację. Potem przygotuj pojedynczy samodzielny plik HTML z CSS i JavaScript, bez zewnętrznych bibliotek, do uruchomienia lokalnie. Używaj wyłącznie fikcyjnych danych.  
> **Faza D: krytyczne spojrzenie.** Zagraj wymagającego menedżera i zadaj mi pięć pytań o sens narzędzia, ograniczenia i dalszą weryfikację. Na końcu pomóż mi wskazać trzy ulepszenia.  
> **Zasady:** jedno pytanie naraz, bez automatycznego przechodzenia do kolejnej fazy, bez danych poufnych. Nie wykonuj wszystkiego za mnie.  
> **Zacznij teraz od fazy A i przyjmij rolę fikcyjnej pracownicy.**

**Warunek sukcesu misji 1:** Patrycja potrafi opowiedzieć, jakie obserwacje z wywiadu stały się funkcjami aplikacji i czego nadal nie wie o rzeczywistym stanowisku.

---

# MISJA 2 (60 min)
## Process Redesign Lab: od kalkulacji i ofertowania do prototypu procesu

**Nowy, odrębny problem:** tym razem nie analizujemy stanowiska, lecz **przepływ informacji i decyzji**. Na przykładzie procesu przygotowania oferty w firmie instalacyjnej Patrycja zbuduje mapę „jak jest” (AS-IS), zaprojektuje „jak mogłoby być” (TO-BE) i stworzy miniaplikację do obsługi etapów.

**Dlaczego to dobre drugie zadanie?** Pozwoli porównać dwa sposoby analizy: *człowiek i kompetencje* kontra *proces i decyzje*. Nie wymaga cen, norm technicznych ani znajomości wewnętrznych systemów Termoinstal.

### Przebieg

| Minuty warsztatu | Krok | Co ma powstać |
|---|---|---|
| **90–100** | Ustalenie celu i granic procesu | Jednozdaniowy problem + lista danych wejściowych |
| **100–115** | Symulowany proces AS-IS | 6–8 kroków od zapytania klienta do zatwierdzenia oferty |
| **115–130** | Projekt TO-BE | Punkty kontrolne, brakujące informacje, rola człowieka i AI |
| **130–145** | Prototyp interaktywny | „Offer Flow Navigator” w pojedynczym pliku HTML |
| **145–150** | Mini-pitch | 60 sekund: problem, zmiana, ograniczenia, dalszy test |

### Prompt nr 2: wklej do ChatGPT po zakończeniu misji 1

> **PATRYCJA.AI | MISJA 2: PROCESS REDESIGN LAB**  
> Zmieniamy perspektywę: z analizy człowieka i kompetencji przechodzimy do analizy procesu biznesowego. Chcę zrozumieć, jak w firmie instalacyjnej mogłoby wyglądać przygotowanie kalkulacji i oferty dla klienta oraz jak AI mogłoby pomóc, nie podejmując samodzielnie decyzji handlowych ani technicznych.  
> **Krok 1: zakres.** Pomóż mi sformułować jednozdaniowy cel analizy. Przyjmijmy fikcyjny scenariusz: przychodzi zapytanie klienta dotyczące instalacji; firma musi zebrać wymagania, sprawdzić kompletność danych, przygotować kalkulację, zweryfikować ją i przesłać ofertę. Nie twierdź, że dokładnie tak działa Termoinstal.  
> **Krok 2: AS-IS.** Zadając mi pytania po jednym, pomóż stworzyć przykładową mapę procesu w 6–8 krokach. Dla każdego kroku oznacz: wejście, działanie, osobę/rolę, decyzję, wyjście i potencjalny problem. Zidentyfikuj minimum trzy miejsca, gdzie brakuje danych lub pojawia się ryzyko pomyłki.  
> **Krok 3: TO-BE.** Wspólnie zaprojektujmy prostszą wersję procesu. Oddziel automatyzację regułową od zastosowań AI. Zaproponuj wsparcie AI np. przy tworzeniu listy brakujących informacji, porządkowaniu zapytań i redagowaniu szkicu odpowiedzi. Kalkulacja techniczna, ceny, warunki umowy i akceptacja oferty muszą pozostawać pod nadzorem uprawnionej osoby.  
> **Krok 4: aplikacja.** Zaproponuj miniaplikację „Offer Flow Navigator”. Ma zawierać: kartę fikcyjnego zapytania, listę wymagań, widoczne braki danych, etapy procesu, checklistę kontroli jakości, przyciski zmiany statusu oraz podsumowanie, co wymaga zatwierdzenia przez człowieka. Najpierw uzgodnij ze mną funkcje. Następnie napisz jeden działający plik HTML z CSS i JavaScript bez zewnętrznych bibliotek, na danych syntetycznych, bez serwera i bez integracji z firmowymi systemami.  
> **Krok 5: prezentacja.** Pomóż mi ułożyć 60-sekundową wypowiedź: co zauważyłam, co proponuję, czego jeszcze nie wiemy i co należałoby zweryfikować w prawdziwej firmie. Potem zadaj jedno trudne pytanie zarządu.  
> **Zasady:** pracuj ze mną etapami; jedno pytanie naraz; nie dopowiadaj nieznanych procesów Termoinstal; nie wymyślaj cen, rabatów ani wymagań prawnych; odróżniaj symulację od danych rzeczywistych; żadnych poufnych danych pracowników i klientów.  
> **Zacznij od kroku 1.**

### Bonus, jeśli powstanie 10 minut zapasu

Poproś mentora: **„Porównaj obie aplikacje. Która opisuje człowieka i kompetencje, a która przepływ decyzji? Co powinniśmy zmierzyć, zanim pokażemy je komuś w Termoinstal?”**

---

# Finał spotkania: cztery rezultaty

1. **Mapa stanowiska i kompetencji** na przykładzie fikcyjnego wywiadu.
2. **Job & Competency Explorer**: pierwszy działający prototyp aplikacji.
3. **Mapa procesu AS-IS / TO-BE** dla przykładowego ofertowania.
4. **Offer Flow Navigator**: drugi prototyp i krótka prezentacja rekomendacji.

### Pytania podsumowujące dla Patrycji

- Co było trudniejsze: zrozumienie pracy człowieka czy zaprojektowanie przepływu decyzji?
- Jakie decyzje potrafi przygotować AI, a które powinien zatwierdzać człowiek?
- Czego musiałabyś dowiedzieć się od rzeczywistych pracowników, aby te prototypy były użyteczne?

**Zasada prowadzącego:** niech Patrycja sama dokonuje wyborów i broni swoich propozycji. Efektem mają być jej własne rozumowanie i dwa działające artefakty, a nie tylko imponujący pokaz ChatGPT.
