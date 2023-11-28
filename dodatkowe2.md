### Ćwiczenie: Azure Functions - Automatyczna analiza i raportowanie danych dotyczących jakości powietrza.

### Scenariusz: 
Tworzymy system, który regularnie pobiera dane o jakości powietrza z publicznie dostępnych źródeł (np. API dostarczane przez rządowe agencje monitorujące środowisko lub niezależne organizacje zajmujące się jakością powietrza) i analizuje te dane, aby dostarczać raporty o stanie jakości powietrza w różnych lokalizacjach.

### Kroki do wykonania

1. **Znalezienie źródła danych**: Wybieramy publicznie dostępne API, które dostarcza aktualne dane o jakości powietrza. Przykładem może być API dostarczane przez Europejską Agencję Środowiska lub lokalne agencje monitorujące jakość powietrza.

2. **Tworzenie funkcji Azure**: Prosze napisać funkcję w Azure Functions, która regularnie (np. co godzinę) wywołuje wybrane API, aby pobrać najnowsze dane o jakości powietrza.

3. **Przetwarzanie danych**: Funkcja analizuje pobrane dane, wyodrębniając kluczowe wskaźniki, takie jak poziom PM2.5, PM10, ozonu, dwutlenku azotu itp., i ocenia jakość powietrza w oparciu o ustalone standardy.

4. **Generowanie raportów**: Na podstawie analizy, funkcja generuje raporty lub alerty dotyczące jakości powietrza w wybranych lokalizacjach. Raporty te mogą być wysyłane do zainteresowanych stron poprzez e-mail, SMS, czy też mogą być publikowane na stronie internetowej.

5. **Zapewnienie skalowalności**: Azure Functions automatycznie skaluje się, aby obsłużyć zwiększony ruch danych w przypadku, gdyby doszło do nagłego wzrostu zanieczyszczenia powietrza i zwiększonej potrzeby analizy danych.

6. **Monitorowanie i aktualizacja**: Należy użyć narzędzi Azure do monitorowania wydajności funkcji i wprowadzania ewentualnych aktualizacji, aby usprawnić proces analizy i raportowania.

### Uwaga:
- Można użyć innego API niż pogodowe

### Sprawozdanie i ocena
 Celem jest wykonanie ćwiczeń i napisanie sprawozdania w formie instrukcji co krok, po kroku należało wykonać aby osiąnać cel. Sprawozdanie powinno być napisane w markdown i umieszczone na serverze np github. Sprawozdanie powinno zawierać, oprócz opisu wykonanych kroków zrzuty ekranu i stanowić kompletne podsumowanie wykonanego zadania. Ćwiczenie można wykonać z użyciem intrefjesu portalu AZURE lub CLI - bardzo mile widziane jest pokazanie obydwu metod.  Ocena 5 punktów. Termin 8.12.2023