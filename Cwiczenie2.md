### Ćwiczenie: Integracja z Azure Bing Search Service

#### Cel:
Celem tego ćwiczenia jest zapoznanie się z usługą Azure Bing Search i praktyczne zastosowanie jej w aplikacji. Będziesz tworzyć aplikację, która wykorzystuje Bing Search API do przeprowadzania złożonych zapytań wyszukiwania i analizy wyników.

 
#### Krok 1: Utworzenie konta w Azure

Zainstalowane środowisko programistyczne obsługujące C# (np. Visual Studio).
---

#### Krok 2: Utworzenie zasobu Azure Cognitive Services

##### a. Tworzenie zasobu
1. Na pulpicie nawigacyjnym portalu Azure wybierz „+ Utwórz zasób”.
2. Wyszukaj „Cognitive Services” i wybierz.
3. Kliknij „Utwórz”.

##### b. Konfiguracja projektu
1. Wybierz lub utwórz grupę zasobów.
2. Wpisz nazwę dla zasobu Cognitive Services.
3. Wybierz lokalizację i plan cenowy.

---

#### Krok 3: Konfiguracja Bing Search w Azure Cognitive Services

1. Po utworzeniu zasobu Cognitive Services, przejdź do jego przeglądu.
2. Znajdź i skopiuj klucz dostępu oraz punkt końcowy.

---

#### Krok 4: Tworzenie aplikacji

1. Stwórz projekt aplikacji w C# w wybranym środowisku programistycznym.
2. Dodaj referencje do Azure Cognitive Services SDK.
3. Skonfiguruj aplikację, aby używała klucza dostępu i punktu końcowego Bing Search API.

---

#### Krok 5: Implementacja funkcji wyszukiwania

1. Dodaj funkcje do wysyłania zapytań do Bing Search API i odbierania wyników.
2. Zaimplementuj logikę przetwarzania i wyświetlania wyników wyszukiwania.
3. Możesz dodać różne rodzaje wyszukiwania (np. ogólne, obrazy, wiadomości).

---

#### Krok 6: Testowanie i debugowanie

1. Przetestuj aplikację, wykonując różne zapytania.
2. Sprawdź poprawność działania i dokonaj ewentualnych korekt.

---

#### Krok 7: Dodatkowe funkcjonalności 

1. Rozszerz aplikację o dodatkowe funkcjonalności, np. filtrowanie wyników.
2. Zaimplementuj interfejs użytkownika, który ułatwi korzystanie z aplikacji.


Na podstawie Twojego poprzedniego przykładu, stworzyłem ćwiczenie skupiające się na usłudze Azure Speech Service, która jest częścią Azure Cognitive Services. Azure Speech Service zapewnia zaawansowane możliwości rozpoznawania mowy, konwersji tekstu na mowę (TTS) i tłumaczenia mowy. Oto przykład ćwiczenia:


### Ćwiczenie: Praca z Azure Speech Service

#### Cel:
Celem tego ćwiczenia jest zaznajomienie się z Azure Speech Service oraz praktyczne wykorzystanie tej usługi do rozpoznawania mowy, konwersji tekstu na mowę i tłumaczenia mowy. Będziesz tworzyć aplikację, która wykorzystuje Speech Service API do przeprowadzania tych operacji.

 

#### Krok 1 i 2: Utworzenie zasobu Azure Speech Service

##### a. Tworzenie zasobu
1. Na pulpicie nawigacyjnym portalu Azure wybierz „+ Utwórz zasób”.
2. Wyszukaj „Speech Service” i wybierz.
3. Kliknij „Utwórz”.

##### b. Konfiguracja projektu
1. Wybierz lub utwórz grupę zasobów.
2. Wpisz nazwę dla zasobu Speech Service.
3. Wybierz lokalizację i plan cenowy.

---

#### Krok 3: Konfiguracja Speech Service w Azure

1. Po utworzeniu zasobu Speech Service, przejdź do jego przeglądu.
2. Znajdź i skopiuj klucz dostępu oraz punkt końcowy.

---

#### Krok 4: Tworzenie aplikacji

1. Stwórz projekt aplikacji w C# w wybranym środowisku programistycznym.
2. Dodaj referencje do Azure Speech SDK.
3. Skonfiguruj aplikację, aby używała klucza dostępu i punktu końcowego Speech Service API.

---

#### Krok 5: Implementacja funkcji rozpoznawania mowy

1. Dodaj funkcje do rozpoznawania mowy za pomocą mikrofonu lub plików dźwiękowych.
2. Implementuj przetwarzanie wyników i wyświetlanie rozpoznanego tekstu.

---

#### Krok 6: Implementacja konwersji tekstu na mowę

1. Zintegruj funkcję TTS (Text-to-Speech), aby aplikacja mogła przekształcać tekst w mowę.
2. Dostosuj różne parametry głosu, takie jak język, płeć, szybkość mówienia.

---

#### Krok 7: Dodatkowe funkcjonalności (opcjonalnie)

1. Rozszerz aplikację o tłumaczenie mowy na inny język w czasie rzeczywistym.
2. Dodaj funkcje interaktywne, takie jak odpowiadanie głosowo na komendy użytkownika.

---

### Sprawozdanie i ocena
Podobnie jak wcześniej, sprawozdanie powinno zawierać dokładny opis wykonanych kroków, zrzuty ekranu, oraz wszelkie inne informacje potrzebne do zrozumienia projektu. Sprawozdanie powinno być przygotowane w formacie markdown i umieszczone na platformie takiej jak GitHub. Oczekuje się zarówno wykorzystania interfejsu portalu Azure, jak i Azure CLI. Ocena będzie opierać się na kompletności wykonania zadania, poprawności implementacji i jakości dokumentacji. Termin: 17.11.2023.


Z przyjemnością przygotowuję dla Ciebie kolejne ćwiczenie, tym razem koncentrując się na usłudze Azure Form Recognizer, która jest częścią Azure Cognitive Services. Azure Form Recognizer wykorzystuje zaawansowane techniki uczenia maszynowego do analizy formularzy i dokumentów, automatycznie wydobywając z nich kluczowe informacje. Oto szczegóły ćwiczenia:

### Ćwiczenie: Wprowadzenie do Azure Form Recognizer

#### Cel:
Celem tego ćwiczenia jest zapoznanie się z Azure Form Recognizer i jego zastosowaniem do analizowania i przetwarzania dokumentów. Będziesz tworzyć aplikację, która wykorzystuje Form Recognizer API do wydobywania danych z obrazów dokumentów i formularzy.

#### Wymagania:
- Aktywne konto Microsoft Azure.
- Zainstalowane środowisko programistyczne obsługujące C# (np. Visual Studio).
- Podstawowa znajomość C# i .NET.

---

 

#### Krok 1 i 2: Utworzenie zasobu Azure Form Recognizer

##### a. Tworzenie zasobu
1. Na pulpicie nawigacyjnym portalu Azure wybierz „+ Utwórz zasób”.
2. Wyszukaj „Form Recognizer” i wybierz.
3. Kliknij „Utwórz”.

##### b. Konfiguracja projektu
1. Wybierz lub utwórz grupę zasobów.
2. Wpisz nazwę dla zasobu Form Recognizer.
3. Wybierz lokalizację i plan cenowy.

---

#### Krok 3: Konfiguracja Form Recognizer w Azure

1. Po utworzeniu zasobu Form Recognizer, przejdź do jego przeglądu.
2. Znajdź i skopiuj klucz dostępu oraz punkt końcowy.

---

#### Krok 4: Tworzenie aplikacji

1. Stwórz projekt aplikacji w C# w wybranym środowisku programistycznym.
2. Dodaj referencje do Azure Form Recognizer SDK.
3. Skonfiguruj aplikację, aby używała klucza dostępu i punktu końcowego Form Recognizer API.

---

#### Krok 5: Implementacja funkcji przetwarzania dokumentów

1. Dodaj funkcje do przesyłania obrazów dokumentów/formularzy do usługi Form Recognizer.
2. Implementuj logikę przetwarzania wyników i wydobywania kluczowych informacji z dokumentów (np. tekstu, tabel, par klucz-wartość).

---

#### Krok 6: Testowanie i debugowanie

1. Przetestuj aplikację z różnymi typami dokumentów.
2. Sprawdź poprawność działania i dokonaj ewentualnych korekt.

---

#### Krok 7: Dodatkowe funkcjonalności (opcjonalnie)

1. Rozszerz aplikację o dodatkowe funkcje, takie jak przetwarzanie dokumentów wielostronicowych.
2. Dodaj możliwość klasyfikacji dokumentów na podstawie wydobytych danych.

 